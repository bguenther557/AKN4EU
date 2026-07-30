# AKN4EU

Human-reviewable, machine-readable mappings of EU legal acts and related case law for GRC practitioners and AI-assisted analysis.

EU legal acts are already available online, but their practical meaning often depends on relations between recitals, articles, paragraphs, annex provisions and judicial decisions. This project makes those relations explicit and records the reasoning behind them so that practitioners can inspect, challenge and reuse the mapping.

The repository is a personal side project by Benjamin Guenther. It is intended to make structured legislation more accessible, especially to small and medium-sized businesses that do not have large legal or consulting teams.

## What this repository contains

Each mapping is published as a Progressive Disclosure-compatible Markdown file with an embedded JSON graph. The format combines:

- document structures and identifiers informed by AKN4EU 4.2;
- a readable Markdown summary for people and AI assistants;
- the verbatim legal fragments used as legislation graph nodes;
- explicit semantic relations between recitals, article paragraphs and annex points;
- verified judgment nodes and judgment-to-legislation relations where relevant case law was identified;
- a short legal and factual rationale for each relation;
- machine-readable metadata, source identifiers, research provenance and QA results.

This repository does not publish canonical AKN4EU XML. Its Markdown and JSON format is an additional practitioner-oriented layer designed for review, AI use and later graph ingestion.

## Relation model

The graph distinguishes the legal function and source role of a relation instead of treating every cross-reference as equivalent. Internal legislation relations and judicial relations use separate vocabularies.

### Internal legislation relations

| Source and target | Relation | Meaning |
|---|---|---|
| Recital to article or annex | `applies_to` | Establishes the entities, situations or subject matter to which the target applies. |
| Recital to article or annex | `defines` | Clarifies the meaning of a term used by the target. |
| Recital to article or annex | `expands` | Broadens the target's scope or reach. |
| Recital to article or annex | `refines` | Makes an open term or requirement in the target more precise. |
| Recital to article or annex | `concretizes` | Supplies concrete examples, criteria or implementation details. |
| Recital to article or annex | `provides_guidance_for` | Provides legislative interpretive guidance for applying the target. |
| Recital to article or annex | `restricts` | Sets a boundary, limitation or proportionality constraint on the target. |
| Recital to recital | `builds_on` | Develops a proposition introduced by another recital. |
| Recital to recital | `qualifies` | Narrows or conditions another recital's proposition. |
| Recital to recital | `provides_context_for` | Supplies context needed to understand another recital. |
| Recital to recital | `contrasts_with` | Expresses a deliberate contrast with another recital. |
| Article to article | `references` | Contains a normative cross-reference to another provision. |
| Article to article | `depends_on` | Relies on another provision for its operation or meaning. |
| Article to article | `qualifies` | Narrows or conditions another provision. |
| Article to article | `excludes` | Establishes an exclusion from another provision. |
| Annex structure | `part_of` | Identifies an annex point as a subdivision of another annex point. |
| Annex to article | `gives_effect_to` | Identifies an annex provision that implements an article's reference to the annex. |

### Judicial relations

The internal relation vocabulary is not sufficient for case law. In particular, legislative `provides_guidance_for` is not the same as a court's holding, and scope-oriented `applies_to` is not the same as judicial `applies`.

| Judgment-to-block relation | Meaning |
|---|---|
| `interprets` | The verified holding construes the meaning, scope, conditions, exception or legal consequence of the target recital, article paragraph, recommendation point or annex point. |
| `applies` | The court applies the target block to the facts without making a material construction that warrants `interprets`. |
| `reviews_validity_of` | The decision reviews the validity or legality of the target block. The edge must also record a `validity_outcome`, such as `upheld`, `invalid`, `annulled_full`, `annulled_part`, `dismissed`, `inadmissible` or `not_determined`. |
| `references` | The judgment contains an exact and materially relevant citation to the target, but the verified holding does not support interpretation, application or validity review. This citation-only relation must not be described as a judicial interpretation. |

Effects such as confirming, limiting, overruling or annulling are recorded in fields such as `holding`, `later_history` and `validity_outcome` rather than being added as overlapping relation types.

A judgment can have more than one relation to more than one existing legal block, but each edge requires relation-specific reasoning and exact decision pinpoints. A general reference to an act is not expanded across all of its articles or paragraphs. If the decision cannot be assigned to an existing block at the required level of precision, it is retained as an unresolved research candidate rather than emitted as a relation.

### Canonical edge list

A single canonical edge list is the source of truth for both internal and judicial relations. Outbound and inbound relations are derived from that list, which makes edge symmetry structural rather than a later reconciliation step. This prevents a consistency routine from inventing a missing relation merely to make both directions match.

For case law, the judgment is the source node and the exact existing recital, article paragraph, recommendation point or annex point is the target node. The judgment's `outbound_relations` and the legal block's `inbound_relations` are regenerated from the same canonical edge.

Structural symmetry is not the same as legal correctness. The mappings therefore retain source text, target identifiers, decision identity, holding, pinpoints, provenance and reasoning so that every edge can be reviewed on its merits.

## Case-law discovery and verification

Case-law enrichment runs only after the internal legislation graph and its QA stages are complete. The stable intermediate graph determines the provisions and interpretation issues for which judgments are researched.

The workflow uses:

- LexAPI for EU case-law discovery through bounded inbound citation lookup, judgment search and, where necessary, semantic case-law search;
- Open Legal Data for discovery of relevant German court decisions applying or interpreting EU law;
- EUR-Lex, CURIA and official national court publications for authoritative verification.

Search results, citation-network entries, snippets, headnotes and semantic similarity are discovery evidence only. They cannot create a relation. Before a judgment is included, the workflow requires:

- retrieval and review of the full decision;
- complete decision identity, including ECLI or another stable identifier where available;
- an authoritative source URL;
- an exact paragraph or equivalent pinpoint;
- a bounded description of the court's holding;
- assignment to the narrowest supported existing legal block;
- `verification_status: verified` and `confidence: high`.

Judgments found through both services are deduplicated first by ECLI, then by judgment CELEX and finally by the normalized combination of court, date and file number. Discovery provenance is merged into one case-law node rather than creating source-specific duplicates.

The embedded metadata records the search date, queries, filters, pages or offsets checked, service limitations, excluded or pending candidates and unresolved targets. Empty search results are reported as bounded database and query outcomes; they are never presented as proof that no relevant case law exists.

## How to use a mapping

You can use a mapping without a graph database:

1. Open the Markdown file in an editor or provide it to an AI assistant.
2. Ask a question about a recital, article paragraph, annex requirement or related judicial interpretation.
3. Require the answer to identify the relevant node IDs, relation types, supporting legal text and, for case law, the decision citation and pinpoint.
4. Check the result against the linked official legal act and official judgment before using it for a legal or compliance decision.

The embedded JSON can also be parsed for search, analysis or import into Neo4j and other graph tools. The metadata includes AKN4EU-informed document identifiers, EU Vocabularies URIs and case-law provenance to support later cross-document linking.

## Method and quality controls

The generation workflow uses separate extraction, mapping, internal QA, case-law enrichment and final validation stages. Its main safeguards are:

- source verification against the official legal act;
- paragraph- and annex-point-level modeling;
- multiple relations where one recital or judgment performs more than one function;
- independent review passes for false positives and missing internal relations;
- a canonical edge list with referential-integrity and symmetry checks;
- mechanical gates for confidence, target coherence, duplicated reasoning and template-like mappings;
- full-decision and authoritative-source verification before emitting a judicial relation;
- exact-target, relation-coherence and pinpoint gates for case law;
- cross-source judgment deduplication;
- documented intentional absences, unresolved targets and pending candidates where no defensible relation was identified.

These controls reduce avoidable errors. They do not remove the need for expert review.

## Review and contribute

Please cross-check the mappings against the official legal text and, for judicial relations, the official decision. If you find an error or an important missing relation, [open a GitHub issue](https://github.com/bguenther557/AKN4EU/issues).

A useful issue should include:

- the mapping filename;
- the source and target node IDs;
- the relation that appears wrong or missing;
- a short explanation with the relevant official text;
- for case law, the court, decision date, case or file number, ECLI where available, and exact pinpoint;
- a link to the authoritative source, preferably an ELI, EUR-Lex, CURIA or official court page.

Challenges supported by the legal text are welcome. The purpose of publishing the reasoning is to make disagreement inspectable and corrections traceable, not to present model output as unquestionable.

## Relationship to AKN4EU

[AKN4EU](https://op.europa.eu/en/web/eu-vocabularies/akn4eu) is the EU Publications Office's work on a machine-readable format for exchanging legal documents during the EU decision-making process. The Publications Office describes it as work in progress that has not yet been fully implemented. This project uses AKN4EU 4.2 concepts where they help identify and structure legal components, while preserving separate semantic relation and case-law layers for GRC analysis.

The project is independent. It is not affiliated with or endorsed by the European Union, the Publications Office of the European Union or the AKN4EU project team. The name of this repository describes its technical alignment goal; it does not claim official conformance or certification.

## Disclaimer

The contents of this repository are unofficial research and engineering artifacts. They are provided for information, experimentation and review only. They do not constitute legal advice, regulatory guidance, a compliance assessment or an authoritative version of EU law or case law.

The mappings were produced with AI-assisted workflows and human review. Despite the QA controls described above, relations, excerpts, metadata, holdings or interpretations may be incomplete, incorrect or outdated. No guarantee is made as to accuracy, completeness, currency or fitness for a particular purpose. Do not rely on this repository as the sole basis for legal, compliance, security or business decisions.

Always verify the relevant provisions and decisions against EUR-Lex, the Official Journal of the European Union, CURIA, official national court publications and other applicable official sources. If this repository conflicts with an official source, the official source prevails. Obtain qualified legal advice where appropriate.

The repository's MIT License applies to the original project material covered by that license. It does not grant rights in third-party material, official emblems, trademarks or source documents beyond the rights provided by their respective owners and applicable law.

## References

- [AKN4EU overview, Publications Office of the European Union](https://op.europa.eu/en/web/eu-vocabularies/akn4eu)
- [AKN4EU schema, version 4.2](https://op.europa.eu/en/web/eu-vocabularies/model/-/resource/dataset/akn4eu)
- [EUR-Lex](https://eur-lex.europa.eu/)
- [CURIA case law](https://curia.europa.eu/)
- [Open Legal Data](https://de.openlegaldata.io/)

## License

See [LICENSE](./LICENSE).
