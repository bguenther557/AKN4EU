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

## Artifact standards and transition rule

The repository contains two deliberately different artifact profiles. They share stable document and node references so that cross-document relations can address both profiles, but they do not claim the same internal completeness.

| Profile | Scope | Purpose and limits |
|---|---|---|
| `legacy_syntax_only` | GDPR, DORA, Delegated Regulation (EU) 2024/1774, the AI Act and Implementing Regulation (EU) 2024/2690 | A one-time, preservation-bound normalization of mappings created before the current contract. Existing nodes, legal text, relation meaning, reasoning and confidence are retained. This profile is supported for reading, graph import and cross-document linking, but it is not a template for a new ingest. |
| `native_full` | The Cyber Resilience Act baseline and every newly ingested instrument from that transition onward | The binding current standard. New artifacts must use `akn4eu/legal-mapping@1.0.0`, declare the `eu-legal-to-json` producer, target `aura-legal-ontology@1.3.0-review-integrated` and schema-contract `0.2.0`, and pass the executable pre-publication validator. They include the full evidence, integrity, provenance, projection and QA structures required by the current pipeline. |

The Cyber Resilience Act is the transition artifact: it establishes the baseline for `native_full`. All later work, including the planned EU Digital Omnibus mapping, must use `native_full`; `legacy_syntax_only` must never be selected for a new document merely because it is simpler.

Legacy artifacts are not silently regenerated or semantically upgraded. A later correction requires a separately authorised, evidence-bound repair with a declared delta and complete re-validation. Official EUR-Lex and Official Journal sources remain authoritative for every profile.

## Relation model

The graph distinguishes the legal function, source role and direction of a relation instead of treating every cross-reference as equivalent. Internal legislation relations and judicial relations use separate vocabularies.

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

### Judicial relations and direction

The internal relation vocabulary is not sufficient for case law. In particular, legislative `provides_guidance_for` is not the same as a court's holding, and scope-oriented `applies_to` is not the same as judicial `applies`.

A judicial relation has two node-local perspectives derived from one canonical edge:

| Canonical edge and judgment `outbound_relations` | Legislation block `inbound_relations` | Meaning |
|---|---|---|
| `interprets` | `interpreted_by` | The verified holding construes the meaning, scope, conditions, exception or legal consequence of the legislation block. |
| `applies` | `applied_by` | The court applies the legislation block to the facts without making a material construction that warrants `interprets`. |
| `reviews_validity_of` | `validity_reviewed_by` | The decision reviews the validity or legality of the legislation block. The edge must also record a `validity_outcome`, such as `upheld`, `invalid`, `annulled_full`, `annulled_part`, `dismissed`, `inadmissible` or `not_determined`. |
| `references` | `referenced_by` | The judgment contains an exact and materially relevant citation to the legislation block, but the verified holding does not support interpretation, application or validity review. This citation-only relation must not be described as a judicial interpretation. |

The canonical edge is directed from the judgment to the legislation block and therefore uses the active predicate. The judgment node also uses that active predicate in its `outbound_relations`. Because the same relation is rendered inside the legislation text's `inbound_relations`, that local representation uses the passive inverse: `interpreted_by`, `applied_by`, `validity_reviewed_by` or `referenced_by`.

The passive form is not a second independently authored edge or a competing canonical relation type. It is a deterministic projection of the canonical edge. The inbound object retains the active value as `canonical_relation` and shares the same `edge_id`, source, target, evidence and pinpoint with the judgment's outbound view.

Effects such as confirming, limiting, overruling or annulling are recorded in fields such as `holding`, `later_history` and `validity_outcome` rather than being added as overlapping relation types.

A judgment can have more than one relation to more than one existing legal block, but each edge requires relation-specific reasoning and exact decision pinpoints. A general reference to an act is not expanded across all of its articles or paragraphs. If the decision cannot be assigned to an existing block at the required level of precision, it is retained as an unresolved research candidate rather than emitted as a relation.

### Canonical edge list

A single canonical edge list is the source of truth for both internal and judicial relations. Outbound and inbound relations are derived from that list, which makes edge symmetry structural rather than a later reconciliation step. This prevents a consistency routine from inventing a missing relation merely to make both directions match.

For case law, the judgment is the source node and the exact existing recital, article paragraph, recommendation point or annex point is the target node. The canonical edge and judgment outbound view use the active predicate. The legal block's inbound view uses the fixed passive inverse while preserving `canonical_relation` and the common `edge_id`.

For example, a canonical `interprets` edge from a judgment to an article paragraph is rendered as `interprets` in the judgment's `outbound_relations` and as `interpreted_by` in the article paragraph's `inbound_relations`. Both views are generated from the same edge; neither is reconciled or invented afterward.

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
4. Interpret judicial relation labels from the node's perspective: active on the judgment, passive in the legislation block.
5. Check the result against the linked official legal act and official judgment before using it for a legal or compliance decision.

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
- exact-target, relation-coherence, direction and pinpoint gates for case law;
- fixed active-to-passive inverse mapping for legislation-block inbound relations;
- shared `edge_id` and preserved `canonical_relation` across judicial relation projections;
- cross-source judgment deduplication;
- documented intentional absences, unresolved targets and pending candidates where no defensible relation was identified.

These controls reduce avoidable errors. They do not remove the need for expert review.

## Review and contribute

Please cross-check the mappings against the official legal text and, for judicial relations, the official decision. If you find an error or an important missing relation, [open a GitHub issue](https://github.com/bguenther557/AKN4EU/issues).

A useful issue should include:

- the mapping filename;
- the source and target node IDs;
- the relation that appears wrong or missing;
- whether the issue concerns the active canonical/outbound predicate or its passive legislation-block inbound projection;
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
