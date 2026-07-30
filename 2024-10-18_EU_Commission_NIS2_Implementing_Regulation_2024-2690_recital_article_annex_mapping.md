---
title: NIS2 Implementing Regulation (EU) 2024/2690 — Recital→Article→Annex Mapping
type: regulatorik
date: 2024-10-18
status: final
source_eli: http://data.europa.eu/eli/reg_impl/2024/2690/oj
legal_status: in force since 07.11.2024
relevance: 'Mapping of 43 recitals, 19 article paragraphs and 60 Annex points in Commission Implementing Regulation (EU) 2024/2690. Annex points 1 to 13 including all sub-points are modelled as first-class nodes. Recitals whose substance is an Annex requirement are anchored on the concrete Annex point. Node relations across all three node types are generated from one canonical edge list; every outbound relation has exactly one inbound counterpart.

  '
tags:
- directive-implementation
- incident-response
- critical-infrastructure
- supply-chain
- cyber-hygiene
- multi-factor-authentication
- vulnerability-management
- business-continuity
- physical-security
- access-control
- akn4eu-4.2
- akoma-ntoso
- eu-vocabularies
tags_extra:
- eu-law
- implementing-act
- annex-requirements
- incident-notification
- recurring-incidents
- financial-loss
- authentication
- network-segmentation
- asset-management
- patch-management
- human-resources-security
- event-monitoring
akn4eu_version: '4.2'
akn4eu_alignment_date: '2026-07-26'
rpm_version: 3.0.0
eur_lex_alignment_date: '2026-07-26'
eur_lex_source_url: https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402690
text_completeness: eur-lex-verbatim
---


# NIS2 Implementing Regulation (EU) 2024/2690 — Recital-Article-Annex Mapping

*Recital-Article-Annex mapping for the Commission Implementing Regulation (EU) 2024/2690 (NIS2). 43 recitals, 19 article paragraphs, 60 Annex points. Generated from the regulation text — see JSON below for the structured edge list.*

## AKN4EU 4.2 Compliance Summary

Generated from the JSON data object at emission time. Free text is for assessments, not numbers.

| Field | Value |
|------|------|
| AKN4EU root element | act |
| AKN4EU document name | REG_IMPL |
| AKN4EU document type URI | http://publications.europa.eu/resource/authority/resource-type/REG_IMPL |
| FRBRprescriptive | true |
| EEA relevance | true |
| Authentic language | en |
| Long title (docType / docNumber / docDate) | REGULATION / (EU) 2024/2690 / 2024-10-17 |
| Preamble present | actingEntity + 2 citations + enactingFormula |
| Preamble ordering check | pass |
| Hierarchy blocks (title / chapter / section) | 0 / 0 / 0 |
| Article kinds (regular / definition / amending) | 18 / 1 / 0 |
| Paragraph kinds (numbered / unnumbered / single) | 19 / 0 / 0 |
| Annex blocks | 1 (ANNEX I) |
| Annex points (reconstructed) | 60 |
| Cross-Act edges with ELI | 1 (NIS2 Directive 2022/2555) |
| Citation blocks (legal basis + enabling act) | 2 |


*KI-generiert. Keine Rechtsberatung: Dieser Text dient nur der allgemeinen Information. Für rechtsverbindliche Entscheidungen konsultieren Sie einen Fachanwalt.*

## Relation Counts

Generated from the JSON data object at emission time.

| Type | Count |
|------|------:|
| Recital to article | 44 |
| Recital to Annex | 53 |
| Recital to recital | 24 |
| Article to article | 56 |
| Annex hierarchy | 47 |
| Annex to article | 13 |
| Case law to block | 0 |
| **Total canonical legal relations** | **237** |

## Consistency Check

| Metric | Value |
|---|---:|
| Run | yes |
| Method | canonical edge list; symmetry structural |
| Orphan outbound | 0 |
| Orphan inbound | 0 |
| Status | pass |

## Source Attribution and Reuse Notice

| Affected content | Provider and retrieval | Original / verification source | Attribution and reuse notice |
|---|---|---|---|
| `metadata.case_law_research` | [LexAPI](https://lex-api.com/); bounded discovery; 2026-07-30 UTC | [EUR-Lex, CELEX 32024R2690](https://eur-lex.europa.eu/legal-content/EN/ALL/?uri=CELEX:32024R2690); [official act text](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32024R2690) | Source: EUR-Lex, © European Union. No raw response, semantic score, citation-graph dump, judgment text, or LexAPI-specific enrichment is included. |
| `metadata.case_law_research` | [Open Legal Data](https://de.openlegaldata.io/); bounded GET-only search and one candidate review; 2026-07-30 UTC | No candidate was retained; official-source verification was not applicable to published legal material. | Search metadata is subject to [ODbL v1.0](https://opendatacommons.org/licenses/odbl/1.0/). No decision text or excerpt is republished. |

The repository licence covers only original selection, structure and analysis. It does not relicense third-party source material or provider-specific enrichment.

## Intentional Absences

- R41-R43: procedural recitals (Cooperation Group and ENISA consultation, EDPS opinion, committee opinion); no substantive referent, hence no outbound edge.
- Art15, Art16: repeal and entry into force; no recital explains them, hence no inbound edge.

## Mapping (JSON)

```json
{
  "annex_hierarchy": [
    {
      "confidence": "high",
      "from_point": "1.1",
      "reasoning": "Annex point 1.1 is a subdivision of point 1.",
      "relation": "part_of",
      "to_point": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "1.2",
      "reasoning": "Annex point 1.2 is a subdivision of point 1.",
      "relation": "part_of",
      "to_point": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "2.1",
      "reasoning": "Annex point 2.1 is a subdivision of point 2.",
      "relation": "part_of",
      "to_point": "2",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "2.2",
      "reasoning": "Annex point 2.2 is a subdivision of point 2.",
      "relation": "part_of",
      "to_point": "2",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "2.3",
      "reasoning": "Annex point 2.3 is a subdivision of point 2.",
      "relation": "part_of",
      "to_point": "2",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "3.1",
      "reasoning": "Annex point 3.1 is a subdivision of point 3.",
      "relation": "part_of",
      "to_point": "3",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "3.2",
      "reasoning": "Annex point 3.2 is a subdivision of point 3.",
      "relation": "part_of",
      "to_point": "3",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "3.3",
      "reasoning": "Annex point 3.3 is a subdivision of point 3.",
      "relation": "part_of",
      "to_point": "3",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "3.4",
      "reasoning": "Annex point 3.4 is a subdivision of point 3.",
      "relation": "part_of",
      "to_point": "3",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "3.5",
      "reasoning": "Annex point 3.5 is a subdivision of point 3.",
      "relation": "part_of",
      "to_point": "3",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "3.6",
      "reasoning": "Annex point 3.6 is a subdivision of point 3.",
      "relation": "part_of",
      "to_point": "3",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "4.1",
      "reasoning": "Annex point 4.1 is a subdivision of point 4.",
      "relation": "part_of",
      "to_point": "4",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "4.2",
      "reasoning": "Annex point 4.2 is a subdivision of point 4.",
      "relation": "part_of",
      "to_point": "4",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "4.3",
      "reasoning": "Annex point 4.3 is a subdivision of point 4.",
      "relation": "part_of",
      "to_point": "4",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "5.1",
      "reasoning": "Annex point 5.1 is a subdivision of point 5.",
      "relation": "part_of",
      "to_point": "5",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "5.2",
      "reasoning": "Annex point 5.2 is a subdivision of point 5.",
      "relation": "part_of",
      "to_point": "5",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "6.1",
      "reasoning": "Annex point 6.1 is a subdivision of point 6.",
      "relation": "part_of",
      "to_point": "6",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "6.2",
      "reasoning": "Annex point 6.2 is a subdivision of point 6.",
      "relation": "part_of",
      "to_point": "6",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "6.3",
      "reasoning": "Annex point 6.3 is a subdivision of point 6.",
      "relation": "part_of",
      "to_point": "6",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "6.4",
      "reasoning": "Annex point 6.4 is a subdivision of point 6.",
      "relation": "part_of",
      "to_point": "6",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "6.5",
      "reasoning": "Annex point 6.5 is a subdivision of point 6.",
      "relation": "part_of",
      "to_point": "6",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "6.6",
      "reasoning": "Annex point 6.6 is a subdivision of point 6.",
      "relation": "part_of",
      "to_point": "6",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "6.7",
      "reasoning": "Annex point 6.7 is a subdivision of point 6.",
      "relation": "part_of",
      "to_point": "6",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "6.8",
      "reasoning": "Annex point 6.8 is a subdivision of point 6.",
      "relation": "part_of",
      "to_point": "6",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "6.9",
      "reasoning": "Annex point 6.9 is a subdivision of point 6.",
      "relation": "part_of",
      "to_point": "6",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "6.10",
      "reasoning": "Annex point 6.10 is a subdivision of point 6.",
      "relation": "part_of",
      "to_point": "6",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "8.1",
      "reasoning": "Annex point 8.1 is a subdivision of point 8.",
      "relation": "part_of",
      "to_point": "8",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "8.2",
      "reasoning": "Annex point 8.2 is a subdivision of point 8.",
      "relation": "part_of",
      "to_point": "8",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "10.1",
      "reasoning": "Annex point 10.1 is a subdivision of point 10.",
      "relation": "part_of",
      "to_point": "10",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "10.2",
      "reasoning": "Annex point 10.2 is a subdivision of point 10.",
      "relation": "part_of",
      "to_point": "10",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "10.3",
      "reasoning": "Annex point 10.3 is a subdivision of point 10.",
      "relation": "part_of",
      "to_point": "10",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "10.4",
      "reasoning": "Annex point 10.4 is a subdivision of point 10.",
      "relation": "part_of",
      "to_point": "10",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "11.1",
      "reasoning": "Annex point 11.1 is a subdivision of point 11.",
      "relation": "part_of",
      "to_point": "11",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "11.2",
      "reasoning": "Annex point 11.2 is a subdivision of point 11.",
      "relation": "part_of",
      "to_point": "11",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "11.3",
      "reasoning": "Annex point 11.3 is a subdivision of point 11.",
      "relation": "part_of",
      "to_point": "11",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "11.4",
      "reasoning": "Annex point 11.4 is a subdivision of point 11.",
      "relation": "part_of",
      "to_point": "11",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "11.5",
      "reasoning": "Annex point 11.5 is a subdivision of point 11.",
      "relation": "part_of",
      "to_point": "11",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "11.6",
      "reasoning": "Annex point 11.6 is a subdivision of point 11.",
      "relation": "part_of",
      "to_point": "11",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "11.7",
      "reasoning": "Annex point 11.7 is a subdivision of point 11.",
      "relation": "part_of",
      "to_point": "11",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "12.1",
      "reasoning": "Annex point 12.1 is a subdivision of point 12.",
      "relation": "part_of",
      "to_point": "12",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "12.2",
      "reasoning": "Annex point 12.2 is a subdivision of point 12.",
      "relation": "part_of",
      "to_point": "12",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "12.3",
      "reasoning": "Annex point 12.3 is a subdivision of point 12.",
      "relation": "part_of",
      "to_point": "12",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "12.4",
      "reasoning": "Annex point 12.4 is a subdivision of point 12.",
      "relation": "part_of",
      "to_point": "12",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "12.5",
      "reasoning": "Annex point 12.5 is a subdivision of point 12.",
      "relation": "part_of",
      "to_point": "12",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "13.1",
      "reasoning": "Annex point 13.1 is a subdivision of point 13.",
      "relation": "part_of",
      "to_point": "13",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "13.2",
      "reasoning": "Annex point 13.2 is a subdivision of point 13.",
      "relation": "part_of",
      "to_point": "13",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "13.3",
      "reasoning": "Annex point 13.3 is a subdivision of point 13.",
      "relation": "part_of",
      "to_point": "13",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    }
  ],
  "annex_to_article": [
    {
      "confidence": "high",
      "from_point": "1",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 1 implements Article 21(2), point (a).",
      "relation": "gives_effect_to",
      "to_article": 2,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "2",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 2 implements Article 21(2), point (a).",
      "relation": "gives_effect_to",
      "to_article": 2,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "3",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 3 implements Article 21(2), point (b).",
      "relation": "gives_effect_to",
      "to_article": 2,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "4",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 4 implements Article 21(2), point (c).",
      "relation": "gives_effect_to",
      "to_article": 2,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "5",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 5 implements Article 21(2), point (d).",
      "relation": "gives_effect_to",
      "to_article": 2,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "6",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 6 implements Article 21(2), point (e).",
      "relation": "gives_effect_to",
      "to_article": 2,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "7",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 7 implements Article 21(2), point (f).",
      "relation": "gives_effect_to",
      "to_article": 2,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "8",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 8 implements Article 21(2), point (g).",
      "relation": "gives_effect_to",
      "to_article": 2,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "9",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 9 implements Article 21(2), point (h).",
      "relation": "gives_effect_to",
      "to_article": 2,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "10",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 10 implements Article 21(2), point (i).",
      "relation": "gives_effect_to",
      "to_article": 2,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "11",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 11 implements Article 21(2), point (i and j).",
      "relation": "gives_effect_to",
      "to_article": 2,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "12",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 12 implements Article 21(2), point (i).",
      "relation": "gives_effect_to",
      "to_article": 2,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_point": "13",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 13 implements Article 21(2), point (c, e and i).",
      "relation": "gives_effect_to",
      "to_article": 2,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    }
  ],
  "article_to_article": [
    {
      "confidence": "high",
      "from_article": 2,
      "from_paragraph": "2",
      "reasoning": "Art2P2 requires entities to ensure a level of security appropriate to the risks when implementing the Annex requirements. This obligation depends on and operates within the framework of Art2P1, which sets out the technical and methodological requirements themselves.",
      "relation": "depends_on",
      "to_article": 2,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "2",
      "reasoning": "Art3P2 excludes scheduled interruptions of service and planned consequences of scheduled maintenance from being considered significant incidents. This directly excludes certain situations from the significant incident criteria established in Art3P1.",
      "relation": "excludes",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 4,
      "from_paragraph": "1",
      "reasoning": "Art4P1 states that recurring incidents which individually are not significant can collectively be considered significant if they share the same root cause. This qualifies Art3P1's general criteria by adding an aggregation rule for recurring incidents.",
      "relation": "qualifies",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 2,
      "from_paragraph": "1",
      "reasoning": "Art2P1 sets out technical and methodological requirements for 'the relevant entities.' The definition of which entities are relevant is established in Art1P1 (subject matter), making Art2P1 dependent on Art1P1's scope definition.",
      "relation": "depends_on",
      "to_article": 1,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "1",
      "reasoning": "Art3P1 defines significant incident criteria for 'the relevant entities.' The entity scope is established in Art1P1, making Art3P1's incident criteria dependent on Art1P1's subject matter and scope definition.",
      "relation": "depends_on",
      "to_article": 1,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 5,
      "from_paragraph": "1",
      "reasoning": "Art5P1 defines significant incidents specifically for DNS service providers. It depends on and applies the general significant incident criteria framework established in Art3P1 to the DNS service provider entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 6,
      "from_paragraph": "1",
      "reasoning": "Art6P1 defines significant incidents specifically for TLD name registries. It depends on and applies the general significant incident criteria framework established in Art3P1 to the TLD name registry entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 7,
      "from_paragraph": "1",
      "reasoning": "Art7P1 defines significant incidents specifically for cloud computing service providers. It depends on and applies the general significant incident criteria framework established in Art3P1 to the cloud computing entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 8,
      "from_paragraph": "1",
      "reasoning": "Art8P1 defines significant incidents specifically for data centre service providers. It depends on and applies the general significant incident criteria framework established in Art3P1 to the data centre entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 9,
      "from_paragraph": "1",
      "reasoning": "Art9P1 defines significant incidents specifically for content delivery network providers. It depends on and applies the general significant incident criteria framework established in Art3P1 to the CDN entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 10,
      "from_paragraph": "1",
      "reasoning": "Art10P1 defines significant incidents specifically for managed service providers and managed security service providers. It depends on and applies the general significant incident criteria framework established in Art3P1 to the MSP/MSSP entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 11,
      "from_paragraph": "1",
      "reasoning": "Art11P1 defines significant incidents specifically for providers of online marketplaces. It depends on and applies the general significant incident criteria framework established in Art3P1 to the online marketplace entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 12,
      "from_paragraph": "1",
      "reasoning": "Art12P1 defines significant incidents specifically for providers of online search engines. It depends on and applies the general significant incident criteria framework established in Art3P1 to the online search engine entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 13,
      "from_paragraph": "1",
      "reasoning": "Art13P1 defines significant incidents specifically for providers of social networking services platforms. It depends on and applies the general significant incident criteria framework established in Art3P1 to the social networking entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 14,
      "from_paragraph": "1",
      "reasoning": "Art14P1 defines significant incidents specifically for trust service providers. It depends on and applies the general significant incident criteria framework established in Art3P1 to the trust service provider entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "3",
      "reasoning": "Art3P3 explicitly states 'for the purpose of Articles 7 and 9 to 14' when defining the user counting methodology. Art7P1 (cloud computing service providers) is directly referenced as one of the articles for which the user count calculation applies.",
      "relation": "references",
      "to_article": 7,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "3",
      "reasoning": "Art3P3 explicitly states 'for the purpose of Articles 7 and 9 to 14' when defining the user counting methodology. Art9P1 (CDN providers) is directly referenced as one of the articles for which the user count calculation applies.",
      "relation": "references",
      "to_article": 9,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "3",
      "reasoning": "Art3P3 explicitly states 'for the purpose of Articles 7 and 9 to 14' when defining the user counting methodology. Art10P1 (MSPs/MSSPs) is directly referenced as one of the articles for which the user count calculation applies.",
      "relation": "references",
      "to_article": 10,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "3",
      "reasoning": "Art3P3 explicitly states 'for the purpose of Articles 7 and 9 to 14' when defining the user counting methodology. Art11P1 (online marketplaces) is directly referenced as one of the articles for which the user count calculation applies.",
      "relation": "references",
      "to_article": 11,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "3",
      "reasoning": "Art3P3 explicitly states 'for the purpose of Articles 7 and 9 to 14' when defining the user counting methodology. Art12P1 (online search engines) is directly referenced as one of the articles for which the user count calculation applies.",
      "relation": "references",
      "to_article": 12,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "3",
      "reasoning": "Art3P3 explicitly states 'for the purpose of Articles 7 and 9 to 14' when defining the user counting methodology. Art13P1 (social networking) is directly referenced as one of the articles for which the user count calculation applies.",
      "relation": "references",
      "to_article": 13,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "3",
      "reasoning": "Art3P3 explicitly states 'for the purpose of Articles 7 and 9 to 14' when defining the user counting methodology. Art14P1 (trust service providers) is directly referenced as one of the articles for which the user count calculation applies.",
      "relation": "references",
      "to_article": 14,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 2,
      "from_paragraph": "2",
      "reasoning": "Art2P2 requires entities to 'ensure a level of security appropriate to the risks' \u2014 this general risk-proportionality requirement depends on the specific technical and methodological measures enumerated in Art2P1. The appropriate security level is achieved by implementing the measures listed in P1.",
      "relation": "depends_on",
      "to_article": 2,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "2",
      "reasoning": "Art3P2 (scheduled interruptions of service and planned maintenance) qualifies Art3P1 (general significant incident criteria) by excluding planned/scheduled events from the significant incident definition \u2014 it narrows the scope of what counts as a significant incident.",
      "relation": "qualifies",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "3",
      "reasoning": "Art3P3 (methodology for counting users impacted by an incident) qualifies Art3P1 (significant incident criteria) by specifying how the user-impact threshold should be calculated \u2014 it refines the measurement methodology for applying the criteria in P1.",
      "relation": "qualifies",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 4,
      "from_paragraph": "1",
      "reasoning": "Art4 (recurring incidents that individually are not significant but collectively may be) qualifies Art3P1 (significant incident criteria) by adding a special case where individually non-significant incidents can become significant through recurrence \u2014 it extends and qualifies the individual-incident-based criteria in P1.",
      "relation": "qualifies",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 5,
      "from_paragraph": "1",
      "reasoning": "Art5 (significant incidents for DNS service providers) depends on Art3P1 (general significant incident criteria) \u2014 the DNS-specific criteria in Art5 build upon and apply the general framework established in Art3P1 to the DNS service provider entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 6,
      "from_paragraph": "1",
      "reasoning": "Art6 (significant incidents for TLD name registries) depends on Art3P1 (general significant incident criteria) \u2014 the TLD-specific criteria in Art6 build upon and apply the general framework established in Art3P1 to the TLD name registry entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 7,
      "from_paragraph": "1",
      "reasoning": "Art7 (significant incidents for cloud computing service providers) depends on Art3P1 (general significant incident criteria) \u2014 the cloud-specific criteria in Art7 build upon and apply the general framework established in Art3P1 to the cloud computing service provider entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 8,
      "from_paragraph": "1",
      "reasoning": "Art8 (significant incidents for data centre service providers) depends on Art3P1 (general significant incident criteria) \u2014 the data-centre-specific criteria in Art8 build upon and apply the general framework established in Art3P1 to the data centre service provider entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 9,
      "from_paragraph": "1",
      "reasoning": "Art9 (significant incidents for content delivery network providers) depends on Art3P1 (general significant incident criteria) \u2014 the CDN-specific criteria in Art9 build upon and apply the general framework established in Art3P1 to the CDN provider entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 10,
      "from_paragraph": "1",
      "reasoning": "Art10 (significant incidents for managed service providers and managed security service providers) depends on Art3P1 (general significant incident criteria) \u2014 the MSP-specific criteria in Art10 build upon and apply the general framework established in Art3P1 to the MSP entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 11,
      "from_paragraph": "1",
      "reasoning": "Art11 (significant incidents for providers of online marketplaces) depends on Art3P1 (general significant incident criteria) \u2014 the online-marketplace-specific criteria in Art11 build upon and apply the general framework established in Art3P1 to the online marketplace provider entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 12,
      "from_paragraph": "1",
      "reasoning": "Art12 (significant incidents for providers of online search engines) depends on Art3P1 (general significant incident criteria) \u2014 the search-engine-specific criteria in Art12 build upon and apply the general framework established in Art3P1 to the online search engine provider entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 13,
      "from_paragraph": "1",
      "reasoning": "Art13 (significant incidents for providers of social networking services platforms) depends on Art3P1 (general significant incident criteria) \u2014 the social-network-specific criteria in Art13 build upon and apply the general framework established in Art3P1 to the social networking service provider entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 14,
      "from_paragraph": "1",
      "reasoning": "Art14 (significant incidents for trust service providers) depends on Art3P1 (general significant incident criteria) \u2014 the trust-service-specific criteria in Art14 build upon and apply the general framework established in Art3P1 to the trust service provider entity type.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "2",
      "reasoning": "Art3-2 (scheduled interruptions and planned maintenance) excludes certain service disruptions from being considered significant incidents under Art3-1's general criteria.",
      "relation": "excludes",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "3",
      "reasoning": "Art3-3 (user counting methodology) qualifies Art3-1 by specifying how to calculate the number of users impacted, which is one of the significance criteria in Art3-1.",
      "relation": "qualifies",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 4,
      "from_paragraph": "1",
      "reasoning": "Art4-1 (recurring incidents) explicitly depends on Art3-1's definition of significant incident: 'Incidents that individually are not considered a significant incident within the meaning of Article 3' are assessed collectively.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 5,
      "from_paragraph": "1",
      "reasoning": "Art5-1 (DNS service providers) defines significance criteria by referencing Art3's general framework: 'an incident shall be considered significant under Article 3.'",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 6,
      "from_paragraph": "1",
      "reasoning": "Art6-1 (TLD name registries) defines significance criteria by referencing Art3's general framework: 'an incident shall be considered significant under Article 3.'",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 7,
      "from_paragraph": "1",
      "reasoning": "Art7-1 (cloud computing service providers) defines significance criteria by referencing Art3's general framework.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 8,
      "from_paragraph": "1",
      "reasoning": "Art8-1 (data centre service providers) defines significance criteria by referencing Art3's general framework.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 9,
      "from_paragraph": "1",
      "reasoning": "Art9-1 (CDN providers) defines significance criteria by referencing Art3's general framework.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 10,
      "from_paragraph": "1",
      "reasoning": "Art10-1 (MSPs and managed security service providers) defines significance criteria by referencing Art3's general framework.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 11,
      "from_paragraph": "1",
      "reasoning": "Art11-1 (online marketplace providers) defines significance criteria by referencing Art3's general framework.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 12,
      "from_paragraph": "1",
      "reasoning": "Art12-1 (online search engine providers) defines significance criteria by referencing Art3's general framework.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 13,
      "from_paragraph": "1",
      "reasoning": "Art13-1 (social networking service platform providers) defines significance criteria by referencing Art3's general framework.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 14,
      "from_paragraph": "1",
      "reasoning": "Art14-1 (trust service providers) defines significance criteria by referencing Art3's general framework.",
      "relation": "depends_on",
      "to_article": 3,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "3",
      "reasoning": "Art3-3 explicitly references Art7: 'When calculating the number of users impacted by an incident for the purpose of Articles 7 and 9 to 14.'",
      "relation": "references",
      "to_article": 7,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "3",
      "reasoning": "Art3-3 explicitly references Art9 as part of 'Articles 7 and 9 to 14' for user counting methodology.",
      "relation": "references",
      "to_article": 9,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "3",
      "reasoning": "Art3-3 explicitly references Art10 as part of 'Articles 7 and 9 to 14' for user counting methodology.",
      "relation": "references",
      "to_article": 10,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "3",
      "reasoning": "Art3-3 explicitly references Art11 as part of 'Articles 7 and 9 to 14' for user counting methodology.",
      "relation": "references",
      "to_article": 11,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "3",
      "reasoning": "Art3-3 explicitly references Art12 as part of 'Articles 7 and 9 to 14' for user counting methodology.",
      "relation": "references",
      "to_article": 12,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "3",
      "reasoning": "Art3-3 explicitly references Art13 as part of 'Articles 7 and 9 to 14' for user counting methodology.",
      "relation": "references",
      "to_article": 13,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_article": 3,
      "from_paragraph": "3",
      "reasoning": "Art3-3 explicitly references Art14 as part of 'Articles 7 and 9 to 14' for user counting methodology.",
      "relation": "references",
      "to_article": 14,
      "to_paragraph": "1",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    }
  ],
  "metadata": {
    "consistency_check": {
      "edge_symmetry": "pass",
      "method": "node relations regenerated from one canonical edge list across all three node types; symmetry is structural, not reconciled afterwards",
      "orphan_inbound": 0,
      "orphan_outbound": 0,
      "referential_integrity": "pass",
      "run": true,
      "status": "pass"
    },
    "document": "Commission Implementing Regulation (EU) 2024/2690 (NIS2)",
    "intentional_absences": [
      "R41-R43: procedural recitals (Cooperation Group and ENISA consultation, EDPS opinion, committee opinion); no substantive referent, hence no outbound edge.",
      "Art15, Art16: repeal and entry into force; no recital explains them, hence no inbound edge."
    ],
    "legal_status": "in force since 07.11.2024; no amendments affecting recital, article or Annex structure",
    "relation_counts": {
      "annex_hierarchy": 47,
      "annex_to_article": 13,
      "article_to_article": 56,
      "recital_to_annex": 53,
      "recital_to_article": 44,
      "recital_to_recital": 24,
      "akn4eu_preamble_to_article": 2,
      "akn4eu_hierarchy_edge": 0,
      "akn4eu_attachment_ref": 1,
      "case_law_to_block": 0
    },
    "source_eli": "http://data.europa.eu/eli/reg_impl/2024/2690/oj",
    "total_annex_points": 60,
    "total_article_paragraphs": 19,
    "total_recitals": 43,
    "akn4eu_root_element": "act",
    "akn4eu_document_name": "REG_IMPL",
    "akn4eu_document_type_uri": "http://publications.europa.eu/resource/authority/resource-type/REG_IMPL",
    "akn4eu_frbrprescriptive": true,
    "akn4eu_eea_relevance": true,
    "akn4eu_authentic_language": "en",
    "akn4eu_long_title": {
      "doc_type": "REGULATION",
      "doc_number": "(EU) 2024/2690",
      "doc_date": "2024-10-17",
      "doc_purpose": "laying down rules for the application of Directive (EU) 2022/2555 as regards technical and methodological requirements for cybersecurity risk-management measures and further specifications of the cases in which an incident is considered to be significant, with regard to specific entities providing domain name registration services, top-level domain name registries, cloud computing services, data centre services, content delivery network services, managed service providers, managed security service providers, providers of online market places, online search engines and social networking services platforms, and of certain types of entities providing electronic communications networks or services"
    },
    "akn4eu_filename_xml": "REG_IMPL-2024-2690-en.xml",
    "akn4eu_filename_leg": "REG_IMPL-2024-2690-en.leg",
    "akn4eu_conflicts": [],
    "akn4eu_hierarchy": [],
    "akn4eu_hierarchy_edges": [],
    "akn4eu_annex": {
      "akn4eu_root_element": "doc",
      "akn4eu_document_name": "ANNEX",
      "akn4eu_document_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ANNEX",
      "akn4eu_frbrprescriptive": true,
      "akn4eu_annex_headerofannex": {
        "num": "ANNEX I",
        "heading": "Cybersecurity risk-management measures and significant-incident thresholds (Article 21(2) NIS2 / Article 23(3) NIS2)"
      },
      "akn4eu_numbered_paragraphs_allowed": false,
      "akn4eu_annex_articles": [],
      "akn4eu_cross_headings": []
    },
    "akn4eu_preamble": {
      "akn4eu_acting_entity": {
        "text": "THE EUROPEAN COMMISSION,",
        "akn4eu_acting_entity_refers_to": "~Commission"
      },
      "akn4eu_citations": [
        {
          "akn4eu_citation_role": "legalBasis",
          "akn4eu_refers_to": "~legalBasis",
          "text": "Having regard to the Treaty on the Functioning of the European Union, and in particular Article 291(2) thereof,",
          "akn4eu_target_uri": "http://eurovoc.europa.eu/5456"
        },
        {
          "akn4eu_citation_role": "enablingAct",
          "akn4eu_refers_to": "~enablingAct",
          "text": "Having regard to Directive (EU) 2022/2555 of the European Parliament and of the Council, and in particular Article 21(2) and Article 23(11) thereof,",
          "akn4eu_target_uri": "http://data.europa.eu/eli/dir/2022/2555/oj"
        }
      ],
      "akn4eu_enacting_formula": {
        "text": "HAS ADOPTED THIS REGULATION:",
        "akn4eu_name": "enactingFormula"
      },
      "ordering_check": "pass"
    },
    "v3_0_0_alignment_runs": {
      "date": "2026-07-26",
      "tool": "eu-legal-to-json skill v3.0.0 retrofit pipeline",
      "additive_only": true,
      "relation_logic_preserved_bit_for_bit": true,
      "akn4eu_conflicts": 0,
      "note": "A retroactive AKN4EU 4.2 alignment pass. Relation logic (canonical edge list, structural symmetry, n:m relations, QA pipeline, pre-delivery gates) is unchanged from v2.4.0. AKN4EU schema fields were added as additive metadata. annex_points array was reconstructed from annex_hierarchy edges because v2.4.0 stored annex points as edges only."
    },
    "eur_lex_alignment_runs": {
      "date": "2026-07-26",
      "tool": "eu-legal-to-json skill + EUR-Lex backfill pipeline",
      "eur_lex_source": "https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402690",
      "articles_text_replaced": 22,
      "annex_points_text_filled": 60,
      "annex_points_skipped": 0,
      "relation_logic_preserved": true,
      "note": "Critical bug fix: v2.4.0 output had heading-prefix concatenated into article text (e.g. \"Subject matter This Regulation...\") and 60/60 annex points had no text/title/NIS2-2-2 mapping. EUR-Lex verbatim text was injected for all articles (now stripped of heading prefix, with heading in akn4eu_heading) and all 60 annex points. Recitals were already correct."
    },
    "document_content_attribution_ids": [],
    "source_attributions": {
      "schema": "eu-legal-to-json/source-attribution@1.0",
      "records": [
        {
          "id": "src-lexapi-case-law-research-32024r2690",
          "provider": "LexAPI",
          "provider_url": "https://lex-api.com/",
          "provider_terms_url": "https://lex-api.com/terms",
          "retrieval_method": "lex_get_metadata; lex_cited_by; lex_search; lex_semantic_case_law",
          "retrieved_at": "2026-07-30T14:39:30Z",
          "provider_source_url": null,
          "content_refs": [
            {
              "kind": "research_audit",
              "id": "metadata.case_law_research"
            }
          ],
          "attributed_fields": [
            "query_audit",
            "lexapi_scope",
            "retrieval_metadata"
          ],
          "content_origin": {
            "name": "EUR-Lex",
            "identifier_type": "CELEX",
            "identifier": "32024R2690",
            "url": "https://eur-lex.europa.eu/legal-content/EN/ALL/?uri=CELEX:32024R2690",
            "attribution_text": "Source: EUR-Lex, \u00a9 European Union."
          },
          "official_verification_url": "https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32024R2690",
          "attribution_text": "EU legal material: EUR-Lex, \u00a9 European Union. Bounded case-law discovery via LexAPI on 2026-07-30; official act record verified at EUR-Lex. No judgment text or LexAPI-specific enrichment is included.",
          "rights_notice": "No LexAPI parsing, structuring, enrichment, citation-graph data, semantic scores, or raw API responses are relicensed.",
          "provider_license": null,
          "provider_specific_material": "none",
          "permission_reference": null,
          "publication_status": "attribution_complete"
        },
        {
          "id": "src-open-legal-data-case-law-research-32024r2690",
          "provider": "Open Legal Data",
          "provider_url": "https://de.openlegaldata.io/",
          "provider_terms_url": null,
          "retrieval_method": "GET /api/cases/search/; GET /api/cases/{id}/",
          "retrieved_at": "2026-07-30T14:39:30Z",
          "provider_source_url": "https://de.openlegaldata.io/case",
          "content_refs": [
            {
              "kind": "research_audit",
              "id": "metadata.case_law_research"
            }
          ],
          "attributed_fields": [
            "query_audit",
            "open_legal_data_scope",
            "retrieval_metadata"
          ],
          "content_origin": {
            "name": "German court decisions indexed by Open Legal Data",
            "identifier_type": "bounded_search_scope",
            "identifier": "Regulation (EU) 2024/2690 / NIS2",
            "url": null,
            "attribution_text": "No decision text or legal proposition was retained."
          },
          "official_verification_url": null,
          "attribution_text": "Open Legal Data case-law discovery metadata, searched 2026-07-30. No candidate was retained; no published legal material required an official-source URL.",
          "rights_notice": "Open Legal Data database content is licensed under ODbL v1.0. No decision text or excerpt is republished.",
          "provider_license": {
            "name": "Open Database License (ODbL) v1.0",
            "url": "https://opendatacommons.org/licenses/odbl/1.0/"
          },
          "provider_specific_material": "none",
          "permission_reference": null,
          "publication_status": "attribution_complete"
        }
      ]
    },
    "case_law_research": {
      "searched_at": "2026-07-30T14:39:30Z",
      "cutoff_date": "2026-07-30",
      "sources": [
        "lexapi",
        "open_legal_data"
      ],
      "query_audit": [
        {
          "source": "lexapi",
          "attribution_id": "src-lexapi-case-law-research-32024r2690",
          "method": "lex_cited_by",
          "query": "CELEX 32024R2690; citationType=reference",
          "filters": {
            "limit": 100,
            "offset": 0
          },
          "pages_fetched": 1,
          "result_count": 0,
          "status": "complete_for_requested_page"
        },
        {
          "source": "lexapi",
          "attribution_id": "src-lexapi-case-law-research-32024r2690",
          "method": "lex_search",
          "query": "Commission Implementing Regulation (EU) 2024/2690 Article 2 Article 3",
          "filters": {
            "maxPages": 1
          },
          "pages_fetched": 1,
          "result_count": 0,
          "status": "complete_for_requested_page"
        },
        {
          "source": "lexapi",
          "attribution_id": "src-lexapi-case-law-research-32024r2690",
          "method": "lex_search",
          "query": "NIS2 cybersecurity risk-management measures significant incident notification",
          "filters": {
            "maxPages": 1
          },
          "pages_fetched": 1,
          "result_count": 0,
          "status": "complete_for_requested_page"
        },
        {
          "source": "lexapi",
          "attribution_id": "src-lexapi-case-law-research-32024r2690",
          "method": "lex_search",
          "query": "cybersecurity risk-management measures",
          "filters": {
            "maxPages": 1
          },
          "pages_fetched": 1,
          "result_count": 1,
          "retained_candidate_count": 0,
          "status": "irrelevant_candidate_excluded"
        },
        {
          "source": "lexapi",
          "attribution_id": "src-lexapi-case-law-research-32024r2690",
          "method": "lex_semantic_case_law",
          "query": "EU judgments interpreting NIS2 risk-management or significant-incident thresholds under Regulation (EU) 2024/2690",
          "filters": {
            "limit": 10
          },
          "pages_fetched": 0,
          "result_count": null,
          "status": "failed_502_after_bounded_retry"
        },
        {
          "source": "open_legal_data",
          "attribution_id": "src-open-legal-data-case-law-research-32024r2690",
          "method": "search",
          "query": "\"2024/2690\"",
          "filters": {
            "page": 1,
            "page_size": 20
          },
          "pages_fetched": 1,
          "result_count": 2,
          "retained_candidate_count": 0,
          "status": "citation_number_false_positives_excluded"
        },
        {
          "source": "open_legal_data",
          "attribution_id": "src-open-legal-data-case-law-research-32024r2690",
          "method": "search",
          "query": "\"Durchf\u00fchrungsverordnung (EU) 2024/2690\"",
          "filters": {
            "page": 1,
            "page_size": 20
          },
          "pages_fetched": 1,
          "result_count": 0,
          "status": "complete_for_requested_page"
        },
        {
          "source": "open_legal_data",
          "attribution_id": "src-open-legal-data-case-law-research-32024r2690",
          "method": "search",
          "query": "NIS2 Cybersicherheitsrisikomanagement erheblicher Sicherheitsvorfall",
          "filters": {
            "page": 1,
            "page_size": 20
          },
          "pages_fetched": 1,
          "result_count": 0,
          "status": "complete_for_requested_page"
        },
        {
          "source": "open_legal_data",
          "attribution_id": "src-open-legal-data-case-law-research-32024r2690",
          "method": "search",
          "query": "NIS2",
          "filters": {
            "page": 1,
            "page_size": 50
          },
          "pages_fetched": 1,
          "result_count": 0,
          "status": "complete_for_requested_page"
        },
        {
          "source": "open_legal_data",
          "attribution_id": "src-open-legal-data-case-law-research-32024r2690",
          "method": "search",
          "query": "\"NIS-2\"",
          "filters": {
            "page": 1,
            "page_size": 50
          },
          "pages_fetched": 1,
          "result_count": 1,
          "retained_candidate_count": 0,
          "status": "topical_candidate_excluded_after_full_text_review"
        },
        {
          "source": "open_legal_data",
          "attribution_id": "src-open-legal-data-case-law-research-32024r2690",
          "method": "search",
          "query": "Cybersicherheitsrisikomanagementma\u00dfnahmen",
          "filters": {
            "page": 1,
            "page_size": 50
          },
          "pages_fetched": 1,
          "result_count": 0,
          "status": "complete_for_requested_page"
        }
      ],
      "lexapi_scope": {
        "pages_fetched": 4,
        "citation_offset_end": 0,
        "partial": true,
        "limitations": [
          "Discovery was bounded to one page per query.",
          "Semantic search returned HTTP 502 after a bounded retry.",
          "No negative legal inference is drawn."
        ]
      },
      "open_legal_data_scope": {
        "health_check": "pass_http_200",
        "pages_checked": [
          1
        ],
        "partial": true,
        "limitations": [
          "Six bounded unfiltered searches checked page 1.",
          "Three false positives were excluded; one full decision did not concern Regulation (EU) 2024/2690.",
          "No negative legal inference is drawn."
        ]
      },
      "candidate_count": 4,
      "verified_case_count": 0,
      "emitted_edge_count": 0,
      "unresolved_targets": [],
      "excluded_or_pending_candidates": [
        {
          "count": 2,
          "source": "open_legal_data",
          "reason": "The exact-number query matched NJW 2024, 2690, not the Regulation."
        },
        {
          "count": 1,
          "source": "open_legal_data",
          "reason": "KG, 18.11.2025 \u2013 5 UKl 10/25 mentioned NIS2 in a \u00a7 312k BGB argument but did not support an edge to this Regulation."
        },
        {
          "count": 1,
          "source": "lexapi",
          "reason": "General Court case 62020TJ0624 used generic cybersecurity language but predated and did not concern this Regulation."
        }
      ],
      "non_exhaustive": true
    },
    "eu_legal_to_json_version": "3.2.2",
    "v3_2_2_alignment_run": {
      "run_at": "2026-07-30T14:39:30Z",
      "scope": "canonical edges, confidence gate, case-law enrichment, directional judicial-relation readiness, and provider attribution",
      "internal_relation_changes": [
        {
          "action": "remove",
          "count": 16,
          "class": "unapproved medium/low recital-to-recital edges",
          "reason": "Current confidence gate blocks unapproved medium/low edges."
        },
        {
          "action": "remove",
          "edge": "recital-6__article-Art2-Para1__concretizes",
          "reason": "The qualifier is directly expressed in Article 2(2); this additional edge was indirect."
        },
        {
          "action": "upgrade_confidence",
          "edge": "recital-36__article-Art4-UN1__provides_guidance_for",
          "from": "medium",
          "to": "high",
          "reason": "Article 4(c) expressly incorporates Article 3(1)(a), whose criterion Recital 36 defines."
        }
      ],
      "case_law_edges_emitted": 0,
      "source_attribution_gate": "pass",
      "note": "No verified candidate was retained; search absence is not a legal conclusion."
    }
  },
  "recital_to_recital": [
    {
      "confidence": "high",
      "from_recital": 1,
      "reasoning": "R1 establishes the scope of entity types covered by the Regulation (DNS, TLD, cloud, data centre, CDN, MSPs). R2 extends the regulatory framework to trust service providers, building on the scope rationale established in R1.",
      "relation": "provides_context_for",
      "to_recital": 2,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 3,
      "reasoning": "R3 establishes the standards basis (ISO, ETSI) for the Annex requirements. R4 discusses proportionality in implementing those same requirements based on risk exposure and entity size. R3's standards context frames R4's proportionality discussion.",
      "relation": "provides_context_for",
      "to_recital": 4,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 4,
      "reasoning": "R4 introduces proportionality when entities cannot implement requirements due to risk exposure or size. R5 builds directly on this by adding the concept of compensating measures that entities should adopt when they cannot implement specific requirements.",
      "relation": "builds_on",
      "to_recital": 5,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 8,
      "reasoning": "R8 describes technical network security measures (protocols, email, DNS). R9 builds on this by moving to the governance layer \u2014 policies on information system security and access control \u2014 which complement and operationalize the technical measures in R8.",
      "relation": "builds_on",
      "to_recital": 9,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 9,
      "reasoning": "R9 discusses policies on information system security including access control, which inherently involves 'users.' R10 builds on this by defining what 'user' encompasses, clarifying a key term used in the access control context of R9.",
      "relation": "builds_on",
      "to_recital": 10,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 11,
      "reasoning": "R11 establishes the risk management framework for identifying and addressing risks. R12 builds on this by specifying the detection and monitoring capabilities that operate within that framework to identify events, near misses, and incidents.",
      "relation": "builds_on",
      "to_recital": 12,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 11,
      "reasoning": "R11 establishes the risk management framework for identifying and addressing risks. R14 builds on this by adding supply chain security policy as a specific component of the risk management framework, addressing risks from suppliers and supply chain relationships.",
      "relation": "builds_on",
      "to_recital": 14,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 25,
      "reasoning": "R25 (asset classification by type, sensitivity, risk level) builds directly on R24 (asset management framework) \u2014 classification is a core component that extends the asset management concept established in R24.",
      "relation": "builds_on",
      "to_recital": 24,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 26,
      "reasoning": "R26 (asset inventory granularity and attributes) builds on R24 (asset management) \u2014 the inventory is a concrete implementation component of the broader asset management framework established in R24.",
      "relation": "builds_on",
      "to_recital": 24,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 26,
      "reasoning": "R26 (asset inventory including unique identifier, owner, classification) builds on R25 (asset classification) \u2014 the inventory incorporates the classification scheme defined in R25 as one of its attributes.",
      "relation": "builds_on",
      "to_recital": 25,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 23,
      "reasoning": "R23 (multi-factor authentication) builds on R21 (access control policy) \u2014 MFA is a specific, strengthened access control mechanism that extends the general access control framework established in R21, particularly for remote and high-privilege access scenarios.",
      "relation": "builds_on",
      "to_recital": 21,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 28,
      "reasoning": "R28 (all-hazards approach covering physical and environmental threats) provides the conceptual framework and context for R29 (specific physical protection measures against fire, flood, power failures) \u2014 the all-hazards approach establishes that physical threats must be addressed, which R29 then details with concrete protection measures.",
      "relation": "provides_context_for",
      "to_recital": 29,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 31,
      "reasoning": "R31 (notification deadlines for significant incidents) builds on R30 (significance criteria specification). Once an incident is deemed significant per R30's framework, R31 establishes the notification timelines.",
      "relation": "builds_on",
      "to_recital": 30,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 32,
      "reasoning": "R32 (user counting methodology) builds on R30 (significance criteria framework). R30 establishes the general framework for determining significance, and R32 specifies how to count impacted users as part of that determination.",
      "relation": "builds_on",
      "to_recital": 30,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 33,
      "reasoning": "R33 (maintenance exclusion) qualifies R30 (significance framework) by establishing that scheduled maintenance operations should not be considered significant incidents, narrowing the scope of what R30's framework covers.",
      "relation": "qualifies",
      "to_recital": 30,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 34,
      "reasoning": "R34 (incident duration measurement) builds on R30 (significance criteria framework) by specifying how to measure the duration criterion that determines significance.",
      "relation": "builds_on",
      "to_recital": 30,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 35,
      "reasoning": "R35 (complete unavailability measurement) builds on R30 (significance criteria framework) by specifying how to measure complete unavailability as a significance criterion.",
      "relation": "builds_on",
      "to_recital": 30,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 35,
      "reasoning": "R35 (complete unavailability measurement) builds on R34 (general duration measurement) by specializing the measurement methodology to the specific case of complete service unavailability.",
      "relation": "builds_on",
      "to_recital": 34,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 36,
      "reasoning": "R36 (financial loss definition) builds on R30 (significance criteria framework) by defining how to calculate direct financial losses as a significance criterion.",
      "relation": "builds_on",
      "to_recital": 30,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 37,
      "reasoning": "R37 (death/health damage criterion) builds on R30 (significance criteria framework) by adding incidents causing death or considerable health damage as a significance criterion.",
      "relation": "builds_on",
      "to_recital": 30,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 38,
      "reasoning": "R38 (limited availability definition) builds on R30 (significance criteria framework) by defining what constitutes limited availability as a significance criterion.",
      "relation": "builds_on",
      "to_recital": 30,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 39,
      "reasoning": "R39 (unauthorized access criterion) builds on R30 (significance criteria framework) by adding malicious unauthorized access as a significance criterion.",
      "relation": "builds_on",
      "to_recital": 30,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 40,
      "reasoning": "R40 (recurring incidents criterion) builds on R30 (significance criteria framework) by establishing that recurring incidents linked by the same root cause should be collectively assessed for significance.",
      "relation": "builds_on",
      "to_recital": 30,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    },
    {
      "confidence": "high",
      "from_recital": 38,
      "reasoning": "R38 defines limited availability (service slower than average or not all functionalities available) while R35 defines complete unavailability (service fully unavailable). These are contrasting concepts on the availability spectrum.",
      "relation": "contrasts_with",
      "to_recital": 35,
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": []
    }
  ],
  "recitals_and_articles": [
    {
      "id": "recital-1",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Recital 1 mirrors the language of Article 1 almost verbatim, explaining the Regulation's dual purpose: laying down technical/methodological requirements for Article 21(2) NIS2 measures and specifying significant incidents under Article 23(3) NIS2.",
          "relation": "provides_guidance_for",
          "target_article": 1,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 1,
      "text": "With regard to DNS service providers, TLD name registries, cloud computing service providers, data centre service providers, content delivery network providers, managed service providers, managed security service providers, providers of online market places, of online search engines and of social networking services platforms, and trust service providers as covered by Article 3 of Directive (EU) 2022/2555 (the relevant entities), this Regulation aims to lay down the technical and the methodological requirements of the measures referred to in Article 21(2) of Directive (EU) 2022/2555 and to further specify the cases in which an incident should be considered to be significant as referred to in Article 23(3) of Directive (EU) 2022/2555.",
      "type": "recital"
    },
    {
      "id": "recital-2",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Recital 2 specifically addresses trust service providers, and Article 14 sets out the entity-specific significant-incident criteria exclusively for trust service providers.",
          "relation": "applies_to",
          "target_article": 14,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 2,
      "text": "Taking account of the cross-border nature of their activities and in order to ensure a coherent framework for trust service providers, this Regulation should, with respect to trust service providers, further specify the cases in which an incident shall be considered to be significant, in addition to laying down the technical and the methodological requirements of the cybersecurity risk-management measures.",
      "type": "recital"
    },
    {
      "id": "recital-3",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 1 (Policy on the security of network and information systems) as part of the Annex as a whole.",
          "relation": "refines",
          "target_point": "1",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 2 (Risk management policy) as part of the Annex as a whole.",
          "relation": "refines",
          "target_point": "2",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 3 (Incident handling) as part of the Annex as a whole.",
          "relation": "refines",
          "target_point": "3",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 4 (Business continuity and crisis management) as part of the Annex as a whole.",
          "relation": "refines",
          "target_point": "4",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 5 (Supply chain security) as part of the Annex as a whole.",
          "relation": "refines",
          "target_point": "5",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 6 (Security in network and information systems acquisition, development and maintenance) as part of the Annex as a whole.",
          "relation": "refines",
          "target_point": "6",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 7 (Policies and procedures to assess the effectiveness of cybersecurity risk-management measures) as part of the Annex as a whole.",
          "relation": "refines",
          "target_point": "7",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 8 (Basic cyber hygiene practices and security training) as part of the Annex as a whole.",
          "relation": "refines",
          "target_point": "8",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 9 (Cryptography) as part of the Annex as a whole.",
          "relation": "refines",
          "target_point": "9",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 10 (Human resources security) as part of the Annex as a whole.",
          "relation": "refines",
          "target_point": "10",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 11 (Access control) as part of the Annex as a whole.",
          "relation": "refines",
          "target_point": "11",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 12 (Asset management) as part of the Annex as a whole.",
          "relation": "refines",
          "target_point": "12",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 13 (Environmental and physical security) as part of the Annex as a whole.",
          "relation": "refines",
          "target_point": "13",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 3,
      "text": "Following Article 21(5), third subparagraph of Directive (EU) 2022/2555, the technical and methodological requirements of the cybersecurity risk-management measures set out in the Annex to this Regulation are based on European and international standards, such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401, and technical specifications, such as CEN/TS 18026:2024, relevant to the security of network and information systems.",
      "type": "recital"
    },
    {
      "id": "recital-4",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Recital 4 explains the proportionality principle that underpins Article 2(2)'s requirement to ensure a risk-appropriate level of security, enumerating factors such as risk exposure, size, and incident likelihood.",
          "relation": "provides_guidance_for",
          "target_article": 2,
          "target_paragraph": "2",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 4,
      "text": "As regards the implementation and application of the technical and the methodological requirements of cybersecurity risk-management measures set out in the Annex to this Regulation, in line with the principle of proportionality, due account should be taken of the divergent risk exposure of relevant entities, such as the criticality of the relevant entity, the risks to which it is exposed, the relevant entity's size and structure as well as the likelihood of occurrence of incidents and their severity, including their societal and economic impact, when complying with the technical and methodological requirements of cybersecurity risk-management measures set out in the Annex to this Regulation.",
      "type": "recital"
    },
    {
      "id": "recital-5",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Recital 5 expands on Article 2(2) by introducing compensating measures as an alternative for entities unable to implement certain requirements due to size, providing concrete examples such as management oversight for micro-entities.",
          "relation": "expands",
          "target_article": 2,
          "target_paragraph": "2",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 5,
      "text": "In line with the principle of proportionality, where relevant entities cannot implement some of the technical and the methodological requirements of the cybersecurity risk-management measures due to their size, those entities should be able to take other compensating measures that are suitable to achieve the purpose of those requirements. For example, when defining roles, responsibilities and authorities for network and information system security within the relevant entity, micro-sized entities might find it difficult to segregate conflicting duties and conflicting areas of responsibility. Such entities should be able to consider compensating measures such as targeted oversight by the entity's management or increased monitoring and logging.",
      "type": "recital"
    },
    {
      "id": "recital-6",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Recital 6 provides concrete interpretive guidance on the 'where appropriate', 'where applicable', or 'to the extent feasible' qualifiers used in Article 2(2), explaining the documentation obligation and adding that authorities may consider implementation timelines.",
          "relation": "concretizes",
          "target_article": 2,
          "target_paragraph": "2",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 6,
      "text": "Certain technical and methodological requirements set out in the Annex to this Regulation should be applied by the relevant entities where appropriate, where applicable, or to the extent feasible. Where a relevant entity considers it not appropriate, not applicable or not feasible for the relevant entity to apply certain technical and methodological requirements as provided for in the Annex to this Regulation, the relevant entity should in a comprehensible manner document its reasoning to that effect. National competent authorities may, when exercising supervision, take into account the appropriate time required for the relevant entities to implement the technical and the methodological requirements of the cybersecurity risk-management measures.",
      "type": "recital"
    },
    {
      "id": "recital-7",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R7 describes guidance by ENISA or national competent authorities for the identification, analysis and assessment of risks for the purpose of establishing and maintaining an appropriate risk management framework, which is required by Annex point 2.1.",
          "relation": "provides_guidance_for",
          "target_point": "2.1",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 7,
      "text": "ENISA or national competent authorities under Directive (EU) 2022/2555 can provide guidance to support relevant entities in the identification, analysis, and assessment of risks for the purpose of implementing the technical and the methodological requirements concerning the establishment and maintenance of an appropriate risk management framework. Such guidance can include, in particular, national and sectoral risk assessments as well as risk assessments specific for a certain type of entity. The guidance may also include tools or templates for the development of risk management framework at the level of the relevant entities. Frameworks, guidance or other mechanisms provided by Member States' national law, as well as relevant European and international standards, can also support relevant entities in demonstrating compliance with this Regulation. Moreover, ENISA or national competent authorities under Directive (EU) 2022/2555 can support relevant entities in identifying and implementing appropriate solutions to treat risks identified in such risk assessments. Such guidance should be without prejudice to the relevant entities' obligation to identify and document the risks posed to the security of network and information systems, and to the relevant entities' obligation to implement the technical and the methodological requirements of the cybersecurity risk management measures set out in the Annex to this Regulation according to their needs and resources.",
      "type": "recital"
    },
    {
      "id": "recital-8",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R8 addresses network security measures on latest generation network layer protocols, modern e-mail standards and DNS/routing best practice, and the multistakeholder forum identifying them. These correspond to Annex points 6.7.2(j), (k) and (l).",
          "relation": "concretizes",
          "target_point": "6.7",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 8,
      "text": "Network security measures in relation to: (i) the transition towards latest generation network layer communication protocols, (ii) the deployment of internationally agreed and interoperable modern e-mail communications standards, and (iii) the application of best practices for DNS security, and for Internet routing security and routing hygiene entail specific challenges regarding the identification of best available standards and deployment techniques. To achieve as soon as possible a high common level of cybersecurity across networks, the Commission, with the assistance of the European Union Agency for Cybersecurity (ENISA) and in collaboration with competent authorities, industry - including telecommunication industry - and other stakeholders, should support the development of a multistakeholder forum tasked to identify these best available standards and deployment techniques. Such multi-stakeholder guidance should be without prejudice to the relevant entities' obligation to implement the technical and the methodological requirements of the cybersecurity risk management measures set out in the Annex to this Regulation.",
      "type": "recital"
    },
    {
      "id": "recital-9",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R9 requires a policy on the security of network and information systems as the highest-level document approved by the management bodies, plus topic-specific policies and monitoring indicators. That is the content of Annex point 1.1.",
          "relation": "concretizes",
          "target_point": "1.1",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 9,
      "text": "Pursuant to Article 21(2), point (a), of Directive (EU) 2022/2555, essential and important entities should have, besides policies on risk analysis, policies on information system security. For that purpose, the relevant entities should establish a policy on the security of network and information systems as well as topic-specific policies, such as policies on access control, which should be coherent with the policy on the security of network and information systems. The policy on the security of network and information systems should be the highest-level document setting out the relevant entities' overall approach to their security of network and information systems and should be approved by the management bodies of the relevant entities. The topic-specific policies should be approved by an appropriate level of management. The policy should lay down indicators and measures to monitor its implementation and the current status of relevant entities' maturity level of network and information security, in particular to facilitate the oversight of the implementation of the cybersecurity risk-management measures through the management bodies.",
      "type": "recital"
    },
    {
      "id": "recital-10",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 1 (Policy on the security of network and information systems).",
          "relation": "defines",
          "target_point": "1",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 2 (Risk management policy).",
          "relation": "defines",
          "target_point": "2",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 3 (Incident handling).",
          "relation": "defines",
          "target_point": "3",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 4 (Business continuity and crisis management).",
          "relation": "defines",
          "target_point": "4",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 5 (Supply chain security).",
          "relation": "defines",
          "target_point": "5",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 6 (Security in network and information systems acquisition, development and maintenance).",
          "relation": "defines",
          "target_point": "6",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 7 (Policies and procedures to assess the effectiveness of cybersecurity risk-management measures).",
          "relation": "defines",
          "target_point": "7",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 8 (Basic cyber hygiene practices and security training).",
          "relation": "defines",
          "target_point": "8",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 9 (Cryptography).",
          "relation": "defines",
          "target_point": "9",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 10 (Human resources security).",
          "relation": "defines",
          "target_point": "10",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 11 (Access control).",
          "relation": "defines",
          "target_point": "11",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 12 (Asset management).",
          "relation": "defines",
          "target_point": "12",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 13 (Environmental and physical security).",
          "relation": "defines",
          "target_point": "13",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 10,
      "text": "For the purposes of the technical and the methodological requirements laid down in the Annex to this Regulation, the term 'user' should encompass all legal and natural persons which have access to the entity's network and information systems.",
      "type": "recital"
    },
    {
      "id": "recital-11",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R11 describes the risk management framework, the risk treatment plan and the available risk treatment options, which Annex point 2.1 lays down.",
          "relation": "concretizes",
          "target_point": "2.1",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 11,
      "text": "To identify and address the risks posed to the security of network and information systems, the relevant entities should establish and maintain an appropriate risk management framework. As a part of the risk management framework, the relevant entities should establish, implement and monitor a risk treatment plan. The relevant entities may use the risk treatment plan to identify and prioritise risk treatment options and measures. Options for risk treatment include, in particular, avoiding, reducing or, in exceptional cases, accepting the risk. The choice of risk treatment options should take into account the results of the risk assessment carried out by the relevant entity, and be in accordance with the relevant entity's policy on the security of network and information systems. To give effect to the chosen risk treatment options, the relevant entities should take the appropriate risk treatment measures.",
      "type": "recital"
    },
    {
      "id": "recital-12",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R12 requires monitoring of network and information systems to detect events, near misses and incidents, including timely detection of anomalous traffic and denial of service attacks, corresponding to Annex point 3.2 on monitoring and logging.",
          "relation": "concretizes",
          "target_point": "3.2",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 12,
      "text": "To detect events, near misses and incidents, the relevant entities should monitor their network and information systems and should take actions to evaluate events, near misses and incidents. Those measures should be capable of allowing the detection of network-based attacks based on anomalous inbound and outbound traffic patterns and denial of service attacks in a timely manner.",
      "type": "recital"
    },
    {
      "id": "recital-13",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R13 encourages a comprehensive business impact analysis establishing maximum tolerable downtime and recovery objectives, which Annex point 4.1.3 requires.",
          "relation": "concretizes",
          "target_point": "4.1",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 13,
      "text": "When the relevant entities conduct a business impact analysis, they are encouraged to carry out a comprehensive analysis establishing, as appropriate, maximum tolerable downtime, recovery time objectives, recovery point objectives and service delivery objectives.",
      "type": "recital"
    },
    {
      "id": "recital-14",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R14 requires a supply chain security policy governing relations with direct suppliers and service providers and adequate security clauses in contracts, which is the content of Annex points 5.1.1 and 5.1.4.",
          "relation": "concretizes",
          "target_point": "5.1",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 14,
      "text": "In order to mitigate risks stemming from a relevant entity's supply chain and its relationship with its suppliers, the relevant entities should establish a supply chain security policy which governs their relations with their direct suppliers and service providers. These entities should specify in the contracts with their direct suppliers or service providers adequate security clauses, for example by requiring, where appropriate, cybersecurity risk-management measures according to Article 21(2) of Directive (EU) 2022/2555 or other similar legal requirements.",
      "type": "recital"
    },
    {
      "id": "recital-15",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R15 describes regular security tests based on a dedicated policy and procedures, their possible forms and the use of their findings, corresponding to Annex point 6.5.",
          "relation": "refines",
          "target_point": "6.5",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 15,
      "text": "The relevant entities should regularly carry out security tests based on a dedicated policy and procedures to verify whether the cybersecurity risk-management measures are implemented and function properly. Security tests may be performed on specific network and information systems or on the relevant entity as a whole and may include automated or manual tests, penetration tests, vulnerability scanning, static and dynamic application security tests, configuration tests or security audits. The relevant entities may conduct security tests on their network and information systems at set-up, after infrastructure or application upgrades or modifications that they deem significant, or after maintenance. The findings of the security tests should inform the relevant entities' policies and procedures to assess the effectiveness of the cybersecurity risk-management measures, as well as independent reviews of their network and information security policies.",
      "type": "recital"
    },
    {
      "id": "recital-16",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R16 requires security patch management procedures aligned with change, vulnerability and risk management, which Annex point 6.6 lays down.",
          "relation": "refines",
          "target_point": "6.6",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 16,
      "text": "In order to avoid significant disruption and harm caused by the exploitation of unpatched vulnerabilities in network and information systems, the relevant entities should set out and apply appropriate security patch management procedures which are aligned with the relevant entities' change management, vulnerability management, risk management and other relevant procedures. Relevant entities should take measures proportionate to their resources to ensure that security patches do not introduce additional vulnerabilities or instabilities. In case of planned inaccessibility to the service caused by the application of security patches, the relevant entities are encouraged to duly inform customers in advance.",
      "type": "recital"
    },
    {
      "id": "recital-17",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R17 addresses the management of risks stemming from the acquisition of ICT products and services and the assurance of cybersecurity protection levels, corresponding to Annex point 6.1.",
          "relation": "refines",
          "target_point": "6.1",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 17,
      "text": "The relevant entities should manage the risks stemming from the acquisition of ICT products or ICT services from suppliers or service providers and should obtain assurance that the ICT products or ICT services to be acquired achieve certain cybersecurity protection levels, for example by European cybersecurity certificates and EU statements of conformity for ICT products or ICT services issued under a European cybersecurity certification scheme adopted pursuant to Article 49 of Regulation (EU) 2019/881 of the European Parliament and of the Council. Where the relevant entities set out security requirements to apply to the ICT products to be acquired, they should take into account the essential cybersecurity requirements set out in a regulation of the European Parliament and of the Council on horizontal cybersecurity requirements for products with digital elements.",
      "type": "recital"
    },
    {
      "id": "recital-18",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R18 describes typical network security solutions such as firewalls, limitation of connections, VPN for remote access and time-limited service provider connections, which Annex point 6.7.2 requires.",
          "relation": "refines",
          "target_point": "6.7",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 18,
      "text": "In order to protect against cyber threats and support the prevention and containment of data breaches, the relevant entities should implement network security solutions. Typical solutions for network security include the use of firewalls to protect the relevant entities' internal networks, the limitation of connections and access to services where connections and access are absolutely needed, and the use of virtual private networks for remote access and allowing connections of service providers only after an authorisation request and for a set time period such as the duration of a maintenance operation.",
      "type": "recital"
    },
    {
      "id": "recital-19",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R19 requires controls preventing or detecting unauthorised software and, where appropriate, detection and response software, which is the content of Annex point 6.9.",
          "relation": "refines",
          "target_point": "6.9",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 19,
      "text": "In order to protect the networks of the relevant entities and their information systems against malicious and unauthorised software, those entities should implement controls that prevent or detect the use of unauthorised software and should, where appropriate, use detection and response software. The relevant entities should also consider implementing measures to minimize the attack surface, reduce vulnerabilities that can be exploited by attackers, control the execution of applications on endpoints, and deploy email and web application filters to reduce exposure to malicious content.",
      "type": "recital"
    },
    {
      "id": "recital-20",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R20 sets out basic cyber hygiene practices and awareness raising for users pursuant to Article 21(2), point (g), of Directive (EU) 2022/2555, corresponding to Annex point 8.1.",
          "relation": "refines",
          "target_point": "8.1",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 20,
      "text": "Pursuant to Article 21(2), point (g), of Directive (EU) 2022/2555, Member States are to ensure that essential and important entities apply basic cyber hygiene practices and cybersecurity training. Basic cyber hygiene practices can include zero-trust principles, software updates, device configuration, network segmentation, identity and access management or user awareness, organise training for their staff and raise awareness concerning cyber threats, phishing or social engineering techniques. Cyber hygiene practices are a part of different technical and methodological requirements of the cybersecurity risk management measures set out in the Annex to this Regulation. With regard to basic cyber hygiene practices for users, the relevant entities should consider practices such as clear desk and screen policy, use of multi-factor and other authentication means, safe email use and web browsing, protection from phishing and social engineering, secure remote working practices.",
      "type": "recital"
    },
    {
      "id": "recital-21",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R21 requires a topic-specific policy addressing access by persons and by network and information systems, which Annex point 11.1 lays down.",
          "relation": "refines",
          "target_point": "11.1",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 21,
      "text": "In order to prevent unauthorised access to the relevant entities' assets, the relevant entities should establish and implement a topic-specific policy addressing access by persons and by network and information systems, such as applications.",
      "type": "recital"
    },
    {
      "id": "recital-22",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R22 addresses employee security management measures and awareness of misuse risks, corresponding to Annex point 10.1.",
          "relation": "refines",
          "target_point": "10.1",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R22 states that verification of the background of employees and, where applicable, direct suppliers and service providers contributes to human resources security, which Annex point 10.2 governs.",
          "relation": "refines",
          "target_point": "10.2",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R22 requires a disciplinary process for handling violations of the security policies, which Annex point 10.4 lays down.",
          "relation": "refines",
          "target_point": "10.4",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 22,
      "text": "In order to avoid that employees can misuse, for instance, access rights within the relevant entity to harm and cause damage, relevant entities should consider adequate employee security management measures and raise awareness among personnel about such risks. The relevant entities should establish, communicate and maintain a disciplinary process for handling violations of the relevant entities' network and information system security policies, which may be embedded in other disciplinary processes established by the relevant entities. Verification of the background of the employees and where applicable the direct suppliers and service providers of the relevant entities should contribute to the goal of human resources security in the relevant entities, and may include measures such as checks of the person's criminal record or past professional duties, as appropriate for the person's duties in the relevant entity and in line with the relevant entity's policy on the security of network and information systems.",
      "type": "recital"
    },
    {
      "id": "recital-23",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R23 addresses multi-factor authentication, in particular for remote access and privileged or administration accounts, which Annex point 11.7 requires.",
          "relation": "refines",
          "target_point": "11.7",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 23,
      "text": "Multi-factor authentication can enhance the entities' cybersecurity and should be considered by the entities in particular when users access network and information systems from remote locations, or when they access sensitive information or privileged accounts and system administration accounts. Multi-factor authentication can be combined with other techniques to require additional factors under specific circumstances, based on predefined rules and patterns, such as access from an unusual location, from an unusual device or at an unusual time.",
      "type": "recital"
    },
    {
      "id": "recital-24",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R24 requires sound asset management covering tangible and intangible assets, an asset inventory, classification and protection throughout the lifecycle, which is the subject of Annex point 12.",
          "relation": "refines",
          "target_point": "12",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 24,
      "text": "The relevant entities should manage and protect the assets which are of value to them through a sound asset management which should also serve as the basis for the risk analysis and business continuity management. The relevant entities should manage both tangible and intangible assets and should create an asset inventory, associate the assets with a defined classification level, handle and track the assets and take steps to protect the assets throughout their lifecycle.",
      "type": "recital"
    },
    {
      "id": "recital-25",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R25 describes classification of assets by type, sensitivity, risk level and security requirements, which Annex point 12.1 lays down.",
          "relation": "refines",
          "target_point": "12.1",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R25 states that employees handling assets should be familiar with the asset handling policies and instructions, corresponding to Annex point 12.2.",
          "relation": "refines",
          "target_point": "12.2",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 25,
      "text": "Asset management should involve classifying assets by their type, sensitivity, risk level, and security requirements and applying appropriate measures and controls to ensure their availability, integrity, confidentiality, and authenticity. By classifying assets by risk level, the relevant entities should be able to apply appropriate security measures and controls to protect assets such as encryption, access control including perimeter and physical and logical access control, backups, logging and monitoring, retention and disposal. When conducting a business impact analysis, the relevant entities may determine the classification level based on the consequences of disruption of assets for the entities. All employees of the entities handling assets should be familiar with the asset handling policies and instructions.",
      "type": "recital"
    },
    {
      "id": "recital-26",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R26 describes the appropriate granularity and possible content of the asset inventory, which Annex point 12.4 requires.",
          "relation": "refines",
          "target_point": "12.4",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 26,
      "text": "The granularity of the asset inventory should be appropriate for the needs of the relevant entities. A comprehensive asset inventory could include, for each asset, at least a unique identifier, the owner of the asset, a description of the asset, the location of the asset, the type of asset, the type and classification of information processed in the asset, the date of last update or patch of the asset, the classification of the asset under the risk assessment, and the end of life of the asset. When identifying the owner of an asset, the relevant entities should also identify the person responsible for protecting said asset.",
      "type": "recital"
    },
    {
      "id": "recital-27",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R27 addresses the allocation and organisation of cybersecurity roles, responsibilities and authorities, including possible role types, which Annex point 1.2 lays down.",
          "relation": "refines",
          "target_point": "1.2",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 27,
      "text": "The allocation and organisation of cybersecurity roles, responsibilities and authorities should establish a consistent structure for the governance and implementation of cybersecurity within the relevant entities, and should ensure effective communication in case of incidents. When defining and assigning responsibilities for certain roles, the relevant entities should consider roles such as chief information security officer, information security officer, incident handling officer, auditor, or comparable equivalents. Relevant entities may assign roles and responsibilities to external parties, such as ICT third-party service providers.",
      "type": "recital"
    },
    {
      "id": "recital-28",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R28 derives from the all-hazards approach in Article 21(2) of Directive (EU) 2022/2555 that the requirements must address physical and environmental security, which is the subject of Annex point 13.",
          "relation": "refines",
          "target_point": "13",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R28 states that preventing loss or damage due to failure and disruption of supporting utilities contributes to business continuity, which Annex point 13.1 governs.",
          "relation": "refines",
          "target_point": "13.1",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 28,
      "text": "In accordance with Article 21(2) of Directive (EU) 2022/2555, the cybersecurity risk-management measures are to be based on an all-hazards approach that aims to protect network and information systems and the physical environment of those systems from events such as theft, fire, flood, telecommunication or power failures, or unauthorised physical access and damage to, and interference with, an essential or important entity's information and information processing facilities, which could compromise the availability, authenticity, integrity or confidentiality of stored, transmitted or processed data or of the services offered by, or accessible via, network and information systems. The technical and the methodological requirements of the cybersecurity risk-management measures should therefore also address the physical and environmental security of network and information systems by including measures to protect such systems from system failures, human error, malicious acts or natural phenomena. Further examples of physical and environmental threats can include earthquakes, explosions, sabotage, insider threat, civil unrest, toxic waste, and environmental emissions. Prevention of loss, damage or compromise of network and information systems or interruption to their operations due to the failure and disruption of supporting utilities should contribute to the goal of business continuity in the relevant entities. Moreover, protection against physical and environmental threats should contribute to security of network and information systems maintenance in the relevant entities.",
      "type": "recital"
    },
    {
      "id": "recital-29",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R29 requires protection measures against physical and environmental threats, minimum and maximum control thresholds and monitoring of environmental parameters, which Annex point 13.2 lays down.",
          "relation": "concretizes",
          "target_point": "13.2",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 29,
      "text": "Relevant entities should design and implement protection measures against physical and environmental threats and determine minimum and maximum control thresholds for physical and environmental threats and monitor environmental parameters. For example, they should consider installing systems to detect at an early stage the flooding of areas where network and information systems are located. Regarding fire hazard, the relevant entities should consider the establishment of a separate fire compartment for the data centre, the use of fire-resistant materials, sensors for monitoring temperature and humidity, the connection of the building to a fire alarm system with an automated notification to the local fire department, and early fire detection and extinguishing systems. The relevant entities should also carry out regular fire drills and fire inspections. Furthermore, to ensure power supply, the relevant entities should consider overvoltage protection and corresponding emergency power supply, in accordance with relevant standards. Moreover, as overheating poses a risk to the availability of network and information systems, relevant entities, in particular data centre service providers, could consider adequate, continuous and redundant air conditioning systems.",
      "type": "recital"
    },
    {
      "id": "recital-30",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Concretizes the horizontal criteria for significant incidents by explaining the Regulation specifies exhaustive criteria to enable entities to assess significance for notification.",
          "relation": "concretizes",
          "target_article": 3,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R30, third sentence, states that the criteria set out in this Regulation should be considered exhaustive, without prejudice to Article 5 of Directive (EU) 2022/2555. That exhaustiveness is a distinct normative qualification of the criteria catalogue in Art3P1, going beyond the concretisation already captured.",
          "relation": "qualifies",
          "target_article": 3,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 30,
      "text": "This Regulation is to further specify the cases in which an incident should be considered to be significant for the purpose of Article 23(3) of Directive (EU) 2022/2555. The criteria should be such that relevant entities are able to assess whether an incident is significant, in order to notify the incident in accordance with Directive (EU) 2022/2555. Furthermore, the criteria set out in this Regulation should be considered exhaustive, without prejudice to Article 5 of Directive (EU) 2022/2555. This regulation specifies the cases in which an incident should be considered to be significant by setting out horizontal as well as entity-type specific cases.",
      "type": "recital"
    },
    {
      "id": "recital-31",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R31 determines the moment at which a relevant entity is to be regarded as having become aware of a significant incident and the standard of the initial assessment. It thereby guides the application of the significance criteria in Art3P1 (and corresponds to Annex point 3.4.1 on event assessment and classification).",
          "relation": "provides_guidance_for",
          "target_article": 3,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R31 requires the relevant entity to assess a suspicious event in a timely manner to determine whether it constitutes an incident and, if so, its nature and severity. That is verbatim the obligation in Annex point 3.4.1, which governs when the entity becomes aware of a significant incident.",
          "relation": "provides_guidance_for",
          "target_point": "3.4",
          "target_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 31,
      "text": "Pursuant to Article 23(4) of Directive (EU) 2022/2555, relevant entities should be required to notify significant incidents within the deadlines set by that provision. Those notification deadlines are running from the moment the entity becomes aware of such significant incidents. The relevant entity is therefore required to report incidents that, based on its initial assessment, could cause severe operational disruption of the services or financial loss for that entity or affect other natural or legal persons by causing considerable material or non-material damage. Therefore, when a relevant entity has detected a suspicious event, or after a potential incident has been brought to its attention by a third party, such as an individual, a customer, an entity, an authority, a media organisation, or another source, the relevant entity should assess in a timely manner the suspicious event to determine whether it constitutes an incident and, if so, determine its nature and severity. The relevant entity is therefore to be regarded as having become \u201caware\u201d of the significant incident when, after such initial assessment, that entity has a reasonable degree of certainty that a significant incident has occurred.",
      "type": "recital"
    },
    {
      "id": "recital-32",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R32 opens with the purpose of establishing whether an incident is significant and is therefore not limited to the counting method in Art3P3 or to trust services in Art14; it guides the significance assessment under Art3P1 as a whole.",
          "relation": "provides_guidance_for",
          "target_article": 3,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Directly explains how to count the number of users impacted by an incident, including business customers and associated natural and legal persons, and provides estimation methodology when exact counts are unavailable.",
          "relation": "provides_guidance_for",
          "target_article": 3,
          "target_paragraph": "3",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Explains that trust service providers should also consider the number of relying parties when establishing significance, and defines 'relying parties' as natural or legal persons that rely upon a trust service.",
          "relation": "provides_guidance_for",
          "target_article": 14,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 32,
      "text": "With a view to establishing whether an incident is significant, where relevant, relevant entities should count the number of users impacted by the incident, taking into consideration business and end customers with whom the relevant entities have a contractual relationship as well as natural and legal persons that are associated with business customers. Where a relevant entity is unable to calculate the number of impacted users, the relevant entity\u2019s estimate of the possible maximum number of affected users should be considered for the purpose of calculating the total number of users affected by the incident. The significance of an incident involving a trust service should not only be determined by the number of users but also by the number of relying parties as these can be equally affected by a significant incident involving a trust service in regard to operational disruption and material or non-material damage. Therefore, trust service providers should, where applicable, also take into account the number of relying parties when establishing whether an incident is significant. For that purpose, relying parties should be understood as natural or legal persons that rely upon a trust service.",
      "type": "recital"
    },
    {
      "id": "recital-33",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Clarifies that scheduled maintenance operations and pre-determined contractual interruptions resulting in limited availability or unavailability should not be considered significant incidents, elaborating on Article 3(2)'s exception.",
          "relation": "provides_guidance_for",
          "target_article": 3,
          "target_paragraph": "2",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 33,
      "text": "Maintenance operations resulting in the limited availability or unavailability of the services should not be considered as significant incidents if the limited availability or unavailability of the service occurs according to a scheduled maintenance operation. Moreover, where a service is unavailable due to scheduled interruptions such as interruptions or non-availability based on pre-determined contractual agreement should not be considered as significant incident.",
      "type": "recital"
    },
    {
      "id": "recital-34",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Provides the methodology for measuring the duration of an availability-impacting incident, which is used to assess the significance criteria in Article 3(1).",
          "relation": "provides_guidance_for",
          "target_article": 3,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R34 defines how the duration of an availability-affecting incident is measured. Art5 sets duration-based thresholds for DNS service providers, which can only be applied using that measurement rule.",
          "relation": "defines",
          "target_article": 5,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R34 defines how the duration of an availability-affecting incident is measured. Art6 sets duration-based thresholds for TLD name registries, which can only be applied using that measurement rule.",
          "relation": "defines",
          "target_article": 6,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R34 defines how the duration of an availability-affecting incident is measured. Art7 sets duration-based thresholds for cloud computing service providers, which can only be applied using that measurement rule.",
          "relation": "defines",
          "target_article": 7,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R34 defines how the duration of an availability-affecting incident is measured. Art9 sets duration-based thresholds for content delivery network providers, which can only be applied using that measurement rule.",
          "relation": "defines",
          "target_article": 9,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R34 defines how the duration of an availability-affecting incident is measured. Art10 sets duration-based thresholds for managed service providers and managed security service providers, which can only be applied using that measurement rule.",
          "relation": "defines",
          "target_article": 10,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R34 defines incident duration, which Art14 uses as a significance criterion for trust service providers (Art14 points (a) to (c)).",
          "relation": "defines",
          "target_article": 14,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 34,
      "text": "The duration of an incident which impacts availability of a service should be measured from the disruption of the proper provision of such service until the time of recovery. Where a relevant entity is unable to determine the moment when the disruption began, the duration of the incident should be measured from the moment the incident was detected, or from the moment when the incident was recorded in network or system logs or other data sources, whichever is earlier.",
      "type": "recital"
    },
    {
      "id": "recital-35",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Provides the methodology for measuring complete unavailability of a service, a core concept underlying the significance criteria in Article 3(1).",
          "relation": "provides_guidance_for",
          "target_article": 3,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art5 applies that criterion to DNS service providers, so the definition in R35 governs the entity-specific threshold directly.",
          "relation": "defines",
          "target_article": 5,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art6 applies that criterion to TLD name registries, so the definition in R35 governs the entity-specific threshold directly.",
          "relation": "defines",
          "target_article": 6,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art7 applies that criterion to cloud computing service providers, so the definition in R35 governs the entity-specific threshold directly.",
          "relation": "defines",
          "target_article": 7,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art8 applies that criterion to data centre service providers, so the definition in R35 governs the entity-specific threshold directly.",
          "relation": "defines",
          "target_article": 8,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art9 applies that criterion to content delivery network providers, so the definition in R35 governs the entity-specific threshold directly.",
          "relation": "defines",
          "target_article": 9,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art10 applies that criterion to managed service providers and managed security service providers, so the definition in R35 governs the entity-specific threshold directly.",
          "relation": "defines",
          "target_article": 10,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art11 applies that criterion to providers of online marketplaces, so the definition in R35 governs the entity-specific threshold directly.",
          "relation": "defines",
          "target_article": 11,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art12 applies that criterion to providers of online search engines, so the definition in R35 governs the entity-specific threshold directly.",
          "relation": "defines",
          "target_article": 12,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art13 applies that criterion to providers of social networking services platforms, so the definition in R35 governs the entity-specific threshold directly.",
          "relation": "defines",
          "target_article": 13,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R35 defines complete unavailability, which Art14 uses as a significance criterion for trust service providers (Art14 points (a) to (c)).",
          "relation": "defines",
          "target_article": 14,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 35,
      "text": "Complete unavailability of a service should be measured from the moment the service is fully unavailable to users, to the moment when regular activities or operations have been restored to the level of service that was provided prior to the incident. Where a relevant entity is unable to determine when the complete unavailability of a service began, the unavailability should be measured from the moment it was detected by that entity.",
      "type": "recital"
    },
    {
      "id": "recital-36",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Defines what constitutes 'direct financial loss' as used in Article 3(1)(a) by specifying included costs (replacement, staff, legal, remediation, lost revenue) and explicitly excluding administrative fines and day-to-day operational costs.",
          "relation": "defines",
          "target_article": 3,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Recital 36 defines the direct-financial-loss criterion in Article 3(1)(a). Article 4(c) expressly incorporates that criterion for recurring incidents, so the definition directly guides the collective assessment under Article 4.",
          "relation": "provides_guidance_for",
          "target_article": 4,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 36,
      "text": "For the purpose of determining the direct financial losses resulting from an incident, relevant entities should take into account all the financial losses which they have incurred as a result of the incident, such as costs for replacement or relocation of software, hardware or infrastructure, staff costs, including costs associated with replacement or relocation of staff, recruitment of extra staff, remuneration of overtime and recovery of lost or impaired skills, fees due to non-compliance with contractual obligations, costs for redress and compensation to customers, losses due to forgone revenues, costs associated with internal and external communication, advisory costs, including costs associated with legal counselling, forensic services and remediation services, and other costs associated to the incident. However, administrative fines, as well as costs that are necessary for the day-to-day operation of the business, should not be considered as financial losses resulting from an incident, including costs for general maintenance of infrastructure, equipment, hardware and software, keeping skills of staff up to date, internal or external costs to enhance the business after the incident, including upgrades, improvements and risk assessment initiatives, and insurance premiums. The relevant entities should calculate the amounts of financial losses based on available data and, where the actual amounts of financial losses cannot be determined, the entities should estimate those amounts.",
      "type": "recital"
    },
    {
      "id": "recital-37",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Provides guidance on determining when an incident has caused or is capable of causing the death of a natural person (Article 3(1)(c)) or considerable damage to health (Article 3(1)(d)), with examples such as unavailability of healthcare services.",
          "relation": "provides_guidance_for",
          "target_article": 3,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 37,
      "text": "Relevant entities should also be obliged to report incidents that have caused or are capable of causing the death of natural persons or considerable damage to natural persons\u2019 health as such incidents are particularly serious cases of causing considerable material or non-material damage. For instance, an incident affecting a relevant entity could cause unavailability of healthcare or emergency services, or the loss of confidentiality or integrity of data with an effect on the health of natural persons. For the purpose of determining whether an incident has caused or is capable of causing considerable damage to a natural person\u2019s health, relevant entities should take into account whether the incident caused or is capable of causing severe injuries and ill-health. For that purpose, the relevant entities should not be required to collect additional information to which they do not have access.",
      "type": "recital"
    },
    {
      "id": "recital-38",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Defines 'limited availability' as used in the significance criteria under Article 3(1) \u2014 slower than average response times or partial loss of service functionality, with reference to objective criteria based on average response times.",
          "relation": "defines",
          "target_article": 3,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R38 defines when limited availability is to be assumed. Art7 uses limited availability as a significance criterion for cloud computing service providers, so R38 governs its interpretation.",
          "relation": "defines",
          "target_article": 7,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R38 defines when limited availability is to be assumed. Art8 uses limited availability as a significance criterion for data centre service providers, so R38 governs its interpretation.",
          "relation": "defines",
          "target_article": 8,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R38 defines when limited availability is to be assumed. Art9 uses limited availability as a significance criterion for content delivery network providers, so R38 governs its interpretation.",
          "relation": "defines",
          "target_article": 9,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R38 defines when limited availability is to be assumed. Art10 uses limited availability as a significance criterion for managed service providers and managed security service providers, so R38 governs its interpretation.",
          "relation": "defines",
          "target_article": 10,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R38 defines when limited availability is to be assumed. Art11 uses limited availability as a significance criterion for providers of online marketplaces, so R38 governs its interpretation.",
          "relation": "defines",
          "target_article": 11,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R38 defines when limited availability is to be assumed. Art12 uses limited availability as a significance criterion for providers of online search engines, so R38 governs its interpretation.",
          "relation": "defines",
          "target_article": 12,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R38 defines when limited availability is to be assumed. Art13 uses limited availability as a significance criterion for providers of social networking services platforms, so R38 governs its interpretation.",
          "relation": "defines",
          "target_article": 13,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R38 defines limited availability, which Art14 uses as a significance criterion for trust service providers (Art14 points (a) to (c)).",
          "relation": "defines",
          "target_article": 14,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 38,
      "text": "Limited availability should be considered to occur in particular when a service provided by a relevant entity is considerably slower than average response time, or where not all functionalities of a service are available. Where possible, objective criteria based on the average response times of services provided by the relevant entities should be used to assess delays in response time. A functionality of a service may be, for instance, a chat functionality or an image search functionality.",
      "type": "recital"
    },
    {
      "id": "recital-39",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Illustrates when successful, suspectedly malicious and unauthorised access is 'capable of causing severe operational disruption' as required by Article 3(1)(e), with the example of a cyber threat actor pre-positioning for future disruption.",
          "relation": "provides_guidance_for",
          "target_article": 3,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 39,
      "text": "Successful, suspectedly malicious and unauthorised access to a relevant entity\u2019s network and information systems should be regarded as a significant incident, where such access is capable of causing severe operational disruption. For instance, where a cyber threat actor pre-positions itself in a relevant entity\u2019s network and information systems with a view to causing disruption of services in the future, the incident should be considered to be significant.",
      "type": "recital"
    },
    {
      "id": "recital-40",
      "inbound_relations": [],
      "outbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Directly explains the rationale and criteria for treating recurring incidents as a single significant incident: same apparent root cause, minimum two occurrences within six months, and collective satisfaction of the financial loss threshold.",
          "relation": "provides_guidance_for",
          "target_article": 4,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "recital_number": 40,
      "text": "Recurring incidents that are linked through the same apparent root cause, which individually do not meet the criteria of a significant incident, should collectively be considered to be a significant incident, provided that they collectively meet the criterion for financial loss, and that they have occurred at least twice within six months. Such recurring incidents can indicate significant deficiencies and weaknesses in the relevant entity\u2019s cybersecurity risk management procedures and their level of cybersecurity maturity. Moreover, such recurring incidents are capable of causing significant financial loss for the relevant entity.",
      "type": "recital"
    },
    {
      "id": "recital-41",
      "inbound_relations": [],
      "outbound_relations": [],
      "recital_number": 41,
      "text": "The Commission has exchanged advice and cooperated with the Cooperation Group and ENISA on the draft implementing act, in accordance with Articles 21(5) and 23(11) of Directive (EU) 2022/2555.",
      "type": "recital"
    },
    {
      "id": "recital-42",
      "inbound_relations": [],
      "outbound_relations": [],
      "recital_number": 42,
      "text": "The European Data Protection Supervisor was consulted in accordance with Article 42(1) of Regulation (EU) 2018/1725 of the European Parliament and of the Council3, and delivered its opinion on 1 September 2024.",
      "type": "recital"
    },
    {
      "id": "recital-43",
      "inbound_relations": [],
      "outbound_relations": [],
      "recital_number": 43,
      "text": "The measures provided for in this Regulation are in accordance with the opinion of the committee established in accordance with Article 39 of Directive (EU) 2022/2555, 3 Regulation (EU) 2018/1725 of the European Parliament and of the Council of 23 October 2018 on the protection of natural persons with regard to the processing of personal data by the Union institutions, bodies, offices and agencies and on the free movement of such data, and repealing Regulation (EC) No 45/2001 and Decision No 1247/2002/EC (OJ L 295, 21.11.2018, p. 39, ELI: http://data.europa.eu/eli/reg/2018/1725/oj).",
      "type": "recital"
    },
    {
      "id": "article-Art1-UN1",
      "type": "article_paragraph",
      "article_number": 1,
      "paragraph_number": null,
      "akn4eu_paragraph_kind": "unnumbered",
      "akn4eu_article_kind": "definition",
      "akn4eu_heading": "Subject matter",
      "akn4eu_sub_units": [],
      "ancestry": [],
      "text": "This Regulation, with regard to DNS service providers, TLD name registries, cloud computing service providers, data centre service providers, content delivery network providers, managed service providers, managed security service providers, providers of online market places, of online search engines and of social networking services platforms, and trust service providers (the relevant entities) lays down the technical and the methodological requirements of the measures referred to in Article\u00a021(2) of Directive (EU)\u00a02022/2555 and further specifies the cases in which an incident shall be considered to be significant as referred to in Article\u00a023(3) of Directive (EU)\u00a02022/2555.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Recital 1 mirrors the language of Article 1 almost verbatim, explaining the Regulation's dual purpose: laying down technical/methodological requirements for Article 21(2) NIS2 measures and specifying significant incidents under Article 23(3) NIS2.",
          "relation": "provides_guidance_for",
          "source_recital": 1,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ]
    },
    {
      "article_number": 2,
      "id": "article-Art2-Para1",
      "inbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 1 implements Article 21(2), point (a).",
          "relation": "gives_effect_to",
          "source_point": "1",
          "source_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 2 implements Article 21(2), point (a).",
          "relation": "gives_effect_to",
          "source_point": "2",
          "source_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 3 implements Article 21(2), point (b).",
          "relation": "gives_effect_to",
          "source_point": "3",
          "source_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 4 implements Article 21(2), point (c).",
          "relation": "gives_effect_to",
          "source_point": "4",
          "source_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 5 implements Article 21(2), point (d).",
          "relation": "gives_effect_to",
          "source_point": "5",
          "source_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 6 implements Article 21(2), point (e).",
          "relation": "gives_effect_to",
          "source_point": "6",
          "source_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 7 implements Article 21(2), point (f).",
          "relation": "gives_effect_to",
          "source_point": "7",
          "source_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 8 implements Article 21(2), point (g).",
          "relation": "gives_effect_to",
          "source_point": "8",
          "source_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 9 implements Article 21(2), point (h).",
          "relation": "gives_effect_to",
          "source_point": "9",
          "source_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 10 implements Article 21(2), point (i).",
          "relation": "gives_effect_to",
          "source_point": "10",
          "source_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 11 implements Article 21(2), point (i and j).",
          "relation": "gives_effect_to",
          "source_point": "11",
          "source_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 12 implements Article 21(2), point (i).",
          "relation": "gives_effect_to",
          "source_point": "12",
          "source_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 13 implements Article 21(2), point (c, e and i).",
          "relation": "gives_effect_to",
          "source_point": "13",
          "source_type": "annex_point",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "outbound_relations": [],
      "paragraph_number": "1",
      "text": "For the relevant entities the technical and methodological requirements of cybersecurity risk-management measures referred to in Article\u00a021(2), points (a) to (j), of Directive (EU)\u00a02022/2555 are set out in the Annex to this Regulation.",
      "type": "article_paragraph",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Technical and methodological requirements",
      "akn4eu_sub_units": [],
      "ancestry": []
    },
    {
      "article_number": 2,
      "id": "article-Art2-Para2",
      "inbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Recital 4 explains the proportionality principle that underpins Article 2(2)'s requirement to ensure a risk-appropriate level of security, enumerating factors such as risk exposure, size, and incident likelihood.",
          "relation": "provides_guidance_for",
          "source_recital": 4,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Recital 5 expands on Article 2(2) by introducing compensating measures as an alternative for entities unable to implement certain requirements due to size, providing concrete examples such as management oversight for micro-entities.",
          "relation": "expands",
          "source_recital": 5,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Recital 6 provides concrete interpretive guidance on the 'where appropriate', 'where applicable', or 'to the extent feasible' qualifiers used in Article 2(2), explaining the documentation obligation and adding that authorities may consider implementation timelines.",
          "relation": "concretizes",
          "source_recital": 6,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "outbound_relations": [],
      "paragraph_number": "2",
      "text": "The relevant entities shall ensure a level of security of network and information systems appropriate to the risks posed when implementing and applying the technical and methodological requirements of cybersecurity risk-management measures set out in the Annex to this Regulation. For that purpose, they shall take due account of the degree of their exposure to risks, their size and the likelihood of occurrence of incidents and their severity, including their societal and economic impact, when complying with the technical and methodological requirements of cybersecurity risk-management measures set out in the Annex to this Regulation.",
      "type": "article_paragraph",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Technical and methodological requirements",
      "akn4eu_sub_units": [],
      "ancestry": []
    },
    {
      "id": "article-Art2-UN1",
      "type": "article_paragraph",
      "article_number": 2,
      "paragraph_number": null,
      "akn4eu_paragraph_kind": "unnumbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Technical and methodological requirements",
      "akn4eu_sub_units": [],
      "ancestry": [],
      "text": "Where the Annex to this Regulation provides that a technical or methodological requirement of a cybersecurity risk-management measure shall be applied \u2018where appropriate\u2019, \u2018where applicable\u2019 or \u2018to the extent feasible\u2019, and where a relevant entity considers it not appropriate, not applicable or not feasible for the relevant entity to apply certain such technical and methodological requirements, the relevant entity shall in a comprehensible manner document its reasoning to that effect.",
      "outbound_relations": [],
      "inbound_relations": []
    },
    {
      "article_number": 3,
      "id": "article-Art3-Para1",
      "inbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Concretizes the horizontal criteria for significant incidents by explaining the Regulation specifies exhaustive criteria to enable entities to assess significance for notification.",
          "relation": "concretizes",
          "source_recital": 30,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R30, third sentence, states that the criteria set out in this Regulation should be considered exhaustive, without prejudice to Article 5 of Directive (EU) 2022/2555. That exhaustiveness is a distinct normative qualification of the criteria catalogue in Art3P1, going beyond the concretisation already captured.",
          "relation": "qualifies",
          "source_recital": 30,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R31 determines the moment at which a relevant entity is to be regarded as having become aware of a significant incident and the standard of the initial assessment. It thereby guides the application of the significance criteria in Art3P1 (and corresponds to Annex point 3.4.1 on event assessment and classification).",
          "relation": "provides_guidance_for",
          "source_recital": 31,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R32 opens with the purpose of establishing whether an incident is significant and is therefore not limited to the counting method in Art3P3 or to trust services in Art14; it guides the significance assessment under Art3P1 as a whole.",
          "relation": "provides_guidance_for",
          "source_recital": 32,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Provides the methodology for measuring the duration of an availability-impacting incident, which is used to assess the significance criteria in Article 3(1).",
          "relation": "provides_guidance_for",
          "source_recital": 34,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Provides the methodology for measuring complete unavailability of a service, a core concept underlying the significance criteria in Article 3(1).",
          "relation": "provides_guidance_for",
          "source_recital": 35,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Defines what constitutes 'direct financial loss' as used in Article 3(1)(a) by specifying included costs (replacement, staff, legal, remediation, lost revenue) and explicitly excluding administrative fines and day-to-day operational costs.",
          "relation": "defines",
          "source_recital": 36,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Provides guidance on determining when an incident has caused or is capable of causing the death of a natural person (Article 3(1)(c)) or considerable damage to health (Article 3(1)(d)), with examples such as unavailability of healthcare services.",
          "relation": "provides_guidance_for",
          "source_recital": 37,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Defines 'limited availability' as used in the significance criteria under Article 3(1) \u2014 slower than average response times or partial loss of service functionality, with reference to objective criteria based on average response times.",
          "relation": "defines",
          "source_recital": 38,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Illustrates when successful, suspectedly malicious and unauthorised access is 'capable of causing severe operational disruption' as required by Article 3(1)(e), with the example of a cyber threat actor pre-positioning for future disruption.",
          "relation": "provides_guidance_for",
          "source_recital": 39,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "outbound_relations": [],
      "paragraph_number": "1",
      "text": "An incident shall be considered to be significant for the purposes of Article\u00a023(3) of Directive (EU)\u00a02022/2555 with regard to the relevant entities where one or more of the following criteria are fulfilled:",
      "type": "article_paragraph",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Significant incidents",
      "akn4eu_sub_units": [],
      "ancestry": []
    },
    {
      "article_number": 3,
      "id": "article-Art3-Para2",
      "inbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Clarifies that scheduled maintenance operations and pre-determined contractual interruptions resulting in limited availability or unavailability should not be considered significant incidents, elaborating on Article 3(2)'s exception.",
          "relation": "provides_guidance_for",
          "source_recital": 33,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "outbound_relations": [],
      "paragraph_number": "2",
      "text": "Scheduled interruptions of service and planned consequences of scheduled maintenance operations carried out by or on behalf of the relevant entities shall not be considered to be significant incidents.",
      "type": "article_paragraph",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Significant incidents",
      "akn4eu_sub_units": [],
      "ancestry": []
    },
    {
      "article_number": 3,
      "id": "article-Art3-Para3",
      "inbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Directly explains how to count the number of users impacted by an incident, including business customers and associated natural and legal persons, and provides estimation methodology when exact counts are unavailable.",
          "relation": "provides_guidance_for",
          "source_recital": 32,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "outbound_relations": [],
      "paragraph_number": "3",
      "text": "When calculating the number of users impacted by an incident for the purpose of Articles\u00a07 and\u00a09 to 14, the relevant entities shall consider all of the following:",
      "type": "article_paragraph",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Significant incidents",
      "akn4eu_sub_units": [],
      "ancestry": []
    },
    {
      "id": "article-Art4-UN1",
      "type": "article_paragraph",
      "article_number": 4,
      "paragraph_number": null,
      "akn4eu_paragraph_kind": "unnumbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Recurring incidents",
      "akn4eu_sub_units": [],
      "ancestry": [],
      "text": "Incidents that individually are not considered a significant incident within the meaning of Article\u00a03, shall be considered collectively as one significant incident where they meet all of the following criteria:",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Recital 36 defines the direct-financial-loss criterion in Article 3(1)(a). Article 4(c) expressly incorporates that criterion for recurring incidents, so the definition directly guides the collective assessment under Article 4.",
          "relation": "provides_guidance_for",
          "source_recital": 36,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Directly explains the rationale and criteria for treating recurring incidents as a single significant incident: same apparent root cause, minimum two occurrences within six months, and collective satisfaction of the financial loss threshold.",
          "relation": "provides_guidance_for",
          "source_recital": 40,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ]
    },
    {
      "id": "article-Art5-UN1",
      "type": "article_paragraph",
      "article_number": 5,
      "paragraph_number": null,
      "akn4eu_paragraph_kind": "unnumbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Significant incidents with regard to DNS service providers",
      "akn4eu_sub_units": [],
      "ancestry": [],
      "text": "With regard to DNS service providers, an incident shall be considered significant under Article\u00a03(1)(g), where it fulfils one or more of the following criteria:",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R34 defines how the duration of an availability-affecting incident is measured. Art5 sets duration-based thresholds for DNS service providers, which can only be applied using that measurement rule.",
          "relation": "defines",
          "source_recital": 34,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art5 applies that criterion to DNS service providers, so the definition in R35 governs the entity-specific threshold directly.",
          "relation": "defines",
          "source_recital": 35,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ]
    },
    {
      "id": "article-Art6-UN1",
      "type": "article_paragraph",
      "article_number": 6,
      "paragraph_number": null,
      "akn4eu_paragraph_kind": "unnumbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Significant incidents with regard to TLD name registries",
      "akn4eu_sub_units": [],
      "ancestry": [],
      "text": "With regard to TLD name registries, an incident shall be considered significant under Article\u00a03(1)(g) where it fulfils one or more of the following criteria:",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R34 defines how the duration of an availability-affecting incident is measured. Art6 sets duration-based thresholds for TLD name registries, which can only be applied using that measurement rule.",
          "relation": "defines",
          "source_recital": 34,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art6 applies that criterion to TLD name registries, so the definition in R35 governs the entity-specific threshold directly.",
          "relation": "defines",
          "source_recital": 35,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ]
    },
    {
      "id": "article-Art7-UN1",
      "type": "article_paragraph",
      "article_number": 7,
      "paragraph_number": null,
      "akn4eu_paragraph_kind": "unnumbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Significant incidents with regard to cloud computing service providers",
      "akn4eu_sub_units": [],
      "ancestry": [],
      "text": "With regard to cloud computing service providers, an incident shall be considered significant under Article\u00a03(1)(g) where it fulfils one or more of the following criteria:",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R34 defines how the duration of an availability-affecting incident is measured. Art7 sets duration-based thresholds for cloud computing service providers, which can only be applied using that measurement rule.",
          "relation": "defines",
          "source_recital": 34,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art7 applies that criterion to cloud computing service providers, so the definition in R35 governs the entity-specific threshold directly.",
          "relation": "defines",
          "source_recital": 35,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R38 defines when limited availability is to be assumed. Art7 uses limited availability as a significance criterion for cloud computing service providers, so R38 governs its interpretation.",
          "relation": "defines",
          "source_recital": 38,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ]
    },
    {
      "id": "article-Art8-UN1",
      "type": "article_paragraph",
      "article_number": 8,
      "paragraph_number": null,
      "akn4eu_paragraph_kind": "unnumbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Significant incidents with regard to data centre service providers",
      "akn4eu_sub_units": [],
      "ancestry": [],
      "text": "With regard to data centre service providers, an incident shall be considered significant under Article\u00a03(1)(g) where it fulfils one or more of the following criteria:",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art8 applies that criterion to data centre service providers, so the definition in R35 governs the entity-specific threshold directly.",
          "relation": "defines",
          "source_recital": 35,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R38 defines when limited availability is to be assumed. Art8 uses limited availability as a significance criterion for data centre service providers, so R38 governs its interpretation.",
          "relation": "defines",
          "source_recital": 38,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ]
    },
    {
      "id": "article-Art9-UN1",
      "type": "article_paragraph",
      "article_number": 9,
      "paragraph_number": null,
      "akn4eu_paragraph_kind": "unnumbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Significant incidents with regard to content delivery network providers",
      "akn4eu_sub_units": [],
      "ancestry": [],
      "text": "With regard to content delivery network providers, an incident shall be considered significant under Article\u00a03(1)(g) where it fulfils one or more of the following criteria:",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R34 defines how the duration of an availability-affecting incident is measured. Art9 sets duration-based thresholds for content delivery network providers, which can only be applied using that measurement rule.",
          "relation": "defines",
          "source_recital": 34,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art9 applies that criterion to content delivery network providers, so the definition in R35 governs the entity-specific threshold directly.",
          "relation": "defines",
          "source_recital": 35,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R38 defines when limited availability is to be assumed. Art9 uses limited availability as a significance criterion for content delivery network providers, so R38 governs its interpretation.",
          "relation": "defines",
          "source_recital": 38,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ]
    },
    {
      "id": "article-Art10-UN1",
      "type": "article_paragraph",
      "article_number": 10,
      "paragraph_number": null,
      "akn4eu_paragraph_kind": "unnumbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Significant incidents with regard to managed service providers and managed security service providers",
      "akn4eu_sub_units": [],
      "ancestry": [],
      "text": "With regard to managed service providers and managed security service providers, an incident shall be considered significant under Article\u00a03(1)(g) where it fulfils one or more of the following criteria:",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R34 defines how the duration of an availability-affecting incident is measured. Art10 sets duration-based thresholds for managed service providers and managed security service providers, which can only be applied using that measurement rule.",
          "relation": "defines",
          "source_recital": 34,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art10 applies that criterion to managed service providers and managed security service providers, so the definition in R35 governs the entity-specific threshold directly.",
          "relation": "defines",
          "source_recital": 35,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R38 defines when limited availability is to be assumed. Art10 uses limited availability as a significance criterion for managed service providers and managed security service providers, so R38 governs its interpretation.",
          "relation": "defines",
          "source_recital": 38,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ]
    },
    {
      "id": "article-Art11-UN1",
      "type": "article_paragraph",
      "article_number": 11,
      "paragraph_number": null,
      "akn4eu_paragraph_kind": "unnumbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Significant incidents with regard to providers of online marketplaces",
      "akn4eu_sub_units": [],
      "ancestry": [],
      "text": "With regard to providers of online marketplaces, an incident shall be considered significant under Article\u00a03(1)(g) where it fulfils one or more of the following criteria:",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art11 applies that criterion to providers of online marketplaces, so the definition in R35 governs the entity-specific threshold directly.",
          "relation": "defines",
          "source_recital": 35,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R38 defines when limited availability is to be assumed. Art11 uses limited availability as a significance criterion for providers of online marketplaces, so R38 governs its interpretation.",
          "relation": "defines",
          "source_recital": 38,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ]
    },
    {
      "id": "article-Art12-UN1",
      "type": "article_paragraph",
      "article_number": 12,
      "paragraph_number": null,
      "akn4eu_paragraph_kind": "unnumbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Significant incidents with regard to providers of online search engines",
      "akn4eu_sub_units": [],
      "ancestry": [],
      "text": "With regard to providers of online search engines, an incident shall be considered significant under Article\u00a03(1)(g) where it fulfils one or more of the following criteria:",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art12 applies that criterion to providers of online search engines, so the definition in R35 governs the entity-specific threshold directly.",
          "relation": "defines",
          "source_recital": 35,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R38 defines when limited availability is to be assumed. Art12 uses limited availability as a significance criterion for providers of online search engines, so R38 governs its interpretation.",
          "relation": "defines",
          "source_recital": 38,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ]
    },
    {
      "id": "article-Art13-UN1",
      "type": "article_paragraph",
      "article_number": 13,
      "paragraph_number": null,
      "akn4eu_paragraph_kind": "unnumbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Significant incidents with regard to providers of social networking services platforms",
      "akn4eu_sub_units": [],
      "ancestry": [],
      "text": "With regard to providers of social networking services platforms, an incident shall be considered significant under Article\u00a03(1)(g) where it fulfils one or more of the following criteria:",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "confidence": "high",
          "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art13 applies that criterion to providers of social networking services platforms, so the definition in R35 governs the entity-specific threshold directly.",
          "relation": "defines",
          "source_recital": 35,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R38 defines when limited availability is to be assumed. Art13 uses limited availability as a significance criterion for providers of social networking services platforms, so R38 governs its interpretation.",
          "relation": "defines",
          "source_recital": 38,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ]
    },
    {
      "id": "article-Art14-UN1",
      "type": "article_paragraph",
      "article_number": 14,
      "paragraph_number": null,
      "akn4eu_paragraph_kind": "unnumbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Significant incidents with regard to trust service providers",
      "akn4eu_sub_units": [],
      "ancestry": [],
      "text": "With regard to trust service providers, an incident shall be considered significant under Article\u00a03(1)(g) where it fulfils one or more of the following criteria:",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "confidence": "high",
          "reasoning": "Recital 2 specifically addresses trust service providers, and Article 14 sets out the entity-specific significant-incident criteria exclusively for trust service providers.",
          "relation": "applies_to",
          "source_recital": 2,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "Explains that trust service providers should also consider the number of relying parties when establishing significance, and defines 'relying parties' as natural or legal persons that rely upon a trust service.",
          "relation": "provides_guidance_for",
          "source_recital": 32,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R34 defines incident duration, which Art14 uses as a significance criterion for trust service providers (Art14 points (a) to (c)).",
          "relation": "defines",
          "source_recital": 34,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R35 defines complete unavailability, which Art14 uses as a significance criterion for trust service providers (Art14 points (a) to (c)).",
          "relation": "defines",
          "source_recital": 35,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        },
        {
          "confidence": "high",
          "reasoning": "R38 defines limited availability, which Art14 uses as a significance criterion for trust service providers (Art14 points (a) to (c)).",
          "relation": "defines",
          "source_recital": 38,
          "source_type": "recital",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ]
    },
    {
      "id": "article-Art15-UN1",
      "type": "article_paragraph",
      "article_number": 15,
      "paragraph_number": null,
      "akn4eu_paragraph_kind": "unnumbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Repeal",
      "akn4eu_sub_units": [],
      "ancestry": [],
      "text": "Commission Implementing Regulation (EU)\u00a02018/151\u00a0 ( 4 )  is repealed.",
      "outbound_relations": [],
      "inbound_relations": []
    },
    {
      "id": "article-Art16-UN1",
      "type": "article_paragraph",
      "article_number": 16,
      "paragraph_number": null,
      "akn4eu_paragraph_kind": "unnumbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Entry into force and application",
      "akn4eu_sub_units": [],
      "ancestry": [],
      "text": "This Regulation shall enter into force on the twentieth day following that of its publication in the  Official Journal of the European Union .",
      "outbound_relations": [],
      "inbound_relations": []
    },
    {
      "id": "article-Art16-UN2",
      "type": "article_paragraph",
      "article_number": 16,
      "paragraph_number": null,
      "akn4eu_paragraph_kind": "unnumbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Entry into force and application",
      "akn4eu_sub_units": [],
      "ancestry": [],
      "text": "This Regulation shall be binding in its entirety and directly applicable in all Member States.",
      "outbound_relations": [],
      "inbound_relations": []
    },
    {
      "id": "article-Art16-UN3",
      "type": "article_paragraph",
      "article_number": 16,
      "paragraph_number": null,
      "akn4eu_paragraph_kind": "unnumbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Entry into force and application",
      "akn4eu_sub_units": [],
      "ancestry": [],
      "text": "Done at Brussels, 17\u00a0October 2024.",
      "outbound_relations": [],
      "inbound_relations": []
    }
  ],
  "annex_points": [
    {
      "id": "annex-Point1",
      "type": "annex_point",
      "point": "1",
      "parent_point": null,
      "title": "Policy on the security of network and information systems (Article\u00a021(2), point (a) of Directive (EU)\u00a02022/2555)",
      "nis2_article_21_2_point": "a",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "relation": "gives_effect_to",
          "target_article": 2,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 1 implements Article 21(2), point (a).",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "text": "Policy on the security of network and information systems (Article\u00a021(2), point (a) of Directive (EU)\u00a02022/2555)"
    },
    {
      "id": "annex-Point1-1",
      "type": "annex_point",
      "point": "1.1",
      "parent_point": "1",
      "title": "Policy on the security of network and information systems",
      "nis2_article_21_2_point": "a",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "1",
          "target_type": "annex_point",
          "reasoning": "Annex point 1.1 is a subdivision of point 1.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "For the purpose of Article\u00a021(2), point (a) of Directive (EU)\u00a02022/2555, the policy on the security of network and information systems shall:\n\nset out the relevant entities\u2019 approach to managing the security of their network and information systems;\n\nbe appropriate to and complementary with the relevant entities\u2019 business strategy and objectives;\n\nset out network and information security objectives;\n\ninclude a commitment to continual improvement of the security of network and information systems;\n\ninclude a commitment to provide the appropriate resources needed for its implementation, including the necessary staff, financial resources, processes, tools and technologies;\n\nbe communicated to and acknowledged by relevant employees and relevant interested external parties;\n\nlay down roles and responsibilities pursuant to point 1.2;\n\nlist the documentation to be kept and the duration of retention of the documentation;\n\nlist the topic-specific policies;\n\nlay down indicators and measures to monitor its implementation and the current status of relevant entities\u2019 maturity level of network and information security;\n\nindicate the date of the formal approval by the management bodies of the relevant entities (the \u2018management bodies\u2019).\n\nThe network and information system security policy shall be reviewed and, where appropriate, updated by management bodies at least annually and when significant incidents or significant changes to operations or risks occur. The result of the reviews shall be documented."
    },
    {
      "id": "annex-Point1-2",
      "type": "annex_point",
      "point": "1.2",
      "parent_point": "1",
      "title": "Roles, responsibilities and authorities",
      "nis2_article_21_2_point": "a",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "1",
          "target_type": "annex_point",
          "reasoning": "Annex point 1.2 is a subdivision of point 1.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "As part of their policy on the security of network and information systems referred to in point 1.1, the relevant entities shall lay down responsibilities and authorities for network and information system security and assign them to roles, allocate them according to the relevant entities\u2019 needs, and communicate them to the management bodies.\n\nThe relevant entities shall require all personnel and third parties to apply network and information system security in accordance with the established network and information security policy, topic-specific policies and procedures of the relevant entities.\n\nAt least one person shall report directly to the management bodies on matters of network and information system security.\n\nDepending on the size of the relevant entities, network and information system security shall be covered by dedicated roles or duties carried out in addition to existing roles.\n\nConflicting duties and conflicting areas of responsibility shall be segregated, where applicable.\n\nRoles, responsibilities and authorities shall be reviewed and, where appropriate, updated by management bodies at planned intervals and when significant incidents or significant changes to operations or risks occur."
    },
    {
      "id": "annex-Point2",
      "type": "annex_point",
      "point": "2",
      "parent_point": null,
      "title": "Risk management policy (Article\u00a021(2), point (a) of Directive (EU)\u00a02022/2555)",
      "nis2_article_21_2_point": "a",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "relation": "gives_effect_to",
          "target_article": 2,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 2 implements Article 21(2), point (a).",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "text": "Risk management policy (Article\u00a021(2), point (a) of Directive (EU)\u00a02022/2555)"
    },
    {
      "id": "annex-Point2-1",
      "type": "annex_point",
      "point": "2.1",
      "parent_point": "2",
      "title": "Risk management framework",
      "nis2_article_21_2_point": "a",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "2",
          "target_type": "annex_point",
          "reasoning": "Annex point 2.1 is a subdivision of point 2.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "For the purpose of Article\u00a021(2), point (a) of Directive (EU)\u00a02022/2555, the relevant entities shall establish and maintain an appropriate risk management framework to identify and address the risks posed to the security of network and information systems. The relevant entities shall perform and document risk assessments and, based on the results, establish, implement and monitor a risk treatment plan. Risk assessment results and residual risks shall be accepted by management bodies or, where applicable, by persons who are accountable and have the authority to manage risks, provided that the relevant entities ensure adequate reporting to the management bodies.\n\nFor the purpose of point 2.1.1, the relevant entities shall establish procedures for identification, analysis, assessment and treatment of risks (\u2018cybersecurity risk management process\u2019). The cybersecurity risk management process shall be an integral part of the relevant entities\u2019 overall risk management process, where applicable. As part of the cybersecurity risk management process, the relevant entities shall:\n\nfollow a risk management methodology;\n\nestablish the risk tolerance level in accordance with the risk appetite of the relevant entities;\n\nestablish and maintain relevant risk criteria;\n\nin line with an all-hazards approach, identify and document the risks posed to the security of network and information systems, in particular in relation to third parties and risks that could lead to disruptions in the availability, integrity, authenticity and confidentiality of the network and information systems, including the identification of single point of failures;\n\nanalyse the risks posed to the security of network and information systems, including threat, likelihood, impact, and risk level, taking into account cyber threat intelligence and vulnerabilities;\n\nevaluate the identified risks based on the risk criteria;\n\nidentify and prioritise appropriate risk treatment options and measures;\n\ncontinuously monitor the implementation of the risk treatment measures;\n\nidentify who is responsible for implementing the risk treatment measures and when they should be implemented;\n\ndocument the chosen risk treatment measures in a risk treatment plan and the reasons justifying the acceptance of residual risks in a comprehensible manner.\n\nWhen identifying and prioritising appropriate risk treatment options and measures, the relevant entities shall take into account the risk assessment results, the results of the procedure to assess the effectiveness of cybersecurity risk-management measures, the cost of implementation in relation to the expected benefit, the asset classification referred to in point 12.1, and the business impact analysis referred to in point 4.1.3.\n\nThe relevant entities shall review and, where appropriate, update the risk assessment results and the risk treatment plan at planned intervals and at least annually, and when significant changes to operations or risks or significant incidents occur."
    },
    {
      "id": "annex-Point2-2",
      "type": "annex_point",
      "point": "2.2",
      "parent_point": "2",
      "title": "Compliance monitoring",
      "nis2_article_21_2_point": "a",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "2",
          "target_type": "annex_point",
          "reasoning": "Annex point 2.2 is a subdivision of point 2.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall regularly review the compliance with their policies on network and information system security, topic-specific policies, rules, and standards. The management bodies shall be informed of the status of network and information security on the basis of the compliance reviews by means of regular reporting.\n\nThe relevant entities shall put in place an effective compliance reporting system which shall be appropriate to their structures, operating environments and threat landscapes. The compliance reporting system shall be capable to provide to the management bodies an informed view of the current state of the relevant entities\u2019 management of risks.\n\nThe relevant entities shall perform the compliance monitoring at planned intervals and when significant incidents or significant changes to operations or risks occur."
    },
    {
      "id": "annex-Point2-3",
      "type": "annex_point",
      "point": "2.3",
      "parent_point": "2",
      "title": "Independent review of information and network security",
      "nis2_article_21_2_point": "a",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "2",
          "target_type": "annex_point",
          "reasoning": "Annex point 2.3 is a subdivision of point 2.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall review independently their approach to managing network and information system security and its implementation including people, processes and technologies.\n\nThe relevant entities shall develop and maintain processes to conduct independent reviews which shall be carried out by individuals with appropriate audit competence. Where the independent review is conducted by staff members of the relevant entity, the persons conducting the reviews shall not be in the line of authority of the personnel of the area under review. If the size of the relevant entities does not allow such separation of line of authority, the relevant entities shall put in place alternative measures to guarantee the impartiality of the reviews.\n\nThe results of the independent reviews, including the results from the compliance monitoring pursuant to point 2.2 and the monitoring and measurement pursuant to point 7, shall be reported to the management bodies. Corrective actions shall be taken or residual risk accepted according to the relevant entities\u2019 risk acceptance criteria.\n\nThe independent reviews shall take place at planned intervals and when significant incidents or significant changes to operations or risks occur."
    },
    {
      "id": "annex-Point3",
      "type": "annex_point",
      "point": "3",
      "parent_point": null,
      "title": "Incident handling (Article\u00a021(2), point (b), of Directive (EU)\u00a02022/2555)",
      "nis2_article_21_2_point": "b",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "relation": "gives_effect_to",
          "target_article": 2,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 3 implements Article 21(2), point (b).",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "text": "Incident handling (Article\u00a021(2), point (b), of Directive (EU)\u00a02022/2555)"
    },
    {
      "id": "annex-Point3-1",
      "type": "annex_point",
      "point": "3.1",
      "parent_point": "3",
      "title": "Incident handling policy",
      "nis2_article_21_2_point": "b",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "3",
          "target_type": "annex_point",
          "reasoning": "Annex point 3.1 is a subdivision of point 3.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "For the purpose of Article\u00a021(2), point (b) of Directive (EU)\u00a02022/2555, the relevant entities shall establish and implement an incident handling policy laying down the roles, responsibilities, and procedures for detecting, analysing, containing or responding to, recovering from, documenting and reporting of incidents in a timely manner.\n\nThe policy referred to in point 3.1.1 shall be coherent with the business continuity and disaster recovery plan referred to in point 4.1. The policy shall include:\n\na categorisation system for incidents that is consistent with the event assessment and classification carried out pursuant to point 3.4.1;\n\neffective communication plans including for escalation and reporting;\n\nassignment of roles to detect and appropriately respond to incidents to competent employees;\n\ndocuments to be used in the course of incident detection and response such as incident response manuals, escalation charts, contact lists and templates.\n\nThe roles, responsibilities and procedures laid down in the policy shall be tested and reviewed and, where appropriate, updated at planned intervals and after significant incidents or significant changes to operations or risks."
    },
    {
      "id": "annex-Point3-2",
      "type": "annex_point",
      "point": "3.2",
      "parent_point": "3",
      "title": "Monitoring and logging",
      "nis2_article_21_2_point": "b",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "3",
          "target_type": "annex_point",
          "reasoning": "Annex point 3.2 is a subdivision of point 3.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall lay down procedures and use tools to monitor and log activities on their network and information systems to detect events that could be considered as incidents and respond accordingly to mitigate the impact.\n\nTo the extent feasible, monitoring shall be automated and carried out either continuously or in periodic intervals, subject to business capabilities. The relevant entities shall implement their monitoring activities in a way which minimises false positives and false negatives.\n\nBased on the procedures referred to in point 3.2.1, the relevant entities shall maintain, document, and review logs. The relevant entities shall establish a list of assets to be subject to logging based on the results of the risk assessment carried out pursuant to point 2.1. Where appropriate, logs shall include:\n\nrelevant outbound and inbound network traffic;\n\ncreation, modification or deletion of users of the relevant entities\u2019 network and information systems and extension of the permissions;\n\naccess to systems and applications;\n\nauthentication-related events;\n\nall privileged access to systems and applications, and activities performed by administrative accounts;\n\naccess or changes to critical configuration and backup files;\n\nevent logs and logs from security tools, such as antivirus, intrusion detection systems or firewalls;\n\nuse of system resources, as well as their performance;\n\nphysical access to facilities;\n\naccess to and use of their network equipment and devices;\n\nactivation, stopping and pausing of the various logs;\n\nenvironmental events.\n\nThe logs shall be regularly reviewed for any unusual or unwanted trends. Where appropriate, the relevant entities shall lay down appropriate values for alarm thresholds. If the laid down values for alarm threshold are exceeded, an alarm shall be triggered, where appropriate, automatically. The relevant entities shall ensure that, in case of an alarm, a qualified and appropriate response is initiated in a timely manner.\n\nThe relevant entities shall maintain and back up logs for a predefined period and shall protect them from unauthorised access or changes.\n\nTo the extent feasible, the relevant entities shall ensure that all systems have synchronised time sources to be able to correlate logs between systems for event assessment. The relevant entities shall establish and keep a list of all assets that are being logged and ensure that monitoring and logging systems are redundant. The availability of the monitoring and logging systems shall be monitored independent of the systems they are monitoring.\n\nThe procedures as well as the list of assets that are being logged shall be reviewed and, where appropriate, updated at regular intervals and after significant incidents."
    },
    {
      "id": "annex-Point3-3",
      "type": "annex_point",
      "point": "3.3",
      "parent_point": "3",
      "title": "Event reporting",
      "nis2_article_21_2_point": "b",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "3",
          "target_type": "annex_point",
          "reasoning": "Annex point 3.3 is a subdivision of point 3.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall put in place a simple mechanism allowing their employees, suppliers, and customers to report suspicious events.\n\nThe relevant entities shall, where appropriate, communicate the event reporting mechanism to their suppliers and customers, and shall regularly train their employees how to use the mechanism."
    },
    {
      "id": "annex-Point3-4",
      "type": "annex_point",
      "point": "3.4",
      "parent_point": "3",
      "title": "Event assessment and classification",
      "nis2_article_21_2_point": "b",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "3",
          "target_type": "annex_point",
          "reasoning": "Annex point 3.4 is a subdivision of point 3.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall assess suspicious events to determine whether they constitute incidents and, if so, determine their nature and severity.\n\nFor the purpose of point 3.4.1, the relevant entities shall act in the following manner:\n\ncarry out the assessment based on predefined criteria laid down in advance, and on a triage to determine prioritisation of incident containment and eradication;\n\nassess the existence of recurring incidents as referred to in Article\u00a04 of this Regulation on a quarterly basis;\n\nreview the appropriate logs for the purposes of event assessment and classification;\n\nput in place a process for log correlation and analysis, and\n\nreassess and reclassify events in case of new information becoming available or after analysis of previously available information."
    },
    {
      "id": "annex-Point3-5",
      "type": "annex_point",
      "point": "3.5",
      "parent_point": "3",
      "title": "Incident response",
      "nis2_article_21_2_point": "b",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "3",
          "target_type": "annex_point",
          "reasoning": "Annex point 3.5 is a subdivision of point 3.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall respond to incidents in accordance with documented procedures and in a timely manner.\n\nThe incident response procedures shall include the following stages:\n\nincident containment, to prevent the consequences of the incident from spreading;\n\neradication, to prevent the incident from continuing or reappearing,\n\nrecovery from the incident, where necessary.\n\nThe relevant entities shall establish communication plans and procedures:\n\nwith the Computer Security Incident Response Teams (CSIRTs) or, where applicable, the competent authorities, related to incident notification;\n\nfor communication among staff members of the relevant entity, and for communication with relevant stakeholders external to the relevant entity.\n\nThe relevant entities shall log incident response activities in accordance with the procedures referred to in point 3.2.1, and record evidence.\n\nThe relevant entities shall test at planned intervals their incident response procedures."
    },
    {
      "id": "annex-Point3-6",
      "type": "annex_point",
      "point": "3.6",
      "parent_point": "3",
      "title": "Post-incident reviews",
      "nis2_article_21_2_point": "b",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "3",
          "target_type": "annex_point",
          "reasoning": "Annex point 3.6 is a subdivision of point 3.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "Where appropriate, the relevant entities shall carry out post-incident reviews after recovery from incidents. The post-incident reviews shall identify, where possible, the root cause of the incident and result in documented lessons learned to reduce the occurrence and consequences of future incidents.\n\nThe relevant entities shall ensure that post-incident reviews contribute to improving their approach to network and information security, to risk treatment measures, and to incident handling, detection and response procedures.\n\nThe relevant entities shall review at planned intervals if incidents led to post-incident reviews."
    },
    {
      "id": "annex-Point4",
      "type": "annex_point",
      "point": "4",
      "parent_point": null,
      "title": "Business continuity and crisis management (Article\u00a021(2), point (c), of Directive (EU)\u00a02022/2555)",
      "nis2_article_21_2_point": "c",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "relation": "gives_effect_to",
          "target_article": 2,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 4 implements Article 21(2), point (c).",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "text": "Business continuity and crisis management (Article\u00a021(2), point (c), of Directive (EU)\u00a02022/2555)"
    },
    {
      "id": "annex-Point4-1",
      "type": "annex_point",
      "point": "4.1",
      "parent_point": "4",
      "title": "Business continuity and disaster recovery plan",
      "nis2_article_21_2_point": "c",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "4",
          "target_type": "annex_point",
          "reasoning": "Annex point 4.1 is a subdivision of point 4.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "For the purpose of Article\u00a021(2), point (c) of Directive (EU)\u00a02022/2555, the relevant entities shall lay down and maintain a business continuity and disaster recovery plan to apply in the case of incidents.\n\nThe relevant entities\u2019 operations shall be restored according to the business continuity and disaster recovery plan. The plan shall be based on the results of the risk assessment carried out pursuant to point 2.1 and shall include, where appropriate, the following:\n\npurpose, scope and audience;\n\nroles and responsibilities;\n\nkey contacts and (internal and external) communication channels;\n\nconditions for plan activation and deactivation;\n\norder of recovery for operations;\n\nrecovery plans for specific operations, including recovery objectives;\n\nrequired resources, including backups and redundancies;\n\nrestoring and resuming activities from temporary measures.\n\nThe relevant entities shall carry out a business impact analysis to assess the potential impact of severe disruptions to their business operations and shall, based on the results of the business impact analysis, establish continuity requirements for the network and information systems.\n\nThe business continuity plan and disaster recovery plan shall be tested, reviewed and, where appropriate, updated at planned intervals and following significant incidents or significant changes to operations or risks. The relevant entities shall ensure that the plans incorporate lessons learnt from such tests."
    },
    {
      "id": "annex-Point4-2",
      "type": "annex_point",
      "point": "4.2",
      "parent_point": "4",
      "title": "Backup and redundancy management",
      "nis2_article_21_2_point": "c",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "4",
          "target_type": "annex_point",
          "reasoning": "Annex point 4.2 is a subdivision of point 4.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall maintain backup copies of data and provide sufficient available resources, including facilities, network and information systems and staff, to ensure an appropriate level of redundancy.\n\nBased on the results of the risk assessment carried out pursuant to point 2.1 and the business continuity plan, the relevant entities shall lay down backup plans which include the following:\n\nrecovery times;\n\nassurance that backup copies are complete and accurate, including configuration data and data stored in cloud computing service environment;\n\nstoring backup copies (online or offline) in a safe location or locations, which are not in the same network as the system, and are at sufficient distance to escape any damage from a disaster at the main site;\n\nappropriate physical and logical access controls to backup copies, in accordance with the asset classification level;\n\nrestoring data from backup copies;\n\nretention periods based on business and regulatory requirements.\n\nThe relevant entities shall perform regular integrity checks on the backup copies.\n\nBased on the results of the risk assessment carried out pursuant to point 2.1 and the business continuity plan, the relevant entities shall ensure sufficient availability of resources by at least partial redundancy of the following:\n\nnetwork and information systems;\n\nassets, including facilities, equipment and supplies;\n\npersonnel with the necessary responsibility, authority and competence;\n\nappropriate communication channels.\n\nWhere appropriate, the relevant entities shall ensure that monitoring and adjustment of resources, including facilities, systems and personnel, is duly informed by backup and redundancy requirements.\n\nThe relevant entities shall carry out regular testing of the recovery of backup copies and redundancies to ensure that, in recovery conditions, they can be relied upon and cover the copies, processes and knowledge to perform an effective recovery. The relevant entities shall document the results of the tests and, where needed, take corrective action."
    },
    {
      "id": "annex-Point4-3",
      "type": "annex_point",
      "point": "4.3",
      "parent_point": "4",
      "title": "Crisis management",
      "nis2_article_21_2_point": "c",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "4",
          "target_type": "annex_point",
          "reasoning": "Annex point 4.3 is a subdivision of point 4.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall put in place a process for crisis management.\n\nThe relevant entities shall ensure that the crisis management process addresses at least the following elements:\n\nroles and responsibilities for personnel and, where appropriate, suppliers and service providers, specifying the allocation of roles in crisis situations, including specific steps to follow;\n\nappropriate communication means between the relevant entities and relevant competent authorities;\n\napplication of appropriate measures to ensure the maintenance of network and information system security in crisis situations.\n\nFor the purpose of point (b), the flow of information between the relevant entities and relevant competent authorities shall include both obligatory communications, such as incident reports and related timelines, and non-obligatory communications.\n\nThe relevant entities shall implement a process for managing and making use of information received from the CSIRTs or, where applicable, the competent authorities, concerning incidents, vulnerabilities, threats or possible mitigation measures.\n\nThe relevant entities shall test, review and, where appropriate, update the crisis management plan on a regular basis or following significant incidents or significant changes to operations or risks."
    },
    {
      "id": "annex-Point5",
      "type": "annex_point",
      "point": "5",
      "parent_point": null,
      "title": "Supply chain security (Article\u00a021(2), point (d), of Directive (EU)\u00a02022/2555)",
      "nis2_article_21_2_point": "d",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "relation": "gives_effect_to",
          "target_article": 2,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 5 implements Article 21(2), point (d).",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "text": "Supply chain security (Article\u00a021(2), point (d), of Directive (EU)\u00a02022/2555)"
    },
    {
      "id": "annex-Point5-1",
      "type": "annex_point",
      "point": "5.1",
      "parent_point": "5",
      "title": "Supply chain security policy",
      "nis2_article_21_2_point": "d",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "5",
          "target_type": "annex_point",
          "reasoning": "Annex point 5.1 is a subdivision of point 5.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "For the purpose of Article\u00a021(2), point (d) of Directive (EU)\u00a02022/2555, the relevant entities shall establish, implement and apply a supply chain security policy which governs the relations with their direct suppliers and service providers in order to mitigate the identified risks to the security of network and information systems. In the supply chain security policy, the relevant entities shall identify their role in the supply chain and communicate it to their direct suppliers and service providers.\n\nAs part of the supply chain security policy referred to in point 5.1.1, the relevant entities shall lay down criteria to select and contract suppliers and service providers. Those criteria shall include the following:\n\nthe cybersecurity practices of the suppliers and service providers, including their secure development procedures;\n\nthe ability of the suppliers and service providers to meet cybersecurity specifications set by the relevant entities;\n\nthe overall quality and resilience of ICT products and ICT services and the cybersecurity risk-management measures embedded in them, including the risks and classification level of the ICT products and ICT services;\n\nthe ability of the relevant entities to diversify sources of supply and limit vendor lock-in, where applicable.\n\nWhen establishing their supply chain security policy, relevant entities shall take into account the results of the coordinated security risk assessments of critical supply chains carried out in accordance with Article\u00a022(1) of Directive (EU)\u00a02022/2555, where applicable.\n\nBased on the supply chain security policy and taking into account the results of the risk assessment carried out in accordance with point 2.1 of this Annex, the relevant entities shall ensure that their contracts with the suppliers and service providers specify, where appropriate through service level agreements, the following, where appropriate:\n\ncybersecurity requirements for the suppliers or service providers, including requirements as regards the security in acquisition of ICT services or ICT products set out in point 6.1;\n\nrequirements regarding awareness, skills and training, and where appropriate certifications, required from the suppliers\u2019 or service providers\u2019 employees;\n\nrequirements regarding the verification of the background of the suppliers\u2019 and service providers\u2019 employees;\n\nan obligation on suppliers and service providers to notify, without undue delay, the relevant entities of incidents that present a risk to the security of the network and information systems of those entities;\n\nthe right to audit or right to receive audit reports;\n\nan obligation on suppliers and service providers to handle vulnerabilities that present a risk to the security of the network and information systems of the relevant entities;\n\nrequirements regarding subcontracting and, where the relevant entities allow subcontracting, cybersecurity requirements for subcontractors in accordance with the cybersecurity requirements referred to in point (a);\n\nobligations on the suppliers and service providers at the termination of the contract, such as retrieval and disposal of the information obtained by the suppliers and service providers in the exercise of their tasks.\n\nThe relevant entities shall take into account the elements referred to in point 5.1.2 and\u00a05.1.3 as part of the selection process of new suppliers and service providers, as well as part of the procurement process referred to in point 6.1.\n\nThe relevant entities shall review the supply chain security policy, and monitor, evaluate and, where necessary, act upon changes in the cybersecurity practices of suppliers and service providers, at planned intervals and when significant changes to operations or risks or significant incidents related to the provision of ICT services or having impact on the security of the ICT products from suppliers and service providers occur.\n\nFor the purpose of point 5.1.6, the relevant entities shall:\n\nregularly monitor reports on the implementation of the service level agreements, where applicable;\n\nreview incidents related to ICT products and ICT services from suppliers and service providers;\n\nassess the need for unscheduled reviews and document the findings in a comprehensible manner;\n\nanalyse the risks presented by changes related to ICT products and ICT services from suppliers and service providers and, where appropriate, take mitigating measures in a timely manner."
    },
    {
      "id": "annex-Point5-2",
      "type": "annex_point",
      "point": "5.2",
      "parent_point": "5",
      "title": "Directory of suppliers and service providers",
      "nis2_article_21_2_point": "d",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "5",
          "target_type": "annex_point",
          "reasoning": "Annex point 5.2 is a subdivision of point 5.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall maintain and keep up to date a registry of their direct suppliers and service providers, including:\n\ncontact points for each direct supplier and service provider;\n\na list of ICT products, ICT services, and ICT processes provided by the direct supplier or service provider to the relevant entities."
    },
    {
      "id": "annex-Point6",
      "type": "annex_point",
      "point": "6",
      "parent_point": null,
      "title": "Security in network and information systems acquisition, development and maintenance (Article\u00a021(2), point (e), of Directive (EU)\u00a02022/2555)",
      "nis2_article_21_2_point": "e",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "relation": "gives_effect_to",
          "target_article": 2,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 6 implements Article 21(2), point (e).",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "text": "Security in network and information systems acquisition, development and maintenance (Article\u00a021(2), point (e), of Directive (EU)\u00a02022/2555)"
    },
    {
      "id": "annex-Point6-1",
      "type": "annex_point",
      "point": "6.1",
      "parent_point": "6",
      "title": "Security in acquisition of ICT services or ICT products",
      "nis2_article_21_2_point": "e",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "6",
          "target_type": "annex_point",
          "reasoning": "Annex point 6.1 is a subdivision of point 6.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "For the purpose of Article\u00a021(2), point (e) of Directive (EU)\u00a02022/2555, the relevant entities shall set and implement processes to manage risks stemming from the acquisition of ICT services or ICT products for components that are critical for the relevant entities\u2019 security of network and information systems, based on the risk assessment carried out pursuant to point 2.1, from suppliers or service providers throughout their life cycle.\n\nFor the purpose of point 6.1.1, the processes referred to in point 6.1.1 shall include:\n\nsecurity requirements to apply to the ICT services or ICT products to be acquired;\n\nrequirements regarding security updates throughout the entire lifetime of the ICT services or ICT products, or replacement after the end of the support period;\n\ninformation describing the hardware and software components used in the ICT services or ICT products;\n\ninformation describing the implemented cybersecurity functions of the ICT services or ICT products and the configuration required for their secure operation;\n\nassurance that the ICT services or ICT products comply with the security requirements according to point (a);\n\nmethods for validating that the delivered ICT services or ICT products are compliant to the stated security requirements, as well as documentation of the results of the validation.\n\nThe relevant entities shall review and, where appropriate, update the processes at planned intervals and when significant incidents occur."
    },
    {
      "id": "annex-Point6-2",
      "type": "annex_point",
      "point": "6.2",
      "parent_point": "6",
      "title": "Secure development life cycle",
      "nis2_article_21_2_point": "e",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "6",
          "target_type": "annex_point",
          "reasoning": "Annex point 6.2 is a subdivision of point 6.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "Before developing a network and information system, including software, the relevant entities shall lay down rules for the secure development of network and information systems and apply them when developing network and information systems in-house, or when outsourcing the development of network and information systems. The rules shall cover all development phases, including specification, design, development, implementation and testing.\n\nFor the purpose of point 6.2.1, the relevant entities shall:\n\ncarry out an analysis of security requirements at the specification and design phases of any development or acquisition project undertaken by the relevant entities or on behalf of those entities;\n\napply principles for engineering secure systems and secure coding principles to any information system development activities such as promoting cybersecurity-by-design, zero-trust architectures;\n\nlay down security requirements regarding development environments;\n\nestablish and implement security testing processes in the development life cycle;\n\nappropriately select, protect and manage security test data;\n\nsanitise and anonymise testing data according to the risk assessment carried out pursuant to point 2.1.\n\nFor outsourced development of network and information systems, the relevant entities shall also apply the policies and procedures referred to in points 5 and\u00a06.1.\n\nThe relevant entities shall review and, where necessary, update their secure development rules at planned intervals."
    },
    {
      "id": "annex-Point6-3",
      "type": "annex_point",
      "point": "6.3",
      "parent_point": "6",
      "title": "Configuration management",
      "nis2_article_21_2_point": "e",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "6",
          "target_type": "annex_point",
          "reasoning": "Annex point 6.3 is a subdivision of point 6.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall take the appropriate measures to establish, document, implement, and monitor configurations, including security configurations of hardware, software, services and networks.\n\nFor the purpose of point 6.3.1, the relevant entities shall:\n\nlay down and ensure security in configurations for their hardware, software, services and networks;\n\nlay down and implement processes and tools to enforce the laid down secure configurations for hardware, software, services and networks, for newly installed systems as well as for systems in operation over their lifetime.\n\nThe relevant entities shall review and, where appropriate, update configurations at planned intervals or when significant incidents or significant changes to operations or risks occur."
    },
    {
      "id": "annex-Point6-4",
      "type": "annex_point",
      "point": "6.4",
      "parent_point": "6",
      "title": "Change management, repairs and maintenance",
      "nis2_article_21_2_point": "e",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "6",
          "target_type": "annex_point",
          "reasoning": "Annex point 6.4 is a subdivision of point 6.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall apply change management procedures to control changes of network and information systems. Where applicable, the procedures shall be consistent with the relevant entities\u2019 general policies concerning change management.\n\nThe procedures referred to in point 6.4.1 shall be applied for releases, modifications and emergency changes of any software and hardware in operation and changes to the configuration. The procedures shall ensure that those changes are documented and, based on the risk assessment carried out pursuant to point 2.1, tested and assessed in view of the potential impact before being implemented.\n\nIn the event that the regular change management procedures could not be followed due to an emergency, the relevant entities shall document the result of the change, and the explanation for why the procedures could not be followed.\n\nThe relevant entities shall review and, where appropriate, update the procedures at planned intervals and when significant incidents or significant changes to operations or risks."
    },
    {
      "id": "annex-Point6-5",
      "type": "annex_point",
      "point": "6.5",
      "parent_point": "6",
      "title": "Security testing",
      "nis2_article_21_2_point": "e",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "6",
          "target_type": "annex_point",
          "reasoning": "Annex point 6.5 is a subdivision of point 6.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall establish, implement and apply a policy and procedures for security testing.\n\nThe relevant entities shall:\n\nestablish, based on the risk assessment carried out pursuant to point 2.1, the need, scope, frequency and type of security tests;\n\ncarry out security tests according to a documented test methodology, covering the components identified as relevant for secure operation in a risk analysis;\n\ndocument the type, scope, time and results of the tests, including assessment of criticality and mitigating actions for each finding;\n\napply mitigating actions in case of critical findings.\n\nThe relevant entities shall review and, where appropriate, update their security testing policies at planned intervals."
    },
    {
      "id": "annex-Point6-6",
      "type": "annex_point",
      "point": "6.6",
      "parent_point": "6",
      "title": "Security patch management",
      "nis2_article_21_2_point": "e",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "6",
          "target_type": "annex_point",
          "reasoning": "Annex point 6.6 is a subdivision of point 6.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall specify and apply procedures, coherent with the change management procedures referred to in point 6.4.1 as well as with vulnerability management, risk management and other relevant management procedures, for ensuring that:\n\nsecurity patches are applied within a reasonable time after they become available;\n\nsecurity patches are tested before being applied in production systems;\n\nsecurity patches come from trusted sources and are checked for integrity;\n\nadditional measures are implemented and residual risks are accepted in cases where a patch is not available or not applied pursuant to point 6.6.2.\n\nBy way of derogation from point 6.6.1(a), the relevant entities may choose not to apply security patches when the disadvantages of applying the security patches outweigh the cybersecurity benefits. The relevant entities shall duly document and substantiate the reasons for any such decision."
    },
    {
      "id": "annex-Point6-7",
      "type": "annex_point",
      "point": "6.7",
      "parent_point": "6",
      "title": "Network security",
      "nis2_article_21_2_point": "e",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "6",
          "target_type": "annex_point",
          "reasoning": "Annex point 6.7 is a subdivision of point 6.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall take the appropriate measures to protect their network and information systems from cyber threats.\n\nFor the purpose of point 6.7.1, the relevant entities shall:\n\ndocument the architecture of the network in a comprehensible and up to date manner;\n\ndetermine and apply controls to protect the relevant entities\u2019 internal network domains from unauthorised access;\n\nconfigure controls to prevent accesses and network communication not required for the operation of the relevant entities;\n\ndetermine and apply controls for remote access to network and information systems, including access by service providers;\n\nnot use systems used for administration of the security policy implementation for other purposes;\n\nexplicitly forbid or deactivate unneeded connections and services;\n\nwhere appropriate, exclusively allow access to the relevant entities\u2019 network and information systems by devices authorised by those entities;\n\nallow connections of service providers only after an authorisation request and for a set time period, such as the duration of a maintenance operation;\n\nestablish communication between distinct systems only through trusted channels that are isolated using logical, cryptographic or physical separation from other communication channels and provide assured identification of their end points and protection of the channel data from modification or disclosure;\n\nadopt an implementation plan for the full transition towards latest generation network layer communication protocols in a secure, appropriate and gradual way and establish measures to accelerate such transition;\n\nadopt an implementation plan for the deployment of internationally agreed and interoperable modern e-mail communications standards to secure e-mail communications to mitigate vulnerabilities linked to e-mail-related threats and establish measures to accelerate such deployment;\n\napply best practices for the security of the DNS, and for Internet routing security and routing hygiene of traffic originating from and destined to the network.\n\nThe relevant entities shall review and, where appropriate, update these measures at planned intervals and when significant incidents or significant changes to operations or risks occur."
    },
    {
      "id": "annex-Point6-8",
      "type": "annex_point",
      "point": "6.8",
      "parent_point": "6",
      "title": "Network segmentation",
      "nis2_article_21_2_point": "e",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "6",
          "target_type": "annex_point",
          "reasoning": "Annex point 6.8 is a subdivision of point 6.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall segment systems into networks or zones in accordance with the results of the risk assessment referred to in point 2.1. They shall segment their systems and networks from third parties\u2019 systems and networks.\n\nFor that purpose, the relevant entities shall:\n\nconsider the functional, logical and physical relationship, including location, between trustworthy systems and services;\n\ngrant access to a network or zone based on an assessment of its security requirements;\n\nkeep systems that are critical to the relevant entities operation or to safety in secured zones;\n\ndeploy a demilitarised zone within their communication networks to ensure secure communication originating from or destined to their networks;\n\nrestrict access and communications between and within zones to those necessary for the operation of the relevant entities or for safety;\n\nseparate the dedicated network for administration of network and information systems from the relevant entities\u2019 operational network;\n\nsegregate network administration channels from other network traffic;\n\nseparate the production systems for the relevant entities\u2019 services from systems used in development and testing, including backups.\n\nThe relevant entities shall review and, where appropriate, update network segmentation at planned intervals and when significant incidents or significant changes to operations or risks."
    },
    {
      "id": "annex-Point6-9",
      "type": "annex_point",
      "point": "6.9",
      "parent_point": "6",
      "title": "Protection against malicious and unauthorised software",
      "nis2_article_21_2_point": "e",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "6",
          "target_type": "annex_point",
          "reasoning": "Annex point 6.9 is a subdivision of point 6.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall protect their network and information systems against malicious and unauthorised software.\n\nFor that purpose, the relevant entities shall in particular implement measures that detect or prevent the use of malicious or unauthorised software. The relevant entities shall, where appropriate, ensure that their network and information systems are equipped with detection and response software, which is updated regularly in accordance with the risk assessment carried out pursuant to point 2.1 and the contractual agreements with the providers."
    },
    {
      "id": "annex-Point6-10",
      "type": "annex_point",
      "point": "6.10",
      "parent_point": "6",
      "title": "Vulnerability handling and disclosure",
      "nis2_article_21_2_point": "e",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "6",
          "target_type": "annex_point",
          "reasoning": "Annex point 6.10 is a subdivision of point 6.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall obtain information about technical vulnerabilities in their network and information systems, evaluate their exposure to such vulnerabilities, and take appropriate measures to manage the vulnerabilities.\n\nFor the purpose of point 6.10.1, the relevant entities shall:\n\nmonitor information about vulnerabilities through appropriate channels, such as announcements of CSIRTs, competent authorities or information provided by suppliers or service providers;\n\nperform, where appropriate, vulnerability scans, and record evidence of the results of the scans, at planned intervals;\n\naddress, without undue delay, vulnerabilities identified by the relevant entities as critical to their operations;\n\nensure that their vulnerability handling is compatible with their change management, security patch management, risk management and incident management procedures;\n\nlay down a procedure for disclosing vulnerabilities in accordance with the applicable national coordinated vulnerability disclosure policy.\n\nWhen justified by the potential impact of the vulnerability, the relevant entities shall create and implement a plan to mitigate the vulnerability. In other cases, the relevant entities shall document and substantiate the reason why the vulnerability does not require remediation.\n\nThe relevant entities shall review and, where appropriate, update at planned intervals the channels they use for monitoring vulnerability information."
    },
    {
      "id": "annex-Point7",
      "type": "annex_point",
      "point": "7",
      "parent_point": null,
      "title": "Policies and procedures to assess the effectiveness of cybersecurity risk-management measures (Article\u00a021(2), point (f), of Directive (EU)\u00a02022/2555)",
      "nis2_article_21_2_point": "f",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "relation": "gives_effect_to",
          "target_article": 2,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 7 implements Article 21(2), point (f).",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "text": "Policies and procedures to assess the effectiveness of cybersecurity risk-management measures (Article\u00a021(2), point (f), of Directive (EU)\u00a02022/2555)"
    },
    {
      "id": "annex-Point8",
      "type": "annex_point",
      "point": "8",
      "parent_point": null,
      "title": "Basic cyber hygiene practices and security training (Article\u00a021(2), point (g), of Directive (EU)\u00a02022/2555)",
      "nis2_article_21_2_point": "g",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "relation": "gives_effect_to",
          "target_article": 2,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 8 implements Article 21(2), point (g).",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "text": "Basic cyber hygiene practices and security training (Article\u00a021(2), point (g), of Directive (EU)\u00a02022/2555)"
    },
    {
      "id": "annex-Point8-1",
      "type": "annex_point",
      "point": "8.1",
      "parent_point": "8",
      "title": "Awareness raising and basic cyber hygiene practices",
      "nis2_article_21_2_point": "g",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "8",
          "target_type": "annex_point",
          "reasoning": "Annex point 8.1 is a subdivision of point 8.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "For the purpose of Article\u00a021(2), point (g) of Directive (EU)\u00a02022/2555, the relevant entities shall ensure that their employees, including members of management bodies, as well as direct suppliers and service providers are aware of risks, are informed of the importance of cybersecurity and apply cyber hygiene practices.\n\nFor the purpose of point 8.1.1, the relevant entities shall offer to their employees, including members of management bodies, as well as to direct suppliers and service providers where appropriate in accordance with point 5.1.4, an awareness raising programme, which shall:\n\nbe scheduled over time, so that the activities are repeated and cover new employees;\n\nbe established in line with the network and information security policy, topic-specific policies and relevant procedures on network and information security;\n\ncover relevant cyber threats, the cybersecurity risk-management measures in place, contact points and resources for additional information and advice on cybersecurity matters, as well as cyber hygiene practices for users.\n\nThe awareness raising programme shall, where appropriate, be tested in terms of effectiveness. The awareness raising programme shall be updated and offered at planned intervals taking into account changes in cyber hygiene practices, and the current threat landscape and risks posed to the relevant entities."
    },
    {
      "id": "annex-Point8-2",
      "type": "annex_point",
      "point": "8.2",
      "parent_point": "8",
      "title": "Security training",
      "nis2_article_21_2_point": "g",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "8",
          "target_type": "annex_point",
          "reasoning": "Annex point 8.2 is a subdivision of point 8.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall identify employees, whose roles require security relevant skill sets and expertise, and ensure that they receive regular training on network and information system security.\n\nThe relevant entities shall establish, implement and apply a training program in line with the network and information security policy, topic-specific policies and other relevant procedures on network and information security which lays down the training needs for certain roles and positions based on criteria.\n\nThe training referred to in point 8.2.1 shall be relevant to the job function of the employee and its effectiveness shall be assessed. Training shall take into consideration security measures in place and cover the following:\n\ninstructions regarding the secure configuration and operation of the network and information systems, including mobile devices;\n\nbriefing on known cyber threats;\n\ntraining of the behaviour when security-relevant events occur.\n\nThe relevant entities shall apply training to staff members who transfer to new positions or roles which require security relevant skill sets and expertise.\n\nThe program shall be updated and run periodically taking into account applicable policies and rules, assigned roles, responsibilities, as well as known cyber threats and technological developments."
    },
    {
      "id": "annex-Point9",
      "type": "annex_point",
      "point": "9",
      "parent_point": null,
      "title": "Cryptography (Article\u00a021(2), point (h), of Directive (EU)\u00a02022/2555)",
      "nis2_article_21_2_point": "h",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "relation": "gives_effect_to",
          "target_article": 2,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 9 implements Article 21(2), point (h).",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "text": "Cryptography (Article\u00a021(2), point (h), of Directive (EU)\u00a02022/2555)"
    },
    {
      "id": "annex-Point10",
      "type": "annex_point",
      "point": "10",
      "parent_point": null,
      "title": "Human resources security (Article\u00a021(2), point (i), of Directive (EU)\u00a02022/2555)",
      "nis2_article_21_2_point": "i",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "relation": "gives_effect_to",
          "target_article": 2,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 10 implements Article 21(2), point (i).",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "text": "Human resources security (Article\u00a021(2), point (i), of Directive (EU)\u00a02022/2555)"
    },
    {
      "id": "annex-Point10-1",
      "type": "annex_point",
      "point": "10.1",
      "parent_point": "10",
      "title": "Human resources security",
      "nis2_article_21_2_point": "i",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "10",
          "target_type": "annex_point",
          "reasoning": "Annex point 10.1 is a subdivision of point 10.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "For the purpose of Article\u00a021(2), point (i) of Directive (EU)\u00a02022/2555, the relevant entities shall ensure that their employees and direct suppliers and service providers, wherever applicable, understand and commit to their security responsibilities, as appropriate for the offered services and the job and in line with the relevant entities\u2019 policy on the security of network and information systems.\n\nThe requirement referred to in point 10.1.1 shall include the following:\n\nmechanisms to ensure that all employees, direct suppliers and service providers, wherever applicable, understand and follow the standard cyber hygiene practices that the relevant entities apply pursuant to point 8.1;\n\nmechanisms to ensure that all users with administrative or privileged access are aware of and act in accordance with their roles, responsibilities and authorities;\n\nmechanisms to ensure that members of management bodies understand and act in accordance with their role, responsibilities and authorities regarding network and information system security;\n\nmechanisms for hiring personnel qualified for the respective roles, such as reference checks, vetting procedures, validation of certifications, or written tests.\n\nThe relevant entities shall review the assignment of personnel to specific roles as referred to in point 1.2, as well as their commitment of human resources in that regard, at planned intervals and at least annually. They shall updatethe assignment where necessary."
    },
    {
      "id": "annex-Point10-2",
      "type": "annex_point",
      "point": "10.2",
      "parent_point": "10",
      "title": "Verification of background",
      "nis2_article_21_2_point": "i",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "10",
          "target_type": "annex_point",
          "reasoning": "Annex point 10.2 is a subdivision of point 10.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall ensure to the extent feasible verification of the background of their employees, and where applicable of direct suppliers and service providers in accordance with point 5.1.4, if necessary for their role, responsibilities and authorisations.\n\nFor the purpose of point 10.2.1, the relevant entities shall:\n\nput in place criteria, which set out which roles, responsibilities and authorities shall only be exercised by persons whose background has been verified;\n\nensure that verification referred to in point 10.2.1 is performed on these persons before they start exercising these roles, responsibilities and authorities, which shall take into consideration the applicable laws, regulations, and ethics in proportion to the business requirements, the asset classification as referred to in point 12.1 and the network and information systems to be accessed, and the perceived risks.\n\nThe relevant entities shall review and, where appropriate, update the policy at planned intervals and update it where necessary."
    },
    {
      "id": "annex-Point10-3",
      "type": "annex_point",
      "point": "10.3",
      "parent_point": "10",
      "title": "Termination or change of employment procedures",
      "nis2_article_21_2_point": "i",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "10",
          "target_type": "annex_point",
          "reasoning": "Annex point 10.3 is a subdivision of point 10.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall ensure that network and information system security responsibilities and duties that remain valid after termination or change of employment of their employees are contractually defined and enforced.\n\nFor the purpose of point 10.3.1, the relevant entities shall include in the individual\u2019s terms and conditions of employment, contract or agreement the responsibilities and duties that are still valid after termination of employment or contract, such as confidentiality clauses."
    },
    {
      "id": "annex-Point10-4",
      "type": "annex_point",
      "point": "10.4",
      "parent_point": "10",
      "title": "Disciplinary process",
      "nis2_article_21_2_point": "i",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "10",
          "target_type": "annex_point",
          "reasoning": "Annex point 10.4 is a subdivision of point 10.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall establish, communicate and maintain a disciplinary process for handling violations of network and information system security policies. The process shall take into consideration relevant legal, statutory, contractual and business requirements.\n\nThe relevant entities shall review and, where appropriate, update the disciplinary process at planned intervals, and when necessary due to legal changes or significant changes to operations or risks."
    },
    {
      "id": "annex-Point11",
      "type": "annex_point",
      "point": "11",
      "parent_point": null,
      "title": "Access control (Article\u00a021(2), points (i) and (j), of Directive (EU)\u00a02022/2555)",
      "nis2_article_21_2_point": null,
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "relation": "gives_effect_to",
          "target_article": 2,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 11 implements Article 21(2), point (i and j).",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "text": "Access control (Article\u00a021(2), points (i) and (j), of Directive (EU)\u00a02022/2555)"
    },
    {
      "id": "annex-Point11-1",
      "type": "annex_point",
      "point": "11.1",
      "parent_point": "11",
      "title": "Access control policy",
      "nis2_article_21_2_point": null,
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "11",
          "target_type": "annex_point",
          "reasoning": "Annex point 11.1 is a subdivision of point 11.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "For the purpose of Article\u00a021(2), point (i) of Directive (EU)\u00a02022/2555, the relevant entities shall establish, document and implement logical and physical access control policies for the access to their network and information systems, based on business requirements as well as network and information system security requirements.\n\nThe policies referred to in point 11.1.1. shall:\n\naddress access by persons, including staff, visitors, and external entities such as suppliers and service providers;\n\naddress access by network and information systems;\n\nensure that access is only granted to users that have been adequately authenticated.\n\nThe relevant entities shall review and, where appropriate, update the policies at planned intervals and when significant incidents or significant changes to operations or risks occur."
    },
    {
      "id": "annex-Point11-2",
      "type": "annex_point",
      "point": "11.2",
      "parent_point": "11",
      "title": "Management of access rights",
      "nis2_article_21_2_point": null,
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "11",
          "target_type": "annex_point",
          "reasoning": "Annex point 11.2 is a subdivision of point 11.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall provide, modify, remove and document access rights to network and information systems in accordance with the access control policy referred to in point 11.1.\n\nThe relevant entities shall:\n\nassign and revoke access rights based on the principles of need-to-know, least privilege and separation of duties;\n\nensure that access rights are modified accordingly upon termination or change of employment;\n\nensure that access to network and information systems is authorised by the relevant persons;\n\nensure that access rights appropriately address third-party access, such as visitors, suppliers and service providers, in particular by limiting access rights in scope and in duration;\n\nmaintain a register of access rights granted;\n\napply logging to the management of access rights.\n\nThe relevant entities shall review access rights at planned intervals and shall modify them based on organisational changes. The relevant entities shall document the results of the review including the necessary changes of access rights."
    },
    {
      "id": "annex-Point11-3",
      "type": "annex_point",
      "point": "11.3",
      "parent_point": "11",
      "title": "Privileged accounts and system administration accounts",
      "nis2_article_21_2_point": null,
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "11",
          "target_type": "annex_point",
          "reasoning": "Annex point 11.3 is a subdivision of point 11.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall maintain policies for management of privileged accounts and system administration accounts as part of the access control policy referred to in point 11.1.\n\nThe policies referred to in point 11.3.1 shall:\n\nestablish strong identification, authentication such as multi-factor authentication, and authorisation procedures for privileged accounts and system administration accounts;\n\nset up specific accounts to be used for system administration operations exclusively, such as installation, configuration, management or maintenance;\n\nindividualise and restrict system administration privileges to the highest extent possible,\n\nprovide that system administration accounts are only used to connect to system administration systems.\n\nThe relevant entities shall review access rights of privileged accounts and system administration accounts at planned intervals and be modified based on organisational changes, and shall document the results of the review, including the necessary changes of access rights."
    },
    {
      "id": "annex-Point11-4",
      "type": "annex_point",
      "point": "11.4",
      "parent_point": "11",
      "title": "Administration systems",
      "nis2_article_21_2_point": null,
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "11",
          "target_type": "annex_point",
          "reasoning": "Annex point 11.4 is a subdivision of point 11.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall restrict and control the use of system administration systems in accordance with the access control policy referred to in point 11.1.\n\nFor that purpose, the relevant entities shall:\n\nonly use system administration systems for system administration purposes, and not for any other operations;\n\nseparate logically such systems from application software not used for system administrative purposes,\n\nprotect access to system administration systems through authentication and encryption."
    },
    {
      "id": "annex-Point11-5",
      "type": "annex_point",
      "point": "11.5",
      "parent_point": "11",
      "title": "Identification",
      "nis2_article_21_2_point": null,
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "11",
          "target_type": "annex_point",
          "reasoning": "Annex point 11.5 is a subdivision of point 11.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall manage the full life cycle of identities of network and information systems and their users.\n\nFor that purpose, the relevant entities shall:\n\nset up unique identities for network and information systems and their users;\n\nlink the identity of users to a single person;\n\nensure oversight of identities of network and information systems;\n\napply logging to the management of identities.\n\nThe relevant entities shall only permit identities assigned to multiple persons, such as shared identities, where they are necessary for business or operational reasons and are subject to an explicit approval process and documentation. The relevant entities shall take identities assigned to multiple persons into account in the cybersecurity risk management framework referred to in point 2.1.\n\nThe relevant entities shall regularly review the identities for network and information systems and their users and, if no longer needed, deactivate them without delay."
    },
    {
      "id": "annex-Point11-6",
      "type": "annex_point",
      "point": "11.6",
      "parent_point": "11",
      "title": "Authentication",
      "nis2_article_21_2_point": null,
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "11",
          "target_type": "annex_point",
          "reasoning": "Annex point 11.6 is a subdivision of point 11.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall implement secure authentication procedures and technologies based on access restrictions and the policy on access control.\n\nFor that purpose, the relevant entities shall:\n\nensure the strength of authentication is appropriate to the classification of the asset to be accessed;\n\ncontrol the allocation to users and management of secret authentication information by a process that ensures the confidentiality of the information, including advising personnel on appropriate handling of authentication information;\n\nrequire the change of authentication credentials initially, at predefined intervals and upon suspicion that the credentials were compromised;\n\nrequire the reset of authentication credentials and the blocking of users after a predefined number of unsuccessful log-in attempts;\n\nterminate inactive sessions after a predefined period of inactivity; and\n\nrequire separate credentials to access privileged access or administrative accounts.\n\nThe relevant entities shall to the extent feasible use state-of-the-art authentication methods, in accordance with the associated assessed risk and the classification of the asset to be accessed, and unique authentication information.\n\nThe relevant entities shall review the authentication procedures and technologies at planned intervals."
    },
    {
      "id": "annex-Point11-7",
      "type": "annex_point",
      "point": "11.7",
      "parent_point": "11",
      "title": "Multi-factor authentication",
      "nis2_article_21_2_point": null,
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "11",
          "target_type": "annex_point",
          "reasoning": "Annex point 11.7 is a subdivision of point 11.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall ensure that users are authenticated by multiple authentication factors or continuous authentication mechanisms for accessing the relevant entities\u2019 network and information systems, where appropriate, in accordance with the classification of the asset to be accessed.\n\nThe relevant entities shall ensure that the strength of authentication is appropriate for the classification of the asset to be accessed."
    },
    {
      "id": "annex-Point12",
      "type": "annex_point",
      "point": "12",
      "parent_point": null,
      "title": "Asset management (Article\u00a021(2), point (i), of Directive (EU)\u00a02022/2555)",
      "nis2_article_21_2_point": "i",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "relation": "gives_effect_to",
          "target_article": 2,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 12 implements Article 21(2), point (i).",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "text": "Asset management (Article\u00a021(2), point (i), of Directive (EU)\u00a02022/2555)"
    },
    {
      "id": "annex-Point12-1",
      "type": "annex_point",
      "point": "12.1",
      "parent_point": "12",
      "title": "Asset classification",
      "nis2_article_21_2_point": "i",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "12",
          "target_type": "annex_point",
          "reasoning": "Annex point 12.1 is a subdivision of point 12.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "For the purpose of Article\u00a021(2), point (i) of Directive (EU)\u00a02022/2555, the relevant entities shall lay down classification levels of all assets, including information, in scope of their network and information systems for the level of protection required.\n\nFor the purpose of point 12.1.1, the relevant entities shall:\n\nlay down a system of classification levels for assets;\n\nassociate all assets with a classification level, based on confidentiality, integrity, authenticity and availability requirements, to indicate the protection required according to their sensitivity, criticality, risk and business value;\n\nalign the availability requirements of the assets with the delivery and recovery objectives set out in their business continuity and disaster recovery plans.\n\nThe relevant entities shall conduct periodic reviews of the classification levels of assets and update them, where appropriate."
    },
    {
      "id": "annex-Point12-2",
      "type": "annex_point",
      "point": "12.2",
      "parent_point": "12",
      "title": "Handling of assets",
      "nis2_article_21_2_point": "i",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "12",
          "target_type": "annex_point",
          "reasoning": "Annex point 12.2 is a subdivision of point 12.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall establish, implement and apply a policy for the proper handling of assets, including information, in accordance with their network and information security policy, and shall communicate the policy on proper handling of assets to anyone who uses or handles assets.\n\nThe policy shall:\n\ncover the entire life cycle of the assets, including acquisition, use, storage, transportation and disposal;\n\nprovide rules on the safe use, safe storage, safe transport, and the irretrievable deletion and destruction of the assets;\n\nprovide that the transfer shall take place in a secure manner, in accordance with the type of asset to be transferred.\n\nThe relevant entities shall review and, where appropriate, update the policy at planned intervals and when significant incidents or significant changes to operations or risks occur."
    },
    {
      "id": "annex-Point12-3",
      "type": "annex_point",
      "point": "12.3",
      "parent_point": "12",
      "title": "Removable media policy",
      "nis2_article_21_2_point": "i",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "12",
          "target_type": "annex_point",
          "reasoning": "Annex point 12.3 is a subdivision of point 12.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall establish, implement and apply a policy on the management of removable storage media and communicate it to their employees and third parties who handle removable storage media at the relevant entities\u2019 premises or other locations where the removable media is connected to the relevant entities\u2019 network and information systems.\n\nThe policy shall:\n\nprovide for a technical prohibition of the connection of removable media unless there is an organisational reason for their use;\n\nprovide for disabling self-execution from such media and scanning the media for malicious code before they are used on the relevant entities\u2019 systems;\n\nprovide measures for controlling and protecting portable storage devices containing data while in transit and in storage;\n\nwhere appropriate, provide measures for the use of cryptographic techniques to protect data on removable storage media.\n\nThe relevant entities shall review and, where appropriate, update the policy at planned intervals and when significant incidents or significant changes to operations or risks occur."
    },
    {
      "id": "annex-Point12-4",
      "type": "annex_point",
      "point": "12.4",
      "parent_point": "12",
      "title": "Asset inventory",
      "nis2_article_21_2_point": "i",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "12",
          "target_type": "annex_point",
          "reasoning": "Annex point 12.4 is a subdivision of point 12.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall develop and maintain a complete, accurate, up-to-date and consistent inventory of their assets. They shall record changes to the entries in the inventory in a traceable manner.\n\nThe granularity of the inventory of the assets shall be at a level appropriate for the needs of the relevant entities. The inventory shall include the following:\n\nthe list of operations and services and their description,\n\nthe list of network and information systems and other associated assets supporting the relevant entities\u2019 operations and services.\n\nThe relevant entities shall regularly review and update the inventory and their assets and document the history of changes."
    },
    {
      "id": "annex-Point12-5",
      "type": "annex_point",
      "point": "12.5",
      "parent_point": "12",
      "title": "Deposit, return or deletion of assets upon termination of employment",
      "nis2_article_21_2_point": "i",
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "12",
          "target_type": "annex_point",
          "reasoning": "Annex point 12.5 is a subdivision of point 12.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "The relevant entities shall establish, implement and apply procedures which ensure that their assets which are under custody of personnel are deposited, returned or deleted upon termination of employment, and shall document the deposit, return and deletion of those assets. Where the deposit, return or deletion of assets is not possible, the relevant entities shall ensure that the assets can no longer access the relevant entities\u2019 network and information systems in accordance with point 12.2.2."
    },
    {
      "id": "annex-Point13",
      "type": "annex_point",
      "point": "13",
      "parent_point": null,
      "title": "Environmental and physical security (Article\u00a021(2), points (c), (e) and (i) of Directive (EU)\u00a02022/2555)",
      "nis2_article_21_2_point": null,
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "relation": "gives_effect_to",
          "target_article": 2,
          "target_paragraph": "1",
          "target_type": "article_paragraph",
          "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 13 implements Article 21(2), point (c, e and i).",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "text": "Environmental and physical security (Article\u00a021(2), points (c), (e) and (i) of Directive (EU)\u00a02022/2555)"
    },
    {
      "id": "annex-Point13-1",
      "type": "annex_point",
      "point": "13.1",
      "parent_point": "13",
      "title": "Supporting utilities",
      "nis2_article_21_2_point": null,
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "13",
          "target_type": "annex_point",
          "reasoning": "Annex point 13.1 is a subdivision of point 13.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "For the purpose of Article\u00a021(2)(c) of Directive (EU)\u00a02022/2555, the relevant entities shall prevent loss, damage or compromise of network and information systems or interruption to their operations due to the failure and disruption of supporting utilities.\n\nFor that purpose, the relevant entities shall, where appropriate:\n\nprotect facilities from power failures and other disruptions caused by failures in supporting utilities such as electricity, telecommunications, water supply, gas, sewage, ventilation and air conditioning;\n\nconsider the use of redundancy in utilities services;\n\nprotect utility services for electricity and telecommunications, which transport data or supply network and information systems, against interception and damage;\n\nmonitor the utility services referred to in point (c) and report to the competent internal or external personnel events outside the minimum and maximum control thresholds referred to in point 13.2.2(b) affecting the utility services;\n\nconclude contracts for the emergency supply with corresponding services, such as for the fuel for emergency power supply;\n\nensure continuous effectiveness, monitor, maintain and test the supply of the network and information systems necessary for the operation of the service offered, in particular the electricity, temperature and humidity control, telecommunications and Internet connection.\n\nThe relevant entities shall test, review and, where appropriate, update the protection measures on a regular basis or following significant incidents or significant changes to operations or risks."
    },
    {
      "id": "annex-Point13-2",
      "type": "annex_point",
      "point": "13.2",
      "parent_point": "13",
      "title": "Protection against physical and environmental threats",
      "nis2_article_21_2_point": null,
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "13",
          "target_type": "annex_point",
          "reasoning": "Annex point 13.2 is a subdivision of point 13.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "For the purpose of Article\u00a021(2)(e) of Directive (EU)\u00a02022/2555, the relevant entities shall prevent or reduce the consequences of events originating from physical and environmental threats, such as natural disasters and other intentional or unintentional threats, based on the results of the risk assessment carried out pursuant to point 2.1.\n\nFor that purpose, the relevant entities shall, where appropriate:\n\ndesign and implement protection measures against physical and environmental threats;\n\ndetermine minimum and maximum control thresholds for physical and environmental threats;\n\nmonitor environmental parameters and report to the competent internal or external personnel events outside the minimum and maximum control thresholds referred to in point (b).\n\nThe relevant entities shall test, review and, where appropriate, update the protection measures against physical and environmental threats on a regular basis or following significant incidents or significant changes to operations or risks."
    },
    {
      "id": "annex-Point13-3",
      "type": "annex_point",
      "point": "13.3",
      "parent_point": "13",
      "title": "Perimeter and physical access control",
      "nis2_article_21_2_point": null,
      "akn4eu_headerofannex_ref": "ANNEX I",
      "akn4eu_annex_element": "level",
      "outbound_relations": [
        {
          "relation": "part_of",
          "target_point": "13",
          "target_type": "annex_point",
          "reasoning": "Annex point 13.3 is a subdivision of point 13.",
          "confidence": "high",
          "akn4eu_source_refers_to": null,
          "akn4eu_target_refers_to": null,
          "akn4eu_target_uri": null,
          "akn4eu_ancestry": []
        }
      ],
      "inbound_relations": [],
      "text": "For the purpose of Article\u00a021(2)(i) of Directive (EU)\u00a02022/2555, the relevant entities shall prevent and monitor unauthorised physical access, damage and interference to their network and information systems.\n\nFor that purpose, the relevant entities shall:\n\non the basis of the risk assessment carried out pursuant to point 2.1, lay down and use security perimeters to protect areas where network and information systems and other associated assets are located;\n\nprotect the areas referred to in point (a) by appropriate entry controls and access points;\n\ndesign and implement physical security for offices, rooms and facilities,\n\ncontinuously monitor their premises for unauthorised physical access.\n\nThe relevant entities shall test, review and, where appropriate, update the physical access control measures on a regular basis or following significant incidents or significant changes to operations or risks.\n\nELI: http://data.europa.eu/eli/reg_impl/2024/2690/oj\n\nISSN 1977-0677 (electronic edition)"
    }
  ],
  "canonical_edges": [
    {
      "confidence": "high",
      "reasoning": "Recital 1 mirrors the language of Article 1 almost verbatim, explaining the Regulation's dual purpose: laying down technical/methodological requirements for Article 21(2) NIS2 measures and specifying significant incidents under Article 23(3) NIS2.",
      "relation": "provides_guidance_for",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-1",
      "source_type": "recital",
      "target": "article-Art1-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-1__article-Art1-UN1__provides_guidance_for"
    },
    {
      "confidence": "high",
      "reasoning": "Recital 2 specifically addresses trust service providers, and Article 14 sets out the entity-specific significant-incident criteria exclusively for trust service providers.",
      "relation": "applies_to",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-2",
      "source_type": "recital",
      "target": "article-Art14-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-2__article-Art14-UN1__applies_to"
    },
    {
      "confidence": "high",
      "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 1 (Policy on the security of network and information systems) as part of the Annex as a whole.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-3",
      "source_type": "recital",
      "target": "annex-Point1",
      "target_type": "annex_point",
      "edge_id": "recital-3__annex-Point1__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 2 (Risk management policy) as part of the Annex as a whole.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-3",
      "source_type": "recital",
      "target": "annex-Point2",
      "target_type": "annex_point",
      "edge_id": "recital-3__annex-Point2__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 3 (Incident handling) as part of the Annex as a whole.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-3",
      "source_type": "recital",
      "target": "annex-Point3",
      "target_type": "annex_point",
      "edge_id": "recital-3__annex-Point3__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 4 (Business continuity and crisis management) as part of the Annex as a whole.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-3",
      "source_type": "recital",
      "target": "annex-Point4",
      "target_type": "annex_point",
      "edge_id": "recital-3__annex-Point4__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 5 (Supply chain security) as part of the Annex as a whole.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-3",
      "source_type": "recital",
      "target": "annex-Point5",
      "target_type": "annex_point",
      "edge_id": "recital-3__annex-Point5__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 6 (Security in network and information systems acquisition, development and maintenance) as part of the Annex as a whole.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-3",
      "source_type": "recital",
      "target": "annex-Point6",
      "target_type": "annex_point",
      "edge_id": "recital-3__annex-Point6__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 7 (Policies and procedures to assess the effectiveness of cybersecurity risk-management measures) as part of the Annex as a whole.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-3",
      "source_type": "recital",
      "target": "annex-Point7",
      "target_type": "annex_point",
      "edge_id": "recital-3__annex-Point7__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 8 (Basic cyber hygiene practices and security training) as part of the Annex as a whole.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-3",
      "source_type": "recital",
      "target": "annex-Point8",
      "target_type": "annex_point",
      "edge_id": "recital-3__annex-Point8__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 9 (Cryptography) as part of the Annex as a whole.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-3",
      "source_type": "recital",
      "target": "annex-Point9",
      "target_type": "annex_point",
      "edge_id": "recital-3__annex-Point9__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 10 (Human resources security) as part of the Annex as a whole.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-3",
      "source_type": "recital",
      "target": "annex-Point10",
      "target_type": "annex_point",
      "edge_id": "recital-3__annex-Point10__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 11 (Access control) as part of the Annex as a whole.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-3",
      "source_type": "recital",
      "target": "annex-Point11",
      "target_type": "annex_point",
      "edge_id": "recital-3__annex-Point11__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 12 (Asset management) as part of the Annex as a whole.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-3",
      "source_type": "recital",
      "target": "annex-Point12",
      "target_type": "annex_point",
      "edge_id": "recital-3__annex-Point12__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R3 states that the technical and methodological requirements set out in the Annex are based on European and international standards such as ISO/IEC 27001, ISO/IEC 27002 and ETSI EN 319 401. That statement refines Annex point 13 (Environmental and physical security) as part of the Annex as a whole.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-3",
      "source_type": "recital",
      "target": "annex-Point13",
      "target_type": "annex_point",
      "edge_id": "recital-3__annex-Point13__refines"
    },
    {
      "confidence": "high",
      "reasoning": "Recital 4 explains the proportionality principle that underpins Article 2(2)'s requirement to ensure a risk-appropriate level of security, enumerating factors such as risk exposure, size, and incident likelihood.",
      "relation": "provides_guidance_for",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-4",
      "source_type": "recital",
      "target": "article-Art2-Para2",
      "target_type": "article_paragraph",
      "edge_id": "recital-4__article-Art2-Para2__provides_guidance_for"
    },
    {
      "confidence": "high",
      "reasoning": "Recital 5 expands on Article 2(2) by introducing compensating measures as an alternative for entities unable to implement certain requirements due to size, providing concrete examples such as management oversight for micro-entities.",
      "relation": "expands",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-5",
      "source_type": "recital",
      "target": "article-Art2-Para2",
      "target_type": "article_paragraph",
      "edge_id": "recital-5__article-Art2-Para2__expands"
    },
    {
      "confidence": "high",
      "reasoning": "Recital 6 provides concrete interpretive guidance on the 'where appropriate', 'where applicable', or 'to the extent feasible' qualifiers used in Article 2(2), explaining the documentation obligation and adding that authorities may consider implementation timelines.",
      "relation": "concretizes",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-6",
      "source_type": "recital",
      "target": "article-Art2-Para2",
      "target_type": "article_paragraph",
      "edge_id": "recital-6__article-Art2-Para2__concretizes"
    },
    {
      "confidence": "high",
      "reasoning": "R7 describes guidance by ENISA or national competent authorities for the identification, analysis and assessment of risks for the purpose of establishing and maintaining an appropriate risk management framework, which is required by Annex point 2.1.",
      "relation": "provides_guidance_for",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-7",
      "source_type": "recital",
      "target": "annex-Point2.1",
      "target_type": "annex_point",
      "edge_id": "recital-7__annex-Point2.1__provides_guidance_for"
    },
    {
      "confidence": "high",
      "reasoning": "R8 addresses network security measures on latest generation network layer protocols, modern e-mail standards and DNS/routing best practice, and the multistakeholder forum identifying them. These correspond to Annex points 6.7.2(j), (k) and (l).",
      "relation": "concretizes",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-8",
      "source_type": "recital",
      "target": "annex-Point6.7",
      "target_type": "annex_point",
      "edge_id": "recital-8__annex-Point6.7__concretizes"
    },
    {
      "confidence": "high",
      "reasoning": "R9 requires a policy on the security of network and information systems as the highest-level document approved by the management bodies, plus topic-specific policies and monitoring indicators. That is the content of Annex point 1.1.",
      "relation": "concretizes",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-9",
      "source_type": "recital",
      "target": "annex-Point1.1",
      "target_type": "annex_point",
      "edge_id": "recital-9__annex-Point1.1__concretizes"
    },
    {
      "confidence": "high",
      "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 1 (Policy on the security of network and information systems).",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-10",
      "source_type": "recital",
      "target": "annex-Point1",
      "target_type": "annex_point",
      "edge_id": "recital-10__annex-Point1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 2 (Risk management policy).",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-10",
      "source_type": "recital",
      "target": "annex-Point2",
      "target_type": "annex_point",
      "edge_id": "recital-10__annex-Point2__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 3 (Incident handling).",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-10",
      "source_type": "recital",
      "target": "annex-Point3",
      "target_type": "annex_point",
      "edge_id": "recital-10__annex-Point3__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 4 (Business continuity and crisis management).",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-10",
      "source_type": "recital",
      "target": "annex-Point4",
      "target_type": "annex_point",
      "edge_id": "recital-10__annex-Point4__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 5 (Supply chain security).",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-10",
      "source_type": "recital",
      "target": "annex-Point5",
      "target_type": "annex_point",
      "edge_id": "recital-10__annex-Point5__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 6 (Security in network and information systems acquisition, development and maintenance).",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-10",
      "source_type": "recital",
      "target": "annex-Point6",
      "target_type": "annex_point",
      "edge_id": "recital-10__annex-Point6__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 7 (Policies and procedures to assess the effectiveness of cybersecurity risk-management measures).",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-10",
      "source_type": "recital",
      "target": "annex-Point7",
      "target_type": "annex_point",
      "edge_id": "recital-10__annex-Point7__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 8 (Basic cyber hygiene practices and security training).",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-10",
      "source_type": "recital",
      "target": "annex-Point8",
      "target_type": "annex_point",
      "edge_id": "recital-10__annex-Point8__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 9 (Cryptography).",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-10",
      "source_type": "recital",
      "target": "annex-Point9",
      "target_type": "annex_point",
      "edge_id": "recital-10__annex-Point9__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 10 (Human resources security).",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-10",
      "source_type": "recital",
      "target": "annex-Point10",
      "target_type": "annex_point",
      "edge_id": "recital-10__annex-Point10__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 11 (Access control).",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-10",
      "source_type": "recital",
      "target": "annex-Point11",
      "target_type": "annex_point",
      "edge_id": "recital-10__annex-Point11__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 12 (Asset management).",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-10",
      "source_type": "recital",
      "target": "annex-Point12",
      "target_type": "annex_point",
      "edge_id": "recital-10__annex-Point12__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R10 defines the term \"user\" expressly for the purposes of the technical and the methodological requirements laid down in the Annex, and therefore governs Annex point 13 (Environmental and physical security).",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-10",
      "source_type": "recital",
      "target": "annex-Point13",
      "target_type": "annex_point",
      "edge_id": "recital-10__annex-Point13__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R11 describes the risk management framework, the risk treatment plan and the available risk treatment options, which Annex point 2.1 lays down.",
      "relation": "concretizes",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-11",
      "source_type": "recital",
      "target": "annex-Point2.1",
      "target_type": "annex_point",
      "edge_id": "recital-11__annex-Point2.1__concretizes"
    },
    {
      "confidence": "high",
      "reasoning": "R12 requires monitoring of network and information systems to detect events, near misses and incidents, including timely detection of anomalous traffic and denial of service attacks, corresponding to Annex point 3.2 on monitoring and logging.",
      "relation": "concretizes",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-12",
      "source_type": "recital",
      "target": "annex-Point3.2",
      "target_type": "annex_point",
      "edge_id": "recital-12__annex-Point3.2__concretizes"
    },
    {
      "confidence": "high",
      "reasoning": "R13 encourages a comprehensive business impact analysis establishing maximum tolerable downtime and recovery objectives, which Annex point 4.1.3 requires.",
      "relation": "concretizes",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-13",
      "source_type": "recital",
      "target": "annex-Point4.1",
      "target_type": "annex_point",
      "edge_id": "recital-13__annex-Point4.1__concretizes"
    },
    {
      "confidence": "high",
      "reasoning": "R14 requires a supply chain security policy governing relations with direct suppliers and service providers and adequate security clauses in contracts, which is the content of Annex points 5.1.1 and 5.1.4.",
      "relation": "concretizes",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-14",
      "source_type": "recital",
      "target": "annex-Point5.1",
      "target_type": "annex_point",
      "edge_id": "recital-14__annex-Point5.1__concretizes"
    },
    {
      "confidence": "high",
      "reasoning": "R15 describes regular security tests based on a dedicated policy and procedures, their possible forms and the use of their findings, corresponding to Annex point 6.5.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-15",
      "source_type": "recital",
      "target": "annex-Point6.5",
      "target_type": "annex_point",
      "edge_id": "recital-15__annex-Point6.5__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R16 requires security patch management procedures aligned with change, vulnerability and risk management, which Annex point 6.6 lays down.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-16",
      "source_type": "recital",
      "target": "annex-Point6.6",
      "target_type": "annex_point",
      "edge_id": "recital-16__annex-Point6.6__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R17 addresses the management of risks stemming from the acquisition of ICT products and services and the assurance of cybersecurity protection levels, corresponding to Annex point 6.1.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-17",
      "source_type": "recital",
      "target": "annex-Point6.1",
      "target_type": "annex_point",
      "edge_id": "recital-17__annex-Point6.1__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R18 describes typical network security solutions such as firewalls, limitation of connections, VPN for remote access and time-limited service provider connections, which Annex point 6.7.2 requires.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-18",
      "source_type": "recital",
      "target": "annex-Point6.7",
      "target_type": "annex_point",
      "edge_id": "recital-18__annex-Point6.7__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R19 requires controls preventing or detecting unauthorised software and, where appropriate, detection and response software, which is the content of Annex point 6.9.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-19",
      "source_type": "recital",
      "target": "annex-Point6.9",
      "target_type": "annex_point",
      "edge_id": "recital-19__annex-Point6.9__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R20 sets out basic cyber hygiene practices and awareness raising for users pursuant to Article 21(2), point (g), of Directive (EU) 2022/2555, corresponding to Annex point 8.1.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-20",
      "source_type": "recital",
      "target": "annex-Point8.1",
      "target_type": "annex_point",
      "edge_id": "recital-20__annex-Point8.1__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R21 requires a topic-specific policy addressing access by persons and by network and information systems, which Annex point 11.1 lays down.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-21",
      "source_type": "recital",
      "target": "annex-Point11.1",
      "target_type": "annex_point",
      "edge_id": "recital-21__annex-Point11.1__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R22 addresses employee security management measures and awareness of misuse risks, corresponding to Annex point 10.1.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-22",
      "source_type": "recital",
      "target": "annex-Point10.1",
      "target_type": "annex_point",
      "edge_id": "recital-22__annex-Point10.1__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R22 states that verification of the background of employees and, where applicable, direct suppliers and service providers contributes to human resources security, which Annex point 10.2 governs.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-22",
      "source_type": "recital",
      "target": "annex-Point10.2",
      "target_type": "annex_point",
      "edge_id": "recital-22__annex-Point10.2__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R22 requires a disciplinary process for handling violations of the security policies, which Annex point 10.4 lays down.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-22",
      "source_type": "recital",
      "target": "annex-Point10.4",
      "target_type": "annex_point",
      "edge_id": "recital-22__annex-Point10.4__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R23 addresses multi-factor authentication, in particular for remote access and privileged or administration accounts, which Annex point 11.7 requires.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-23",
      "source_type": "recital",
      "target": "annex-Point11.7",
      "target_type": "annex_point",
      "edge_id": "recital-23__annex-Point11.7__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R24 requires sound asset management covering tangible and intangible assets, an asset inventory, classification and protection throughout the lifecycle, which is the subject of Annex point 12.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-24",
      "source_type": "recital",
      "target": "annex-Point12",
      "target_type": "annex_point",
      "edge_id": "recital-24__annex-Point12__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R25 describes classification of assets by type, sensitivity, risk level and security requirements, which Annex point 12.1 lays down.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-25",
      "source_type": "recital",
      "target": "annex-Point12.1",
      "target_type": "annex_point",
      "edge_id": "recital-25__annex-Point12.1__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R25 states that employees handling assets should be familiar with the asset handling policies and instructions, corresponding to Annex point 12.2.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-25",
      "source_type": "recital",
      "target": "annex-Point12.2",
      "target_type": "annex_point",
      "edge_id": "recital-25__annex-Point12.2__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R26 describes the appropriate granularity and possible content of the asset inventory, which Annex point 12.4 requires.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-26",
      "source_type": "recital",
      "target": "annex-Point12.4",
      "target_type": "annex_point",
      "edge_id": "recital-26__annex-Point12.4__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R27 addresses the allocation and organisation of cybersecurity roles, responsibilities and authorities, including possible role types, which Annex point 1.2 lays down.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-27",
      "source_type": "recital",
      "target": "annex-Point1.2",
      "target_type": "annex_point",
      "edge_id": "recital-27__annex-Point1.2__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R28 derives from the all-hazards approach in Article 21(2) of Directive (EU) 2022/2555 that the requirements must address physical and environmental security, which is the subject of Annex point 13.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-28",
      "source_type": "recital",
      "target": "annex-Point13",
      "target_type": "annex_point",
      "edge_id": "recital-28__annex-Point13__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R28 states that preventing loss or damage due to failure and disruption of supporting utilities contributes to business continuity, which Annex point 13.1 governs.",
      "relation": "refines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-28",
      "source_type": "recital",
      "target": "annex-Point13.1",
      "target_type": "annex_point",
      "edge_id": "recital-28__annex-Point13.1__refines"
    },
    {
      "confidence": "high",
      "reasoning": "R29 requires protection measures against physical and environmental threats, minimum and maximum control thresholds and monitoring of environmental parameters, which Annex point 13.2 lays down.",
      "relation": "concretizes",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-29",
      "source_type": "recital",
      "target": "annex-Point13.2",
      "target_type": "annex_point",
      "edge_id": "recital-29__annex-Point13.2__concretizes"
    },
    {
      "confidence": "high",
      "reasoning": "Concretizes the horizontal criteria for significant incidents by explaining the Regulation specifies exhaustive criteria to enable entities to assess significance for notification.",
      "relation": "concretizes",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-30",
      "source_type": "recital",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "recital-30__article-Art3-Para1__concretizes"
    },
    {
      "confidence": "high",
      "reasoning": "R30, third sentence, states that the criteria set out in this Regulation should be considered exhaustive, without prejudice to Article 5 of Directive (EU) 2022/2555. That exhaustiveness is a distinct normative qualification of the criteria catalogue in Art3P1, going beyond the concretisation already captured.",
      "relation": "qualifies",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-30",
      "source_type": "recital",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "recital-30__article-Art3-Para1__qualifies"
    },
    {
      "confidence": "high",
      "reasoning": "R31 determines the moment at which a relevant entity is to be regarded as having become aware of a significant incident and the standard of the initial assessment. It thereby guides the application of the significance criteria in Art3P1 (and corresponds to Annex point 3.4.1 on event assessment and classification).",
      "relation": "provides_guidance_for",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-31",
      "source_type": "recital",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "recital-31__article-Art3-Para1__provides_guidance_for"
    },
    {
      "confidence": "high",
      "reasoning": "R31 requires the relevant entity to assess a suspicious event in a timely manner to determine whether it constitutes an incident and, if so, its nature and severity. That is verbatim the obligation in Annex point 3.4.1, which governs when the entity becomes aware of a significant incident.",
      "relation": "provides_guidance_for",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-31",
      "source_type": "recital",
      "target": "annex-Point3.4",
      "target_type": "annex_point",
      "edge_id": "recital-31__annex-Point3.4__provides_guidance_for"
    },
    {
      "confidence": "high",
      "reasoning": "R32 opens with the purpose of establishing whether an incident is significant and is therefore not limited to the counting method in Art3P3 or to trust services in Art14; it guides the significance assessment under Art3P1 as a whole.",
      "relation": "provides_guidance_for",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-32",
      "source_type": "recital",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "recital-32__article-Art3-Para1__provides_guidance_for"
    },
    {
      "confidence": "high",
      "reasoning": "Directly explains how to count the number of users impacted by an incident, including business customers and associated natural and legal persons, and provides estimation methodology when exact counts are unavailable.",
      "relation": "provides_guidance_for",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-32",
      "source_type": "recital",
      "target": "article-Art3-Para3",
      "target_type": "article_paragraph",
      "edge_id": "recital-32__article-Art3-Para3__provides_guidance_for"
    },
    {
      "confidence": "high",
      "reasoning": "Explains that trust service providers should also consider the number of relying parties when establishing significance, and defines 'relying parties' as natural or legal persons that rely upon a trust service.",
      "relation": "provides_guidance_for",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-32",
      "source_type": "recital",
      "target": "article-Art14-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-32__article-Art14-UN1__provides_guidance_for"
    },
    {
      "confidence": "high",
      "reasoning": "Clarifies that scheduled maintenance operations and pre-determined contractual interruptions resulting in limited availability or unavailability should not be considered significant incidents, elaborating on Article 3(2)'s exception.",
      "relation": "provides_guidance_for",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-33",
      "source_type": "recital",
      "target": "article-Art3-Para2",
      "target_type": "article_paragraph",
      "edge_id": "recital-33__article-Art3-Para2__provides_guidance_for"
    },
    {
      "confidence": "high",
      "reasoning": "Provides the methodology for measuring the duration of an availability-impacting incident, which is used to assess the significance criteria in Article 3(1).",
      "relation": "provides_guidance_for",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-34",
      "source_type": "recital",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "recital-34__article-Art3-Para1__provides_guidance_for"
    },
    {
      "confidence": "high",
      "reasoning": "R34 defines how the duration of an availability-affecting incident is measured. Art5 sets duration-based thresholds for DNS service providers, which can only be applied using that measurement rule.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-34",
      "source_type": "recital",
      "target": "article-Art5-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-34__article-Art5-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R34 defines how the duration of an availability-affecting incident is measured. Art6 sets duration-based thresholds for TLD name registries, which can only be applied using that measurement rule.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-34",
      "source_type": "recital",
      "target": "article-Art6-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-34__article-Art6-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R34 defines how the duration of an availability-affecting incident is measured. Art7 sets duration-based thresholds for cloud computing service providers, which can only be applied using that measurement rule.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-34",
      "source_type": "recital",
      "target": "article-Art7-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-34__article-Art7-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R34 defines how the duration of an availability-affecting incident is measured. Art9 sets duration-based thresholds for content delivery network providers, which can only be applied using that measurement rule.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-34",
      "source_type": "recital",
      "target": "article-Art9-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-34__article-Art9-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R34 defines how the duration of an availability-affecting incident is measured. Art10 sets duration-based thresholds for managed service providers and managed security service providers, which can only be applied using that measurement rule.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-34",
      "source_type": "recital",
      "target": "article-Art10-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-34__article-Art10-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R34 defines incident duration, which Art14 uses as a significance criterion for trust service providers (Art14 points (a) to (c)).",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-34",
      "source_type": "recital",
      "target": "article-Art14-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-34__article-Art14-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "Provides the methodology for measuring complete unavailability of a service, a core concept underlying the significance criteria in Article 3(1).",
      "relation": "provides_guidance_for",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-35",
      "source_type": "recital",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "recital-35__article-Art3-Para1__provides_guidance_for"
    },
    {
      "confidence": "high",
      "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art5 applies that criterion to DNS service providers, so the definition in R35 governs the entity-specific threshold directly.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-35",
      "source_type": "recital",
      "target": "article-Art5-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-35__article-Art5-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art6 applies that criterion to TLD name registries, so the definition in R35 governs the entity-specific threshold directly.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-35",
      "source_type": "recital",
      "target": "article-Art6-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-35__article-Art6-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art7 applies that criterion to cloud computing service providers, so the definition in R35 governs the entity-specific threshold directly.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-35",
      "source_type": "recital",
      "target": "article-Art7-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-35__article-Art7-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art8 applies that criterion to data centre service providers, so the definition in R35 governs the entity-specific threshold directly.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-35",
      "source_type": "recital",
      "target": "article-Art8-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-35__article-Art8-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art9 applies that criterion to content delivery network providers, so the definition in R35 governs the entity-specific threshold directly.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-35",
      "source_type": "recital",
      "target": "article-Art9-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-35__article-Art9-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art10 applies that criterion to managed service providers and managed security service providers, so the definition in R35 governs the entity-specific threshold directly.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-35",
      "source_type": "recital",
      "target": "article-Art10-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-35__article-Art10-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art11 applies that criterion to providers of online marketplaces, so the definition in R35 governs the entity-specific threshold directly.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-35",
      "source_type": "recital",
      "target": "article-Art11-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-35__article-Art11-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art12 applies that criterion to providers of online search engines, so the definition in R35 governs the entity-specific threshold directly.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-35",
      "source_type": "recital",
      "target": "article-Art12-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-35__article-Art12-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R35 defines how complete unavailability of a service is to be measured. Art13 applies that criterion to providers of social networking services platforms, so the definition in R35 governs the entity-specific threshold directly.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-35",
      "source_type": "recital",
      "target": "article-Art13-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-35__article-Art13-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R35 defines complete unavailability, which Art14 uses as a significance criterion for trust service providers (Art14 points (a) to (c)).",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-35",
      "source_type": "recital",
      "target": "article-Art14-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-35__article-Art14-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "Defines what constitutes 'direct financial loss' as used in Article 3(1)(a) by specifying included costs (replacement, staff, legal, remediation, lost revenue) and explicitly excluding administrative fines and day-to-day operational costs.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-36",
      "source_type": "recital",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "recital-36__article-Art3-Para1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "Recital 36 defines the direct-financial-loss criterion in Article 3(1)(a). Article 4(c) expressly incorporates that criterion for recurring incidents, so the definition directly guides the collective assessment under Article 4.",
      "relation": "provides_guidance_for",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-36",
      "source_type": "recital",
      "target": "article-Art4-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-36__article-Art4-UN1__provides_guidance_for"
    },
    {
      "confidence": "high",
      "reasoning": "Provides guidance on determining when an incident has caused or is capable of causing the death of a natural person (Article 3(1)(c)) or considerable damage to health (Article 3(1)(d)), with examples such as unavailability of healthcare services.",
      "relation": "provides_guidance_for",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-37",
      "source_type": "recital",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "recital-37__article-Art3-Para1__provides_guidance_for"
    },
    {
      "confidence": "high",
      "reasoning": "Defines 'limited availability' as used in the significance criteria under Article 3(1) \u2014 slower than average response times or partial loss of service functionality, with reference to objective criteria based on average response times.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-38",
      "source_type": "recital",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "recital-38__article-Art3-Para1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R38 defines when limited availability is to be assumed. Art7 uses limited availability as a significance criterion for cloud computing service providers, so R38 governs its interpretation.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-38",
      "source_type": "recital",
      "target": "article-Art7-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-38__article-Art7-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R38 defines when limited availability is to be assumed. Art8 uses limited availability as a significance criterion for data centre service providers, so R38 governs its interpretation.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-38",
      "source_type": "recital",
      "target": "article-Art8-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-38__article-Art8-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R38 defines when limited availability is to be assumed. Art9 uses limited availability as a significance criterion for content delivery network providers, so R38 governs its interpretation.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-38",
      "source_type": "recital",
      "target": "article-Art9-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-38__article-Art9-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R38 defines when limited availability is to be assumed. Art10 uses limited availability as a significance criterion for managed service providers and managed security service providers, so R38 governs its interpretation.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-38",
      "source_type": "recital",
      "target": "article-Art10-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-38__article-Art10-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R38 defines when limited availability is to be assumed. Art11 uses limited availability as a significance criterion for providers of online marketplaces, so R38 governs its interpretation.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-38",
      "source_type": "recital",
      "target": "article-Art11-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-38__article-Art11-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R38 defines when limited availability is to be assumed. Art12 uses limited availability as a significance criterion for providers of online search engines, so R38 governs its interpretation.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-38",
      "source_type": "recital",
      "target": "article-Art12-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-38__article-Art12-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R38 defines when limited availability is to be assumed. Art13 uses limited availability as a significance criterion for providers of social networking services platforms, so R38 governs its interpretation.",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-38",
      "source_type": "recital",
      "target": "article-Art13-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-38__article-Art13-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "R38 defines limited availability, which Art14 uses as a significance criterion for trust service providers (Art14 points (a) to (c)).",
      "relation": "defines",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-38",
      "source_type": "recital",
      "target": "article-Art14-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-38__article-Art14-UN1__defines"
    },
    {
      "confidence": "high",
      "reasoning": "Illustrates when successful, suspectedly malicious and unauthorised access is 'capable of causing severe operational disruption' as required by Article 3(1)(e), with the example of a cyber threat actor pre-positioning for future disruption.",
      "relation": "provides_guidance_for",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-39",
      "source_type": "recital",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "recital-39__article-Art3-Para1__provides_guidance_for"
    },
    {
      "confidence": "high",
      "reasoning": "Directly explains the rationale and criteria for treating recurring incidents as a single significant incident: same apparent root cause, minimum two occurrences within six months, and collective satisfaction of the financial loss threshold.",
      "relation": "provides_guidance_for",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-40",
      "source_type": "recital",
      "target": "article-Art4-UN1",
      "target_type": "article_paragraph",
      "edge_id": "recital-40__article-Art4-UN1__provides_guidance_for"
    },
    {
      "confidence": "high",
      "reasoning": "R1 establishes the scope of entity types covered by the Regulation (DNS, TLD, cloud, data centre, CDN, MSPs). R2 extends the regulatory framework to trust service providers, building on the scope rationale established in R1.",
      "relation": "provides_context_for",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-1",
      "source_type": "recital",
      "target": "recital-2",
      "target_type": "recital",
      "edge_id": "recital-1__recital-2__provides_context_for"
    },
    {
      "confidence": "high",
      "reasoning": "R3 establishes the standards basis (ISO, ETSI) for the Annex requirements. R4 discusses proportionality in implementing those same requirements based on risk exposure and entity size. R3's standards context frames R4's proportionality discussion.",
      "relation": "provides_context_for",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-3",
      "source_type": "recital",
      "target": "recital-4",
      "target_type": "recital",
      "edge_id": "recital-3__recital-4__provides_context_for"
    },
    {
      "confidence": "high",
      "reasoning": "R4 introduces proportionality when entities cannot implement requirements due to risk exposure or size. R5 builds directly on this by adding the concept of compensating measures that entities should adopt when they cannot implement specific requirements.",
      "relation": "builds_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-4",
      "source_type": "recital",
      "target": "recital-5",
      "target_type": "recital",
      "edge_id": "recital-4__recital-5__builds_on"
    },
    {
      "confidence": "high",
      "reasoning": "R8 describes technical network security measures (protocols, email, DNS). R9 builds on this by moving to the governance layer \u2014 policies on information system security and access control \u2014 which complement and operationalize the technical measures in R8.",
      "relation": "builds_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-8",
      "source_type": "recital",
      "target": "recital-9",
      "target_type": "recital",
      "edge_id": "recital-8__recital-9__builds_on"
    },
    {
      "confidence": "high",
      "reasoning": "R9 discusses policies on information system security including access control, which inherently involves 'users.' R10 builds on this by defining what 'user' encompasses, clarifying a key term used in the access control context of R9.",
      "relation": "builds_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-9",
      "source_type": "recital",
      "target": "recital-10",
      "target_type": "recital",
      "edge_id": "recital-9__recital-10__builds_on"
    },
    {
      "confidence": "high",
      "reasoning": "R11 establishes the risk management framework for identifying and addressing risks. R12 builds on this by specifying the detection and monitoring capabilities that operate within that framework to identify events, near misses, and incidents.",
      "relation": "builds_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-11",
      "source_type": "recital",
      "target": "recital-12",
      "target_type": "recital",
      "edge_id": "recital-11__recital-12__builds_on"
    },
    {
      "confidence": "high",
      "reasoning": "R11 establishes the risk management framework for identifying and addressing risks. R14 builds on this by adding supply chain security policy as a specific component of the risk management framework, addressing risks from suppliers and supply chain relationships.",
      "relation": "builds_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-11",
      "source_type": "recital",
      "target": "recital-14",
      "target_type": "recital",
      "edge_id": "recital-11__recital-14__builds_on"
    },
    {
      "confidence": "high",
      "reasoning": "R25 (asset classification by type, sensitivity, risk level) builds directly on R24 (asset management framework) \u2014 classification is a core component that extends the asset management concept established in R24.",
      "relation": "builds_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-25",
      "source_type": "recital",
      "target": "recital-24",
      "target_type": "recital",
      "edge_id": "recital-25__recital-24__builds_on"
    },
    {
      "confidence": "high",
      "reasoning": "R26 (asset inventory granularity and attributes) builds on R24 (asset management) \u2014 the inventory is a concrete implementation component of the broader asset management framework established in R24.",
      "relation": "builds_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-26",
      "source_type": "recital",
      "target": "recital-24",
      "target_type": "recital",
      "edge_id": "recital-26__recital-24__builds_on"
    },
    {
      "confidence": "high",
      "reasoning": "R26 (asset inventory including unique identifier, owner, classification) builds on R25 (asset classification) \u2014 the inventory incorporates the classification scheme defined in R25 as one of its attributes.",
      "relation": "builds_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-26",
      "source_type": "recital",
      "target": "recital-25",
      "target_type": "recital",
      "edge_id": "recital-26__recital-25__builds_on"
    },
    {
      "confidence": "high",
      "reasoning": "R23 (multi-factor authentication) builds on R21 (access control policy) \u2014 MFA is a specific, strengthened access control mechanism that extends the general access control framework established in R21, particularly for remote and high-privilege access scenarios.",
      "relation": "builds_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-23",
      "source_type": "recital",
      "target": "recital-21",
      "target_type": "recital",
      "edge_id": "recital-23__recital-21__builds_on"
    },
    {
      "confidence": "high",
      "reasoning": "R28 (all-hazards approach covering physical and environmental threats) provides the conceptual framework and context for R29 (specific physical protection measures against fire, flood, power failures) \u2014 the all-hazards approach establishes that physical threats must be addressed, which R29 then details with concrete protection measures.",
      "relation": "provides_context_for",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-28",
      "source_type": "recital",
      "target": "recital-29",
      "target_type": "recital",
      "edge_id": "recital-28__recital-29__provides_context_for"
    },
    {
      "confidence": "high",
      "reasoning": "R31 (notification deadlines for significant incidents) builds on R30 (significance criteria specification). Once an incident is deemed significant per R30's framework, R31 establishes the notification timelines.",
      "relation": "builds_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-31",
      "source_type": "recital",
      "target": "recital-30",
      "target_type": "recital",
      "edge_id": "recital-31__recital-30__builds_on"
    },
    {
      "confidence": "high",
      "reasoning": "R32 (user counting methodology) builds on R30 (significance criteria framework). R30 establishes the general framework for determining significance, and R32 specifies how to count impacted users as part of that determination.",
      "relation": "builds_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-32",
      "source_type": "recital",
      "target": "recital-30",
      "target_type": "recital",
      "edge_id": "recital-32__recital-30__builds_on"
    },
    {
      "confidence": "high",
      "reasoning": "R33 (maintenance exclusion) qualifies R30 (significance framework) by establishing that scheduled maintenance operations should not be considered significant incidents, narrowing the scope of what R30's framework covers.",
      "relation": "qualifies",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-33",
      "source_type": "recital",
      "target": "recital-30",
      "target_type": "recital",
      "edge_id": "recital-33__recital-30__qualifies"
    },
    {
      "confidence": "high",
      "reasoning": "R34 (incident duration measurement) builds on R30 (significance criteria framework) by specifying how to measure the duration criterion that determines significance.",
      "relation": "builds_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-34",
      "source_type": "recital",
      "target": "recital-30",
      "target_type": "recital",
      "edge_id": "recital-34__recital-30__builds_on"
    },
    {
      "confidence": "high",
      "reasoning": "R35 (complete unavailability measurement) builds on R30 (significance criteria framework) by specifying how to measure complete unavailability as a significance criterion.",
      "relation": "builds_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-35",
      "source_type": "recital",
      "target": "recital-30",
      "target_type": "recital",
      "edge_id": "recital-35__recital-30__builds_on"
    },
    {
      "confidence": "high",
      "reasoning": "R35 (complete unavailability measurement) builds on R34 (general duration measurement) by specializing the measurement methodology to the specific case of complete service unavailability.",
      "relation": "builds_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-35",
      "source_type": "recital",
      "target": "recital-34",
      "target_type": "recital",
      "edge_id": "recital-35__recital-34__builds_on"
    },
    {
      "confidence": "high",
      "reasoning": "R36 (financial loss definition) builds on R30 (significance criteria framework) by defining how to calculate direct financial losses as a significance criterion.",
      "relation": "builds_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-36",
      "source_type": "recital",
      "target": "recital-30",
      "target_type": "recital",
      "edge_id": "recital-36__recital-30__builds_on"
    },
    {
      "confidence": "high",
      "reasoning": "R37 (death/health damage criterion) builds on R30 (significance criteria framework) by adding incidents causing death or considerable health damage as a significance criterion.",
      "relation": "builds_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-37",
      "source_type": "recital",
      "target": "recital-30",
      "target_type": "recital",
      "edge_id": "recital-37__recital-30__builds_on"
    },
    {
      "confidence": "high",
      "reasoning": "R38 (limited availability definition) builds on R30 (significance criteria framework) by defining what constitutes limited availability as a significance criterion.",
      "relation": "builds_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-38",
      "source_type": "recital",
      "target": "recital-30",
      "target_type": "recital",
      "edge_id": "recital-38__recital-30__builds_on"
    },
    {
      "confidence": "high",
      "reasoning": "R39 (unauthorized access criterion) builds on R30 (significance criteria framework) by adding malicious unauthorized access as a significance criterion.",
      "relation": "builds_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-39",
      "source_type": "recital",
      "target": "recital-30",
      "target_type": "recital",
      "edge_id": "recital-39__recital-30__builds_on"
    },
    {
      "confidence": "high",
      "reasoning": "R40 (recurring incidents criterion) builds on R30 (significance criteria framework) by establishing that recurring incidents linked by the same root cause should be collectively assessed for significance.",
      "relation": "builds_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-40",
      "source_type": "recital",
      "target": "recital-30",
      "target_type": "recital",
      "edge_id": "recital-40__recital-30__builds_on"
    },
    {
      "confidence": "high",
      "reasoning": "R38 defines limited availability (service slower than average or not all functionalities available) while R35 defines complete unavailability (service fully unavailable). These are contrasting concepts on the availability spectrum.",
      "relation": "contrasts_with",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "recital-38",
      "source_type": "recital",
      "target": "recital-35",
      "target_type": "recital",
      "edge_id": "recital-38__recital-35__contrasts_with"
    },
    {
      "confidence": "high",
      "reasoning": "Art2P2 requires entities to ensure a level of security appropriate to the risks when implementing the Annex requirements. This obligation depends on and operates within the framework of Art2P1, which sets out the technical and methodological requirements themselves.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art2-Para2",
      "source_type": "article_paragraph",
      "target": "article-Art2-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art2-Para2__article-Art2-Para1__depends_on"
    },
    {
      "confidence": "high",
      "reasoning": "Art3P2 excludes scheduled interruptions of service and planned consequences of scheduled maintenance from being considered significant incidents. This directly excludes certain situations from the significant incident criteria established in Art3P1.",
      "relation": "excludes",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para2",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para2__article-Art3-Para1__excludes"
    },
    {
      "confidence": "high",
      "reasoning": "Art4P1 states that recurring incidents which individually are not significant can collectively be considered significant if they share the same root cause. This qualifies Art3P1's general criteria by adding an aggregation rule for recurring incidents.",
      "relation": "qualifies",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art4-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art4-UN1__article-Art3-Para1__qualifies"
    },
    {
      "confidence": "high",
      "reasoning": "Art2P1 sets out technical and methodological requirements for 'the relevant entities.' The definition of which entities are relevant is established in Art1P1 (subject matter), making Art2P1 dependent on Art1P1's scope definition.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art2-Para1",
      "source_type": "article_paragraph",
      "target": "article-Art1-UN1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art2-Para1__article-Art1-UN1__depends_on"
    },
    {
      "confidence": "high",
      "reasoning": "Art3P1 defines significant incident criteria for 'the relevant entities.' The entity scope is established in Art1P1, making Art3P1's incident criteria dependent on Art1P1's subject matter and scope definition.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para1",
      "source_type": "article_paragraph",
      "target": "article-Art1-UN1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para1__article-Art1-UN1__depends_on"
    },
    {
      "confidence": "high",
      "reasoning": "Art5P1 defines significant incidents specifically for DNS service providers. It depends on and applies the general significant incident criteria framework established in Art3P1 to the DNS service provider entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art5-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art5-UN1__article-Art3-Para1__depends_on"
    },
    {
      "confidence": "high",
      "reasoning": "Art6P1 defines significant incidents specifically for TLD name registries. It depends on and applies the general significant incident criteria framework established in Art3P1 to the TLD name registry entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art6-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art6-UN1__article-Art3-Para1__depends_on"
    },
    {
      "confidence": "high",
      "reasoning": "Art7P1 defines significant incidents specifically for cloud computing service providers. It depends on and applies the general significant incident criteria framework established in Art3P1 to the cloud computing entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art7-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art7-UN1__article-Art3-Para1__depends_on"
    },
    {
      "confidence": "high",
      "reasoning": "Art8P1 defines significant incidents specifically for data centre service providers. It depends on and applies the general significant incident criteria framework established in Art3P1 to the data centre entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art8-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art8-UN1__article-Art3-Para1__depends_on"
    },
    {
      "confidence": "high",
      "reasoning": "Art9P1 defines significant incidents specifically for content delivery network providers. It depends on and applies the general significant incident criteria framework established in Art3P1 to the CDN entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art9-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art9-UN1__article-Art3-Para1__depends_on"
    },
    {
      "confidence": "high",
      "reasoning": "Art10P1 defines significant incidents specifically for managed service providers and managed security service providers. It depends on and applies the general significant incident criteria framework established in Art3P1 to the MSP/MSSP entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art10-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art10-UN1__article-Art3-Para1__depends_on"
    },
    {
      "confidence": "high",
      "reasoning": "Art11P1 defines significant incidents specifically for providers of online marketplaces. It depends on and applies the general significant incident criteria framework established in Art3P1 to the online marketplace entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art11-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art11-UN1__article-Art3-Para1__depends_on"
    },
    {
      "confidence": "high",
      "reasoning": "Art12P1 defines significant incidents specifically for providers of online search engines. It depends on and applies the general significant incident criteria framework established in Art3P1 to the online search engine entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art12-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art12-UN1__article-Art3-Para1__depends_on"
    },
    {
      "confidence": "high",
      "reasoning": "Art13P1 defines significant incidents specifically for providers of social networking services platforms. It depends on and applies the general significant incident criteria framework established in Art3P1 to the social networking entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art13-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art13-UN1__article-Art3-Para1__depends_on"
    },
    {
      "confidence": "high",
      "reasoning": "Art14P1 defines significant incidents specifically for trust service providers. It depends on and applies the general significant incident criteria framework established in Art3P1 to the trust service provider entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art14-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art14-UN1__article-Art3-Para1__depends_on"
    },
    {
      "confidence": "high",
      "reasoning": "Art3P3 explicitly states 'for the purpose of Articles 7 and 9 to 14' when defining the user counting methodology. Art7P1 (cloud computing service providers) is directly referenced as one of the articles for which the user count calculation applies.",
      "relation": "references",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para3",
      "source_type": "article_paragraph",
      "target": "article-Art7-UN1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para3__article-Art7-UN1__references"
    },
    {
      "confidence": "high",
      "reasoning": "Art3P3 explicitly states 'for the purpose of Articles 7 and 9 to 14' when defining the user counting methodology. Art9P1 (CDN providers) is directly referenced as one of the articles for which the user count calculation applies.",
      "relation": "references",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para3",
      "source_type": "article_paragraph",
      "target": "article-Art9-UN1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para3__article-Art9-UN1__references"
    },
    {
      "confidence": "high",
      "reasoning": "Art3P3 explicitly states 'for the purpose of Articles 7 and 9 to 14' when defining the user counting methodology. Art10P1 (MSPs/MSSPs) is directly referenced as one of the articles for which the user count calculation applies.",
      "relation": "references",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para3",
      "source_type": "article_paragraph",
      "target": "article-Art10-UN1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para3__article-Art10-UN1__references"
    },
    {
      "confidence": "high",
      "reasoning": "Art3P3 explicitly states 'for the purpose of Articles 7 and 9 to 14' when defining the user counting methodology. Art11P1 (online marketplaces) is directly referenced as one of the articles for which the user count calculation applies.",
      "relation": "references",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para3",
      "source_type": "article_paragraph",
      "target": "article-Art11-UN1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para3__article-Art11-UN1__references"
    },
    {
      "confidence": "high",
      "reasoning": "Art3P3 explicitly states 'for the purpose of Articles 7 and 9 to 14' when defining the user counting methodology. Art12P1 (online search engines) is directly referenced as one of the articles for which the user count calculation applies.",
      "relation": "references",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para3",
      "source_type": "article_paragraph",
      "target": "article-Art12-UN1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para3__article-Art12-UN1__references"
    },
    {
      "confidence": "high",
      "reasoning": "Art3P3 explicitly states 'for the purpose of Articles 7 and 9 to 14' when defining the user counting methodology. Art13P1 (social networking) is directly referenced as one of the articles for which the user count calculation applies.",
      "relation": "references",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para3",
      "source_type": "article_paragraph",
      "target": "article-Art13-UN1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para3__article-Art13-UN1__references"
    },
    {
      "confidence": "high",
      "reasoning": "Art3P3 explicitly states 'for the purpose of Articles 7 and 9 to 14' when defining the user counting methodology. Art14P1 (trust service providers) is directly referenced as one of the articles for which the user count calculation applies.",
      "relation": "references",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para3",
      "source_type": "article_paragraph",
      "target": "article-Art14-UN1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para3__article-Art14-UN1__references"
    },
    {
      "confidence": "high",
      "reasoning": "Art2P2 requires entities to 'ensure a level of security appropriate to the risks' \u2014 this general risk-proportionality requirement depends on the specific technical and methodological measures enumerated in Art2P1. The appropriate security level is achieved by implementing the measures listed in P1.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art2-Para2",
      "source_type": "article_paragraph",
      "target": "article-Art2-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art2-Para2__article-Art2-Para1__depends_on__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art3P2 (scheduled interruptions of service and planned maintenance) qualifies Art3P1 (general significant incident criteria) by excluding planned/scheduled events from the significant incident definition \u2014 it narrows the scope of what counts as a significant incident.",
      "relation": "qualifies",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para2",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para2__article-Art3-Para1__qualifies"
    },
    {
      "confidence": "high",
      "reasoning": "Art3P3 (methodology for counting users impacted by an incident) qualifies Art3P1 (significant incident criteria) by specifying how the user-impact threshold should be calculated \u2014 it refines the measurement methodology for applying the criteria in P1.",
      "relation": "qualifies",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para3",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para3__article-Art3-Para1__qualifies"
    },
    {
      "confidence": "high",
      "reasoning": "Art4 (recurring incidents that individually are not significant but collectively may be) qualifies Art3P1 (significant incident criteria) by adding a special case where individually non-significant incidents can become significant through recurrence \u2014 it extends and qualifies the individual-incident-based criteria in P1.",
      "relation": "qualifies",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art4-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art4-UN1__article-Art3-Para1__qualifies__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art5 (significant incidents for DNS service providers) depends on Art3P1 (general significant incident criteria) \u2014 the DNS-specific criteria in Art5 build upon and apply the general framework established in Art3P1 to the DNS service provider entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art5-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art5-UN1__article-Art3-Para1__depends_on__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art6 (significant incidents for TLD name registries) depends on Art3P1 (general significant incident criteria) \u2014 the TLD-specific criteria in Art6 build upon and apply the general framework established in Art3P1 to the TLD name registry entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art6-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art6-UN1__article-Art3-Para1__depends_on__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art7 (significant incidents for cloud computing service providers) depends on Art3P1 (general significant incident criteria) \u2014 the cloud-specific criteria in Art7 build upon and apply the general framework established in Art3P1 to the cloud computing service provider entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art7-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art7-UN1__article-Art3-Para1__depends_on__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art8 (significant incidents for data centre service providers) depends on Art3P1 (general significant incident criteria) \u2014 the data-centre-specific criteria in Art8 build upon and apply the general framework established in Art3P1 to the data centre service provider entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art8-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art8-UN1__article-Art3-Para1__depends_on__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art9 (significant incidents for content delivery network providers) depends on Art3P1 (general significant incident criteria) \u2014 the CDN-specific criteria in Art9 build upon and apply the general framework established in Art3P1 to the CDN provider entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art9-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art9-UN1__article-Art3-Para1__depends_on__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art10 (significant incidents for managed service providers and managed security service providers) depends on Art3P1 (general significant incident criteria) \u2014 the MSP-specific criteria in Art10 build upon and apply the general framework established in Art3P1 to the MSP entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art10-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art10-UN1__article-Art3-Para1__depends_on__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art11 (significant incidents for providers of online marketplaces) depends on Art3P1 (general significant incident criteria) \u2014 the online-marketplace-specific criteria in Art11 build upon and apply the general framework established in Art3P1 to the online marketplace provider entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art11-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art11-UN1__article-Art3-Para1__depends_on__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art12 (significant incidents for providers of online search engines) depends on Art3P1 (general significant incident criteria) \u2014 the search-engine-specific criteria in Art12 build upon and apply the general framework established in Art3P1 to the online search engine provider entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art12-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art12-UN1__article-Art3-Para1__depends_on__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art13 (significant incidents for providers of social networking services platforms) depends on Art3P1 (general significant incident criteria) \u2014 the social-network-specific criteria in Art13 build upon and apply the general framework established in Art3P1 to the social networking service provider entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art13-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art13-UN1__article-Art3-Para1__depends_on__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art14 (significant incidents for trust service providers) depends on Art3P1 (general significant incident criteria) \u2014 the trust-service-specific criteria in Art14 build upon and apply the general framework established in Art3P1 to the trust service provider entity type.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art14-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art14-UN1__article-Art3-Para1__depends_on__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art3-2 (scheduled interruptions and planned maintenance) excludes certain service disruptions from being considered significant incidents under Art3-1's general criteria.",
      "relation": "excludes",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para2",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para2__article-Art3-Para1__excludes__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art3-3 (user counting methodology) qualifies Art3-1 by specifying how to calculate the number of users impacted, which is one of the significance criteria in Art3-1.",
      "relation": "qualifies",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para3",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para3__article-Art3-Para1__qualifies__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art4-1 (recurring incidents) explicitly depends on Art3-1's definition of significant incident: 'Incidents that individually are not considered a significant incident within the meaning of Article 3' are assessed collectively.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art4-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art4-UN1__article-Art3-Para1__depends_on"
    },
    {
      "confidence": "high",
      "reasoning": "Art5-1 (DNS service providers) defines significance criteria by referencing Art3's general framework: 'an incident shall be considered significant under Article 3.'",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art5-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art5-UN1__article-Art3-Para1__depends_on__3"
    },
    {
      "confidence": "high",
      "reasoning": "Art6-1 (TLD name registries) defines significance criteria by referencing Art3's general framework: 'an incident shall be considered significant under Article 3.'",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art6-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art6-UN1__article-Art3-Para1__depends_on__3"
    },
    {
      "confidence": "high",
      "reasoning": "Art7-1 (cloud computing service providers) defines significance criteria by referencing Art3's general framework.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art7-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art7-UN1__article-Art3-Para1__depends_on__3"
    },
    {
      "confidence": "high",
      "reasoning": "Art8-1 (data centre service providers) defines significance criteria by referencing Art3's general framework.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art8-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art8-UN1__article-Art3-Para1__depends_on__3"
    },
    {
      "confidence": "high",
      "reasoning": "Art9-1 (CDN providers) defines significance criteria by referencing Art3's general framework.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art9-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art9-UN1__article-Art3-Para1__depends_on__3"
    },
    {
      "confidence": "high",
      "reasoning": "Art10-1 (MSPs and managed security service providers) defines significance criteria by referencing Art3's general framework.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art10-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art10-UN1__article-Art3-Para1__depends_on__3"
    },
    {
      "confidence": "high",
      "reasoning": "Art11-1 (online marketplace providers) defines significance criteria by referencing Art3's general framework.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art11-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art11-UN1__article-Art3-Para1__depends_on__3"
    },
    {
      "confidence": "high",
      "reasoning": "Art12-1 (online search engine providers) defines significance criteria by referencing Art3's general framework.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art12-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art12-UN1__article-Art3-Para1__depends_on__3"
    },
    {
      "confidence": "high",
      "reasoning": "Art13-1 (social networking service platform providers) defines significance criteria by referencing Art3's general framework.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art13-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art13-UN1__article-Art3-Para1__depends_on__3"
    },
    {
      "confidence": "high",
      "reasoning": "Art14-1 (trust service providers) defines significance criteria by referencing Art3's general framework.",
      "relation": "depends_on",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art14-UN1",
      "source_type": "article_paragraph",
      "target": "article-Art3-Para1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art14-UN1__article-Art3-Para1__depends_on__3"
    },
    {
      "confidence": "high",
      "reasoning": "Art3-3 explicitly references Art7: 'When calculating the number of users impacted by an incident for the purpose of Articles 7 and 9 to 14.'",
      "relation": "references",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para3",
      "source_type": "article_paragraph",
      "target": "article-Art7-UN1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para3__article-Art7-UN1__references__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art3-3 explicitly references Art9 as part of 'Articles 7 and 9 to 14' for user counting methodology.",
      "relation": "references",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para3",
      "source_type": "article_paragraph",
      "target": "article-Art9-UN1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para3__article-Art9-UN1__references__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art3-3 explicitly references Art10 as part of 'Articles 7 and 9 to 14' for user counting methodology.",
      "relation": "references",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para3",
      "source_type": "article_paragraph",
      "target": "article-Art10-UN1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para3__article-Art10-UN1__references__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art3-3 explicitly references Art11 as part of 'Articles 7 and 9 to 14' for user counting methodology.",
      "relation": "references",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para3",
      "source_type": "article_paragraph",
      "target": "article-Art11-UN1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para3__article-Art11-UN1__references__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art3-3 explicitly references Art12 as part of 'Articles 7 and 9 to 14' for user counting methodology.",
      "relation": "references",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para3",
      "source_type": "article_paragraph",
      "target": "article-Art12-UN1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para3__article-Art12-UN1__references__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art3-3 explicitly references Art13 as part of 'Articles 7 and 9 to 14' for user counting methodology.",
      "relation": "references",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para3",
      "source_type": "article_paragraph",
      "target": "article-Art13-UN1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para3__article-Art13-UN1__references__2"
    },
    {
      "confidence": "high",
      "reasoning": "Art3-3 explicitly references Art14 as part of 'Articles 7 and 9 to 14' for user counting methodology.",
      "relation": "references",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "article-Art3-Para3",
      "source_type": "article_paragraph",
      "target": "article-Art14-UN1",
      "target_type": "article_paragraph",
      "edge_id": "article-Art3-Para3__article-Art14-UN1__references__2"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 1.1 is a subdivision of point 1.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point1.1",
      "source_type": "annex_point",
      "target": "annex-Point1",
      "target_type": "annex_point",
      "edge_id": "annex-Point1.1__annex-Point1__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 1.2 is a subdivision of point 1.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point1.2",
      "source_type": "annex_point",
      "target": "annex-Point1",
      "target_type": "annex_point",
      "edge_id": "annex-Point1.2__annex-Point1__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 2.1 is a subdivision of point 2.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point2.1",
      "source_type": "annex_point",
      "target": "annex-Point2",
      "target_type": "annex_point",
      "edge_id": "annex-Point2.1__annex-Point2__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 2.2 is a subdivision of point 2.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point2.2",
      "source_type": "annex_point",
      "target": "annex-Point2",
      "target_type": "annex_point",
      "edge_id": "annex-Point2.2__annex-Point2__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 2.3 is a subdivision of point 2.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point2.3",
      "source_type": "annex_point",
      "target": "annex-Point2",
      "target_type": "annex_point",
      "edge_id": "annex-Point2.3__annex-Point2__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 3.1 is a subdivision of point 3.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point3.1",
      "source_type": "annex_point",
      "target": "annex-Point3",
      "target_type": "annex_point",
      "edge_id": "annex-Point3.1__annex-Point3__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 3.2 is a subdivision of point 3.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point3.2",
      "source_type": "annex_point",
      "target": "annex-Point3",
      "target_type": "annex_point",
      "edge_id": "annex-Point3.2__annex-Point3__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 3.3 is a subdivision of point 3.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point3.3",
      "source_type": "annex_point",
      "target": "annex-Point3",
      "target_type": "annex_point",
      "edge_id": "annex-Point3.3__annex-Point3__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 3.4 is a subdivision of point 3.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point3.4",
      "source_type": "annex_point",
      "target": "annex-Point3",
      "target_type": "annex_point",
      "edge_id": "annex-Point3.4__annex-Point3__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 3.5 is a subdivision of point 3.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point3.5",
      "source_type": "annex_point",
      "target": "annex-Point3",
      "target_type": "annex_point",
      "edge_id": "annex-Point3.5__annex-Point3__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 3.6 is a subdivision of point 3.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point3.6",
      "source_type": "annex_point",
      "target": "annex-Point3",
      "target_type": "annex_point",
      "edge_id": "annex-Point3.6__annex-Point3__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 4.1 is a subdivision of point 4.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point4.1",
      "source_type": "annex_point",
      "target": "annex-Point4",
      "target_type": "annex_point",
      "edge_id": "annex-Point4.1__annex-Point4__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 4.2 is a subdivision of point 4.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point4.2",
      "source_type": "annex_point",
      "target": "annex-Point4",
      "target_type": "annex_point",
      "edge_id": "annex-Point4.2__annex-Point4__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 4.3 is a subdivision of point 4.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point4.3",
      "source_type": "annex_point",
      "target": "annex-Point4",
      "target_type": "annex_point",
      "edge_id": "annex-Point4.3__annex-Point4__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 5.1 is a subdivision of point 5.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point5.1",
      "source_type": "annex_point",
      "target": "annex-Point5",
      "target_type": "annex_point",
      "edge_id": "annex-Point5.1__annex-Point5__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 5.2 is a subdivision of point 5.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point5.2",
      "source_type": "annex_point",
      "target": "annex-Point5",
      "target_type": "annex_point",
      "edge_id": "annex-Point5.2__annex-Point5__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 6.1 is a subdivision of point 6.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point6.1",
      "source_type": "annex_point",
      "target": "annex-Point6",
      "target_type": "annex_point",
      "edge_id": "annex-Point6.1__annex-Point6__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 6.2 is a subdivision of point 6.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point6.2",
      "source_type": "annex_point",
      "target": "annex-Point6",
      "target_type": "annex_point",
      "edge_id": "annex-Point6.2__annex-Point6__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 6.3 is a subdivision of point 6.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point6.3",
      "source_type": "annex_point",
      "target": "annex-Point6",
      "target_type": "annex_point",
      "edge_id": "annex-Point6.3__annex-Point6__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 6.4 is a subdivision of point 6.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point6.4",
      "source_type": "annex_point",
      "target": "annex-Point6",
      "target_type": "annex_point",
      "edge_id": "annex-Point6.4__annex-Point6__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 6.5 is a subdivision of point 6.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point6.5",
      "source_type": "annex_point",
      "target": "annex-Point6",
      "target_type": "annex_point",
      "edge_id": "annex-Point6.5__annex-Point6__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 6.6 is a subdivision of point 6.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point6.6",
      "source_type": "annex_point",
      "target": "annex-Point6",
      "target_type": "annex_point",
      "edge_id": "annex-Point6.6__annex-Point6__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 6.7 is a subdivision of point 6.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point6.7",
      "source_type": "annex_point",
      "target": "annex-Point6",
      "target_type": "annex_point",
      "edge_id": "annex-Point6.7__annex-Point6__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 6.8 is a subdivision of point 6.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point6.8",
      "source_type": "annex_point",
      "target": "annex-Point6",
      "target_type": "annex_point",
      "edge_id": "annex-Point6.8__annex-Point6__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 6.9 is a subdivision of point 6.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point6.9",
      "source_type": "annex_point",
      "target": "annex-Point6",
      "target_type": "annex_point",
      "edge_id": "annex-Point6.9__annex-Point6__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 6.10 is a subdivision of point 6.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point6.10",
      "source_type": "annex_point",
      "target": "annex-Point6",
      "target_type": "annex_point",
      "edge_id": "annex-Point6.10__annex-Point6__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 8.1 is a subdivision of point 8.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point8.1",
      "source_type": "annex_point",
      "target": "annex-Point8",
      "target_type": "annex_point",
      "edge_id": "annex-Point8.1__annex-Point8__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 8.2 is a subdivision of point 8.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point8.2",
      "source_type": "annex_point",
      "target": "annex-Point8",
      "target_type": "annex_point",
      "edge_id": "annex-Point8.2__annex-Point8__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 10.1 is a subdivision of point 10.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point10.1",
      "source_type": "annex_point",
      "target": "annex-Point10",
      "target_type": "annex_point",
      "edge_id": "annex-Point10.1__annex-Point10__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 10.2 is a subdivision of point 10.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point10.2",
      "source_type": "annex_point",
      "target": "annex-Point10",
      "target_type": "annex_point",
      "edge_id": "annex-Point10.2__annex-Point10__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 10.3 is a subdivision of point 10.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point10.3",
      "source_type": "annex_point",
      "target": "annex-Point10",
      "target_type": "annex_point",
      "edge_id": "annex-Point10.3__annex-Point10__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 10.4 is a subdivision of point 10.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point10.4",
      "source_type": "annex_point",
      "target": "annex-Point10",
      "target_type": "annex_point",
      "edge_id": "annex-Point10.4__annex-Point10__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 11.1 is a subdivision of point 11.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point11.1",
      "source_type": "annex_point",
      "target": "annex-Point11",
      "target_type": "annex_point",
      "edge_id": "annex-Point11.1__annex-Point11__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 11.2 is a subdivision of point 11.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point11.2",
      "source_type": "annex_point",
      "target": "annex-Point11",
      "target_type": "annex_point",
      "edge_id": "annex-Point11.2__annex-Point11__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 11.3 is a subdivision of point 11.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point11.3",
      "source_type": "annex_point",
      "target": "annex-Point11",
      "target_type": "annex_point",
      "edge_id": "annex-Point11.3__annex-Point11__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 11.4 is a subdivision of point 11.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point11.4",
      "source_type": "annex_point",
      "target": "annex-Point11",
      "target_type": "annex_point",
      "edge_id": "annex-Point11.4__annex-Point11__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 11.5 is a subdivision of point 11.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point11.5",
      "source_type": "annex_point",
      "target": "annex-Point11",
      "target_type": "annex_point",
      "edge_id": "annex-Point11.5__annex-Point11__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 11.6 is a subdivision of point 11.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point11.6",
      "source_type": "annex_point",
      "target": "annex-Point11",
      "target_type": "annex_point",
      "edge_id": "annex-Point11.6__annex-Point11__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 11.7 is a subdivision of point 11.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point11.7",
      "source_type": "annex_point",
      "target": "annex-Point11",
      "target_type": "annex_point",
      "edge_id": "annex-Point11.7__annex-Point11__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 12.1 is a subdivision of point 12.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point12.1",
      "source_type": "annex_point",
      "target": "annex-Point12",
      "target_type": "annex_point",
      "edge_id": "annex-Point12.1__annex-Point12__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 12.2 is a subdivision of point 12.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point12.2",
      "source_type": "annex_point",
      "target": "annex-Point12",
      "target_type": "annex_point",
      "edge_id": "annex-Point12.2__annex-Point12__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 12.3 is a subdivision of point 12.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point12.3",
      "source_type": "annex_point",
      "target": "annex-Point12",
      "target_type": "annex_point",
      "edge_id": "annex-Point12.3__annex-Point12__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 12.4 is a subdivision of point 12.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point12.4",
      "source_type": "annex_point",
      "target": "annex-Point12",
      "target_type": "annex_point",
      "edge_id": "annex-Point12.4__annex-Point12__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 12.5 is a subdivision of point 12.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point12.5",
      "source_type": "annex_point",
      "target": "annex-Point12",
      "target_type": "annex_point",
      "edge_id": "annex-Point12.5__annex-Point12__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 13.1 is a subdivision of point 13.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point13.1",
      "source_type": "annex_point",
      "target": "annex-Point13",
      "target_type": "annex_point",
      "edge_id": "annex-Point13.1__annex-Point13__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 13.2 is a subdivision of point 13.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point13.2",
      "source_type": "annex_point",
      "target": "annex-Point13",
      "target_type": "annex_point",
      "edge_id": "annex-Point13.2__annex-Point13__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Annex point 13.3 is a subdivision of point 13.",
      "relation": "part_of",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point13.3",
      "source_type": "annex_point",
      "target": "annex-Point13",
      "target_type": "annex_point",
      "edge_id": "annex-Point13.3__annex-Point13__part_of"
    },
    {
      "confidence": "high",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 1 implements Article 21(2), point (a).",
      "relation": "gives_effect_to",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point1",
      "source_type": "annex_point",
      "target": "article-Art2-Para1",
      "target_type": "article_paragraph",
      "edge_id": "annex-Point1__article-Art2-Para1__gives_effect_to"
    },
    {
      "confidence": "high",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 2 implements Article 21(2), point (a).",
      "relation": "gives_effect_to",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point2",
      "source_type": "annex_point",
      "target": "article-Art2-Para1",
      "target_type": "article_paragraph",
      "edge_id": "annex-Point2__article-Art2-Para1__gives_effect_to"
    },
    {
      "confidence": "high",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 3 implements Article 21(2), point (b).",
      "relation": "gives_effect_to",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point3",
      "source_type": "annex_point",
      "target": "article-Art2-Para1",
      "target_type": "article_paragraph",
      "edge_id": "annex-Point3__article-Art2-Para1__gives_effect_to"
    },
    {
      "confidence": "high",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 4 implements Article 21(2), point (c).",
      "relation": "gives_effect_to",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point4",
      "source_type": "annex_point",
      "target": "article-Art2-Para1",
      "target_type": "article_paragraph",
      "edge_id": "annex-Point4__article-Art2-Para1__gives_effect_to"
    },
    {
      "confidence": "high",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 5 implements Article 21(2), point (d).",
      "relation": "gives_effect_to",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point5",
      "source_type": "annex_point",
      "target": "article-Art2-Para1",
      "target_type": "article_paragraph",
      "edge_id": "annex-Point5__article-Art2-Para1__gives_effect_to"
    },
    {
      "confidence": "high",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 6 implements Article 21(2), point (e).",
      "relation": "gives_effect_to",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point6",
      "source_type": "annex_point",
      "target": "article-Art2-Para1",
      "target_type": "article_paragraph",
      "edge_id": "annex-Point6__article-Art2-Para1__gives_effect_to"
    },
    {
      "confidence": "high",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 7 implements Article 21(2), point (f).",
      "relation": "gives_effect_to",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point7",
      "source_type": "annex_point",
      "target": "article-Art2-Para1",
      "target_type": "article_paragraph",
      "edge_id": "annex-Point7__article-Art2-Para1__gives_effect_to"
    },
    {
      "confidence": "high",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 8 implements Article 21(2), point (g).",
      "relation": "gives_effect_to",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point8",
      "source_type": "annex_point",
      "target": "article-Art2-Para1",
      "target_type": "article_paragraph",
      "edge_id": "annex-Point8__article-Art2-Para1__gives_effect_to"
    },
    {
      "confidence": "high",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 9 implements Article 21(2), point (h).",
      "relation": "gives_effect_to",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point9",
      "source_type": "annex_point",
      "target": "article-Art2-Para1",
      "target_type": "article_paragraph",
      "edge_id": "annex-Point9__article-Art2-Para1__gives_effect_to"
    },
    {
      "confidence": "high",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 10 implements Article 21(2), point (i).",
      "relation": "gives_effect_to",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point10",
      "source_type": "annex_point",
      "target": "article-Art2-Para1",
      "target_type": "article_paragraph",
      "edge_id": "annex-Point10__article-Art2-Para1__gives_effect_to"
    },
    {
      "confidence": "high",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 11 implements Article 21(2), point (i and j).",
      "relation": "gives_effect_to",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point11",
      "source_type": "annex_point",
      "target": "article-Art2-Para1",
      "target_type": "article_paragraph",
      "edge_id": "annex-Point11__article-Art2-Para1__gives_effect_to"
    },
    {
      "confidence": "high",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 12 implements Article 21(2), point (i).",
      "relation": "gives_effect_to",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point12",
      "source_type": "annex_point",
      "target": "article-Art2-Para1",
      "target_type": "article_paragraph",
      "edge_id": "annex-Point12__article-Art2-Para1__gives_effect_to"
    },
    {
      "confidence": "high",
      "reasoning": "Art2(1) declares the technical and methodological requirements referred to in Article 21(2), points (a) to (j), of Directive (EU) 2022/2555 to be set out in the Annex. Annex point 13 implements Article 21(2), point (c, e and i).",
      "relation": "gives_effect_to",
      "akn4eu_source_refers_to": null,
      "akn4eu_target_refers_to": null,
      "akn4eu_target_uri": null,
      "akn4eu_ancestry": [],
      "source": "annex-Point13",
      "source_type": "annex_point",
      "target": "article-Art2-Para1",
      "target_type": "article_paragraph",
      "edge_id": "annex-Point13__article-Art2-Para1__gives_effect_to"
    }
  ],
  "case_law": []
}
```
