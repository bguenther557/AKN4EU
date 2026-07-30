# AKN4EU

Human-reviewable, machine-readable mappings of EU legal acts for GRC practitioners and AI-assisted analysis.

EU legal acts are already available online, but their practical meaning often depends on relations between recitals, articles, paragraphs and annex provisions. This project makes those relations explicit and records the reasoning behind them so that practitioners can inspect, challenge and reuse the mapping.

The repository is a personal side project by Benjamin Guenther. It is intended to make structured legislation more accessible, especially to small and medium-sized businesses that do not have large legal or consulting teams.

## What this repository contains

Each mapping is published as a Progressive Disclosure-compatible Markdown file with an embedded JSON graph. The format combines:

- document structures and identifiers informed by AKN4EU 4.2;
- a readable Markdown summary for people and AI assistants;
- the verbatim legal fragments used as graph nodes;
- explicit semantic relations between recitals, article paragraphs and annex points;
- a short legal and factual rationale for each relation;
- machine-readable metadata, source identifiers and QA results.

This repository does not publish canonical AKN4EU XML. Its Markdown and JSON format is an additional practitioner-oriented layer designed for review, AI use and later graph ingestion.

## Relation model

The graph distinguishes the function of a relation instead of treating every cross-reference as equivalent. Examples include:

- recital to article or annex: `applies_to`, `defines`, `expands`, `refines`, `concretizes`, `provides_guidance_for`;
- recital to recital: `builds_on`, `qualifies`, `provides_context_for`, `contrasts_with`;
- article to article: `references`, `depends_on`, `qualifies`, `excludes`;
- annex structure and effect: `part_of`, `gives_effect_to`.

A single canonical edge list is the source of truth. Outbound and inbound relations are derived from that list, which makes edge symmetry structural rather than a later reconciliation step. This prevents a consistency routine from inventing a missing relation merely to make both directions match.

Structural symmetry is not the same as legal correctness. The mappings therefore retain source text, target identifiers and reasoning so that every edge can be reviewed on its merits.

## How to use a mapping

You can use a mapping without a graph database:

1. Open the Markdown file in an editor or provide it to an AI assistant.
2. Ask a question about a recital, article paragraph or annex requirement.
3. Require the answer to identify the relevant node IDs, relation types and supporting text.
4. Check the result against the linked official source before using it for a legal or compliance decision.

The embedded JSON can also be parsed for search, analysis or import into Neo4j and other graph tools. The metadata includes AKN4EU-informed document identifiers and EU Vocabularies URIs to support later cross-document linking.

## Method and quality controls

The generation workflow uses separate extraction, mapping and QA stages. Its main safeguards are:

- source verification against the official legal act;
- paragraph- and annex-point-level modeling;
- multiple relations where one recital performs more than one function;
- independent review passes for false positives and missing relations;
- a canonical edge list with referential-integrity and symmetry checks;
- mechanical gates for confidence, target coherence, duplicated reasoning and template-like mappings;
- documented intentional absences where no defensible relation was identified.

These controls reduce avoidable errors. They do not remove the need for expert review.

## Review and contribute

Please cross-check the mappings against the official legal text. If you find an error or an important missing relation, [open a GitHub issue](https://github.com/bguenther557/AKN4EU/issues).

A useful issue should include:

- the mapping filename;
- the source and target node IDs;
- the relation that appears wrong or missing;
- a short explanation with the relevant official text;
- a link to the authoritative source, preferably an ELI or EUR-Lex page.

Challenges supported by the legal text are welcome. The purpose of publishing the reasoning is to make disagreement inspectable and corrections traceable, not to present model output as unquestionable.

## Relationship to AKN4EU

[AKN4EU](https://op.europa.eu/en/web/eu-vocabularies/akn4eu) is the EU Publications Office's work on a machine-readable format for exchanging legal documents during the EU decision-making process. The Publications Office describes it as work in progress that has not yet been fully implemented. This project uses AKN4EU 4.2 concepts where they help identify and structure legal components, while preserving a separate semantic relation layer for GRC analysis.

The project is independent. It is not affiliated with or endorsed by the European Union, the Publications Office of the European Union or the AKN4EU project team. The name of this repository describes its technical alignment goal; it does not claim official conformance or certification.

## Disclaimer

The contents of this repository are unofficial research and engineering artifacts. They are provided for information, experimentation and review only. They do not constitute legal advice, regulatory guidance, a compliance assessment or an authoritative version of EU law.

The mappings were produced with AI-assisted workflows and human review. Despite the QA controls described above, relations, excerpts, metadata or interpretations may be incomplete, incorrect or outdated. No guarantee is made as to accuracy, completeness, currency or fitness for a particular purpose. Do not rely on this repository as the sole basis for legal, compliance, security or business decisions.

Always verify the relevant provisions against EUR-Lex, the Official Journal of the European Union and other applicable official sources. If this repository conflicts with an official source, the official source prevails. Obtain qualified legal advice where appropriate.

The repository's MIT License applies to the original project material covered by that license. It does not grant rights in third-party material, official emblems, trademarks or source documents beyond the rights provided by their respective owners and applicable law.

## References

- [AKN4EU overview, Publications Office of the European Union](https://op.europa.eu/en/web/eu-vocabularies/akn4eu)
- [AKN4EU schema, version 4.2](https://op.europa.eu/en/web/eu-vocabularies/model/-/resource/dataset/akn4eu)

## License

See [LICENSE](./LICENSE).
