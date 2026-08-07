---
title: "European Commission DORA ICT Risk Management Delegated Regulation — Recital-to-Article Mapping"
type: regulatorik
date: 2024-03-13
status: final
relevance: "Regulatory technical standards under DORA specifying information and communication technology risk-management tools, methods, processes and policies, including the simplified framework. The artifact enables controls-oriented legal analysis while retaining EUR-Lex as the official authority."
tags: ["eu-law", "financial-regulation", "digital-operational-resilience", "ict-risk-management", "cybersecurity-controls", "operational-resilience", "regulatory-technical-standards", "akn4eu", "legal-knowledge-graph", "compliance-engineering"]
tags_extra: ["dora-rts", "delegated-regulation-eu-2024-1774", "celex-32024r1774", "ict-security-policies", "asset-management", "cryptographic-controls", "network-security", "change-management", "business-continuity", "incident-management", "simplified-risk-framework"]
---

# European Commission DORA ICT Risk Management Delegated Regulation — Recital-to-Article Mapping

*AKN4EU 4.2-aligned, evidence-bounded graph of Commission Delegated Regulation (EU) 2024/1774, preserving the official recitals, article paragraphs, internal legal relations, source provenance and bounded case-law research audit.*

## AKN4EU 4.2 Compliance Summary

| Field | Value |
|---|---|
| AKN4EU root element | act |
| AKN4EU document name | REG_DELEG |
| AKN4EU document type URI | http://publications.europa.eu/resource/authority/resource-type/REG_DELEG |
| FRBRprescriptive | true |
| EEA relevance | true |
| Expression language (FRBRlanguage) | en |
| Authentic language | omitted (not explicitly stated) |
| Hierarchy blocks (title/chapter/section) | 21 |
| Article kinds (regular / definition / amending) | 42 / 0 / 0 |
| Paragraph kinds (numbered / unnumbered / single) | 100 / 0 / 11 |
| Citation blocks (including legal basis) | 2 |
| Cross-Act citation targets with ELI | 1 |

## Relation Counts

| Type | Count |
|---|---:|
| R-to-A outbound | 59 |
| R-to-A inbound | 59 |
| R-to-R | 17 |
| A-to-A | 132 |
| Case-law-to-block | 0 |
| **Total canonical semantic edges** | **208** |

## Consistency Check

| Metric | Value |
|---|---:|
| Run | yes |
| Method | canonical edge list; symmetry structural |
| Orphan outbound | 0 |
| Orphan inbound | 0 |
| Status | pass |

## Source Attribution and Reuse Notice

- **src-lexapi-case-law-research-32024r1774** — affected: `case_law_research:case-law-research-32024r1774`; provider: [LexAPI](https://lex-api.com/); method/date: `lex_search + lex_cited_by` / `2026-08-05T21:21:51Z`; original source: [EUR-Lex — CELEX 32024R1774](http://data.europa.eu/eli/reg_del/2024/1774/oj); LexAPI supplied bounded query and citation-count metadata for CELEX 32024R1774; the target act is identified through EUR-Lex, © European Union. No judgment content or case identity was retained. LexAPI was used for bounded discovery metadata only. This artifact does not relicense LexAPI parsing, structuring, enrichment, citation-graph data, semantic scores or raw API responses; official EUR-Lex material remains subject to its own reuse terms.
- **src-oldp-case-law-research-32024r1774** — affected: `case_law_research:case-law-research-32024r1774`; provider: [Open Legal Data](https://de.openlegaldata.io/); method/date: `Open Legal Data paginated case search (two query formulations, page 1 each)` / `2026-08-05T21:21:51Z`; original source: [Open Legal Data search index; no decision retained — query_set oldp-32024r1774](https://de.openlegaldata.io/api/cases/search/); Search-result count metadata only; no German decision text or case record was retained in the artifact. Open Legal Data database metadata is attributed under the Open Database License (ODbL) v1.0. No decision text was copied or relicensed, and no official court source was required because no case item was retained.

The repository licence covers only original selection, structure and analysis. It does not relicense third-party source material or provider-specific enrichment.

## Intentional Absences

- **article_to_article: 39** reviewed source/family pairs without a high-confidence edge. Examples: `article-Art1-Para1`, `article-Art10-Para1`, `article-Art10-Para3`, `article-Art11-Para1`, `article-Art12-Para1`, `article-Art14-Para1`, `article-Art15-Para1`, `article-Art16-Para1` ...
- **recital_to_article: 3** reviewed source/family pairs without a high-confidence edge. Examples: `recital-27`, `recital-28`, `recital-29`
- **recital_to_recital: 15** reviewed source/family pairs without a high-confidence edge. Examples: `recital-1`, `recital-10`, `recital-11`, `recital-13`, `recital-14`, `recital-15`, `recital-16`, `recital-18` ...

## Mapping (JSON)
```json
{
  "recitals_and_articles": [
    {
      "id": "recital-1",
      "type": "recital",
      "recital_number": 1,
      "paragraphs": [
        "Regulation (EU) 2022/2554 covers a wide variety of financial entities that differ in size, structure, internal organisation, and in the nature and complexity of their activities, and thus have increased or reduced elements of complexity or risks. To ensure that that variety is duly taken into account, any requirements as regards ICT security policies, procedures, protocols and tools, and as regards a simplified ICT risk management framework, should be proportionate to that size, structure, internal organisation, nature and complexity of those financial entities, and to the corresponding risks."
      ],
      "text": "Regulation (EU) 2022/2554 covers a wide variety of financial entities that differ in size, structure, internal organisation, and in the nature and complexity of their activities, and thus have increased or reduced elements of complexity or risks. To ensure that that variety is duly taken into account, any requirements as regards ICT security policies, procedures, protocols and tools, and as regards a simplified ICT risk management framework, should be proportionate to that size, structure, internal organisation, nature and complexity of those financial entities, and to the corresponding risks.",
      "outbound_relations": [
        {
          "edge_id": "recital-1__article-Art1-Para1__provides_guidance_for",
          "source": "recital-1",
          "target": "article-Art1-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-1 explains the proportionality rationale for article-Art1-Para1 by tying ICT requirements to entity size, structure, complexity and corresponding ICT risk.",
          "source_canonical_ref": "celex:32024R1774/recital-1",
          "target_canonical_ref": "celex:32024R1774/article-Art1-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-2__recital-1__builds_on",
          "source": "recital-2",
          "target": "recital-1",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-2 expressly proceeds 'for the same reason' from recital-1's proportionality rationale and develops that rationale into flexibility and documentation reuse.",
          "source_canonical_ref": "celex:32024R1774/recital-2",
          "target_canonical_ref": "celex:32024R1774/recital-1"
        }
      ],
      "canonical_ref": "celex:32024R1774/recital-1",
      "text_sha256": "60bdf836fae2b01089bd3480647414a17e76ac59a678d5a75de7da83c94d64e6"
    },
    {
      "id": "recital-2",
      "type": "recital",
      "recital_number": 2,
      "paragraphs": [
        "For the same reason, financial entities subject to Regulation (EU) 2022/2554 should have a certain flexibility in the way they comply with any requirements as regards ICT security policies, procedures, protocols and tools, and as regards any simplified ICT risk management framework. For that reason, financial entities should be allowed to use any documentation they have already to comply with any documentation requirements that flow from those requirements. It follows that the development, documentation, and implementation of specific ICT security policies should be required only for certain essential elements, taking into account, inter alia, leading industry practices and standards. Furthermore, to cover specific technical implementation aspects, it is necessary to develop, document and implement ICT security procedures to cover specific technical implementation aspects, including capacity and performance management, vulnerability and patch management, data and system security, and logging."
      ],
      "text": "For the same reason, financial entities subject to Regulation (EU) 2022/2554 should have a certain flexibility in the way they comply with any requirements as regards ICT security policies, procedures, protocols and tools, and as regards any simplified ICT risk management framework. For that reason, financial entities should be allowed to use any documentation they have already to comply with any documentation requirements that flow from those requirements. It follows that the development, documentation, and implementation of specific ICT security policies should be required only for certain essential elements, taking into account, inter alia, leading industry practices and standards. Furthermore, to cover specific technical implementation aspects, it is necessary to develop, document and implement ICT security procedures to cover specific technical implementation aspects, including capacity and performance management, vulnerability and patch management, data and system security, and logging.",
      "outbound_relations": [
        {
          "edge_id": "recital-2__article-Art10-Para1__provides_guidance_for",
          "source": "recital-2",
          "target": "article-Art10-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-2 expressly lists vulnerability management among the technical implementation procedures that article-Art10-Para1 requires financial entities to establish.",
          "source_canonical_ref": "celex:32024R1774/recital-2",
          "target_canonical_ref": "celex:32024R1774/article-Art10-Para1"
        },
        {
          "edge_id": "recital-2__article-Art10-Para3__provides_guidance_for",
          "source": "recital-2",
          "target": "article-Art10-Para3",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-2 separately names patch management as a necessary technical procedure, directly explaining the obligation in article-Art10-Para3.",
          "source_canonical_ref": "celex:32024R1774/recital-2",
          "target_canonical_ref": "celex:32024R1774/article-Art10-Para3"
        },
        {
          "edge_id": "recital-2__article-Art11-Para1__provides_guidance_for",
          "source": "recital-2",
          "target": "article-Art11-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-2 identifies data and system security as a technical implementation area, which is the precise procedure created by article-Art11-Para1.",
          "source_canonical_ref": "celex:32024R1774/recital-2",
          "target_canonical_ref": "celex:32024R1774/article-Art11-Para1"
        },
        {
          "edge_id": "recital-2__article-Art12-Para1__provides_guidance_for",
          "source": "recital-2",
          "target": "article-Art12-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-2 expressly includes logging among necessary technical procedures, supplying the policy rationale for article-Art12-Para1's logging obligation.",
          "source_canonical_ref": "celex:32024R1774/recital-2",
          "target_canonical_ref": "celex:32024R1774/article-Art12-Para1"
        },
        {
          "edge_id": "recital-2__article-Art2-Para2__provides_guidance_for",
          "source": "recital-2",
          "target": "article-Art2-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-2 guides application of article-Art2-Para2 by allowing existing documentation to satisfy documentation duties and by explaining why only essential policy elements require dedicated documentation.",
          "source_canonical_ref": "celex:32024R1774/recital-2",
          "target_canonical_ref": "celex:32024R1774/article-Art2-Para2"
        },
        {
          "edge_id": "recital-2__article-Art9-Para1__provides_guidance_for",
          "source": "recital-2",
          "target": "article-Art9-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-2 expressly identifies capacity and performance management as a technical procedure domain, providing the rationale for the procedure mandated by article-Art9-Para1.",
          "source_canonical_ref": "celex:32024R1774/recital-2",
          "target_canonical_ref": "celex:32024R1774/article-Art9-Para1"
        },
        {
          "edge_id": "recital-2__recital-1__builds_on",
          "source": "recital-2",
          "target": "recital-1",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-2 expressly proceeds 'for the same reason' from recital-1's proportionality rationale and develops that rationale into flexibility and documentation reuse.",
          "source_canonical_ref": "celex:32024R1774/recital-2",
          "target_canonical_ref": "celex:32024R1774/recital-1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-26__recital-2__builds_on",
          "source": "recital-26",
          "target": "recital-2",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-26 builds_on recital-2 by turning recital-2’s flexibility and essential-policy premise into the simplified-framework rule that entities maintain one high-level information security policy proportionate to scale and risk.",
          "source_canonical_ref": "celex:32024R1774/recital-26",
          "target_canonical_ref": "celex:32024R1774/recital-2"
        },
        {
          "edge_id": "recital-6__recital-2__builds_on",
          "source": "recital-6",
          "target": "recital-2",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-6 builds on recital-2's leading-practice and standards principle by explaining its continuing importance in an evolving ICT-risk landscape.",
          "source_canonical_ref": "celex:32024R1774/recital-6",
          "target_canonical_ref": "celex:32024R1774/recital-2"
        },
        {
          "edge_id": "recital-7__recital-2__builds_on",
          "source": "recital-7",
          "target": "recital-2",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-7 builds on recital-2's identification of technical procedure domains by explaining the operational purposes of asset, capacity and ICT-operations controls.",
          "source_canonical_ref": "celex:32024R1774/recital-7",
          "target_canonical_ref": "celex:32024R1774/recital-2"
        }
      ],
      "canonical_ref": "celex:32024R1774/recital-2",
      "text_sha256": "71cf4ad9ff5e68f4e5cb6733380944be64de7b36ac01fec290d29269ab7a2e0a"
    },
    {
      "id": "recital-3",
      "type": "recital",
      "recital_number": 3,
      "paragraphs": [
        "To ensure the correct implementation over time of ICT security policies, procedures, protocols, and tools referred to in Title II, Chapter I of this Regulation, it is important that financial entities correctly assign and maintain any roles and responsibilities relating to ICT security, and that they lay down the consequences of non-compliance with ICT security policies or procedures."
      ],
      "text": "To ensure the correct implementation over time of ICT security policies, procedures, protocols, and tools referred to in Title II, Chapter I of this Regulation, it is important that financial entities correctly assign and maintain any roles and responsibilities relating to ICT security, and that they lay down the consequences of non-compliance with ICT security policies or procedures.",
      "outbound_relations": [
        {
          "edge_id": "recital-3__article-Art2-Para2__provides_guidance_for",
          "source": "recital-3",
          "target": "article-Art2-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-3 explains why article-Art2-Para2 requires maintained ICT-security roles and responsibilities and consequences for staff non-compliance.",
          "source_canonical_ref": "celex:32024R1774/recital-3",
          "target_canonical_ref": "celex:32024R1774/article-Art2-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-4__recital-3__qualifies",
          "source": "recital-4",
          "target": "recital-3",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "recital-4 qualifies recital-3's general assignment of ICT roles by requiring segregation of duties where needed to avoid conflicts of interest.",
          "source_canonical_ref": "celex:32024R1774/recital-4",
          "target_canonical_ref": "celex:32024R1774/recital-3"
        },
        {
          "edge_id": "recital-5__recital-3__qualifies",
          "source": "recital-5",
          "target": "recital-3",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "recital-5 qualifies recital-3's requirement for non-compliance consequences by creating an exception when another policy or procedure already states them.",
          "source_canonical_ref": "celex:32024R1774/recital-5",
          "target_canonical_ref": "celex:32024R1774/recital-3"
        }
      ],
      "canonical_ref": "celex:32024R1774/recital-3",
      "text_sha256": "4ff432740e2386237e0dad58aaef5eba42e57a9120fd30c1462ca3644b4c0eed"
    },
    {
      "id": "recital-4",
      "type": "recital",
      "recital_number": 4,
      "paragraphs": [
        "To limit the risk of conflicts of interests, financial entities should ensure the segregation of duties when assigning ICT roles and responsibilities."
      ],
      "text": "To limit the risk of conflicts of interests, financial entities should ensure the segregation of duties when assigning ICT roles and responsibilities.",
      "outbound_relations": [
        {
          "edge_id": "recital-4__article-Art2-Para2__provides_guidance_for",
          "source": "recital-4",
          "target": "article-Art2-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-4 supplies the conflict-of-interest rationale for the segregation-of-duties arrangements mandated in article-Art2-Para2.",
          "source_canonical_ref": "celex:32024R1774/recital-4",
          "target_canonical_ref": "celex:32024R1774/article-Art2-Para2"
        },
        {
          "edge_id": "recital-4__recital-3__qualifies",
          "source": "recital-4",
          "target": "recital-3",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "recital-4 qualifies recital-3's general assignment of ICT roles by requiring segregation of duties where needed to avoid conflicts of interest.",
          "source_canonical_ref": "celex:32024R1774/recital-4",
          "target_canonical_ref": "celex:32024R1774/recital-3"
        }
      ],
      "inbound_relations": [],
      "canonical_ref": "celex:32024R1774/recital-4",
      "text_sha256": "c47710e80fb437074f5b38f555f403f9dc72fff2a36133d9c377a76156266968"
    },
    {
      "id": "recital-5",
      "type": "recital",
      "recital_number": 5,
      "paragraphs": [
        "To ensure flexibility and to simplify the financial entities’ control framework, financial entities should not be required to develop specific provisions on the consequences of non-compliance with ICT security policies, procedures and protocols referred to in Title II, Chapter I of this Regulation where such provisions are already set out in another policy or procedure."
      ],
      "text": "To ensure flexibility and to simplify the financial entities’ control framework, financial entities should not be required to develop specific provisions on the consequences of non-compliance with ICT security policies, procedures and protocols referred to in Title II, Chapter I of this Regulation where such provisions are already set out in another policy or procedure.",
      "outbound_relations": [
        {
          "edge_id": "recital-5__article-Art2-Para2__restricts",
          "source": "recital-5",
          "target": "article-Art2-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "restricts",
          "confidence": "high",
          "reasoning": "recital-5 limits article-Art2-Para2's non-compliance provision by confirming that a dedicated provision is unnecessary when another policy or procedure already contains it.",
          "source_canonical_ref": "celex:32024R1774/recital-5",
          "target_canonical_ref": "celex:32024R1774/article-Art2-Para2"
        },
        {
          "edge_id": "recital-5__recital-3__qualifies",
          "source": "recital-5",
          "target": "recital-3",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "recital-5 qualifies recital-3's requirement for non-compliance consequences by creating an exception when another policy or procedure already states them.",
          "source_canonical_ref": "celex:32024R1774/recital-5",
          "target_canonical_ref": "celex:32024R1774/recital-3"
        }
      ],
      "inbound_relations": [],
      "canonical_ref": "celex:32024R1774/recital-5",
      "text_sha256": "41aeaf3ebfa3b017262f0b00171ea7a2f0c7b072440e28c86f4ec1103abe0909"
    },
    {
      "id": "recital-6",
      "type": "recital",
      "recital_number": 6,
      "paragraphs": [
        "In a dynamic environment where ICT risks constantly evolve, it is important that financial entities develop their set of ICT security policies on the basis of leading practices, and where applicable, of standards as defined in Article 2, point (1), of Regulation (EU) No 1025/2012 of the European Parliament and of the Council ( 2 ) .This should enable financial entities referred to in Title II of this Regulation to remain informed and prepared in a changing landscape."
      ],
      "text": "In a dynamic environment where ICT risks constantly evolve, it is important that financial entities develop their set of ICT security policies on the basis of leading practices, and where applicable, of standards as defined in Article 2, point (1), of Regulation (EU) No 1025/2012 of the European Parliament and of the Council ( 2 ) .This should enable financial entities referred to in Title II of this Regulation to remain informed and prepared in a changing landscape.",
      "outbound_relations": [
        {
          "edge_id": "recital-6__article-Art2-Para2__provides_guidance_for",
          "source": "recital-6",
          "target": "article-Art2-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-6 explains that evolving ICT risk requires leading practices and applicable standards, guiding the corresponding standards and material-change criteria in article-Art2-Para2.",
          "source_canonical_ref": "celex:32024R1774/recital-6",
          "target_canonical_ref": "celex:32024R1774/article-Art2-Para2"
        },
        {
          "edge_id": "recital-6__recital-2__builds_on",
          "source": "recital-6",
          "target": "recital-2",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-6 builds on recital-2's leading-practice and standards principle by explaining its continuing importance in an evolving ICT-risk landscape.",
          "source_canonical_ref": "celex:32024R1774/recital-6",
          "target_canonical_ref": "celex:32024R1774/recital-2"
        }
      ],
      "inbound_relations": [],
      "canonical_ref": "celex:32024R1774/recital-6",
      "text_sha256": "3abbb297f6dd4ca669830e5d21bca27efaca555193987fa17c87dbcad25317c9"
    },
    {
      "id": "recital-7",
      "type": "recital",
      "recital_number": 7,
      "paragraphs": [
        "To ensure their digital operational resilience, financial entities referred to in Title II of this Regulation should, as part of their ICT security policies, procedures, protocols, and tools, develop and implement an ICT asset management policy, capacity and performance management procedures, and policies and procedures for ICT operations. Those policies and procedures are necessary to ensure the monitoring of the status of ICT assets throughout their lifecycles, so that those assets are used and maintained effectively (ICT asset management). Those policies and procedures should also ensure the optimisation of ICT systems’ operation and that the ICT systems’ and capacity’s performance meets the established business and information security objectives (capacity and performance management). Lastly, those policies and procedures should ensure the effective and smooth day-to-day management and operation of ICT systems (ICT operations), thereby minimising the risk of loss of confidentiality, integrity, and availability of data. Those policies and procedures are thus necessary to ensure the security of networks, to provide for adequate safeguards against intrusions and data misuse, and to preserve the availability, authenticity, integrity, and confidentiality of data."
      ],
      "text": "To ensure their digital operational resilience, financial entities referred to in Title II of this Regulation should, as part of their ICT security policies, procedures, protocols, and tools, develop and implement an ICT asset management policy, capacity and performance management procedures, and policies and procedures for ICT operations. Those policies and procedures are necessary to ensure the monitoring of the status of ICT assets throughout their lifecycles, so that those assets are used and maintained effectively (ICT asset management). Those policies and procedures should also ensure the optimisation of ICT systems’ operation and that the ICT systems’ and capacity’s performance meets the established business and information security objectives (capacity and performance management). Lastly, those policies and procedures should ensure the effective and smooth day-to-day management and operation of ICT systems (ICT operations), thereby minimising the risk of loss of confidentiality, integrity, and availability of data. Those policies and procedures are thus necessary to ensure the security of networks, to provide for adequate safeguards against intrusions and data misuse, and to preserve the availability, authenticity, integrity, and confidentiality of data.",
      "outbound_relations": [
        {
          "edge_id": "recital-7__article-Art2-Para1__provides_guidance_for",
          "source": "recital-7",
          "target": "article-Art2-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-7 links operational, asset and capacity controls to network security, intrusion safeguards and data protection, explaining the common outcomes required by article-Art2-Para1.",
          "source_canonical_ref": "celex:32024R1774/recital-7",
          "target_canonical_ref": "celex:32024R1774/article-Art2-Para1"
        },
        {
          "edge_id": "recital-7__article-Art4-Para1__provides_guidance_for",
          "source": "recital-7",
          "target": "article-Art4-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-7 expressly identifies development and implementation of an ICT asset-management policy as necessary for digital operational resilience, explaining the obligation in article-Art4-Para1.",
          "source_canonical_ref": "celex:32024R1774/recital-7",
          "target_canonical_ref": "celex:32024R1774/article-Art4-Para1"
        },
        {
          "edge_id": "recital-7__article-Art4-Para2__provides_guidance_for",
          "source": "recital-7",
          "target": "article-Art4-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-7 explains lifecycle monitoring as the purpose of ICT asset management, directly guiding the lifecycle-management content of article-Art4-Para2.",
          "source_canonical_ref": "celex:32024R1774/recital-7",
          "target_canonical_ref": "celex:32024R1774/article-Art4-Para2"
        },
        {
          "edge_id": "recital-7__article-Art8-Para1__provides_guidance_for",
          "source": "recital-7",
          "target": "article-Art8-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-7 describes effective and smooth day-to-day ICT operation as the objective of the operational policies and procedures required by article-Art8-Para1.",
          "source_canonical_ref": "celex:32024R1774/recital-7",
          "target_canonical_ref": "celex:32024R1774/article-Art8-Para1"
        },
        {
          "edge_id": "recital-7__article-Art9-Para1__provides_guidance_for",
          "source": "recital-7",
          "target": "article-Art9-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-7 explains that capacity and performance management should optimise ICT operations and meet business and security objectives, guiding article-Art9-Para1.",
          "source_canonical_ref": "celex:32024R1774/recital-7",
          "target_canonical_ref": "celex:32024R1774/article-Art9-Para1"
        },
        {
          "edge_id": "recital-7__recital-2__builds_on",
          "source": "recital-7",
          "target": "recital-2",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-7 builds on recital-2's identification of technical procedure domains by explaining the operational purposes of asset, capacity and ICT-operations controls.",
          "source_canonical_ref": "celex:32024R1774/recital-7",
          "target_canonical_ref": "celex:32024R1774/recital-2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-8__recital-7__builds_on",
          "source": "recital-8",
          "target": "recital-7",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-8 builds on recital-7's lifecycle-based asset-management rationale by addressing the specific legacy-system risk created when third-party support expires.",
          "source_canonical_ref": "celex:32024R1774/recital-8",
          "target_canonical_ref": "celex:32024R1774/recital-7"
        }
      ],
      "canonical_ref": "celex:32024R1774/recital-7",
      "text_sha256": "2fa938d9ccd9049648ba3e51137ed391feb28b6a814961014a1b03fdeea853e6"
    },
    {
      "id": "recital-8",
      "type": "recital",
      "recital_number": 8,
      "paragraphs": [
        "To ensure a proper management of the legacy ICT systems risk, financial entities should record and monitor end-dates of ICT third party support services. Because of the potential impact that a loss of confidentiality, integrity and availability of data may have, financial entities should focus on those ICT assets or systems that are critical for business operation when recording and monitoring those end-dates."
      ],
      "text": "To ensure a proper management of the legacy ICT systems risk, financial entities should record and monitor end-dates of ICT third party support services. Because of the potential impact that a loss of confidentiality, integrity and availability of data may have, financial entities should focus on those ICT assets or systems that are critical for business operation when recording and monitoring those end-dates.",
      "outbound_relations": [
        {
          "edge_id": "recital-8__article-Art4-Para2__provides_guidance_for",
          "source": "recital-8",
          "target": "article-Art4-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-8 explains the legacy-system risk purpose of recording and monitoring support end-dates, directly guiding the support-date records in article-Art4-Para2.",
          "source_canonical_ref": "celex:32024R1774/recital-8",
          "target_canonical_ref": "celex:32024R1774/article-Art4-Para2"
        },
        {
          "edge_id": "recital-8__article-Art5-Para2__provides_guidance_for",
          "source": "recital-8",
          "target": "article-Art5-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-8 prioritises business-critical assets by the impact of confidentiality, integrity and availability loss, guiding the criticality assessment criteria in article-Art5-Para2.",
          "source_canonical_ref": "celex:32024R1774/recital-8",
          "target_canonical_ref": "celex:32024R1774/article-Art5-Para2"
        },
        {
          "edge_id": "recital-8__article-Art8-Para2__provides_guidance_for",
          "source": "recital-8",
          "target": "article-Art8-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-8 identifies support expiry monitoring as a means to manage legacy-system risk, providing application guidance for the legacy-system control required by article-Art8-Para2.",
          "source_canonical_ref": "celex:32024R1774/recital-8",
          "target_canonical_ref": "celex:32024R1774/article-Art8-Para2"
        },
        {
          "edge_id": "recital-8__recital-7__builds_on",
          "source": "recital-8",
          "target": "recital-7",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-8 builds on recital-7's lifecycle-based asset-management rationale by addressing the specific legacy-system risk created when third-party support expires.",
          "source_canonical_ref": "celex:32024R1774/recital-8",
          "target_canonical_ref": "celex:32024R1774/recital-7"
        }
      ],
      "inbound_relations": [],
      "canonical_ref": "celex:32024R1774/recital-8",
      "text_sha256": "93f2380791b5687e32e01a0fbfbe116a84e71ddec492f5a019964e6c9f354705"
    },
    {
      "id": "recital-9",
      "type": "recital",
      "recital_number": 9,
      "paragraphs": [
        "Cryptographic controls can ensure the availability, authenticity, integrity, and confidentiality of data. Financial entities referred to in Title II of this Regulation should therefore identify and implement such controls on the basis of a risk-based approach. To that end, financial entities should encrypt the data concerned at rest, in transit or, where necessary, in use, on the basis of the results of a two-pronged process, namely data classification and a comprehensive ICT risk assessment. Given the complexity of encrypting data in use, financial entities referred to in Title II of this Regulation should encrypt date in use only where that would be appropriate in light of the results of the ICT risk assessment. Financial entities referred to in Title II of this Regulation should, however, be able, where encryption of data in use is not feasible or is too complex, to protect the confidentiality, integrity, and availability of the data concerned through other ICT security measures. Given the rapid technological developments in the field of cryptographic techniques, financial entities referred to in Title II of this Regulation should remain abreast of relevant developments in cryptanalysis and consider leading practices and standards. Financial entities referred to in Title II of this Regulation should hence follow a flexible approach, based on risk mitigation and monitoring, to deal with the dynamic landscape of cryptographic threats, including threats from quantum advancements."
      ],
      "text": "Cryptographic controls can ensure the availability, authenticity, integrity, and confidentiality of data. Financial entities referred to in Title II of this Regulation should therefore identify and implement such controls on the basis of a risk-based approach. To that end, financial entities should encrypt the data concerned at rest, in transit or, where necessary, in use, on the basis of the results of a two-pronged process, namely data classification and a comprehensive ICT risk assessment. Given the complexity of encrypting data in use, financial entities referred to in Title II of this Regulation should encrypt date in use only where that would be appropriate in light of the results of the ICT risk assessment. Financial entities referred to in Title II of this Regulation should, however, be able, where encryption of data in use is not feasible or is too complex, to protect the confidentiality, integrity, and availability of the data concerned through other ICT security measures. Given the rapid technological developments in the field of cryptographic techniques, financial entities referred to in Title II of this Regulation should remain abreast of relevant developments in cryptanalysis and consider leading practices and standards. Financial entities referred to in Title II of this Regulation should hence follow a flexible approach, based on risk mitigation and monitoring, to deal with the dynamic landscape of cryptographic threats, including threats from quantum advancements.",
      "outbound_relations": [
        {
          "edge_id": "recital-9__article-Art6-Para2__concretizes",
          "source": "recital-9",
          "target": "article-Art6-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-9 concretizes article-Art6-Para2 by linking the encryption policy to approved data classification and ICT risk assessment, distinguishing data at rest, in transit and in use, and explaining the equivalent safeguards required when in-use encryption is infeasible.",
          "source_canonical_ref": "celex:32024R1774/recital-9",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para2"
        },
        {
          "edge_id": "recital-9__article-Art6-Para3__provides_guidance_for",
          "source": "recital-9",
          "target": "article-Art6-Para3",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-9 provides guidance for article-Art6-Para3 by explaining why cryptographic techniques must track leading practices and standards and why a flexible combination of risk mitigation and monitoring is needed when the most reliable techniques cannot be used.",
          "source_canonical_ref": "celex:32024R1774/recital-9",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para3"
        },
        {
          "edge_id": "recital-9__article-Art6-Para4__provides_guidance_for",
          "source": "recital-9",
          "target": "article-Art6-Para4",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-9 provides guidance for article-Art6-Para4 by identifying rapid cryptanalysis developments, including quantum-related threats, as the reason to update cryptographic technology or adopt compensating mitigation and monitoring measures.",
          "source_canonical_ref": "celex:32024R1774/recital-9",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para4"
        }
      ],
      "inbound_relations": [],
      "canonical_ref": "celex:32024R1774/recital-9",
      "text_sha256": "68c20ad089da68913f9a1a4b3740d808fd0b395a3cfd5796dd2875e66ff5b709"
    },
    {
      "id": "recital-10",
      "type": "recital",
      "recital_number": 10,
      "paragraphs": [
        "ICT operations security and operational policies, procedures, protocols, and tools are essential to ensure the confidentiality, integrity, and availability of data. One pivotal aspect is the strict separation of ICT production environments from the environments where ICT systems are developed and tested or from other non-production environments. That separation should serve as an important ICT security measure against unintended and unauthorised access to, modifications of, and deletions of data in the production environment, which could result in major disruptions in the business operations of financial entities referred to in Title II of this Regulation. However, considering current ICT system development practices, in exceptional circumstances, financial entities should be allowed to test in production environments, provided that they justify such testing and obtain the required approval."
      ],
      "text": "ICT operations security and operational policies, procedures, protocols, and tools are essential to ensure the confidentiality, integrity, and availability of data. One pivotal aspect is the strict separation of ICT production environments from the environments where ICT systems are developed and tested or from other non-production environments. That separation should serve as an important ICT security measure against unintended and unauthorised access to, modifications of, and deletions of data in the production environment, which could result in major disruptions in the business operations of financial entities referred to in Title II of this Regulation. However, considering current ICT system development practices, in exceptional circumstances, financial entities should be allowed to test in production environments, provided that they justify such testing and obtain the required approval.",
      "outbound_relations": [
        {
          "edge_id": "recital-10__article-Art8-Para2__provides_guidance_for",
          "source": "recital-10",
          "target": "article-Art8-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-10 provides guidance for article-Art8-Para2 by explaining the security purpose of separating production from development, testing and other non-production environments and the exceptional justification and approval required for testing in production.",
          "source_canonical_ref": "celex:32024R1774/recital-10",
          "target_canonical_ref": "celex:32024R1774/article-Art8-Para2"
        }
      ],
      "inbound_relations": [],
      "canonical_ref": "celex:32024R1774/recital-10",
      "text_sha256": "68ade9e8534047b9bd00333da35bc0a888a23832a1dea6fdd7a000a254fab66f"
    },
    {
      "id": "recital-11",
      "type": "recital",
      "recital_number": 11,
      "paragraphs": [
        "The fast-evolving nature of ICT landscapes, ICT vulnerabilities and cyber threats necessitates a proactive and comprehensive approach to identifying, evaluating, and addressing ICT vulnerabilities. Without such an approach, financial entities, their customers, users, or counterparties may be severely exposed to risks, which would put at risk their digital operational resilience, the security of their networks, and the availability, authenticity, integrity, and confidentiality of data that ICT security policies and procedures should protect. Financial entities referred to in Title II of this Regulation should therefore identify and remedy vulnerabilities in their ICT environment, and both the financial entities and their ICT third-party service providers should adhere to a coherent, transparent, and responsible vulnerability management framework. For the same reason, financial entities should monitor ICT vulnerabilities using reliable resources and automated tools, verifying that ICT third-party service providers ensure prompt action on vulnerabilities in provided ICT services."
      ],
      "text": "The fast-evolving nature of ICT landscapes, ICT vulnerabilities and cyber threats necessitates a proactive and comprehensive approach to identifying, evaluating, and addressing ICT vulnerabilities. Without such an approach, financial entities, their customers, users, or counterparties may be severely exposed to risks, which would put at risk their digital operational resilience, the security of their networks, and the availability, authenticity, integrity, and confidentiality of data that ICT security policies and procedures should protect. Financial entities referred to in Title II of this Regulation should therefore identify and remedy vulnerabilities in their ICT environment, and both the financial entities and their ICT third-party service providers should adhere to a coherent, transparent, and responsible vulnerability management framework. For the same reason, financial entities should monitor ICT vulnerabilities using reliable resources and automated tools, verifying that ICT third-party service providers ensure prompt action on vulnerabilities in provided ICT services.",
      "outbound_relations": [
        {
          "edge_id": "recital-11__article-Art10-Para2__concretizes",
          "source": "recital-11",
          "target": "article-Art10-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-11 concretizes article-Art10-Para2 by requiring reliable vulnerability information, automated monitoring, remediation, and verification that ICT third-party service providers promptly investigate and address vulnerabilities in supplied services.",
          "source_canonical_ref": "celex:32024R1774/recital-11",
          "target_canonical_ref": "celex:32024R1774/article-Art10-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-12__recital-11__builds_on",
          "source": "recital-12",
          "target": "recital-11",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-12 builds on recital-11 by presenting controlled patch testing and deployment as the remediation step for the vulnerabilities that recital-11 requires financial entities and their ICT providers to identify and address.",
          "source_canonical_ref": "celex:32024R1774/recital-12",
          "target_canonical_ref": "celex:32024R1774/recital-11"
        }
      ],
      "canonical_ref": "celex:32024R1774/recital-11",
      "text_sha256": "7b1e3467693f7d4aab3ade9f3b656f348b69a556ceb6d04cc01c96548001229a"
    },
    {
      "id": "recital-12",
      "type": "recital",
      "recital_number": 12,
      "paragraphs": [
        "Patch management should be a crucial part of those ICT security policies and procedures that, through testing and deployment in a controlled environment, are to resolve identified vulnerabilities and to prevent disruptions from the installation of patches."
      ],
      "text": "Patch management should be a crucial part of those ICT security policies and procedures that, through testing and deployment in a controlled environment, are to resolve identified vulnerabilities and to prevent disruptions from the installation of patches.",
      "outbound_relations": [
        {
          "edge_id": "recital-12__article-Art10-Para4__provides_guidance_for",
          "source": "recital-12",
          "target": "article-Art10-Para4",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-12 provides guidance for article-Art10-Para4 by explaining that patches should be tested and deployed in a controlled environment so that identified vulnerabilities are remedied without creating operational disruption.",
          "source_canonical_ref": "celex:32024R1774/recital-12",
          "target_canonical_ref": "celex:32024R1774/article-Art10-Para4"
        },
        {
          "edge_id": "recital-12__recital-11__builds_on",
          "source": "recital-12",
          "target": "recital-11",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-12 builds on recital-11 by presenting controlled patch testing and deployment as the remediation step for the vulnerabilities that recital-11 requires financial entities and their ICT providers to identify and address.",
          "source_canonical_ref": "celex:32024R1774/recital-12",
          "target_canonical_ref": "celex:32024R1774/recital-11"
        }
      ],
      "inbound_relations": [],
      "canonical_ref": "celex:32024R1774/recital-12",
      "text_sha256": "027377e13073495c75f265c744f1a55c1eb3eea2df34b390768c950ab81a68fb"
    },
    {
      "id": "recital-13",
      "type": "recital",
      "recital_number": 13,
      "paragraphs": [
        "To ensure timely and transparent communication of potential security threats that could impact the financial entity and its stakeholders, financial entities should establish procedures for the responsible disclosure of ICT vulnerabilities to clients, counterparts, and the public. When establishing those procedures, financial entities should consider factors, including the severity of the vulnerability, the potential impact of such vulnerability on stakeholders, and the readiness of a fix or mitigation measures."
      ],
      "text": "To ensure timely and transparent communication of potential security threats that could impact the financial entity and its stakeholders, financial entities should establish procedures for the responsible disclosure of ICT vulnerabilities to clients, counterparts, and the public. When establishing those procedures, financial entities should consider factors, including the severity of the vulnerability, the potential impact of such vulnerability on stakeholders, and the readiness of a fix or mitigation measures.",
      "outbound_relations": [
        {
          "edge_id": "recital-13__article-Art10-Para2__provides_guidance_for",
          "source": "recital-13",
          "target": "article-Art10-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-13 provides guidance for the responsible-disclosure procedure in article-Art10-Para2 by identifying severity, stakeholder impact, and the readiness of a fix or mitigation as factors for communicating ICT vulnerabilities.",
          "source_canonical_ref": "celex:32024R1774/recital-13",
          "target_canonical_ref": "celex:32024R1774/article-Art10-Para2"
        }
      ],
      "inbound_relations": [],
      "canonical_ref": "celex:32024R1774/recital-13",
      "text_sha256": "be2bcfff3475600150214be86e8f9ec83ea97192a8a45af4ed6c11af09a90e1e"
    },
    {
      "id": "recital-14",
      "type": "recital",
      "recital_number": 14,
      "paragraphs": [
        "To allow for the assignment of user access rights, financial entities referred to in Title II of this Regulation should establish strong measures to ascertain the unique identification of individuals and systems that will access the financial entity’s information. A failure to do so would expose financial entities to potential unauthorised access, data breaches, and fraudulent activities, thus compromising the confidentiality, integrity, and availability of sensitive financial data. While the use of generic or shared accounts should exceptionally be permitted under circumstances specified by financial entities, financial entities should ensure that the accountability for actions taken through those accounts is maintained. Without that safeguard, potential malicious users would be able to hinder investigative and corrective measures, leaving financial entities vulnerable to undetected malicious activities or non-compliance penalties."
      ],
      "text": "To allow for the assignment of user access rights, financial entities referred to in Title II of this Regulation should establish strong measures to ascertain the unique identification of individuals and systems that will access the financial entity’s information. A failure to do so would expose financial entities to potential unauthorised access, data breaches, and fraudulent activities, thus compromising the confidentiality, integrity, and availability of sensitive financial data. While the use of generic or shared accounts should exceptionally be permitted under circumstances specified by financial entities, financial entities should ensure that the accountability for actions taken through those accounts is maintained. Without that safeguard, potential malicious users would be able to hinder investigative and corrective measures, leaving financial entities vulnerable to undetected malicious activities or non-compliance penalties.",
      "outbound_relations": [
        {
          "edge_id": "recital-14__article-Art20-Para1__concretizes",
          "source": "recital-14",
          "target": "article-Art20-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-14 concretizes article-Art20-Para1 by explaining that unique identification must cover both individuals and systems so that user access rights can be assigned without exposing the entity to unauthorised access and untraceable activity.",
          "source_canonical_ref": "celex:32024R1774/recital-14",
          "target_canonical_ref": "celex:32024R1774/article-Art20-Para1"
        },
        {
          "edge_id": "recital-14__article-Art21-Para1__restricts",
          "source": "recital-14",
          "target": "article-Art21-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "restricts",
          "confidence": "high",
          "reasoning": "recital-14 restricts article-Art21-Para1 by clarifying that generic or shared accounts are exceptional and may be used only under specified circumstances while preserving accountability for every action performed through them.",
          "source_canonical_ref": "celex:32024R1774/recital-14",
          "target_canonical_ref": "celex:32024R1774/article-Art21-Para1"
        }
      ],
      "inbound_relations": [],
      "canonical_ref": "celex:32024R1774/recital-14",
      "text_sha256": "f821c5dea1db293af1b0249700ad8c9ef69d6debb9f833518c209d5091039eaf"
    },
    {
      "id": "recital-15",
      "type": "recital",
      "recital_number": 15,
      "paragraphs": [
        "To manage the rapid advancement in ICT environments, financial entities referred to in Title II of this Regulation should implement robust ICT project management policies and procedures to maintain data availability, authenticity, integrity, and confidentiality. Those ICT project management policies and procedures should identify the elements that are necessary to successfully manage ICT projects, including changes to, acquisitions of, the maintenance of, and developments of the financial entity’s ICT systems, regardless of the ICT project management methodology chosen by the financial entity. In the context of those policies and procedures, financial entities should adopt testing practices and methods that suit their needs, while adhering to a risk-based approach and ensuring that a secure, reliable, and resilient ICT environment is maintained. To guarantee the secure implementation of an ICT project, financial entities should ensure that staff from specific business sectors or roles influenced or impacted by that ICT project can provide the necessary information and expertise. To ensure effective oversight, reports on ICT projects, in particular about projects that affect critical or important functions and about their associated risks, should be submitted to the management body. Financial entities should tailor the frequency and details of the systematic and ongoing reviews and reports to the importance and the size of the ICT projects concerned."
      ],
      "text": "To manage the rapid advancement in ICT environments, financial entities referred to in Title II of this Regulation should implement robust ICT project management policies and procedures to maintain data availability, authenticity, integrity, and confidentiality. Those ICT project management policies and procedures should identify the elements that are necessary to successfully manage ICT projects, including changes to, acquisitions of, the maintenance of, and developments of the financial entity’s ICT systems, regardless of the ICT project management methodology chosen by the financial entity. In the context of those policies and procedures, financial entities should adopt testing practices and methods that suit their needs, while adhering to a risk-based approach and ensuring that a secure, reliable, and resilient ICT environment is maintained. To guarantee the secure implementation of an ICT project, financial entities should ensure that staff from specific business sectors or roles influenced or impacted by that ICT project can provide the necessary information and expertise. To ensure effective oversight, reports on ICT projects, in particular about projects that affect critical or important functions and about their associated risks, should be submitted to the management body. Financial entities should tailor the frequency and details of the systematic and ongoing reviews and reports to the importance and the size of the ICT projects concerned.",
      "outbound_relations": [
        {
          "edge_id": "recital-15__article-Art15-Para2__concretizes",
          "source": "recital-15",
          "target": "article-Art15-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-15 concretizes article-Art15-Para2 by identifying acquisition, maintenance, development and change of ICT systems as project-management subject matter regardless of the methodology selected by the financial entity.",
          "source_canonical_ref": "celex:32024R1774/recital-15",
          "target_canonical_ref": "celex:32024R1774/article-Art15-Para2"
        },
        {
          "edge_id": "recital-15__article-Art15-Para3__provides_guidance_for",
          "source": "recital-15",
          "target": "article-Art15-Para3",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-15 provides guidance for article-Art15-Para3 by requiring project testing methods suited to the entity, applied on a risk basis, while preserving a secure, reliable and resilient ICT environment.",
          "source_canonical_ref": "celex:32024R1774/recital-15",
          "target_canonical_ref": "celex:32024R1774/article-Art15-Para3"
        },
        {
          "edge_id": "recital-15__article-Art15-Para4__concretizes",
          "source": "recital-15",
          "target": "article-Art15-Para4",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-15 concretizes article-Art15-Para4 by explaining that staff from business areas or roles affected by an ICT project must supply the information and expertise needed for secure implementation.",
          "source_canonical_ref": "celex:32024R1774/recital-15",
          "target_canonical_ref": "celex:32024R1774/article-Art15-Para4"
        },
        {
          "edge_id": "recital-15__article-Art15-Para5__provides_guidance_for",
          "source": "recital-15",
          "target": "article-Art15-Para5",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-15 provides guidance for article-Art15-Para5 by linking management-body reporting to projects affecting critical or important functions and by tying report frequency and detail to each project’s importance and size.",
          "source_canonical_ref": "celex:32024R1774/recital-15",
          "target_canonical_ref": "celex:32024R1774/article-Art15-Para5"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-17__recital-15__builds_on",
          "source": "recital-17",
          "target": "recital-15",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-17 builds on recital-15 because recital-15 places ICT changes within project management and testing, while recital-17 develops that change strand into dedicated approval-separation, transition, quality, and fall-back controls.",
          "source_canonical_ref": "celex:32024R1774/recital-17",
          "target_canonical_ref": "celex:32024R1774/recital-15"
        }
      ],
      "canonical_ref": "celex:32024R1774/recital-15",
      "text_sha256": "0c7fdb6a6fc4ad9038e1fc751bcdaab65760ce45d71918f38273ba63aa61eae1"
    },
    {
      "id": "recital-16",
      "type": "recital",
      "recital_number": 16,
      "paragraphs": [
        "It is necessary to ensure that software packages that financial entities referred to in Title II of this Regulation acquire and develop are effectively and securely integrated into the existing ICT environment, in accordance with established business and information security objectives. Financial entities should therefore thoroughly evaluate such software packages. For that purpose, and to identify vulnerabilities and potential security gaps within both software packages and the broader ICT systems, financial entities should carry out ICT security testing. To assess the integrity of the software and to ensure that the use of that software does not pose ICT security risks, financial entities should also review source codes of software acquired, including, where feasible, of proprietary software provided by ICT third-party service providers, using both static and dynamic testing methods."
      ],
      "text": "It is necessary to ensure that software packages that financial entities referred to in Title II of this Regulation acquire and develop are effectively and securely integrated into the existing ICT environment, in accordance with established business and information security objectives. Financial entities should therefore thoroughly evaluate such software packages. For that purpose, and to identify vulnerabilities and potential security gaps within both software packages and the broader ICT systems, financial entities should carry out ICT security testing. To assess the integrity of the software and to ensure that the use of that software does not pose ICT security risks, financial entities should also review source codes of software acquired, including, where feasible, of proprietary software provided by ICT third-party service providers, using both static and dynamic testing methods.",
      "outbound_relations": [
        {
          "edge_id": "recital-16__article-Art16-Para3__concretizes",
          "source": "recital-16",
          "target": "article-Art16-Para3",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-16 concretizes article-Art16-Para3 by requiring source-code review through both static and dynamic testing to reveal vulnerabilities and security gaps and to assess software integrity before operational use.",
          "source_canonical_ref": "celex:32024R1774/recital-16",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para3"
        },
        {
          "edge_id": "recital-16__article-Art16-Para4__concretizes",
          "source": "recital-16",
          "target": "article-Art16-Para4",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-16 concretizes article-Art16-Para4 by explaining that acquired or developed software packages must undergo ICT security testing so that they can be integrated securely into the existing ICT environment.",
          "source_canonical_ref": "celex:32024R1774/recital-16",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para4"
        },
        {
          "edge_id": "recital-16__article-Art16-Para8__provides_guidance_for",
          "source": "recital-16",
          "target": "article-Art16-Para8",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-16 provides guidance for article-Art16-Para8 by specifying that review should cover acquired software, including proprietary software and, where feasible, source code supplied by ICT third-party service providers.",
          "source_canonical_ref": "celex:32024R1774/recital-16",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para8"
        }
      ],
      "inbound_relations": [],
      "canonical_ref": "celex:32024R1774/recital-16",
      "text_sha256": "5a71432f8800a0e1684e2841b3f3c44802439ddafc3c0f9b284f20070a34d8c4"
    },
    {
      "id": "recital-17",
      "type": "recital",
      "recital_number": 17,
      "paragraphs": [
        "Changes, regardless of their scale, carry inherent risks and may pose significant risks of loss of confidentiality, integrity, and availability of data, and could thus lead to severe business disruptions. To safeguard financial entities from potential ICT vulnerabilities and weaknesses that could expose them to significant risks, a rigorous verification process is necessary to confirm that all changes meet the necessary ICT security requirements. Financial entities referred to in Title II of this Regulation should therefore, as an essential element of their ICT security policies and procedures, have in place sound ICT change management policies and procedures. To uphold the objectivity and effectiveness of the ICT change management process, to prevent conflicts of interest, and to ensure that ICT changes are evaluated objectively, it is necessary to separate the functions responsible for approving those changes from the functions that request and implement those changes. To achieve effective transitions, controlled ICT change implementation, and minimal disruptions to the operation of the ICT systems, financial entities should assign clear roles and responsibilities that ensure that ICT changes are planned, adequately tested, and that quality is ensured. To ensure that ICT systems continue to operate effectively, and to provide a safety net for financial entities, financial entities should also develop and implement fall-back procedures. Financial entities should clearly identify those fall-back procedures and assign responsibilities to ensure a swift and effective response in the event of unsuccessful ICT changes."
      ],
      "text": "Changes, regardless of their scale, carry inherent risks and may pose significant risks of loss of confidentiality, integrity, and availability of data, and could thus lead to severe business disruptions. To safeguard financial entities from potential ICT vulnerabilities and weaknesses that could expose them to significant risks, a rigorous verification process is necessary to confirm that all changes meet the necessary ICT security requirements. Financial entities referred to in Title II of this Regulation should therefore, as an essential element of their ICT security policies and procedures, have in place sound ICT change management policies and procedures. To uphold the objectivity and effectiveness of the ICT change management process, to prevent conflicts of interest, and to ensure that ICT changes are evaluated objectively, it is necessary to separate the functions responsible for approving those changes from the functions that request and implement those changes. To achieve effective transitions, controlled ICT change implementation, and minimal disruptions to the operation of the ICT systems, financial entities should assign clear roles and responsibilities that ensure that ICT changes are planned, adequately tested, and that quality is ensured. To ensure that ICT systems continue to operate effectively, and to provide a safety net for financial entities, financial entities should also develop and implement fall-back procedures. Financial entities should clearly identify those fall-back procedures and assign responsibilities to ensure a swift and effective response in the event of unsuccessful ICT changes.",
      "outbound_relations": [
        {
          "edge_id": "recital-17__article-Art17-Para1__concretizes",
          "source": "recital-17",
          "target": "article-Art17-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-17 concretizes article-Art17-Para1 by explaining why change-security verification, separation of approval from request and implementation, assigned roles, controlled testing, quality assurance, and fall-back responsibilities are required to contain confidentiality, integrity, availability, and disruption risks.",
          "source_canonical_ref": "celex:32024R1774/recital-17",
          "target_canonical_ref": "celex:32024R1774/article-Art17-Para1"
        },
        {
          "edge_id": "recital-17__recital-15__builds_on",
          "source": "recital-17",
          "target": "recital-15",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-17 builds on recital-15 because recital-15 places ICT changes within project management and testing, while recital-17 develops that change strand into dedicated approval-separation, transition, quality, and fall-back controls.",
          "source_canonical_ref": "celex:32024R1774/recital-17",
          "target_canonical_ref": "celex:32024R1774/recital-15"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-22__recital-17__builds_on",
          "source": "recital-22",
          "target": "recital-17",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-22 builds on recital-17 by expressly making the ICT change-management process developed in recital-17 an input to the design of the ICT business continuity policy.",
          "source_canonical_ref": "celex:32024R1774/recital-22",
          "target_canonical_ref": "celex:32024R1774/recital-17"
        }
      ],
      "canonical_ref": "celex:32024R1774/recital-17",
      "text_sha256": "bfa3b5bb88f1734731451cfe028479815faffd4d5493b815ac4d7e179778cc4d"
    },
    {
      "id": "recital-18",
      "type": "recital",
      "recital_number": 18,
      "paragraphs": [
        "To detect, manage, and report ICT-related incidents, financial entities referred to in Title II of this Regulation should establish an ICT-related incident policy encompassing the components of an ICT-related incident management process. For that purpose, financial entities should identify all relevant contacts inside and outside the organisation that can facilitate the correct coordination and implementation of the different phases within that process. To optimise the detection of, and response to, ICT-related incidents, and to identify trends among those incidents, which are a valuable source of information enabling financial entities to identify and address root causes and problems in an effective manner, financial entities should in particular analyse in detail the ICT-related incidents that they consider to be most significant, inter alia, because of their regular reoccurrence."
      ],
      "text": "To detect, manage, and report ICT-related incidents, financial entities referred to in Title II of this Regulation should establish an ICT-related incident policy encompassing the components of an ICT-related incident management process. For that purpose, financial entities should identify all relevant contacts inside and outside the organisation that can facilitate the correct coordination and implementation of the different phases within that process. To optimise the detection of, and response to, ICT-related incidents, and to identify trends among those incidents, which are a valuable source of information enabling financial entities to identify and address root causes and problems in an effective manner, financial entities should in particular analyse in detail the ICT-related incidents that they consider to be most significant, inter alia, because of their regular reoccurrence.",
      "outbound_relations": [
        {
          "edge_id": "recital-18__article-Art22-Para1__concretizes",
          "source": "recital-18",
          "target": "article-Art22-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-18 concretizes article-Art22-Para1 by identifying the incident-policy functions implemented there: an end-to-end management process, internal and external coordination contacts, and detailed analysis of significant or recurring incidents and patterns.",
          "source_canonical_ref": "celex:32024R1774/recital-18",
          "target_canonical_ref": "celex:32024R1774/article-Art22-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-19__recital-18__builds_on",
          "source": "recital-19",
          "target": "recital-18",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-19 builds on recital-18 by developing the detection phase of recital-18's incident-management process into concrete internal, log, external, and ICT-provider information sources with assigned responsibilities.",
          "source_canonical_ref": "celex:32024R1774/recital-19",
          "target_canonical_ref": "celex:32024R1774/recital-18"
        },
        {
          "edge_id": "recital-20__recital-18__builds_on",
          "source": "recital-20",
          "target": "recital-18",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-20 builds on recital-18 by adding evidence retention and a calibrated retention period to the incident-policy and incident-management process introduced in recital-18.",
          "source_canonical_ref": "celex:32024R1774/recital-20",
          "target_canonical_ref": "celex:32024R1774/recital-18"
        },
        {
          "edge_id": "recital-21__recital-18__builds_on",
          "source": "recital-21",
          "target": "recital-18",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-21 builds on recital-18 by specifying how trigger criteria are to operate within the detection and response phases of the incident-management process established in recital-18.",
          "source_canonical_ref": "celex:32024R1774/recital-21",
          "target_canonical_ref": "celex:32024R1774/recital-18"
        },
        {
          "edge_id": "recital-22__recital-18__builds_on",
          "source": "recital-22",
          "target": "recital-18",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-22 builds on recital-18 by expressly incorporating ICT-related incident management and its communication dimension into the ICT business continuity policy.",
          "source_canonical_ref": "celex:32024R1774/recital-22",
          "target_canonical_ref": "celex:32024R1774/recital-18"
        }
      ],
      "canonical_ref": "celex:32024R1774/recital-18",
      "text_sha256": "1350d270a2b20dcb417ab3a2550e241556cec06b16840136f754106ef1bb2e09"
    },
    {
      "id": "recital-19",
      "type": "recital",
      "recital_number": 19,
      "paragraphs": [
        "To guarantee an early and effective detection of anomalous activities, financial entities referred to in Title II of this Regulation should collect, monitor, and analyse the different sources of information and should allocate related roles and responsibilities. As regards internal sources of information, logs are an extremely relevant source, but financial entities should not rely on logs alone. Instead, financial entities should consider broader information to include what is reported by other internal functions, as those functions are often a valuable source of relevant information. For the same reason, financial entities should analyse and monitor information gathered from external sources, including information provided by ICT third-party providers on incidents affecting their systems and networks, and other sources of information that financial entities consider relevant. In so far as such information constitutes personal data, the Union data protection law applies. The personal data should be limited to what is necessary for the incident detection."
      ],
      "text": "To guarantee an early and effective detection of anomalous activities, financial entities referred to in Title II of this Regulation should collect, monitor, and analyse the different sources of information and should allocate related roles and responsibilities. As regards internal sources of information, logs are an extremely relevant source, but financial entities should not rely on logs alone. Instead, financial entities should consider broader information to include what is reported by other internal functions, as those functions are often a valuable source of relevant information. For the same reason, financial entities should analyse and monitor information gathered from external sources, including information provided by ICT third-party providers on incidents affecting their systems and networks, and other sources of information that financial entities consider relevant. In so far as such information constitutes personal data, the Union data protection law applies. The personal data should be limited to what is necessary for the incident detection.",
      "outbound_relations": [
        {
          "edge_id": "recital-19__article-Art23-Para1__concretizes",
          "source": "recital-19",
          "target": "article-Art23-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-19 concretizes article-Art23-Para1 by tying that paragraph's clear-role requirement specifically to responsibility for collecting, monitoring, and analysing information used to detect anomalous activities early and effectively.",
          "source_canonical_ref": "celex:32024R1774/recital-19",
          "target_canonical_ref": "celex:32024R1774/article-Art23-Para1"
        },
        {
          "edge_id": "recital-19__article-Art23-Para2__concretizes",
          "source": "recital-19",
          "target": "article-Art23-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-19 concretizes article-Art23-Para2 by explaining that its detection mechanism must combine logs with reports from internal functions, external information, and incident notices from ICT third-party providers rather than relying on logs alone.",
          "source_canonical_ref": "celex:32024R1774/recital-19",
          "target_canonical_ref": "celex:32024R1774/article-Art23-Para2"
        },
        {
          "edge_id": "recital-19__recital-18__builds_on",
          "source": "recital-19",
          "target": "recital-18",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-19 builds on recital-18 by developing the detection phase of recital-18's incident-management process into concrete internal, log, external, and ICT-provider information sources with assigned responsibilities.",
          "source_canonical_ref": "celex:32024R1774/recital-19",
          "target_canonical_ref": "celex:32024R1774/recital-18"
        },
        {
          "edge_id": "recital-19__recital-30__provides_context_for",
          "source": "recital-19",
          "target": "recital-30",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "provides_context_for",
          "confidence": "high",
          "reasoning": "recital-19 provides context for recital-30 because its incident-detection data collection is the concrete setting in which recital-30 reiterates full data-protection application and uses data minimisation for incident detection as its example.",
          "source_canonical_ref": "celex:32024R1774/recital-19",
          "target_canonical_ref": "celex:32024R1774/recital-30"
        }
      ],
      "inbound_relations": [],
      "canonical_ref": "celex:32024R1774/recital-19",
      "text_sha256": "5a53840714ddd1cefdcce252e6819cc06389691fd0b8518e16a5c9e9ca9b4a47"
    },
    {
      "id": "recital-20",
      "type": "recital",
      "recital_number": 20,
      "paragraphs": [
        "To facilitate ICT-related incidents detection, financial entities should retain evidence of those incidents. To ensure, on the one hand, that such evidence is retained sufficiently long and to avoid, on the other hand, an excessive regulatory burden, financial entities should determine the retention period considering, among other things, the criticality of the data and retention requirements stemming from Union law."
      ],
      "text": "To facilitate ICT-related incidents detection, financial entities should retain evidence of those incidents. To ensure, on the one hand, that such evidence is retained sufficiently long and to avoid, on the other hand, an excessive regulatory burden, financial entities should determine the retention period considering, among other things, the criticality of the data and retention requirements stemming from Union law.",
      "outbound_relations": [
        {
          "edge_id": "recital-20__article-Art22-Para1__concretizes",
          "source": "recital-20",
          "target": "article-Art22-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-20 concretizes the evidence-retention duty in article-Art22-Para1 by explaining that its period must balance effective incident detection against regulatory burden while reflecting data criticality and Union-law retention requirements.",
          "source_canonical_ref": "celex:32024R1774/recital-20",
          "target_canonical_ref": "celex:32024R1774/article-Art22-Para1"
        },
        {
          "edge_id": "recital-20__recital-18__builds_on",
          "source": "recital-20",
          "target": "recital-18",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-20 builds on recital-18 by adding evidence retention and a calibrated retention period to the incident-policy and incident-management process introduced in recital-18.",
          "source_canonical_ref": "celex:32024R1774/recital-20",
          "target_canonical_ref": "celex:32024R1774/recital-18"
        }
      ],
      "inbound_relations": [],
      "canonical_ref": "celex:32024R1774/recital-20",
      "text_sha256": "d79ffa3b870a70d97a15b42759ed28b1b6e07142b7114d93a6a4d9ed39ef0416"
    },
    {
      "id": "recital-21",
      "type": "recital",
      "recital_number": 21,
      "paragraphs": [
        "To ensure that ICT-related incidents are detected in time, financial entities referred to in Title II of this Regulation should consider the criteria identified for triggering the detection of and responses to ICT-related incidents as not exhaustive. Moreover, while financial entities should consider each of those criteria, the circumstances described in the criteria should not need to occur simultaneously and the importance of the affected ICT services should be appropriately considered to trigger ICT-related incident detection and response processes."
      ],
      "text": "To ensure that ICT-related incidents are detected in time, financial entities referred to in Title II of this Regulation should consider the criteria identified for triggering the detection of and responses to ICT-related incidents as not exhaustive. Moreover, while financial entities should consider each of those criteria, the circumstances described in the criteria should not need to occur simultaneously and the importance of the affected ICT services should be appropriately considered to trigger ICT-related incident detection and response processes.",
      "outbound_relations": [
        {
          "edge_id": "recital-21__article-Art23-Para5__provides_guidance_for",
          "source": "recital-21",
          "target": "article-Art23-Para5",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-21 provides guidance for article-Art23-Para5 by clarifying that every listed trigger criterion must be considered, but that the list is non-exhaustive and the listed circumstances need not occur simultaneously.",
          "source_canonical_ref": "celex:32024R1774/recital-21",
          "target_canonical_ref": "celex:32024R1774/article-Art23-Para5"
        },
        {
          "edge_id": "recital-21__article-Art23-Para6__provides_guidance_for",
          "source": "recital-21",
          "target": "article-Art23-Para6",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-21 provides guidance for article-Art23-Para6 by explaining that the criticality assessment concerns the importance of the affected ICT services when deciding whether to trigger incident detection and response.",
          "source_canonical_ref": "celex:32024R1774/recital-21",
          "target_canonical_ref": "celex:32024R1774/article-Art23-Para6"
        },
        {
          "edge_id": "recital-21__recital-18__builds_on",
          "source": "recital-21",
          "target": "recital-18",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-21 builds on recital-18 by specifying how trigger criteria are to operate within the detection and response phases of the incident-management process established in recital-18.",
          "source_canonical_ref": "celex:32024R1774/recital-21",
          "target_canonical_ref": "celex:32024R1774/recital-18"
        }
      ],
      "inbound_relations": [],
      "canonical_ref": "celex:32024R1774/recital-21",
      "text_sha256": "6aeb9289bb0deb0e38aa7035bf8ea38e9bb7ef1b1a255c20d516675b0db62c07"
    },
    {
      "id": "recital-22",
      "type": "recital",
      "recital_number": 22,
      "paragraphs": [
        "When developing an ICT business continuity policy, financial entities referred to in Title II of this Regulation should take into account the essential components of ICT risk management, including ICT-related incident management and communication strategies, the ICT change management process, and risks associated with ICT third-party service providers."
      ],
      "text": "When developing an ICT business continuity policy, financial entities referred to in Title II of this Regulation should take into account the essential components of ICT risk management, including ICT-related incident management and communication strategies, the ICT change management process, and risks associated with ICT third-party service providers.",
      "outbound_relations": [
        {
          "edge_id": "recital-22__article-Art24-Para1__provides_guidance_for",
          "source": "recital-22",
          "target": "article-Art24-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-22 provides guidance for article-Art24-Para1 by requiring the ICT business continuity policy assembled under that paragraph to integrate incident management, communication, change management, and ICT third-party-provider risk considerations.",
          "source_canonical_ref": "celex:32024R1774/recital-22",
          "target_canonical_ref": "celex:32024R1774/article-Art24-Para1"
        },
        {
          "edge_id": "recital-22__recital-17__builds_on",
          "source": "recital-22",
          "target": "recital-17",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-22 builds on recital-17 by expressly making the ICT change-management process developed in recital-17 an input to the design of the ICT business continuity policy.",
          "source_canonical_ref": "celex:32024R1774/recital-22",
          "target_canonical_ref": "celex:32024R1774/recital-17"
        },
        {
          "edge_id": "recital-22__recital-18__builds_on",
          "source": "recital-22",
          "target": "recital-18",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-22 builds on recital-18 by expressly incorporating ICT-related incident management and its communication dimension into the ICT business continuity policy.",
          "source_canonical_ref": "celex:32024R1774/recital-22",
          "target_canonical_ref": "celex:32024R1774/recital-18"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-23__recital-22__builds_on",
          "source": "recital-23",
          "target": "recital-22",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-23 builds on recital-22 by moving from the components to be integrated into an ICT business continuity policy to the scenarios used to implement response and recovery plans and test continuity plans.",
          "source_canonical_ref": "celex:32024R1774/recital-23",
          "target_canonical_ref": "celex:32024R1774/recital-22"
        }
      ],
      "canonical_ref": "celex:32024R1774/recital-22",
      "text_sha256": "4e6d78761ceac5f1a6bd7c7671d48308d9f4e0f0e6ed177d51c55121e4eb6d22"
    },
    {
      "id": "recital-23",
      "type": "recital",
      "recital_number": 23,
      "paragraphs": [
        "It is necessary to set out the set of scenarios that financial entities referred to in Title II of this Regulation should take into account both for the implementation of ICT response and recovery plans and for the testing of ICT business continuity plans. Those scenarios should serve as a starting point for financial entities to analyse both the relevance and plausibility of each scenario and the need to develop alternative scenarios. Financial entities should focus on those scenarios in which investment in resilience measures could be more efficient and effective. By testing switchovers between the primary ICT infrastructure and any redundant capacity, backups and redundant facilities, financial institutions should assess whether that capacity, backup, and those facilities operate effectively for a sufficient period of time and ensure that the normal functioning of the primary ICT infrastructure is restored in accordance with the recovery objectives."
      ],
      "text": "It is necessary to set out the set of scenarios that financial entities referred to in Title II of this Regulation should take into account both for the implementation of ICT response and recovery plans and for the testing of ICT business continuity plans. Those scenarios should serve as a starting point for financial entities to analyse both the relevance and plausibility of each scenario and the need to develop alternative scenarios. Financial entities should focus on those scenarios in which investment in resilience measures could be more efficient and effective. By testing switchovers between the primary ICT infrastructure and any redundant capacity, backups and redundant facilities, financial institutions should assess whether that capacity, backup, and those facilities operate effectively for a sufficient period of time and ensure that the normal functioning of the primary ICT infrastructure is restored in accordance with the recovery objectives.",
      "outbound_relations": [
        {
          "edge_id": "recital-23__article-Art25-Para2__provides_guidance_for",
          "source": "recital-23",
          "target": "article-Art25-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-23 provides guidance for article-Art25-Para2 by explaining the purpose of severe-but-plausible scenario testing and of switchover tests: verify redundant capacity, backups, and facilities over a sufficient period and restore normal operation to the recovery objectives.",
          "source_canonical_ref": "celex:32024R1774/recital-23",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para2"
        },
        {
          "edge_id": "recital-23__article-Art26-Para2__provides_guidance_for",
          "source": "recital-23",
          "target": "article-Art26-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-23 provides guidance for article-Art26-Para2 by directing entities to assess the relevance and plausibility of the response-and-recovery scenarios listed there and to consider whether alternative scenarios are needed.",
          "source_canonical_ref": "celex:32024R1774/recital-23",
          "target_canonical_ref": "celex:32024R1774/article-Art26-Para2"
        },
        {
          "edge_id": "recital-23__recital-22__builds_on",
          "source": "recital-23",
          "target": "recital-22",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-23 builds on recital-22 by moving from the components to be integrated into an ICT business continuity policy to the scenarios used to implement response and recovery plans and test continuity plans.",
          "source_canonical_ref": "celex:32024R1774/recital-23",
          "target_canonical_ref": "celex:32024R1774/recital-22"
        }
      ],
      "inbound_relations": [],
      "canonical_ref": "celex:32024R1774/recital-23",
      "text_sha256": "ef5613c3c48e3d7d4a13f7704d352dab288c308c16daf02be98c34f0b9503f5b"
    },
    {
      "id": "recital-24",
      "type": "recital",
      "recital_number": 24,
      "paragraphs": [
        "It is necessary to lay down requirements for operational risk, and more particularly requirements for ICT project and change management and ICT business continuity management building on those that apply already to central counterparties, central securities depositories and trading venues under, respectively, Regulations (EU) No 648/2012 ( 3 ) , (EU) No 600/2014 ( 4 ) and (EU) No 909/2014 ( 5 ) of the European Parliament and of the Council."
      ],
      "text": "It is necessary to lay down requirements for operational risk, and more particularly requirements for ICT project and change management and ICT business continuity management building on those that apply already to central counterparties, central securities depositories and trading venues under, respectively, Regulations (EU) No 648/2012 ( 3 ) , (EU) No 600/2014 ( 4 ) and (EU) No 909/2014 ( 5 ) of the European Parliament and of the Council.",
      "outbound_relations": [
        {
          "edge_id": "recital-24__article-Art16-Para2__provides_guidance_for",
          "source": "recital-24",
          "target": "article-Art16-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-24 explains why article-Art16-Para2 adds sector-specific ICT-system testing participation for central counterparties and central securities depositories: the RTS builds project-management controls on the operational-risk rules already applicable to those infrastructures.",
          "source_canonical_ref": "celex:32024R1774/recital-24",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
        },
        {
          "edge_id": "recital-24__article-Art17-Para2__provides_guidance_for",
          "source": "recital-24",
          "target": "article-Art17-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-24 supplies the sectoral rationale for article-Art17-Para2, whose stringent post-change testing duties specifically address central counterparties and central securities depositories under the ICT change-management requirements.",
          "source_canonical_ref": "celex:32024R1774/recital-24",
          "target_canonical_ref": "celex:32024R1774/article-Art17-Para2"
        },
        {
          "edge_id": "recital-24__article-Art24-Para2__provides_guidance_for",
          "source": "recital-24",
          "target": "article-Art24-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-24 explains the legislative basis for the central-counterparty-specific continuity requirements in article-Art24-Para2 by stating that the RTS builds on operational-risk rules already applicable to central counterparties.",
          "source_canonical_ref": "celex:32024R1774/recital-24",
          "target_canonical_ref": "celex:32024R1774/article-Art24-Para2"
        },
        {
          "edge_id": "recital-24__article-Art24-Para3__provides_guidance_for",
          "source": "recital-24",
          "target": "article-Art24-Para3",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-24 explains the legislative basis for the central-securities-depository-specific continuity requirements in article-Art24-Para3 by linking the RTS to pre-existing operational-risk rules for those depositories.",
          "source_canonical_ref": "celex:32024R1774/recital-24",
          "target_canonical_ref": "celex:32024R1774/article-Art24-Para3"
        },
        {
          "edge_id": "recital-24__article-Art24-Para4__provides_guidance_for",
          "source": "recital-24",
          "target": "article-Art24-Para4",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-24 explains why article-Art24-Para4 preserves trading-venue-specific recovery and data-loss requirements within the RTS business-continuity framework.",
          "source_canonical_ref": "celex:32024R1774/recital-24",
          "target_canonical_ref": "celex:32024R1774/article-Art24-Para4"
        },
        {
          "edge_id": "recital-24__article-Art25-Para3__provides_guidance_for",
          "source": "recital-24",
          "target": "article-Art25-Para3",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-24 provides the sectoral context for article-Art25-Para3, which supplements general continuity-plan testing with participation duties tailored to central counterparties.",
          "source_canonical_ref": "celex:32024R1774/recital-24",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para3"
        },
        {
          "edge_id": "recital-24__article-Art25-Para4__provides_guidance_for",
          "source": "recital-24",
          "target": "article-Art25-Para4",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-24 provides the sectoral context for article-Art25-Para4, which supplements continuity-plan testing with participants and infrastructures relevant specifically to central securities depositories.",
          "source_canonical_ref": "celex:32024R1774/recital-24",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para4"
        }
      ],
      "inbound_relations": [],
      "canonical_ref": "celex:32024R1774/recital-24",
      "text_sha256": "53f7595e53165604201b7b231e6b718e482a17d4b35ef761ca94810e1693f823"
    },
    {
      "id": "recital-25",
      "type": "recital",
      "recital_number": 25,
      "paragraphs": [
        "Article 6(5) of Regulation (EU) 2022/2554 requires financial entities to review their ICT risk management framework and to provide their competent authority with a report on that review. To enable competent authorities to easily process the information in those reports, and to guarantee an adequate transmission of that information, financial entities should submit those reports in a searchable electronic format."
      ],
      "text": "Article 6(5) of Regulation (EU) 2022/2554 requires financial entities to review their ICT risk management framework and to provide their competent authority with a report on that review. To enable competent authorities to easily process the information in those reports, and to guarantee an adequate transmission of that information, financial entities should submit those reports in a searchable electronic format.",
      "outbound_relations": [
        {
          "edge_id": "recital-25__article-Art27-Para1__provides_guidance_for",
          "source": "recital-25",
          "target": "article-Art27-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-25 explains the processing and transmission rationale for article-Art27-Para1 requiring the DORA Article 6(5) ICT-risk-framework review report to be submitted in a searchable electronic format.",
          "source_canonical_ref": "celex:32024R1774/recital-25",
          "target_canonical_ref": "celex:32024R1774/article-Art27-Para1"
        }
      ],
      "inbound_relations": [],
      "canonical_ref": "celex:32024R1774/recital-25",
      "text_sha256": "8e1a5c2d610be350729d61573ac1469ee4e50d8fe6700eafe2ee9b78196f5264"
    },
    {
      "id": "recital-26",
      "type": "recital",
      "recital_number": 26,
      "paragraphs": [
        "The requirements for financial entities that are subject to the simplified ICT risk management framework referred to in Article 16 of Regulation (EU) 2022/2554 should be focused on those essential areas and elements that, in light of the scale, risk, size, and complexity of those financial entities, are as a minimum necessary to ensure the confidentiality, integrity, availability, and authenticity of the data and services of those financial entities. In that context, those financial entities should have in place an internal governance and control framework with clear responsibilities to enable an effective and sound risk management framework. Furthermore, to reduce the administrative and operational burden, those financial entities should develop and document only one policy, that is an information security policy, that specifies the high-level principles and rules necessary to protect the confidentiality, integrity, availability, and authenticity of data and of the services of those financial entities."
      ],
      "text": "The requirements for financial entities that are subject to the simplified ICT risk management framework referred to in Article 16 of Regulation (EU) 2022/2554 should be focused on those essential areas and elements that, in light of the scale, risk, size, and complexity of those financial entities, are as a minimum necessary to ensure the confidentiality, integrity, availability, and authenticity of the data and services of those financial entities. In that context, those financial entities should have in place an internal governance and control framework with clear responsibilities to enable an effective and sound risk management framework. Furthermore, to reduce the administrative and operational burden, those financial entities should develop and document only one policy, that is an information security policy, that specifies the high-level principles and rules necessary to protect the confidentiality, integrity, availability, and authenticity of data and of the services of those financial entities.",
      "outbound_relations": [
        {
          "edge_id": "recital-26__article-Art1-Para1__provides_guidance_for",
          "source": "recital-26",
          "target": "article-Art1-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-26 guides application of article-Art1-Para1 by explaining that scale, risk, size and complexity justify limiting the simplified ICT risk management framework to the minimum controls needed to protect data and services.",
          "source_canonical_ref": "celex:32024R1774/recital-26",
          "target_canonical_ref": "celex:32024R1774/article-Art1-Para1"
        },
        {
          "edge_id": "recital-26__article-Art28-Para1__concretizes",
          "source": "recital-26",
          "target": "article-Art28-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-26 concretizes article-Art28-Para1 by identifying an internal governance and control framework as the organisational basis for effective and sound ICT risk management by simplified-framework entities.",
          "source_canonical_ref": "celex:32024R1774/recital-26",
          "target_canonical_ref": "celex:32024R1774/article-Art28-Para1"
        },
        {
          "edge_id": "recital-26__article-Art28-Para2__concretizes",
          "source": "recital-26",
          "target": "article-Art28-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-26 concretizes the clear-responsibility element of article-Art28-Para2 by requiring governance arrangements with unambiguous responsibilities for the simplified ICT risk management framework.",
          "source_canonical_ref": "celex:32024R1774/recital-26",
          "target_canonical_ref": "celex:32024R1774/article-Art28-Para2"
        },
        {
          "edge_id": "recital-26__article-Art29-Para1__concretizes",
          "source": "recital-26",
          "target": "article-Art29-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-26 directly concretizes article-Art29-Para1: simplified-framework entities use one information security policy containing high-level rules that protect confidentiality, integrity, availability and authenticity.",
          "source_canonical_ref": "celex:32024R1774/recital-26",
          "target_canonical_ref": "celex:32024R1774/article-Art29-Para1"
        },
        {
          "edge_id": "recital-26__recital-2__builds_on",
          "source": "recital-26",
          "target": "recital-2",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-26 builds_on recital-2 by turning recital-2’s flexibility and essential-policy premise into the simplified-framework rule that entities maintain one high-level information security policy proportionate to scale and risk.",
          "source_canonical_ref": "celex:32024R1774/recital-26",
          "target_canonical_ref": "celex:32024R1774/recital-2"
        }
      ],
      "inbound_relations": [],
      "canonical_ref": "celex:32024R1774/recital-26",
      "text_sha256": "620c9347d31afb418532cbc041288280bf0f5685884d04c4f764fab300e9d326"
    },
    {
      "id": "recital-27",
      "type": "recital",
      "recital_number": 27,
      "paragraphs": [
        "The provisions of this Regulation relate to the area of the ICT risk management framework, by detailing specific elements applicable to the financial entities in accordance with Article 15 of Regulation (EU) 2022/2554 and by designing the simplified ICT risk management framework for the financial entities set out in Article 16(1) of that Regulation. To ensure coherence between the ordinary and the simplified ICT risk management framework, and considering that those provisions should become applicable at the same time, it is appropriate to include those provisions in a single legislative act."
      ],
      "text": "The provisions of this Regulation relate to the area of the ICT risk management framework, by detailing specific elements applicable to the financial entities in accordance with Article 15 of Regulation (EU) 2022/2554 and by designing the simplified ICT risk management framework for the financial entities set out in Article 16(1) of that Regulation. To ensure coherence between the ordinary and the simplified ICT risk management framework, and considering that those provisions should become applicable at the same time, it is appropriate to include those provisions in a single legislative act.",
      "outbound_relations": [],
      "inbound_relations": [],
      "canonical_ref": "celex:32024R1774/recital-27",
      "text_sha256": "e65622cd3277d903cdeba990d1e1f6c08e7665b0258180abe1169c39f2da59cc"
    },
    {
      "id": "recital-28",
      "type": "recital",
      "recital_number": 28,
      "paragraphs": [
        "This Regulation is based on the draft regulatory technical standards submitted to the Commission by the European Banking Authority, the European Insurance and Occupational Pensions Authority and the European Securities and Markets Authority (European Supervisory Authorities), in consultation with the European Union Agency for Cybersecurity (ENISA)."
      ],
      "text": "This Regulation is based on the draft regulatory technical standards submitted to the Commission by the European Banking Authority, the European Insurance and Occupational Pensions Authority and the European Securities and Markets Authority (European Supervisory Authorities), in consultation with the European Union Agency for Cybersecurity (ENISA).",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "recital-29__recital-28__builds_on",
          "source": "recital-29",
          "target": "recital-28",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-29 builds_on recital-28: recital-28 identifies the ESAs’ draft regulatory technical standards, while recital-29 records the Joint Committee consultation, cost-benefit analysis and stakeholder advice for that same draft.",
          "source_canonical_ref": "celex:32024R1774/recital-29",
          "target_canonical_ref": "celex:32024R1774/recital-28"
        }
      ],
      "canonical_ref": "celex:32024R1774/recital-28",
      "text_sha256": "874dc015eff2126ed07d620584476736f5102da93a191d328bc2eefbfd305ac0"
    },
    {
      "id": "recital-29",
      "type": "recital",
      "recital_number": 29,
      "paragraphs": [
        "The Joint Committee of the European Supervisory Authorities referred to in Article 54 of Regulation (EU) No 1093/2010 of the European Parliament and of the Council ( 6 ) , in Article 54 of Regulation (EU) No 1094/2010 of the European Parliament and of the Council ( 7 ) and in Article 54 of Regulation (EU) No 1095/2010 of the European Parliament and of the Council ( 8 ) has conducted open public consultations on the draft regulatory technical standards on which this Regulation is based, analysed the potential costs and benefits of the proposed standards and requested advice of the Banking Stakeholder Group established in accordance with Article 37 of Regulation (EU) No 1093/2010, the Insurance and Reinsurance Stakeholder Group and the Occupational Pensions Stakeholder Group established in accordance with Article 37 of Regulation (EU) No 1094/2010, and the Securities and Markets Stakeholder Group established in accordance with Article 37 of Regulation (EU) No 1095/2010."
      ],
      "text": "The Joint Committee of the European Supervisory Authorities referred to in Article 54 of Regulation (EU) No 1093/2010 of the European Parliament and of the Council ( 6 ) , in Article 54 of Regulation (EU) No 1094/2010 of the European Parliament and of the Council ( 7 ) and in Article 54 of Regulation (EU) No 1095/2010 of the European Parliament and of the Council ( 8 ) has conducted open public consultations on the draft regulatory technical standards on which this Regulation is based, analysed the potential costs and benefits of the proposed standards and requested advice of the Banking Stakeholder Group established in accordance with Article 37 of Regulation (EU) No 1093/2010, the Insurance and Reinsurance Stakeholder Group and the Occupational Pensions Stakeholder Group established in accordance with Article 37 of Regulation (EU) No 1094/2010, and the Securities and Markets Stakeholder Group established in accordance with Article 37 of Regulation (EU) No 1095/2010.",
      "outbound_relations": [
        {
          "edge_id": "recital-29__recital-28__builds_on",
          "source": "recital-29",
          "target": "recital-28",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "builds_on",
          "confidence": "high",
          "reasoning": "recital-29 builds_on recital-28: recital-28 identifies the ESAs’ draft regulatory technical standards, while recital-29 records the Joint Committee consultation, cost-benefit analysis and stakeholder advice for that same draft.",
          "source_canonical_ref": "celex:32024R1774/recital-29",
          "target_canonical_ref": "celex:32024R1774/recital-28"
        }
      ],
      "inbound_relations": [],
      "canonical_ref": "celex:32024R1774/recital-29",
      "text_sha256": "42ee2be3cd2f119489c92589f5f5017e8b8d77068a329275535ea605097856d3"
    },
    {
      "id": "recital-30",
      "type": "recital",
      "recital_number": 30,
      "paragraphs": [
        "To the extent to which processing of personal data is required to comply with the obligations set out in this Act, Regulations (EU) 2016/679 ( 9 ) and (EU) 2018/1725 ( 10 ) of the European Parliament and of the Council should fully apply. For instance, the data minimisation principle should be complied with where personal data are collected to ensure an appropriate incident detection. The European Data Protection Supervisor has also been consulted on the draft text of this Act,"
      ],
      "text": "To the extent to which processing of personal data is required to comply with the obligations set out in this Act, Regulations (EU) 2016/679 ( 9 ) and (EU) 2018/1725 ( 10 ) of the European Parliament and of the Council should fully apply. For instance, the data minimisation principle should be complied with where personal data are collected to ensure an appropriate incident detection. The European Data Protection Supervisor has also been consulted on the draft text of this Act,",
      "outbound_relations": [
        {
          "edge_id": "recital-30__article-Art23-Para2__restricts",
          "source": "recital-30",
          "target": "article-Art23-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "restricts",
          "confidence": "high",
          "reasoning": "recital-30 restricts the collection and analysis required by article-Art23-Para2: where incident-detection information is personal data, the Union data-protection regime and data-minimisation principle continue to apply.",
          "source_canonical_ref": "celex:32024R1774/recital-30",
          "target_canonical_ref": "celex:32024R1774/article-Art23-Para2"
        },
        {
          "edge_id": "recital-30__article-Art34-Para1__restricts",
          "source": "recital-30",
          "target": "article-Art34-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "restricts",
          "confidence": "high",
          "reasoning": "recital-30 restricts the anomalous-activity monitoring and security-information measures in article-Art34-Para1 by requiring any personal-data processing for incident detection to comply fully with Union data-protection law and data minimisation.",
          "source_canonical_ref": "celex:32024R1774/recital-30",
          "target_canonical_ref": "celex:32024R1774/article-Art34-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-19__recital-30__provides_context_for",
          "source": "recital-19",
          "target": "recital-30",
          "source_type": "recital",
          "target_type": "recital",
          "relation": "provides_context_for",
          "confidence": "high",
          "reasoning": "recital-19 provides context for recital-30 because its incident-detection data collection is the concrete setting in which recital-30 reiterates full data-protection application and uses data minimisation for incident detection as its example.",
          "source_canonical_ref": "celex:32024R1774/recital-19",
          "target_canonical_ref": "celex:32024R1774/recital-30"
        }
      ],
      "canonical_ref": "celex:32024R1774/recital-30",
      "text_sha256": "9c752752272670ac759a67563ddc4668b31cab2ce1780d5c5f73a4ccde4176ad"
    },
    {
      "id": "article-Art1-Para1",
      "type": "article_paragraph",
      "article_number": 1,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "single",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Overall risk profile and complexity",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "encryption and cryptography;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 574,
          "source_line_end": 577
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "ICT operations security;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 588,
          "source_line_end": 591
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "network security;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 602,
          "source_line_end": 605
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "ICT project and change management;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 616,
          "source_line_end": 619
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "the potential impact of the ICT risk on confidentiality, integrity and availability of data, and of the disruptions on the continuity and availability of the financial entity’s activities.",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 630,
          "source_line_end": 633
        }
      ],
      "ancestry": [
        "TITLE I"
      ],
      "text": "When developing and implementing the ICT security policies, procedures, protocols and tools referred to in Title II and the simplified ICT risk management framework referred to in Title III, the size and the overall risk profile of the financial entity, and the nature, scale and elements of increased or reduced complexity of its services, activities and operations shall be taken into account, including elements relating to: (a) encryption and cryptography; (b) ICT operations security; (c) network security; (d) ICT project and change management; (e) the potential impact of the ICT risk on confidentiality, integrity and availability of data, and of the disruptions on the continuity and availability of the financial entity’s activities.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "recital-1__article-Art1-Para1__provides_guidance_for",
          "source": "recital-1",
          "target": "article-Art1-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-1 explains the proportionality rationale for article-Art1-Para1 by tying ICT requirements to entity size, structure, complexity and corresponding ICT risk.",
          "source_canonical_ref": "celex:32024R1774/recital-1",
          "target_canonical_ref": "celex:32024R1774/article-Art1-Para1"
        },
        {
          "edge_id": "recital-26__article-Art1-Para1__provides_guidance_for",
          "source": "recital-26",
          "target": "article-Art1-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-26 guides application of article-Art1-Para1 by explaining that scale, risk, size and complexity justify limiting the simplified ICT risk management framework to the minimum controls needed to protect data and services.",
          "source_canonical_ref": "celex:32024R1774/recital-26",
          "target_canonical_ref": "celex:32024R1774/article-Art1-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "When developing and implementing the ICT security policies, procedures, protocols and tools referred to in Title II and the simplified ICT risk management framework referred to in Title III, the size and the overall risk profile of the financial entity, and the nature, scale and elements of increased or reduced complexity of its services, activities and operations shall be taken into account, including elements relating to:",
          "source_line_start": 567,
          "source_line_end": 567
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art1-Para1",
      "text_sha256": "bfa6a9f3590b1b0197dabaac0d2c7d6f172d3ed76bdee2b5d9d66402f5b40132"
    },
    {
      "id": "article-Art2-Para1",
      "type": "article_paragraph",
      "article_number": 2,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "General elements of ICT security policies, procedures, protocols, and tools",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "ensure the security of networks;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 675,
          "source_line_end": 678
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "contain safeguards against intrusions and data misuse;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 689,
          "source_line_end": 692
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "preserve the availability, authenticity, integrity, and confidentiality of data, including via the use of cryptographic techniques;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 703,
          "source_line_end": 706
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "guarantee an accurate and prompt data transmission without major disruptions and undue delays.",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 717,
          "source_line_end": 720
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 1"
      ],
      "text": "Financial entities shall ensure that their ICT security policies, information security, and related procedures, protocols, and tools as referred to in Article 9(2) of Regulation (EU) 2022/2554 are embedded in their ICT risk management framework. Financial entities shall establish the ICT security policies, procedures, protocols, and tools laid down in this Chapter that: (a) ensure the security of networks; (b) contain safeguards against intrusions and data misuse; (c) preserve the availability, authenticity, integrity, and confidentiality of data, including via the use of cryptographic techniques; (d) guarantee an accurate and prompt data transmission without major disruptions and undue delays.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art2-Para2__article-Art2-Para1__depends_on",
          "source": "article-Art2-Para2",
          "target": "article-Art2-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art2-Para2 expressly applies its governance and content requirements to the ICT security policies established under article-Art2-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art2-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art2-Para1"
        },
        {
          "edge_id": "recital-7__article-Art2-Para1__provides_guidance_for",
          "source": "recital-7",
          "target": "article-Art2-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-7 links operational, asset and capacity controls to network security, intrusion safeguards and data protection, explaining the common outcomes required by article-Art2-Para1.",
          "source_canonical_ref": "celex:32024R1774/recital-7",
          "target_canonical_ref": "celex:32024R1774/article-Art2-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall ensure that their ICT security policies, information security, and related procedures, protocols, and tools as referred to in Article 9(2) of Regulation (EU) 2022/2554 are embedded in their ICT risk management framework. Financial entities shall establish the ICT security policies, procedures, protocols, and tools laid down in this Chapter that:",
          "source_line_start": 668,
          "source_line_end": 668
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art2-Para1",
      "text_sha256": "b9486d74985bc95eb4b5cc650dca45156a6837a53f72f59e6c7380b09e89999d"
    },
    {
      "id": "article-Art2-Para2",
      "type": "article_paragraph",
      "article_number": 2,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "General elements of ICT security policies, procedures, protocols, and tools",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "are aligned to the financial entity’s information security objectives included in the digital operational resilience strategy referred to in Article 6(8) of Regulation (EU) 2022/2554;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 734,
          "source_line_end": 737
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "indicate the date of the formal approval of the ICT security policies by the management body;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 748,
          "source_line_end": 751
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "contain indicators and measures to:",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 762,
          "source_line_end": 765
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "monitor the implementation of the ICT security policies, procedures, protocols, and tools;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(i)",
          "source_line_start": 772,
          "source_line_end": 775
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "record exceptions from that implementation;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(ii)",
          "source_line_start": 786,
          "source_line_end": 789
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "ensure that the digital operational resilience of the financial entity is ensured in case of exceptions as referred to in point (ii);",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(iii)",
          "source_line_start": 800,
          "source_line_end": 803
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "specify the responsibilities of staff at all levels to ensure the financial entity’s ICT security;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 818,
          "source_line_end": 821
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "specify the consequences of non-compliance by staff of the financial entity with the ICT security policies, where provisions to that effect are not laid down in other policies of the financial entity;",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 832,
          "source_line_end": 835
        },
        {
          "type": "point",
          "marker": "(f)",
          "text": "list the documentation to be maintained;",
          "depth": 1,
          "parent_marker": null,
          "path": "(f)",
          "source_line_start": 846,
          "source_line_end": 849
        },
        {
          "type": "point",
          "marker": "(g)",
          "text": "specify the segregation of duties arrangements in the context of the three lines of defence model or other internal risk management and control model, as applicable, to avoid conflicts of interest;",
          "depth": 1,
          "parent_marker": null,
          "path": "(g)",
          "source_line_start": 860,
          "source_line_end": 863
        },
        {
          "type": "point",
          "marker": "(h)",
          "text": "consider leading practices and, where applicable, standards as defined in Article 2, point (1), of Regulation (EU) No 1025/2012;",
          "depth": 1,
          "parent_marker": null,
          "path": "(h)",
          "source_line_start": 874,
          "source_line_end": 877
        },
        {
          "type": "point",
          "marker": "(i)",
          "text": "identify the roles and responsibilities for the development, implementation and maintenance of ICT security policies, procedures, protocols, and tools;",
          "depth": 1,
          "parent_marker": null,
          "path": "(i)",
          "source_line_start": 888,
          "source_line_end": 891
        },
        {
          "type": "point",
          "marker": "(j)",
          "text": "are reviewed in accordance with Article 6(5) of Regulation (EU) 2022/2554;",
          "depth": 1,
          "parent_marker": null,
          "path": "(j)",
          "source_line_start": 902,
          "source_line_end": 905
        },
        {
          "type": "point",
          "marker": "(k)",
          "text": "take into account material changes concerning the financial entity, including material changes to the activities or processes of the financial entity, to the cyber threat landscape, or to applicable legal obligations.",
          "depth": 1,
          "parent_marker": null,
          "path": "(k)",
          "source_line_start": 916,
          "source_line_end": 919
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 1"
      ],
      "text": "Financial entities shall ensure that the ICT security policies referred to in paragraph 1: (a) are aligned to the financial entity’s information security objectives included in the digital operational resilience strategy referred to in Article 6(8) of Regulation (EU) 2022/2554; (b) indicate the date of the formal approval of the ICT security policies by the management body; (c) contain indicators and measures to: (i) monitor the implementation of the ICT security policies, procedures, protocols, and tools; (ii) record exceptions from that implementation; (iii) ensure that the digital operational resilience of the financial entity is ensured in case of exceptions as referred to in point (ii); (d) specify the responsibilities of staff at all levels to ensure the financial entity’s ICT security; (e) specify the consequences of non-compliance by staff of the financial entity with the ICT security policies, where provisions to that effect are not laid down in other policies of the financial entity; (f) list the documentation to be maintained; (g) specify the segregation of duties arrangements in the context of the three lines of defence model or other internal risk management and control model, as applicable, to avoid conflicts of interest; (h) consider leading practices and, where applicable, standards as defined in Article 2, point (1), of Regulation (EU) No 1025/2012; (i) identify the roles and responsibilities for the development, implementation and maintenance of ICT security policies, procedures, protocols, and tools; (j) are reviewed in accordance with Article 6(5) of Regulation (EU) 2022/2554; (k) take into account material changes concerning the financial entity, including material changes to the activities or processes of the financial entity, to the cyber threat landscape, or to applicable legal obligations.",
      "outbound_relations": [
        {
          "edge_id": "article-Art2-Para2__article-Art2-Para1__depends_on",
          "source": "article-Art2-Para2",
          "target": "article-Art2-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art2-Para2 expressly applies its governance and content requirements to the ICT security policies established under article-Art2-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art2-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art2-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-2__article-Art2-Para2__provides_guidance_for",
          "source": "recital-2",
          "target": "article-Art2-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-2 guides application of article-Art2-Para2 by allowing existing documentation to satisfy documentation duties and by explaining why only essential policy elements require dedicated documentation.",
          "source_canonical_ref": "celex:32024R1774/recital-2",
          "target_canonical_ref": "celex:32024R1774/article-Art2-Para2"
        },
        {
          "edge_id": "recital-3__article-Art2-Para2__provides_guidance_for",
          "source": "recital-3",
          "target": "article-Art2-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-3 explains why article-Art2-Para2 requires maintained ICT-security roles and responsibilities and consequences for staff non-compliance.",
          "source_canonical_ref": "celex:32024R1774/recital-3",
          "target_canonical_ref": "celex:32024R1774/article-Art2-Para2"
        },
        {
          "edge_id": "recital-4__article-Art2-Para2__provides_guidance_for",
          "source": "recital-4",
          "target": "article-Art2-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-4 supplies the conflict-of-interest rationale for the segregation-of-duties arrangements mandated in article-Art2-Para2.",
          "source_canonical_ref": "celex:32024R1774/recital-4",
          "target_canonical_ref": "celex:32024R1774/article-Art2-Para2"
        },
        {
          "edge_id": "recital-5__article-Art2-Para2__restricts",
          "source": "recital-5",
          "target": "article-Art2-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "restricts",
          "confidence": "high",
          "reasoning": "recital-5 limits article-Art2-Para2's non-compliance provision by confirming that a dedicated provision is unnecessary when another policy or procedure already contains it.",
          "source_canonical_ref": "celex:32024R1774/recital-5",
          "target_canonical_ref": "celex:32024R1774/article-Art2-Para2"
        },
        {
          "edge_id": "recital-6__article-Art2-Para2__provides_guidance_for",
          "source": "recital-6",
          "target": "article-Art2-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-6 explains that evolving ICT risk requires leading practices and applicable standards, guiding the corresponding standards and material-change criteria in article-Art2-Para2.",
          "source_canonical_ref": "celex:32024R1774/recital-6",
          "target_canonical_ref": "celex:32024R1774/article-Art2-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall ensure that the ICT security policies referred to in paragraph 1:",
          "source_line_start": 727,
          "source_line_end": 727
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art2-Para2",
      "text_sha256": "59e1e2155a4ebee695037ee90d688c86588a5c40cffa0f1df5c7828854e0677b"
    },
    {
      "id": "article-Art3-Para1",
      "type": "article_paragraph",
      "article_number": 3,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "single",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT risk management",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "an indication of the approval of the risk tolerance level for ICT risk established in accordance with Article 6(8), point (b), of Regulation (EU) 2022/2554;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 943,
          "source_line_end": 946
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "a procedure and a methodology to conduct the ICT risk assessment, identifying:",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 957,
          "source_line_end": 960
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "vulnerabilities and threats that affect or may affect the supported business functions, the ICT systems and ICT assets supporting those functions;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(i)",
          "source_line_start": 967,
          "source_line_end": 970
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "the quantitative or qualitative indicators to measure the impact and likelihood of the vulnerabilities and threats referred to in point (i);",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(ii)",
          "source_line_start": 981,
          "source_line_end": 984
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "the procedure to identify, implement, and document ICT risk treatment measures for the ICT risks identified and assessed, including the determination of ICT risk treatment measures necessary to bring ICT risk within the risk tolerance level referred to in point (a);",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 999,
          "source_line_end": 1002
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "for the residual ICT risks that are still present following the implementation of the ICT risk treatment measures referred to in point (c):",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 1013,
          "source_line_end": 1016
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "provisions on the identification of those residual ICT risks;",
          "depth": 2,
          "parent_marker": "(d)",
          "path": "(d)(i)",
          "source_line_start": 1023,
          "source_line_end": 1026
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "the assignment of roles and responsibilities regarding:",
          "depth": 2,
          "parent_marker": "(d)",
          "path": "(d)(ii)",
          "source_line_start": 1037,
          "source_line_end": 1040
        },
        {
          "type": "subpoint",
          "marker": "(1)",
          "text": "the acceptance of the residual ICT risks that exceed the financial entity’s risk tolerance level referred to in point (a);",
          "depth": 3,
          "parent_marker": "(ii)",
          "path": "(d)(ii)(1)",
          "source_line_start": 1047,
          "source_line_end": 1050
        },
        {
          "type": "subpoint",
          "marker": "(2)",
          "text": "for the review process referred to in point (iv) of this point (d);",
          "depth": 3,
          "parent_marker": "(ii)",
          "path": "(d)(ii)(2)",
          "source_line_start": 1061,
          "source_line_end": 1064
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "the development of an inventory of the accepted residual ICT risks, including a justification for their acceptance;",
          "depth": 2,
          "parent_marker": "(d)",
          "path": "(d)(iii)",
          "source_line_start": 1079,
          "source_line_end": 1082
        },
        {
          "type": "subpoint",
          "marker": "(iv)",
          "text": "provisions on the review of the accepted residual ICT risks at least once a year, including:",
          "depth": 2,
          "parent_marker": "(d)",
          "path": "(d)(iv)",
          "source_line_start": 1093,
          "source_line_end": 1096
        },
        {
          "type": "subpoint",
          "marker": "(1)",
          "text": "the identification of any changes to the residual ICT risks;",
          "depth": 3,
          "parent_marker": "(iv)",
          "path": "(d)(iv)(1)",
          "source_line_start": 1103,
          "source_line_end": 1106
        },
        {
          "type": "subpoint",
          "marker": "(2)",
          "text": "the assessment of available mitigation measures;",
          "depth": 3,
          "parent_marker": "(iv)",
          "path": "(d)(iv)(2)",
          "source_line_start": 1117,
          "source_line_end": 1120
        },
        {
          "type": "subpoint",
          "marker": "(3)",
          "text": "the assessment of whether the reasons justifying the acceptance of residual ICT risks are still valid and applicable at the date of the review;",
          "depth": 3,
          "parent_marker": "(iv)",
          "path": "(d)(iv)(3)",
          "source_line_start": 1131,
          "source_line_end": 1134
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "provisions on the monitoring of:",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 1153,
          "source_line_end": 1156
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "any changes to the ICT risk and cyber threat landscape;",
          "depth": 2,
          "parent_marker": "(e)",
          "path": "(e)(i)",
          "source_line_start": 1163,
          "source_line_end": 1166
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "internal and external vulnerabilities and threats:",
          "depth": 2,
          "parent_marker": "(e)",
          "path": "(e)(ii)",
          "source_line_start": 1177,
          "source_line_end": 1180
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "ICT risk of the financial entity that enables promp detection of changes that could affect its ICT risk profile;",
          "depth": 2,
          "parent_marker": "(e)",
          "path": "(e)(iii)",
          "source_line_start": 1191,
          "source_line_end": 1194
        },
        {
          "type": "point",
          "marker": "(f)",
          "text": "provisions on a process to ensure that any changes to the business strategy and the digital operational resilience strategy of the financial entity are taken into account.",
          "depth": 1,
          "parent_marker": null,
          "path": "(f)",
          "source_line_start": 1209,
          "source_line_end": 1212
        },
        {
          "type": "point",
          "marker": "(a)",
          "text": "the monitoring of the effectiveness of the ICT risk treatment measures implemented;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 1224,
          "source_line_end": 1227
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "the assessment of whether the established risk tolerance levels of the financial entity have been attained;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 1238,
          "source_line_end": 1241
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "the assessment of whether the financial entity has taken actions to correct or improve those measures where necessary.",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 1252,
          "source_line_end": 1255
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 2"
      ],
      "text": "Financial entities shall develop, document, and implement ICT risk management policies and procedures that shall contain all of the following: (a) an indication of the approval of the risk tolerance level for ICT risk established in accordance with Article 6(8), point (b), of Regulation (EU) 2022/2554; (b) a procedure and a methodology to conduct the ICT risk assessment, identifying: (i) vulnerabilities and threats that affect or may affect the supported business functions, the ICT systems and ICT assets supporting those functions; (ii) the quantitative or qualitative indicators to measure the impact and likelihood of the vulnerabilities and threats referred to in point (i); (c) the procedure to identify, implement, and document ICT risk treatment measures for the ICT risks identified and assessed, including the determination of ICT risk treatment measures necessary to bring ICT risk within the risk tolerance level referred to in point (a); (d) for the residual ICT risks that are still present following the implementation of the ICT risk treatment measures referred to in point (c): (i) provisions on the identification of those residual ICT risks; (ii) the assignment of roles and responsibilities regarding: (1) the acceptance of the residual ICT risks that exceed the financial entity’s risk tolerance level referred to in point (a); (2) for the review process referred to in point (iv) of this point (d); (iii) the development of an inventory of the accepted residual ICT risks, including a justification for their acceptance; (iv) provisions on the review of the accepted residual ICT risks at least once a year, including: (1) the identification of any changes to the residual ICT risks; (2) the assessment of available mitigation measures; (3) the assessment of whether the reasons justifying the acceptance of residual ICT risks are still valid and applicable at the date of the review; (e) provisions on the monitoring of: (i) any changes to the ICT risk and cyber threat landscape; (ii) internal and external vulnerabilities and threats: (iii) ICT risk of the financial entity that enables promp detection of changes that could affect its ICT risk profile; (f) provisions on a process to ensure that any changes to the business strategy and the digital operational resilience strategy of the financial entity are taken into account. For the purposes of the first paragraph, point (c), the procedure referred to in that point shall ensure: (a) the monitoring of the effectiveness of the ICT risk treatment measures implemented; (b) the assessment of whether the established risk tolerance levels of the financial entity have been attained; (c) the assessment of whether the financial entity has taken actions to correct or improve those measures where necessary.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art11-Para2__article-Art3-Para1__references",
          "source": "article-Art11-Para2",
          "target": "article-Art3-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art11-Para2 conditions use of removable data-storage devices on residual ICT risk remaining within the risk-tolerance level established in article-Art3-Para1, first subparagraph, point (a).",
          "source_canonical_ref": "celex:32024R1774/article-Art11-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art3-Para1"
        },
        {
          "edge_id": "article-Art25-Para1__article-Art3-Para1__references",
          "source": "article-Art25-Para1",
          "target": "article-Art3-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art25-Para1 expressly requires continuity-plan testing to take account of the ICT risk assessment in article-Art3-Para1, point (b), which defines the assessment procedure and methodology.",
          "source_canonical_ref": "celex:32024R1774/article-Art25-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art3-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall develop, document, and implement ICT risk management policies and procedures that shall contain all of the following:",
          "source_line_start": 936,
          "source_line_end": 936
        },
        {
          "sequence": 2,
          "text": "For the purposes of the first paragraph, point (c), the procedure referred to in that point shall ensure:",
          "source_line_start": 1217,
          "source_line_end": 1217
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art3-Para1",
      "text_sha256": "abfa2c8af7faedc7c244d27acf845fd4cf9b79b909bc2fad20974c816b3cceac"
    },
    {
      "id": "article-Art4-Para1",
      "type": "article_paragraph",
      "article_number": 4,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT asset management policy",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 3"
      ],
      "text": "As part of the ICT security policies, procedures, protocols, and tools referred to in Article 9(2) of Regulation (EU) 2022/2554, financial entities shall develop, document, and implement a policy on management of ICT assets.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art4-Para2__article-Art4-Para1__depends_on",
          "source": "article-Art4-Para2",
          "target": "article-Art4-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art4-Para2 defines the mandatory contents of the ICT asset-management policy that article-Art4-Para1 requires financial entities to establish.",
          "source_canonical_ref": "celex:32024R1774/article-Art4-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art4-Para1"
        },
        {
          "edge_id": "recital-7__article-Art4-Para1__provides_guidance_for",
          "source": "recital-7",
          "target": "article-Art4-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-7 expressly identifies development and implementation of an ICT asset-management policy as necessary for digital operational resilience, explaining the obligation in article-Art4-Para1.",
          "source_canonical_ref": "celex:32024R1774/recital-7",
          "target_canonical_ref": "celex:32024R1774/article-Art4-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "As part of the ICT security policies, procedures, protocols, and tools referred to in Article 9(2) of Regulation (EU) 2022/2554, financial entities shall develop, document, and implement a policy on management of ICT assets.",
          "source_line_start": 1279,
          "source_line_end": 1279
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art4-Para1",
      "text_sha256": "fc42d037a8cc3d61905e670e1923a7f6ebd2115e23a43c65ce281d4640183839"
    },
    {
      "id": "article-Art4-Para2",
      "type": "article_paragraph",
      "article_number": 4,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT asset management policy",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "prescribe the monitoring and management of the lifecycle of ICT assets identified and classified in accordance with Article 8(1) of Regulation (EU) 2022/2554;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 1289,
          "source_line_end": 1292
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "prescribe that the financial entity keeps records of all of the following:",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 1303,
          "source_line_end": 1306
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "the unique identifier of each ICT asset;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(i)",
          "source_line_start": 1313,
          "source_line_end": 1316
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "information on the location, either physical or logical, of all ICT assets;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(ii)",
          "source_line_start": 1327,
          "source_line_end": 1330
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "the classification of all ICT assets, as referred to in Article 8(1) of Regulation (EU) 2022/2254;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(iii)",
          "source_line_start": 1341,
          "source_line_end": 1344
        },
        {
          "type": "subpoint",
          "marker": "(iv)",
          "text": "the identity of ICT asset owners;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(iv)",
          "source_line_start": 1355,
          "source_line_end": 1358
        },
        {
          "type": "subpoint",
          "marker": "(v)",
          "text": "the business functions or services supported by the ICT asset;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(v)",
          "source_line_start": 1369,
          "source_line_end": 1372
        },
        {
          "type": "subpoint",
          "marker": "(vi)",
          "text": "the ICT business continuity requirements, including recovery time objectives and recovery point objectives;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(vi)",
          "source_line_start": 1383,
          "source_line_end": 1386
        },
        {
          "type": "subpoint",
          "marker": "(vii)",
          "text": "whether the ICT asset can be or is exposed to external networks, including the internet;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(vii)",
          "source_line_start": 1397,
          "source_line_end": 1400
        },
        {
          "type": "subpoint",
          "marker": "(viii)",
          "text": "the links and interdependencies among ICT assets and the business functions using each ICT asset;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(viii)",
          "source_line_start": 1411,
          "source_line_end": 1414
        },
        {
          "type": "subpoint",
          "marker": "(ix)",
          "text": "where applicable, for all ICT assets, the end dates of the ICT third-party service provider’s regular, extended, and custom support services after which those ICT assets are no longer supported by their supplier or by an ICT third-party service provider;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(ix)",
          "source_line_start": 1425,
          "source_line_end": 1428
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "for financial entities other than microenterprises, prescribe that those financial entities keep records of the information necessary to perform a specific ICT risk assessment on all legacy ICT systems referred to in Article 8(7) of Regulation (EU) 2022/2554.",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 1443,
          "source_line_end": 1446
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 3"
      ],
      "text": "The policy on management of ICT assets referred to in paragraph 1 shall: (a) prescribe the monitoring and management of the lifecycle of ICT assets identified and classified in accordance with Article 8(1) of Regulation (EU) 2022/2554; (b) prescribe that the financial entity keeps records of all of the following: (i) the unique identifier of each ICT asset; (ii) information on the location, either physical or logical, of all ICT assets; (iii) the classification of all ICT assets, as referred to in Article 8(1) of Regulation (EU) 2022/2254; (iv) the identity of ICT asset owners; (v) the business functions or services supported by the ICT asset; (vi) the ICT business continuity requirements, including recovery time objectives and recovery point objectives; (vii) whether the ICT asset can be or is exposed to external networks, including the internet; (viii) the links and interdependencies among ICT assets and the business functions using each ICT asset; (ix) where applicable, for all ICT assets, the end dates of the ICT third-party service provider’s regular, extended, and custom support services after which those ICT assets are no longer supported by their supplier or by an ICT third-party service provider; (c) for financial entities other than microenterprises, prescribe that those financial entities keep records of the information necessary to perform a specific ICT risk assessment on all legacy ICT systems referred to in Article 8(7) of Regulation (EU) 2022/2554.",
      "outbound_relations": [
        {
          "edge_id": "article-Art4-Para2__article-Art4-Para1__depends_on",
          "source": "article-Art4-Para2",
          "target": "article-Art4-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art4-Para2 defines the mandatory contents of the ICT asset-management policy that article-Art4-Para1 requires financial entities to establish.",
          "source_canonical_ref": "celex:32024R1774/article-Art4-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art4-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-7__article-Art4-Para2__provides_guidance_for",
          "source": "recital-7",
          "target": "article-Art4-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-7 explains lifecycle monitoring as the purpose of ICT asset management, directly guiding the lifecycle-management content of article-Art4-Para2.",
          "source_canonical_ref": "celex:32024R1774/recital-7",
          "target_canonical_ref": "celex:32024R1774/article-Art4-Para2"
        },
        {
          "edge_id": "recital-8__article-Art4-Para2__provides_guidance_for",
          "source": "recital-8",
          "target": "article-Art4-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-8 explains the legacy-system risk purpose of recording and monitoring support end-dates, directly guiding the support-date records in article-Art4-Para2.",
          "source_canonical_ref": "celex:32024R1774/recital-8",
          "target_canonical_ref": "celex:32024R1774/article-Art4-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The policy on management of ICT assets referred to in paragraph 1 shall:",
          "source_line_start": 1282,
          "source_line_end": 1282
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art4-Para2",
      "text_sha256": "574a7e18019f24830980102faf9b242e142ef3e78e76d1df5cb23c78369a32d6"
    },
    {
      "id": "article-Art5-Para1",
      "type": "article_paragraph",
      "article_number": 5,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT asset management procedure",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 3"
      ],
      "text": "Financial entities shall develop, document, and implement a procedure for the management of ICT assets.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art5-Para2__article-Art5-Para1__depends_on",
          "source": "article-Art5-Para2",
          "target": "article-Art5-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art5-Para2 supplies the criticality-assessment criteria for the ICT asset-management procedure created by article-Art5-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art5-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art5-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall develop, document, and implement a procedure for the management of ICT assets.",
          "source_line_start": 1459,
          "source_line_end": 1459
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art5-Para1",
      "text_sha256": "db75b2ef5af1c113c79cfda9f8955117687d290b8ab108b656946f3f38348eb8"
    },
    {
      "id": "article-Art5-Para2",
      "type": "article_paragraph",
      "article_number": 5,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT asset management procedure",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "the ICT risk related to those business functions and their dependencies on the information assets or ICT assets;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 1469,
          "source_line_end": 1472
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "how the loss of confidentiality, integrity, and availability of such information assets and ICT assets would impact the business processes and activities of the financial entities.",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 1483,
          "source_line_end": 1486
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 3"
      ],
      "text": "The procedure for management of ICT assets referred to in paragraph 1 shall specify the criteria to perform the criticality assessment of information assets and ICT assets supporting business functions. That assessment shall take into account: (a) the ICT risk related to those business functions and their dependencies on the information assets or ICT assets; (b) how the loss of confidentiality, integrity, and availability of such information assets and ICT assets would impact the business processes and activities of the financial entities.",
      "outbound_relations": [
        {
          "edge_id": "article-Art5-Para2__article-Art5-Para1__depends_on",
          "source": "article-Art5-Para2",
          "target": "article-Art5-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art5-Para2 supplies the criticality-assessment criteria for the ICT asset-management procedure created by article-Art5-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art5-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art5-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-8__article-Art5-Para2__provides_guidance_for",
          "source": "recital-8",
          "target": "article-Art5-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-8 prioritises business-critical assets by the impact of confidentiality, integrity and availability loss, guiding the criticality assessment criteria in article-Art5-Para2.",
          "source_canonical_ref": "celex:32024R1774/recital-8",
          "target_canonical_ref": "celex:32024R1774/article-Art5-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The procedure for management of ICT assets referred to in paragraph 1 shall specify the criteria to perform the criticality assessment of information assets and ICT assets supporting business functions. That assessment shall take into account:",
          "source_line_start": 1462,
          "source_line_end": 1462
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art5-Para2",
      "text_sha256": "ec522e034aa494daa4b52eda3ba341aed881911c421f919b739a3d627acc3698"
    },
    {
      "id": "article-Art6-Para1",
      "type": "article_paragraph",
      "article_number": 6,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Encryption and cryptographic controls",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 4"
      ],
      "text": "As part of their ICT security policies, procedures, protocols, and tools referred to in Article 9(2) of Regulation (EU) 2022/2554, financial entities shall develop, document, and implement a policy on encryption and cryptographic controls.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art6-Para2__article-Art6-Para1__depends_on",
          "source": "article-Art6-Para2",
          "target": "article-Art6-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art6-Para2 prescribes the design and rules of the encryption and cryptographic-controls policy mandated by article-Art6-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art6-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para1"
        },
        {
          "edge_id": "article-Art6-Para3__article-Art6-Para1__depends_on",
          "source": "article-Art6-Para3",
          "target": "article-Art6-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art6-Para3 adds technique-selection and mitigation criteria to the cryptographic-controls policy established by article-Art6-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art6-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para1"
        },
        {
          "edge_id": "article-Art6-Para4__article-Art6-Para1__depends_on",
          "source": "article-Art6-Para4",
          "target": "article-Art6-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art6-Para4 requires technology-update provisions within the encryption and cryptographic-controls policy mandated by article-Art6-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art6-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para1"
        },
        {
          "edge_id": "article-Art6-Para5__article-Art6-Para1__depends_on",
          "source": "article-Art6-Para5",
          "target": "article-Art6-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art6-Para5 places recording and explanation duties inside the cryptographic-controls policy first required by article-Art6-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art6-Para5",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "As part of their ICT security policies, procedures, protocols, and tools referred to in Article 9(2) of Regulation (EU) 2022/2554, financial entities shall develop, document, and implement a policy on encryption and cryptographic controls.",
          "source_line_start": 1511,
          "source_line_end": 1511
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art6-Para1",
      "text_sha256": "453c2abed8d3e61ea341378a6f9fd8ef3b32a478a973ce995425026643a1528a"
    },
    {
      "id": "article-Art6-Para2",
      "type": "article_paragraph",
      "article_number": 6,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Encryption and cryptographic controls",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "the encryption of data at rest and in transit;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 1521,
          "source_line_end": 1524
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "the encryption of data in use, where necessary;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 1535,
          "source_line_end": 1538
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "the encryption of internal network connections and traffic with external parties;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 1549,
          "source_line_end": 1552
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "the cryptographic key management referred to in Article 7, laying down rules on the correct use, protection, and lifecycle of cryptographic keys.",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 1563,
          "source_line_end": 1566
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 4"
      ],
      "text": "Financial entities shall design the policy on encryption and cryptographic controls referred to in paragraph 1 on the basis of the results of an approved data classification and ICT risk assessment. That policy shall contain rules for all of the following: (a) the encryption of data at rest and in transit; (b) the encryption of data in use, where necessary; (c) the encryption of internal network connections and traffic with external parties; (d) the cryptographic key management referred to in Article 7, laying down rules on the correct use, protection, and lifecycle of cryptographic keys. For the purposes of point (b), where encryption of data in use is not possible, financial entities shall process data in use in a separated and protected environment, or take equivalent measures to ensure the confidentiality, integrity, authenticity, and availability of data.",
      "outbound_relations": [
        {
          "edge_id": "article-Art6-Para2__article-Art6-Para1__depends_on",
          "source": "article-Art6-Para2",
          "target": "article-Art6-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art6-Para2 prescribes the design and rules of the encryption and cryptographic-controls policy mandated by article-Art6-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art6-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para1"
        },
        {
          "edge_id": "article-Art6-Para2__article-Art7-Para1__references",
          "source": "article-Art6-Para2",
          "target": "article-Art7-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art6-Para2 refers cryptographic-key management to Article 7, and article-Art7-Para1 is the narrow paragraph specifying whole-lifecycle key management.",
          "source_canonical_ref": "celex:32024R1774/article-Art6-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art7-Para1"
        },
        {
          "edge_id": "article-Art6-Para2__article-Art7-Para2__references",
          "source": "article-Art6-Para2",
          "target": "article-Art7-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art6-Para2's express Article 7 reference includes protection of cryptographic keys, which article-Art7-Para2 specifically regulates throughout the key lifecycle.",
          "source_canonical_ref": "celex:32024R1774/article-Art6-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art7-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art13-Para1__article-Art6-Para2__references",
          "source": "article-Art13-Para1",
          "target": "article-Art6-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art13-Para1 expressly requires network-connection encryption to take account of the encryption of network connections governed by article-Art6-Para2.",
          "source_canonical_ref": "celex:32024R1774/article-Art13-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para2"
        },
        {
          "edge_id": "article-Art7-Para1__article-Art6-Para2__depends_on",
          "source": "article-Art7-Para1",
          "target": "article-Art6-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art7-Para1 expressly makes its whole-lifecycle key requirements part of the cryptographic-key management policy specified in article-Art6-Para2 point (d).",
          "source_canonical_ref": "celex:32024R1774/article-Art7-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para2"
        },
        {
          "edge_id": "recital-9__article-Art6-Para2__concretizes",
          "source": "recital-9",
          "target": "article-Art6-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-9 concretizes article-Art6-Para2 by linking the encryption policy to approved data classification and ICT risk assessment, distinguishing data at rest, in transit and in use, and explaining the equivalent safeguards required when in-use encryption is infeasible.",
          "source_canonical_ref": "celex:32024R1774/recital-9",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall design the policy on encryption and cryptographic controls referred to in paragraph 1 on the basis of the results of an approved data classification and ICT risk assessment. That policy shall contain rules for all of the following:",
          "source_line_start": 1514,
          "source_line_end": 1514
        },
        {
          "sequence": 2,
          "text": "For the purposes of point (b), where encryption of data in use is not possible, financial entities shall process data in use in a separated and protected environment, or take equivalent measures to ensure the confidentiality, integrity, authenticity, and availability of data.",
          "source_line_start": 1571,
          "source_line_end": 1571
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art6-Para2",
      "text_sha256": "004428d9ee2c854d80d5f8cb2df2c6a1ba03f3325bb1d23682d01a41c1c9584d"
    },
    {
      "id": "article-Art6-Para3",
      "type": "article_paragraph",
      "article_number": 6,
      "paragraph_number": "3",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Encryption and cryptographic controls",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 4"
      ],
      "text": "Financial entities shall include in the policy on encryption and cryptographic controls referred to in paragraph 1 criteria for the selection of cryptographic techniques and use practices, taking into account leading practices, and standards as defined in Article 2, point (1), of Regulation (EU) No 1025/2012, and the classification of relevant ICT assets established in accordance with Article 8(1) of Regulation (EU) 2022/2554. Financial entities that are not able to adhere to the leading practices or standards, or to use the most reliable techniques, shall adopt mitigation and monitoring measures that ensure resilience against cyber threats.",
      "outbound_relations": [
        {
          "edge_id": "article-Art6-Para3__article-Art6-Para1__depends_on",
          "source": "article-Art6-Para3",
          "target": "article-Art6-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art6-Para3 adds technique-selection and mitigation criteria to the cryptographic-controls policy established by article-Art6-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art6-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art6-Para5__article-Art6-Para3__depends_on",
          "source": "article-Art6-Para5",
          "target": "article-Art6-Para3",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art6-Para5 expressly requires records for mitigation and monitoring measures adopted under article-Art6-Para3 when leading practices or reliable techniques cannot be followed.",
          "source_canonical_ref": "celex:32024R1774/article-Art6-Para5",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para3"
        },
        {
          "edge_id": "recital-9__article-Art6-Para3__provides_guidance_for",
          "source": "recital-9",
          "target": "article-Art6-Para3",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-9 provides guidance for article-Art6-Para3 by explaining why cryptographic techniques must track leading practices and standards and why a flexible combination of risk mitigation and monitoring is needed when the most reliable techniques cannot be used.",
          "source_canonical_ref": "celex:32024R1774/recital-9",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para3"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall include in the policy on encryption and cryptographic controls referred to in paragraph 1 criteria for the selection of cryptographic techniques and use practices, taking into account leading practices, and standards as defined in Article 2, point (1), of Regulation (EU) No 1025/2012, and the classification of relevant ICT assets established in accordance with Article 8(1) of Regulation (EU) 2022/2554. Financial entities that are not able to adhere to the leading practices or standards, or to use the most reliable techniques, shall adopt mitigation and monitoring measures that ensure resilience against cyber threats.",
          "source_line_start": 1574,
          "source_line_end": 1574
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art6-Para3",
      "text_sha256": "f9a8d8969a61542c78f687a7ed16aafc2b59b89f3693a07dbc4af26268f89f96"
    },
    {
      "id": "article-Art6-Para4",
      "type": "article_paragraph",
      "article_number": 6,
      "paragraph_number": "4",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Encryption and cryptographic controls",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 4"
      ],
      "text": "Financial entities shall include in the policy on encryption and cryptographic controls referred to in paragraph 1 provisions for updating or changing, where necessary, the cryptographic technology on the basis of developments in cryptanalysis. Those updates or changes shall ensure that the cryptographic technology remains resilient against cyber threats, as required by Article 10(2), point (a). Financial entities that are not able to update or change the cryptographic technology shall adopt mitigation and monitoring measures that ensure resilience against cyber threats.",
      "outbound_relations": [
        {
          "edge_id": "article-Art6-Para4__article-Art10-Para2__references",
          "source": "article-Art6-Para4",
          "target": "article-Art10-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art6-Para4 expressly invokes article-Art10-Para2 point (a) when requiring awareness-driven updates that keep cryptographic technology resilient to cyber threats.",
          "source_canonical_ref": "celex:32024R1774/article-Art6-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art10-Para2"
        },
        {
          "edge_id": "article-Art6-Para4__article-Art6-Para1__depends_on",
          "source": "article-Art6-Para4",
          "target": "article-Art6-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art6-Para4 requires technology-update provisions within the encryption and cryptographic-controls policy mandated by article-Art6-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art6-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art6-Para5__article-Art6-Para4__depends_on",
          "source": "article-Art6-Para5",
          "target": "article-Art6-Para4",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art6-Para5 expressly requires a reasoned record of the mitigation and monitoring measures adopted under article-Art6-Para4 when cryptographic technology cannot be updated.",
          "source_canonical_ref": "celex:32024R1774/article-Art6-Para5",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para4"
        },
        {
          "edge_id": "recital-9__article-Art6-Para4__provides_guidance_for",
          "source": "recital-9",
          "target": "article-Art6-Para4",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-9 provides guidance for article-Art6-Para4 by identifying rapid cryptanalysis developments, including quantum-related threats, as the reason to update cryptographic technology or adopt compensating mitigation and monitoring measures.",
          "source_canonical_ref": "celex:32024R1774/recital-9",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para4"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall include in the policy on encryption and cryptographic controls referred to in paragraph 1 provisions for updating or changing, where necessary, the cryptographic technology on the basis of developments in cryptanalysis. Those updates or changes shall ensure that the cryptographic technology remains resilient against cyber threats, as required by Article 10(2), point (a). Financial entities that are not able to update or change the cryptographic technology shall adopt mitigation and monitoring measures that ensure resilience against cyber threats.",
          "source_line_start": 1577,
          "source_line_end": 1577
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art6-Para4",
      "text_sha256": "e4f4ed84b5316e89cf13cd44dfd09611f7e2380089f2feaafb83ab7413739280"
    },
    {
      "id": "article-Art6-Para5",
      "type": "article_paragraph",
      "article_number": 6,
      "paragraph_number": "5",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Encryption and cryptographic controls",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 4"
      ],
      "text": "Financial entities shall include in the policy on encryption and cryptographic controls referred to in paragraph 1 a requirement to record the adoption of mitigation and monitoring measures adopted in accordance with paragraphs 3 and 4 and to provide a reasoned explanation for doing so.",
      "outbound_relations": [
        {
          "edge_id": "article-Art6-Para5__article-Art6-Para1__depends_on",
          "source": "article-Art6-Para5",
          "target": "article-Art6-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art6-Para5 places recording and explanation duties inside the cryptographic-controls policy first required by article-Art6-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art6-Para5",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para1"
        },
        {
          "edge_id": "article-Art6-Para5__article-Art6-Para3__depends_on",
          "source": "article-Art6-Para5",
          "target": "article-Art6-Para3",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art6-Para5 expressly requires records for mitigation and monitoring measures adopted under article-Art6-Para3 when leading practices or reliable techniques cannot be followed.",
          "source_canonical_ref": "celex:32024R1774/article-Art6-Para5",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para3"
        },
        {
          "edge_id": "article-Art6-Para5__article-Art6-Para4__depends_on",
          "source": "article-Art6-Para5",
          "target": "article-Art6-Para4",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art6-Para5 expressly requires a reasoned record of the mitigation and monitoring measures adopted under article-Art6-Para4 when cryptographic technology cannot be updated.",
          "source_canonical_ref": "celex:32024R1774/article-Art6-Para5",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para4"
        }
      ],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall include in the policy on encryption and cryptographic controls referred to in paragraph 1 a requirement to record the adoption of mitigation and monitoring measures adopted in accordance with paragraphs 3 and 4 and to provide a reasoned explanation for doing so.",
          "source_line_start": 1580,
          "source_line_end": 1580
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art6-Para5",
      "text_sha256": "977390b6873faaa9974fc46b393e35f5cbb0c5b3c78c88313132220fc45a0f4b"
    },
    {
      "id": "article-Art7-Para1",
      "type": "article_paragraph",
      "article_number": 7,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Cryptographic key management",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 4"
      ],
      "text": "Financial entities shall include in the cryptographic key management policy referred to in Article 6(2), point (d), requirements for managing cryptographic keys through their whole lifecycle, including generating, renewing, storing, backing up, archiving, retrieving, transmitting, retiring, revoking, and destroying those cryptographic keys.",
      "outbound_relations": [
        {
          "edge_id": "article-Art7-Para1__article-Art6-Para2__depends_on",
          "source": "article-Art7-Para1",
          "target": "article-Art6-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art7-Para1 expressly makes its whole-lifecycle key requirements part of the cryptographic-key management policy specified in article-Art6-Para2 point (d).",
          "source_canonical_ref": "celex:32024R1774/article-Art7-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art6-Para2__article-Art7-Para1__references",
          "source": "article-Art6-Para2",
          "target": "article-Art7-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art6-Para2 refers cryptographic-key management to Article 7, and article-Art7-Para1 is the narrow paragraph specifying whole-lifecycle key management.",
          "source_canonical_ref": "celex:32024R1774/article-Art6-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art7-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall include in the cryptographic key management policy referred to in Article 6(2), point (d), requirements for managing cryptographic keys through their whole lifecycle, including generating, renewing, storing, backing up, archiving, retrieving, transmitting, retiring, revoking, and destroying those cryptographic keys.",
          "source_line_start": 1589,
          "source_line_end": 1589
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art7-Para1",
      "text_sha256": "8140cdf663bc07abea985c12c5d10b79c34d21053afe5b669cc5843ea35e9288"
    },
    {
      "id": "article-Art7-Para2",
      "type": "article_paragraph",
      "article_number": 7,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Cryptographic key management",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 4"
      ],
      "text": "Financial entities shall identify and implement controls to protect cryptographic keys through their whole lifecycle against loss, unauthorised access, disclosure, and modification. Financial entities shall design those controls on the basis of the results of the approved data classification and the ICT risk assessment.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art6-Para2__article-Art7-Para2__references",
          "source": "article-Art6-Para2",
          "target": "article-Art7-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art6-Para2's express Article 7 reference includes protection of cryptographic keys, which article-Art7-Para2 specifically regulates throughout the key lifecycle.",
          "source_canonical_ref": "celex:32024R1774/article-Art6-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art7-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall identify and implement controls to protect cryptographic keys through their whole lifecycle against loss, unauthorised access, disclosure, and modification. Financial entities shall design those controls on the basis of the results of the approved data classification and the ICT risk assessment.",
          "source_line_start": 1592,
          "source_line_end": 1592
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art7-Para2",
      "text_sha256": "5a97d1c57be14e03b4e5aaa9214e0cac74f8e80755ea688abc734ef15addf443"
    },
    {
      "id": "article-Art7-Para3",
      "type": "article_paragraph",
      "article_number": 7,
      "paragraph_number": "3",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Cryptographic key management",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 4"
      ],
      "text": "Financial entities shall develop and implement methods to replace the cryptographic keys in the case of loss, or where those keys are compromised or damaged.",
      "outbound_relations": [],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall develop and implement methods to replace the cryptographic keys in the case of loss, or where those keys are compromised or damaged.",
          "source_line_start": 1595,
          "source_line_end": 1595
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art7-Para3",
      "text_sha256": "6e98a6aeb3125aa36a8ab9b1389c1bd2f9d4397d6445096a2e3d4985fb2448ba"
    },
    {
      "id": "article-Art7-Para4",
      "type": "article_paragraph",
      "article_number": 7,
      "paragraph_number": "4",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Cryptographic key management",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 4"
      ],
      "text": "Financial entities shall create and maintain a register for all certificates and certificate-storing devices for at least ICT assets supporting critical or important functions. Financial entities shall keep that register up to date.",
      "outbound_relations": [],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall create and maintain a register for all certificates and certificate-storing devices for at least ICT assets supporting critical or important functions. Financial entities shall keep that register up to date.",
          "source_line_start": 1598,
          "source_line_end": 1598
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art7-Para4",
      "text_sha256": "4aa85b0a81b7f4d83eab98e6df5f7bf7561480a5d5da2f4dd531a9b98254a728"
    },
    {
      "id": "article-Art7-Para5",
      "type": "article_paragraph",
      "article_number": 7,
      "paragraph_number": "5",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Cryptographic key management",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 4"
      ],
      "text": "Financial entities shall ensure the prompt renewal of certificates in advance of their expiration.",
      "outbound_relations": [],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall ensure the prompt renewal of certificates in advance of their expiration.",
          "source_line_start": 1601,
          "source_line_end": 1601
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art7-Para5",
      "text_sha256": "077759c5f64a089626c76b3a7ec3e0fa0487ecff010900c628af52267af7bad2"
    },
    {
      "id": "article-Art8-Para1",
      "type": "article_paragraph",
      "article_number": 8,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Policies and procedures for ICT operations",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 5"
      ],
      "text": "As part of the ICT security policies, procedures, protocols, and tools referred to in Article 9(2) of Regulation (EU) 2022/2554, financial entities shall develop, document, and implement policies and procedures to manage the ICT operations. Those policies and procedures shall specify how financial entities operate, monitor, control, and restore their ICT assets, including the documentation of ICT operations.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art8-Para2__article-Art8-Para1__depends_on",
          "source": "article-Art8-Para2",
          "target": "article-Art8-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art8-Para2 prescribes the required operational, monitoring and error-handling contents of the ICT-operations policies created by article-Art8-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art8-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art8-Para1"
        },
        {
          "edge_id": "recital-7__article-Art8-Para1__provides_guidance_for",
          "source": "recital-7",
          "target": "article-Art8-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-7 describes effective and smooth day-to-day ICT operation as the objective of the operational policies and procedures required by article-Art8-Para1.",
          "source_canonical_ref": "celex:32024R1774/recital-7",
          "target_canonical_ref": "celex:32024R1774/article-Art8-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "As part of the ICT security policies, procedures, protocols, and tools referred to in Article 9(2) of Regulation (EU) 2022/2554, financial entities shall develop, document, and implement policies and procedures to manage the ICT operations. Those policies and procedures shall specify how financial entities operate, monitor, control, and restore their ICT assets, including the documentation of ICT operations.",
          "source_line_start": 1622,
          "source_line_end": 1622
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art8-Para1",
      "text_sha256": "af742524194def427c71d3df3dd89df8598306adaa6e734e30a70413e3b2b71a"
    },
    {
      "id": "article-Art8-Para2",
      "type": "article_paragraph",
      "article_number": 8,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Policies and procedures for ICT operations",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "an ICT assets description, including all of the following:",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 1632,
          "source_line_end": 1635
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "requirements regarding secure installation, maintenance, configuration, and deinstallation of an ICT system;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(i)",
          "source_line_start": 1642,
          "source_line_end": 1645
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "requirements regarding the management of information assets used by ICT assets, including their processing and handling, both automated and manual;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(ii)",
          "source_line_start": 1656,
          "source_line_end": 1659
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "requirements regarding the identification and control of legacy ICT systems;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(iii)",
          "source_line_start": 1670,
          "source_line_end": 1673
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "controls and monitoring of ICT systems, including all of the following:",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 1688,
          "source_line_end": 1691
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "backup and restore requirements of ICT systems;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(i)",
          "source_line_start": 1698,
          "source_line_end": 1701
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "scheduling requirements, taking into consideration interdependencies among the ICT systems;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(ii)",
          "source_line_start": 1712,
          "source_line_end": 1715
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "protocols for audit-trail and system log information;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(iii)",
          "source_line_start": 1726,
          "source_line_end": 1729
        },
        {
          "type": "subpoint",
          "marker": "(iv)",
          "text": "requirements to ensure that the performance of internal audit and other testing minimises disruptions to business operations;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(iv)",
          "source_line_start": 1740,
          "source_line_end": 1743
        },
        {
          "type": "subpoint",
          "marker": "(v)",
          "text": "requirements on the separation of ICT production environments from the development, testing, and other non-production environments;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(v)",
          "source_line_start": 1754,
          "source_line_end": 1757
        },
        {
          "type": "subpoint",
          "marker": "(vi)",
          "text": "requirements to conduct the development and testing in environments which are separated from the production environment;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(vi)",
          "source_line_start": 1768,
          "source_line_end": 1771
        },
        {
          "type": "subpoint",
          "marker": "(vii)",
          "text": "requirements to conduct the development and testing in production environments;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(vii)",
          "source_line_start": 1782,
          "source_line_end": 1785
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "error handling concerning ICT systems, including all of the following:",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 1800,
          "source_line_end": 1803
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "procedures and protocols for handling errors;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(i)",
          "source_line_start": 1810,
          "source_line_end": 1813
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "support and escalation contacts, including external support contacts in case of unexpected operational or technical issues;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(ii)",
          "source_line_start": 1824,
          "source_line_end": 1827
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "ICT system restart, rollback, and recovery procedures for use in the event of ICT system disruption.",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(iii)",
          "source_line_start": 1838,
          "source_line_end": 1841
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 5"
      ],
      "text": "The policies and procedures for ICT operations referred to in paragraph 1 shall contain all of the following: (a) an ICT assets description, including all of the following: (i) requirements regarding secure installation, maintenance, configuration, and deinstallation of an ICT system; (ii) requirements regarding the management of information assets used by ICT assets, including their processing and handling, both automated and manual; (iii) requirements regarding the identification and control of legacy ICT systems; (b) controls and monitoring of ICT systems, including all of the following: (i) backup and restore requirements of ICT systems; (ii) scheduling requirements, taking into consideration interdependencies among the ICT systems; (iii) protocols for audit-trail and system log information; (iv) requirements to ensure that the performance of internal audit and other testing minimises disruptions to business operations; (v) requirements on the separation of ICT production environments from the development, testing, and other non-production environments; (vi) requirements to conduct the development and testing in environments which are separated from the production environment; (vii) requirements to conduct the development and testing in production environments; (c) error handling concerning ICT systems, including all of the following: (i) procedures and protocols for handling errors; (ii) support and escalation contacts, including external support contacts in case of unexpected operational or technical issues; (iii) ICT system restart, rollback, and recovery procedures for use in the event of ICT system disruption. For the purposes of point (b)(v), the separation shall consider all of the components of the environment, including accounts, data or connections, as required by Article 13, first subparagraph, point (a). For the purposes of point (b)(vii), the policies and procedures referred to in paragraph 1 shall provide that the instances in which testing is performed in a production environment are clearly identified, reasoned, are for limited periods of time, and are approved by the relevant function in accordance with Article 16(6). Financial entities shall ensure the availability, confidentiality, integrity, and authenticity of ICT systems and production data during development and test activities in the production environment.",
      "outbound_relations": [
        {
          "edge_id": "article-Art8-Para2__article-Art13-Para1__references",
          "source": "article-Art8-Para2",
          "target": "article-Art13-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art8-Para2 expressly applies the segregation requirement in article-Art13-Para1 point (a) to all components of separated production and non-production environments.",
          "source_canonical_ref": "celex:32024R1774/article-Art8-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art13-Para1"
        },
        {
          "edge_id": "article-Art8-Para2__article-Art16-Para6__references",
          "source": "article-Art8-Para2",
          "target": "article-Art16-Para6",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art8-Para2 expressly uses article-Art16-Para6 as the approval and limited-duration standard for testing in production environments.",
          "source_canonical_ref": "celex:32024R1774/article-Art8-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para6"
        },
        {
          "edge_id": "article-Art8-Para2__article-Art8-Para1__depends_on",
          "source": "article-Art8-Para2",
          "target": "article-Art8-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art8-Para2 prescribes the required operational, monitoring and error-handling contents of the ICT-operations policies created by article-Art8-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art8-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art8-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art10-Para4__article-Art8-Para2__references",
          "source": "article-Art10-Para4",
          "target": "article-Art8-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art10-Para4 expressly refers patch and update testing and deployment to the production and non-production testing controls in article-Art8-Para2 points (b)(v) to (vii).",
          "source_canonical_ref": "celex:32024R1774/article-Art10-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art8-Para2"
        },
        {
          "edge_id": "article-Art16-Para2__article-Art8-Para2__references",
          "source": "article-Art16-Para2",
          "target": "article-Art8-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art16-Para2 expressly requires pre-use and post-maintenance ICT-system testing to follow the production-separation and testing controls in article-Art8-Para2, point (b)(v) to (vii).",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art8-Para2"
        },
        {
          "edge_id": "article-Art16-Para3__article-Art8-Para2__references",
          "source": "article-Art16-Para3",
          "target": "article-Art8-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art16-Para3 expressly subjects security testing for internet-exposed systems and applications to the environment-separation and production-testing requirements in article-Art8-Para2, point (b)(v) to (vii).",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art8-Para2"
        },
        {
          "edge_id": "article-Art16-Para4__article-Art8-Para2__references",
          "source": "article-Art16-Para4",
          "target": "article-Art8-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art16-Para4 expressly subjects software-package security testing to the environment-separation and production-testing requirements in article-Art8-Para2, point (b)(v) to (vii).",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art8-Para2"
        },
        {
          "edge_id": "recital-10__article-Art8-Para2__provides_guidance_for",
          "source": "recital-10",
          "target": "article-Art8-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-10 provides guidance for article-Art8-Para2 by explaining the security purpose of separating production from development, testing and other non-production environments and the exceptional justification and approval required for testing in production.",
          "source_canonical_ref": "celex:32024R1774/recital-10",
          "target_canonical_ref": "celex:32024R1774/article-Art8-Para2"
        },
        {
          "edge_id": "recital-8__article-Art8-Para2__provides_guidance_for",
          "source": "recital-8",
          "target": "article-Art8-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-8 identifies support expiry monitoring as a means to manage legacy-system risk, providing application guidance for the legacy-system control required by article-Art8-Para2.",
          "source_canonical_ref": "celex:32024R1774/recital-8",
          "target_canonical_ref": "celex:32024R1774/article-Art8-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The policies and procedures for ICT operations referred to in paragraph 1 shall contain all of the following:",
          "source_line_start": 1625,
          "source_line_end": 1625
        },
        {
          "sequence": 2,
          "text": "For the purposes of point (b)(v), the separation shall consider all of the components of the environment, including accounts, data or connections, as required by Article 13, first subparagraph, point (a).",
          "source_line_start": 1850,
          "source_line_end": 1850
        },
        {
          "sequence": 3,
          "text": "For the purposes of point (b)(vii), the policies and procedures referred to in paragraph 1 shall provide that the instances in which testing is performed in a production environment are clearly identified, reasoned, are for limited periods of time, and are approved by the relevant function in accordance with Article 16(6). Financial entities shall ensure the availability, confidentiality, integrity, and authenticity of ICT systems and production data during development and test activities in the production environment.",
          "source_line_start": 1851,
          "source_line_end": 1851
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art8-Para2",
      "text_sha256": "6f870132e78b73fa7f1c4c58b62a14d7a9f42279f77cb27c4d20a8b3c3924f02"
    },
    {
      "id": "article-Art9-Para1",
      "type": "article_paragraph",
      "article_number": 9,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Capacity and performance management",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "the identification of capacity requirements of their ICT systems;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 1867,
          "source_line_end": 1870
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "the application of resource optimisation;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 1881,
          "source_line_end": 1884
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "the monitoring procedures for maintaining and improving:",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 1895,
          "source_line_end": 1898
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "the availability of data and ICT systems;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(i)",
          "source_line_start": 1905,
          "source_line_end": 1908
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "the efficiency of ICT systems;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(ii)",
          "source_line_start": 1919,
          "source_line_end": 1922
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "the prevention of ICT capacity shortages.",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(iii)",
          "source_line_start": 1933,
          "source_line_end": 1936
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 5"
      ],
      "text": "As part of the ICT security policies, procedures, protocols, and tools referred to in Article 9(2) of Regulation (EU) 2022/2554, financial entities shall develop, document, and implement capacity and performance management procedures for the following: (a) the identification of capacity requirements of their ICT systems; (b) the application of resource optimisation; (c) the monitoring procedures for maintaining and improving: (i) the availability of data and ICT systems; (ii) the efficiency of ICT systems; (iii) the prevention of ICT capacity shortages.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art9-Para2__article-Art9-Para1__depends_on",
          "source": "article-Art9-Para2",
          "target": "article-Art9-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art9-Para2 adds system-specific proportional measures to the capacity and performance management procedures required by article-Art9-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art9-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art9-Para1"
        },
        {
          "edge_id": "recital-2__article-Art9-Para1__provides_guidance_for",
          "source": "recital-2",
          "target": "article-Art9-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-2 expressly identifies capacity and performance management as a technical procedure domain, providing the rationale for the procedure mandated by article-Art9-Para1.",
          "source_canonical_ref": "celex:32024R1774/recital-2",
          "target_canonical_ref": "celex:32024R1774/article-Art9-Para1"
        },
        {
          "edge_id": "recital-7__article-Art9-Para1__provides_guidance_for",
          "source": "recital-7",
          "target": "article-Art9-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-7 explains that capacity and performance management should optimise ICT operations and meet business and security objectives, guiding article-Art9-Para1.",
          "source_canonical_ref": "celex:32024R1774/recital-7",
          "target_canonical_ref": "celex:32024R1774/article-Art9-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "As part of the ICT security policies, procedures, protocols, and tools referred to in Article 9(2) of Regulation (EU) 2022/2554, financial entities shall develop, document, and implement capacity and performance management procedures for the following:",
          "source_line_start": 1860,
          "source_line_end": 1860
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art9-Para1",
      "text_sha256": "df1230c74ca1d7336404d617d934a75ad02614819e74f77bfa42c5abda0cd9da"
    },
    {
      "id": "article-Art9-Para2",
      "type": "article_paragraph",
      "article_number": 9,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Capacity and performance management",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 5"
      ],
      "text": "The capacity and performance management procedures referred to in paragraph 1 shall ensure that financial entities take measures that are appropriate to cater for the specificities of ICT systems with long or complex procurement or approval processes or ICT systems that are resource-intensive.",
      "outbound_relations": [
        {
          "edge_id": "article-Art9-Para2__article-Art9-Para1__depends_on",
          "source": "article-Art9-Para2",
          "target": "article-Art9-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art9-Para2 adds system-specific proportional measures to the capacity and performance management procedures required by article-Art9-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art9-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art9-Para1"
        }
      ],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The capacity and performance management procedures referred to in paragraph 1 shall ensure that financial entities take measures that are appropriate to cater for the specificities of ICT systems with long or complex procurement or approval processes or ICT systems that are resource-intensive.",
          "source_line_start": 1947,
          "source_line_end": 1947
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art9-Para2",
      "text_sha256": "0659d3dbfada2af1efbc0fc68cd204dfcf281aaceb77c3b9dd96a6e8ff6e1f29"
    },
    {
      "id": "article-Art10-Para1",
      "type": "article_paragraph",
      "article_number": 10,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Vulnerability and patch management",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 5"
      ],
      "text": "As part of the ICT security policies, procedures, protocols, and tools referred to in Article 9(2) of Regulation (EU) 2022/2554, financial entities shall develop, document, and implement vulnerability management procedures.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art10-Para2__article-Art10-Para1__depends_on",
          "source": "article-Art10-Para2",
          "target": "article-Art10-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art10-Para2 enumerates the scanning, third-party, remediation and recording controls for the vulnerability-management procedures mandated by article-Art10-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art10-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art10-Para1"
        },
        {
          "edge_id": "recital-2__article-Art10-Para1__provides_guidance_for",
          "source": "recital-2",
          "target": "article-Art10-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-2 expressly lists vulnerability management among the technical implementation procedures that article-Art10-Para1 requires financial entities to establish.",
          "source_canonical_ref": "celex:32024R1774/recital-2",
          "target_canonical_ref": "celex:32024R1774/article-Art10-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "As part of the ICT security policies, procedures, protocols, and tools referred to in Article 9(2) of Regulation (EU) 2022/2554, financial entities shall develop, document, and implement vulnerability management procedures.",
          "source_line_start": 1956,
          "source_line_end": 1956
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art10-Para1",
      "text_sha256": "193319c7e67f6246fdf8da71cae0faaf4f4e8fa55f07bfda109854a4eff16be8"
    },
    {
      "id": "article-Art10-Para2",
      "type": "article_paragraph",
      "article_number": 10,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Vulnerability and patch management",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "identify and update relevant and trustworthy information resources to build and maintain awareness about vulnerabilities;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 1966,
          "source_line_end": 1969
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "ensure the performance of automated vulnerability scanning and assessments on ICT assets, whereby the frequency and scope of those activities shall be commensurate to the classification established in accordance with Article 8(1) of Regulation (EU) 2022/2554 and the overall risk profile of the ICT asset;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 1980,
          "source_line_end": 1983
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "verify whether:",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 1994,
          "source_line_end": 1997
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "ICT third-party service providers handle vulnerabilities related to the ICT services provided to the financial entity;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(i)",
          "source_line_start": 2004,
          "source_line_end": 2007
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "whether those service providers report to the financial entity at least the critical vulnerabilities and statistics and trends in a timely manner;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(ii)",
          "source_line_start": 2018,
          "source_line_end": 2021
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "track the usage of:",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 2036,
          "source_line_end": 2039
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "third-party libraries, including open-source libraries, used by ICT services supporting critical or important functions;",
          "depth": 2,
          "parent_marker": "(d)",
          "path": "(d)(i)",
          "source_line_start": 2046,
          "source_line_end": 2049
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "ICT services developed by the financial entity itself or specifically customised or developed for the financial entity by an ICT third-party service provider;",
          "depth": 2,
          "parent_marker": "(d)",
          "path": "(d)(ii)",
          "source_line_start": 2060,
          "source_line_end": 2063
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "establish procedures for the responsible disclosure of vulnerabilities to clients, counterparties, and to the public;",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 2078,
          "source_line_end": 2081
        },
        {
          "type": "point",
          "marker": "(f)",
          "text": "prioritise the deployment of patches and other mitigation measures to address the vulnerabilities identified;",
          "depth": 1,
          "parent_marker": null,
          "path": "(f)",
          "source_line_start": 2092,
          "source_line_end": 2095
        },
        {
          "type": "point",
          "marker": "(g)",
          "text": "monitor and verify the remediation of vulnerabilities;",
          "depth": 1,
          "parent_marker": null,
          "path": "(g)",
          "source_line_start": 2106,
          "source_line_end": 2109
        },
        {
          "type": "point",
          "marker": "(h)",
          "text": "require the recording of any detected vulnerabilities affecting ICT systems and the monitoring of their resolution.",
          "depth": 1,
          "parent_marker": null,
          "path": "(h)",
          "source_line_start": 2120,
          "source_line_end": 2123
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 5"
      ],
      "text": "The vulnerability management procedures referred to in paragraph 1 shall: (a) identify and update relevant and trustworthy information resources to build and maintain awareness about vulnerabilities; (b) ensure the performance of automated vulnerability scanning and assessments on ICT assets, whereby the frequency and scope of those activities shall be commensurate to the classification established in accordance with Article 8(1) of Regulation (EU) 2022/2554 and the overall risk profile of the ICT asset; (c) verify whether: (i) ICT third-party service providers handle vulnerabilities related to the ICT services provided to the financial entity; (ii) whether those service providers report to the financial entity at least the critical vulnerabilities and statistics and trends in a timely manner; (d) track the usage of: (i) third-party libraries, including open-source libraries, used by ICT services supporting critical or important functions; (ii) ICT services developed by the financial entity itself or specifically customised or developed for the financial entity by an ICT third-party service provider; (e) establish procedures for the responsible disclosure of vulnerabilities to clients, counterparties, and to the public; (f) prioritise the deployment of patches and other mitigation measures to address the vulnerabilities identified; (g) monitor and verify the remediation of vulnerabilities; (h) require the recording of any detected vulnerabilities affecting ICT systems and the monitoring of their resolution. For the purposes of point (b), financial entities shall perform the automated vulnerability scanning and assessments on ICT assets for the ICT assets supporting critical or important functions on at least a weekly basis. For the purposes of point (c), financial entities shall request that ICT third-party service providers investigate the relevant vulnerabilities, determine the root causes, and implement appropriate mitigating action. For the purposes of point (d), financial entities shall, where appropriate in collaboration with the ICT third-party service provider, monitor the version and possible updates of the third-party libraries. In case of ready to use (off-the-shelf) ICT assets or components of ICT assets acquired and used in the operation of ICT services not supporting critical or important functions, financial entities shall track the usage to the extent possible of third-party libraries, including open-source libraries. For the purposes of point (f), financial entities shall consider the criticality of the vulnerability, the classification established in accordance with Article 8(1) of Regulation (EU) 2022/2554, and the risk profile of the ICT assets affected by the identified vulnerabilities.",
      "outbound_relations": [
        {
          "edge_id": "article-Art10-Para2__article-Art10-Para1__depends_on",
          "source": "article-Art10-Para2",
          "target": "article-Art10-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art10-Para2 enumerates the scanning, third-party, remediation and recording controls for the vulnerability-management procedures mandated by article-Art10-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art10-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art10-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art6-Para4__article-Art10-Para2__references",
          "source": "article-Art6-Para4",
          "target": "article-Art10-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art6-Para4 expressly invokes article-Art10-Para2 point (a) when requiring awareness-driven updates that keep cryptographic technology resilient to cyber threats.",
          "source_canonical_ref": "celex:32024R1774/article-Art6-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art10-Para2"
        },
        {
          "edge_id": "recital-11__article-Art10-Para2__concretizes",
          "source": "recital-11",
          "target": "article-Art10-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-11 concretizes article-Art10-Para2 by requiring reliable vulnerability information, automated monitoring, remediation, and verification that ICT third-party service providers promptly investigate and address vulnerabilities in supplied services.",
          "source_canonical_ref": "celex:32024R1774/recital-11",
          "target_canonical_ref": "celex:32024R1774/article-Art10-Para2"
        },
        {
          "edge_id": "recital-13__article-Art10-Para2__provides_guidance_for",
          "source": "recital-13",
          "target": "article-Art10-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-13 provides guidance for the responsible-disclosure procedure in article-Art10-Para2 by identifying severity, stakeholder impact, and the readiness of a fix or mitigation as factors for communicating ICT vulnerabilities.",
          "source_canonical_ref": "celex:32024R1774/recital-13",
          "target_canonical_ref": "celex:32024R1774/article-Art10-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The vulnerability management procedures referred to in paragraph 1 shall:",
          "source_line_start": 1959,
          "source_line_end": 1959
        },
        {
          "sequence": 2,
          "text": "For the purposes of point (b), financial entities shall perform the automated vulnerability scanning and assessments on ICT assets for the ICT assets supporting critical or important functions on at least a weekly basis.",
          "source_line_start": 2128,
          "source_line_end": 2128
        },
        {
          "sequence": 3,
          "text": "For the purposes of point (c), financial entities shall request that ICT third-party service providers investigate the relevant vulnerabilities, determine the root causes, and implement appropriate mitigating action.",
          "source_line_start": 2129,
          "source_line_end": 2129
        },
        {
          "sequence": 4,
          "text": "For the purposes of point (d), financial entities shall, where appropriate in collaboration with the ICT third-party service provider, monitor the version and possible updates of the third-party libraries. In case of ready to use (off-the-shelf) ICT assets or components of ICT assets acquired and used in the operation of ICT services not supporting critical or important functions, financial entities shall track the usage to the extent possible of third-party libraries, including open-source libraries.",
          "source_line_start": 2130,
          "source_line_end": 2130
        },
        {
          "sequence": 5,
          "text": "For the purposes of point (f), financial entities shall consider the criticality of the vulnerability, the classification established in accordance with Article 8(1) of Regulation (EU) 2022/2554, and the risk profile of the ICT assets affected by the identified vulnerabilities.",
          "source_line_start": 2131,
          "source_line_end": 2131
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art10-Para2",
      "text_sha256": "395d127757b42d60898ace7dcc2b70d95a77b06e67bcd61916775fa76a494d26"
    },
    {
      "id": "article-Art10-Para3",
      "type": "article_paragraph",
      "article_number": 10,
      "paragraph_number": "3",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Vulnerability and patch management",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 5"
      ],
      "text": "As part of the ICT security policies, procedures, protocols, and tools referred to in Article 9(2) of Regulation (EU) 2022/2554, financial entities shall develop, document and implement patch management procedures.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art10-Para4__article-Art10-Para3__depends_on",
          "source": "article-Art10-Para4",
          "target": "article-Art10-Para3",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art10-Para4 sets the evaluation, emergency, testing, deployment and deadline requirements for the patch-management procedures established by article-Art10-Para3.",
          "source_canonical_ref": "celex:32024R1774/article-Art10-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art10-Para3"
        },
        {
          "edge_id": "recital-2__article-Art10-Para3__provides_guidance_for",
          "source": "recital-2",
          "target": "article-Art10-Para3",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-2 separately names patch management as a necessary technical procedure, directly explaining the obligation in article-Art10-Para3.",
          "source_canonical_ref": "celex:32024R1774/recital-2",
          "target_canonical_ref": "celex:32024R1774/article-Art10-Para3"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "As part of the ICT security policies, procedures, protocols, and tools referred to in Article 9(2) of Regulation (EU) 2022/2554, financial entities shall develop, document and implement patch management procedures.",
          "source_line_start": 2134,
          "source_line_end": 2134
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art10-Para3",
      "text_sha256": "327ef7ac1889001ec0a002eee748c79bb96dc3b30cc78417ac6ad77c06215089"
    },
    {
      "id": "article-Art10-Para4",
      "type": "article_paragraph",
      "article_number": 10,
      "paragraph_number": "4",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Vulnerability and patch management",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "to the extent possible identify and evaluate available software and hardware patches and updates using automated tools;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 2144,
          "source_line_end": 2147
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "identify emergency procedures for the patching and updating of ICT assets;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 2158,
          "source_line_end": 2161
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "test and deploy the software and hardware patches and the updates referred to in Article 8(2), points (b)(v), (vi) and (vii);",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 2172,
          "source_line_end": 2175
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "set deadlines for the installation of software and hardware patches and updates and escalation procedures in case those deadlines cannot be met.",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 2186,
          "source_line_end": 2189
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 5"
      ],
      "text": "The patch management procedures referred to in paragraph 3 shall: (a) to the extent possible identify and evaluate available software and hardware patches and updates using automated tools; (b) identify emergency procedures for the patching and updating of ICT assets; (c) test and deploy the software and hardware patches and the updates referred to in Article 8(2), points (b)(v), (vi) and (vii); (d) set deadlines for the installation of software and hardware patches and updates and escalation procedures in case those deadlines cannot be met.",
      "outbound_relations": [
        {
          "edge_id": "article-Art10-Para4__article-Art10-Para3__depends_on",
          "source": "article-Art10-Para4",
          "target": "article-Art10-Para3",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art10-Para4 sets the evaluation, emergency, testing, deployment and deadline requirements for the patch-management procedures established by article-Art10-Para3.",
          "source_canonical_ref": "celex:32024R1774/article-Art10-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art10-Para3"
        },
        {
          "edge_id": "article-Art10-Para4__article-Art8-Para2__references",
          "source": "article-Art10-Para4",
          "target": "article-Art8-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art10-Para4 expressly refers patch and update testing and deployment to the production and non-production testing controls in article-Art8-Para2 points (b)(v) to (vii).",
          "source_canonical_ref": "celex:32024R1774/article-Art10-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art8-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-12__article-Art10-Para4__provides_guidance_for",
          "source": "recital-12",
          "target": "article-Art10-Para4",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-12 provides guidance for article-Art10-Para4 by explaining that patches should be tested and deployed in a controlled environment so that identified vulnerabilities are remedied without creating operational disruption.",
          "source_canonical_ref": "celex:32024R1774/recital-12",
          "target_canonical_ref": "celex:32024R1774/article-Art10-Para4"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The patch management procedures referred to in paragraph 3 shall:",
          "source_line_start": 2137,
          "source_line_end": 2137
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art10-Para4",
      "text_sha256": "e04e7410fb13d3fbfa9f93cb45e6f6cb88318097221d61a45cb368bc8c32c423"
    },
    {
      "id": "article-Art11-Para1",
      "type": "article_paragraph",
      "article_number": 11,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Data and system security",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 5"
      ],
      "text": "As part of the ICT security policies, procedures, protocols, and tools referred to in Article 9(2) of Regulation (EU) 2022/2554, financial entities shall develop, document, and implement a data and system security procedure.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art11-Para2__article-Art11-Para1__depends_on",
          "source": "article-Art11-Para2",
          "target": "article-Art11-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art11-Para2 expressly takes the data and system security procedure established by article-Art11-Para1 as the procedure whose mandatory security elements it enumerates.",
          "source_canonical_ref": "celex:32024R1774/article-Art11-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art11-Para1"
        },
        {
          "edge_id": "recital-2__article-Art11-Para1__provides_guidance_for",
          "source": "recital-2",
          "target": "article-Art11-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-2 identifies data and system security as a technical implementation area, which is the precise procedure created by article-Art11-Para1.",
          "source_canonical_ref": "celex:32024R1774/recital-2",
          "target_canonical_ref": "celex:32024R1774/article-Art11-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "As part of the ICT security policies, procedures, protocols, and tools referred to in Article 9(2) of Regulation (EU) 2022/2554, financial entities shall develop, document, and implement a data and system security procedure.",
          "source_line_start": 2202,
          "source_line_end": 2202
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art11-Para1",
      "text_sha256": "ffe4e2810ae4bf18a1e45f654b43ae7d0643b4f623ee4913970bc0970da5ddb3"
    },
    {
      "id": "article-Art11-Para2",
      "type": "article_paragraph",
      "article_number": 11,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Data and system security",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "the access restrictions referred to in Article 21 of this Regulation, supporting the protection requirements for each level of classification;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 2212,
          "source_line_end": 2215
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "the identification of a secure configuration baseline for ICT assets that minimise exposure of those ICT assets to cyber threats and measures to verify regularly that those baselines are effectively deployed;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 2226,
          "source_line_end": 2229
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "the identification of security measures to ensure that only authorised software is installed in ICT systems and endpoint devices;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 2240,
          "source_line_end": 2243
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "the identification of security measures against malicious codes;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 2254,
          "source_line_end": 2257
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "the identification of security measures to ensure that only authorised data storage media, systems, and endpoint devices are used to transfer and store data of the financial entity;",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 2268,
          "source_line_end": 2271
        },
        {
          "type": "point",
          "marker": "(f)",
          "text": "the following requirements to secure the use of portable endpoint devices and private non-portable endpoint devices:",
          "depth": 1,
          "parent_marker": null,
          "path": "(f)",
          "source_line_start": 2282,
          "source_line_end": 2285
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "the requirement to use a management solution to remotely manage the endpoint devices and remotely wipe the financial entity’s data;",
          "depth": 2,
          "parent_marker": "(f)",
          "path": "(f)(i)",
          "source_line_start": 2292,
          "source_line_end": 2295
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "the requirement to use security mechanisms that cannot be modified, removed or bypassed by staff members or ICT third-party service providers in an unauthorised manner;",
          "depth": 2,
          "parent_marker": "(f)",
          "path": "(f)(ii)",
          "source_line_start": 2306,
          "source_line_end": 2309
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "the requirement to use removable data storage devices only where the residual ICT risk remains within the financial entity’s risk tolerance level referred to in Article 3, first subparagraph, point (a);",
          "depth": 2,
          "parent_marker": "(f)",
          "path": "(f)(iii)",
          "source_line_start": 2320,
          "source_line_end": 2323
        },
        {
          "type": "point",
          "marker": "(g)",
          "text": "the process to securely delete data, present on premises of the financial entity or stored externally, that the financial entity no longer needs to collect or to store;",
          "depth": 1,
          "parent_marker": null,
          "path": "(g)",
          "source_line_start": 2338,
          "source_line_end": 2341
        },
        {
          "type": "point",
          "marker": "(h)",
          "text": "the process to securely dispose or decommission of data storage devices present on premises of the financial entity or stored externally containing confidential information;",
          "depth": 1,
          "parent_marker": null,
          "path": "(h)",
          "source_line_start": 2352,
          "source_line_end": 2355
        },
        {
          "type": "point",
          "marker": "(i)",
          "text": "the identification and implementation of security measures to prevent data loss and leakage for systems and endpoint devices;",
          "depth": 1,
          "parent_marker": null,
          "path": "(i)",
          "source_line_start": 2366,
          "source_line_end": 2369
        },
        {
          "type": "point",
          "marker": "(j)",
          "text": "the implementation of security measures to ensure that teleworking and the use of private endpoint devices does not adversely impact the ICT security of the financial entity;",
          "depth": 1,
          "parent_marker": null,
          "path": "(j)",
          "source_line_start": 2380,
          "source_line_end": 2383
        },
        {
          "type": "point",
          "marker": "(k)",
          "text": "for ICT assets or services operated by an ICT third-party service provider, the identification and implementation of requirements to maintain digital operational resilience, in accordance with the results of the data classification and ICT risk assessment.",
          "depth": 1,
          "parent_marker": null,
          "path": "(k)",
          "source_line_start": 2394,
          "source_line_end": 2397
        },
        {
          "type": "point",
          "marker": "(a)",
          "text": "the implementation of vendor recommended settings on the elements operated by the financial entity;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 2410,
          "source_line_end": 2413
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "a clear allocation of information security roles and responsibilities between the financial entity and the ICT third-party service provider, in accordance with the principle of full responsibility of the financial entity over its ICT third-party service provider referred to in Article 28(1), point (a), of Regulation (EU) 2022/2554, and for financial entities referred to in Article 28(2) of that Regulation, and in accordance with the financial entity’s policy on the use of ICT services supporting critical or important functions;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 2424,
          "source_line_end": 2427
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "the need to ensure and maintain adequate competences within the financial entity in the management and security of the service used;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 2438,
          "source_line_end": 2441
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "technical and organisational measures to minimise the risks related to the infrastructure used by the ICT third-party service provider for its ICT services, considering leading practices, and standards as defined in Article 2, point (1), of Regulation (EU) No 1025/2012.",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 2452,
          "source_line_end": 2455
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 5"
      ],
      "text": "The data and system security procedure referred to in paragraph 1 shall contain all of the following elements related to data and ICT system security, in accordance with the classification established in accordance with Article 8(1) of Regulation (EU) 2022/2554: (a) the access restrictions referred to in Article 21 of this Regulation, supporting the protection requirements for each level of classification; (b) the identification of a secure configuration baseline for ICT assets that minimise exposure of those ICT assets to cyber threats and measures to verify regularly that those baselines are effectively deployed; (c) the identification of security measures to ensure that only authorised software is installed in ICT systems and endpoint devices; (d) the identification of security measures against malicious codes; (e) the identification of security measures to ensure that only authorised data storage media, systems, and endpoint devices are used to transfer and store data of the financial entity; (f) the following requirements to secure the use of portable endpoint devices and private non-portable endpoint devices: (i) the requirement to use a management solution to remotely manage the endpoint devices and remotely wipe the financial entity’s data; (ii) the requirement to use security mechanisms that cannot be modified, removed or bypassed by staff members or ICT third-party service providers in an unauthorised manner; (iii) the requirement to use removable data storage devices only where the residual ICT risk remains within the financial entity’s risk tolerance level referred to in Article 3, first subparagraph, point (a); (g) the process to securely delete data, present on premises of the financial entity or stored externally, that the financial entity no longer needs to collect or to store; (h) the process to securely dispose or decommission of data storage devices present on premises of the financial entity or stored externally containing confidential information; (i) the identification and implementation of security measures to prevent data loss and leakage for systems and endpoint devices; (j) the implementation of security measures to ensure that teleworking and the use of private endpoint devices does not adversely impact the ICT security of the financial entity; (k) for ICT assets or services operated by an ICT third-party service provider, the identification and implementation of requirements to maintain digital operational resilience, in accordance with the results of the data classification and ICT risk assessment. For the purposes of point (b), the secure configuration baseline referred to in that point shall take into account leading practices and appropriate techniques laid down in the standards defined in Article 2, point (1), of Regulation (EU) No 1025/2012. For the purposes of point (k), financial entities shall consider the following: (a) the implementation of vendor recommended settings on the elements operated by the financial entity; (b) a clear allocation of information security roles and responsibilities between the financial entity and the ICT third-party service provider, in accordance with the principle of full responsibility of the financial entity over its ICT third-party service provider referred to in Article 28(1), point (a), of Regulation (EU) 2022/2554, and for financial entities referred to in Article 28(2) of that Regulation, and in accordance with the financial entity’s policy on the use of ICT services supporting critical or important functions; (c) the need to ensure and maintain adequate competences within the financial entity in the management and security of the service used; (d) technical and organisational measures to minimise the risks related to the infrastructure used by the ICT third-party service provider for its ICT services, considering leading practices, and standards as defined in Article 2, point (1), of Regulation (EU) No 1025/2012.",
      "outbound_relations": [
        {
          "edge_id": "article-Art11-Para2__article-Art11-Para1__depends_on",
          "source": "article-Art11-Para2",
          "target": "article-Art11-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art11-Para2 expressly takes the data and system security procedure established by article-Art11-Para1 as the procedure whose mandatory security elements it enumerates.",
          "source_canonical_ref": "celex:32024R1774/article-Art11-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art11-Para1"
        },
        {
          "edge_id": "article-Art11-Para2__article-Art21-Para1__references",
          "source": "article-Art11-Para2",
          "target": "article-Art21-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art11-Para2 expressly imports the access restrictions laid down in article-Art21-Para1 as an element supporting the protection requirements attached to each data-classification level.",
          "source_canonical_ref": "celex:32024R1774/article-Art11-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art21-Para1"
        },
        {
          "edge_id": "article-Art11-Para2__article-Art3-Para1__references",
          "source": "article-Art11-Para2",
          "target": "article-Art3-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art11-Para2 conditions use of removable data-storage devices on residual ICT risk remaining within the risk-tolerance level established in article-Art3-Para1, first subparagraph, point (a).",
          "source_canonical_ref": "celex:32024R1774/article-Art11-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art3-Para1"
        }
      ],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The data and system security procedure referred to in paragraph 1 shall contain all of the following elements related to data and ICT system security, in accordance with the classification established in accordance with Article 8(1) of Regulation (EU) 2022/2554:",
          "source_line_start": 2205,
          "source_line_end": 2205
        },
        {
          "sequence": 2,
          "text": "For the purposes of point (b), the secure configuration baseline referred to in that point shall take into account leading practices and appropriate techniques laid down in the standards defined in Article 2, point (1), of Regulation (EU) No 1025/2012.",
          "source_line_start": 2402,
          "source_line_end": 2402
        },
        {
          "sequence": 3,
          "text": "For the purposes of point (k), financial entities shall consider the following:",
          "source_line_start": 2403,
          "source_line_end": 2403
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art11-Para2",
      "text_sha256": "f3c05de0936f8f8b0bea658f0b4035a250aee33fd95f42b93547885c471a8d19"
    },
    {
      "id": "article-Art12-Para1",
      "type": "article_paragraph",
      "article_number": 12,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Logging",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 5"
      ],
      "text": "Financial entities shall, as part of the safeguards against intrusions and data misuse, develop, document, and implement logging procedures, protocols and tools.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art12-Para2__article-Art12-Para1__depends_on",
          "source": "article-Art12-Para2",
          "target": "article-Art12-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art12-Para2 expressly specifies the mandatory contents of the logging procedures, protocols and tools that article-Art12-Para1 requires financial entities to establish.",
          "source_canonical_ref": "celex:32024R1774/article-Art12-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art12-Para1"
        },
        {
          "edge_id": "recital-2__article-Art12-Para1__provides_guidance_for",
          "source": "recital-2",
          "target": "article-Art12-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-2 expressly includes logging among necessary technical procedures, supplying the policy rationale for article-Art12-Para1's logging obligation.",
          "source_canonical_ref": "celex:32024R1774/recital-2",
          "target_canonical_ref": "celex:32024R1774/article-Art12-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall, as part of the safeguards against intrusions and data misuse, develop, document, and implement logging procedures, protocols and tools.",
          "source_line_start": 2468,
          "source_line_end": 2468
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art12-Para1",
      "text_sha256": "ecd1a5116ef8280f30a5c18e5c036264f7adc21b8c146a7ad652f3903973978a"
    },
    {
      "id": "article-Art12-Para2",
      "type": "article_paragraph",
      "article_number": 12,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Logging",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "the identification of the events to be logged, the retention period of the logs, and the measures to secure and handle the log data, considering the purpose for which the logs are created;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 2478,
          "source_line_end": 2481
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "the alignment of the level of detail of the logs with their purpose and usage to enable the effective detection of anomalous activities as referred to in Article 24;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 2492,
          "source_line_end": 2495
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "the requirement to log events related to all of the following:",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 2506,
          "source_line_end": 2509
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "logical and physical access control, as referred to in Article 21, and identity management;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(i)",
          "source_line_start": 2516,
          "source_line_end": 2519
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "capacity management;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(ii)",
          "source_line_start": 2530,
          "source_line_end": 2533
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "change management;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(iii)",
          "source_line_start": 2544,
          "source_line_end": 2547
        },
        {
          "type": "subpoint",
          "marker": "(iv)",
          "text": "ICT operations, including ICT system activities;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(iv)",
          "source_line_start": 2558,
          "source_line_end": 2561
        },
        {
          "type": "subpoint",
          "marker": "(v)",
          "text": "network traffic activities, including ICT network performance;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(v)",
          "source_line_start": 2572,
          "source_line_end": 2575
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "measures to protect logging systems and log information against tampering, deletion, and unauthorised access at rest, in transit, and, where relevant, in use;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 2590,
          "source_line_end": 2593
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "measures to detect a failure of logging systems;",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 2604,
          "source_line_end": 2607
        },
        {
          "type": "point",
          "marker": "(f)",
          "text": "without prejudice to any applicable regulatory requirements under Union or national law, the synchronisation of the clocks of each of the financial entity’s ICT systems upon a documented reliable reference time source.",
          "depth": 1,
          "parent_marker": null,
          "path": "(f)",
          "source_line_start": 2618,
          "source_line_end": 2621
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 5"
      ],
      "text": "The logging procedures, protocols, and tools referred to in paragraph 1 shall contain all of the following: (a) the identification of the events to be logged, the retention period of the logs, and the measures to secure and handle the log data, considering the purpose for which the logs are created; (b) the alignment of the level of detail of the logs with their purpose and usage to enable the effective detection of anomalous activities as referred to in Article 24; (c) the requirement to log events related to all of the following: (i) logical and physical access control, as referred to in Article 21, and identity management; (ii) capacity management; (iii) change management; (iv) ICT operations, including ICT system activities; (v) network traffic activities, including ICT network performance; (d) measures to protect logging systems and log information against tampering, deletion, and unauthorised access at rest, in transit, and, where relevant, in use; (e) measures to detect a failure of logging systems; (f) without prejudice to any applicable regulatory requirements under Union or national law, the synchronisation of the clocks of each of the financial entity’s ICT systems upon a documented reliable reference time source. For the purposes of point (a), financial entities shall establish the retention period, taking into account the business and information security objectives, the reason for recording the event in the logs, and the results of the ICT risk assessment.",
      "outbound_relations": [
        {
          "edge_id": "article-Art12-Para2__article-Art12-Para1__depends_on",
          "source": "article-Art12-Para2",
          "target": "article-Art12-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art12-Para2 expressly specifies the mandatory contents of the logging procedures, protocols and tools that article-Art12-Para1 requires financial entities to establish.",
          "source_canonical_ref": "celex:32024R1774/article-Art12-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art12-Para1"
        },
        {
          "edge_id": "article-Art12-Para2__article-Art21-Para1__references",
          "source": "article-Art12-Para2",
          "target": "article-Art21-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art12-Para2 expressly requires logs for logical and physical access-control events governed by article-Art21-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art12-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art21-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art23-Para2__article-Art12-Para2__references",
          "source": "article-Art23-Para2",
          "target": "article-Art12-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art23-Para2 expressly includes logs collected under Article 12 among its detection inputs, and article-Art12-Para2 is the narrow target specifying the events, retention, protection, and handling requirements for those logs.",
          "source_canonical_ref": "celex:32024R1774/article-Art23-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art12-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The logging procedures, protocols, and tools referred to in paragraph 1 shall contain all of the following:",
          "source_line_start": 2471,
          "source_line_end": 2471
        },
        {
          "sequence": 2,
          "text": "For the purposes of point (a), financial entities shall establish the retention period, taking into account the business and information security objectives, the reason for recording the event in the logs, and the results of the ICT risk assessment.",
          "source_line_start": 2626,
          "source_line_end": 2626
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art12-Para2",
      "text_sha256": "10d4c476733e50a485cdeb031325a4b2e28b4db0f6a6fe56b81d3981d9b866b1"
    },
    {
      "id": "article-Art13-Para1",
      "type": "article_paragraph",
      "article_number": 13,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "single",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Network security management",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "the segregation and segmentation of ICT systems and networks taking into account:",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 2653,
          "source_line_end": 2656
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "the criticality or importance of the function those ICT systems and networks support;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(i)",
          "source_line_start": 2663,
          "source_line_end": 2666
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "the classification established in accordance with Article 8(1) of Regulation (EU) 2022/2554;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(ii)",
          "source_line_start": 2677,
          "source_line_end": 2680
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "the overall risk profile of ICT assets using those ICT systems and networks;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(iii)",
          "source_line_start": 2691,
          "source_line_end": 2694
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "the documentation of all of the financial entity’s network connections and data flows;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 2709,
          "source_line_end": 2712
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "the use of a separate and dedicated network for the administration of ICT assets;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 2723,
          "source_line_end": 2726
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "the identification and implementation of network access controls to prevent and detect connections to the financial entity’s network by any unauthorised device or system, or any endpoint not meeting the financial entity’s security requirements;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 2737,
          "source_line_end": 2740
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "the encryption of network connections passing over corporate networks, public networks, domestic networks, third-party networks, and wireless networks, for communication protocols used, taking into account the results of the approved data classification, the results of the ICT risk assessment and the encryption of network connections referred to in Article 6(2);",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 2751,
          "source_line_end": 2754
        },
        {
          "type": "point",
          "marker": "(f)",
          "text": "the design of networks in line with the ICT security requirements established by the financial entity, taking into account leading practices to ensure the confidentiality, integrity, and availability of the network;",
          "depth": 1,
          "parent_marker": null,
          "path": "(f)",
          "source_line_start": 2765,
          "source_line_end": 2768
        },
        {
          "type": "point",
          "marker": "(g)",
          "text": "the securing of network traffic between the internal networks and the internet and other external connections;",
          "depth": 1,
          "parent_marker": null,
          "path": "(g)",
          "source_line_start": 2779,
          "source_line_end": 2782
        },
        {
          "type": "point",
          "marker": "(h)",
          "text": "the identification of the roles and responsibilities and steps for the specification, implementation, approval, change, and review of firewall rules and connections filters;",
          "depth": 1,
          "parent_marker": null,
          "path": "(h)",
          "source_line_start": 2793,
          "source_line_end": 2796
        },
        {
          "type": "point",
          "marker": "(i)",
          "text": "the performance of reviews of the network architecture and of the network security design once a year, and periodically for microenterprises, to identify potential vulnerabilities;",
          "depth": 1,
          "parent_marker": null,
          "path": "(i)",
          "source_line_start": 2807,
          "source_line_end": 2810
        },
        {
          "type": "point",
          "marker": "(j)",
          "text": "the measures to temporarily isolate, where necessary, subnetworks, and network components and devices;",
          "depth": 1,
          "parent_marker": null,
          "path": "(j)",
          "source_line_start": 2821,
          "source_line_end": 2824
        },
        {
          "type": "point",
          "marker": "(k)",
          "text": "the implementation of a secure configuration baseline of all network components, and the hardening of the network and of network devices in line with any vendor instructions, where applicable standards, as defined in Article 2, point (1), of Regulation (EU) No 1025/2012, and leading practices;",
          "depth": 1,
          "parent_marker": null,
          "path": "(k)",
          "source_line_start": 2835,
          "source_line_end": 2838
        },
        {
          "type": "point",
          "marker": "(l)",
          "text": "the procedures to limit, lock, and terminate system and remote sessions after a specified period of inactivity;",
          "depth": 1,
          "parent_marker": null,
          "path": "(l)",
          "source_line_start": 2849,
          "source_line_end": 2852
        },
        {
          "type": "point",
          "marker": "(m)",
          "text": "for network services agreements:",
          "depth": 1,
          "parent_marker": null,
          "path": "(m)",
          "source_line_start": 2863,
          "source_line_end": 2866
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "the identification and specification of ICT and information security measures, service levels, and management requirements of all network services;",
          "depth": 2,
          "parent_marker": "(m)",
          "path": "(m)(i)",
          "source_line_start": 2873,
          "source_line_end": 2876
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "whether those services are provided by an ICT intra-group service provider or by ICT third-party service providers.",
          "depth": 2,
          "parent_marker": "(m)",
          "path": "(m)(ii)",
          "source_line_start": 2887,
          "source_line_end": 2890
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 6"
      ],
      "text": "Financial entities shall, as part of the safeguards ensuring the security of networks against intrusions and data misuse, develop, document, and implement policies, procedures, protocols, and tools on network security management, including all of the following: (a) the segregation and segmentation of ICT systems and networks taking into account: (i) the criticality or importance of the function those ICT systems and networks support; (ii) the classification established in accordance with Article 8(1) of Regulation (EU) 2022/2554; (iii) the overall risk profile of ICT assets using those ICT systems and networks; (b) the documentation of all of the financial entity’s network connections and data flows; (c) the use of a separate and dedicated network for the administration of ICT assets; (d) the identification and implementation of network access controls to prevent and detect connections to the financial entity’s network by any unauthorised device or system, or any endpoint not meeting the financial entity’s security requirements; (e) the encryption of network connections passing over corporate networks, public networks, domestic networks, third-party networks, and wireless networks, for communication protocols used, taking into account the results of the approved data classification, the results of the ICT risk assessment and the encryption of network connections referred to in Article 6(2); (f) the design of networks in line with the ICT security requirements established by the financial entity, taking into account leading practices to ensure the confidentiality, integrity, and availability of the network; (g) the securing of network traffic between the internal networks and the internet and other external connections; (h) the identification of the roles and responsibilities and steps for the specification, implementation, approval, change, and review of firewall rules and connections filters; (i) the performance of reviews of the network architecture and of the network security design once a year, and periodically for microenterprises, to identify potential vulnerabilities; (j) the measures to temporarily isolate, where necessary, subnetworks, and network components and devices; (k) the implementation of a secure configuration baseline of all network components, and the hardening of the network and of network devices in line with any vendor instructions, where applicable standards, as defined in Article 2, point (1), of Regulation (EU) No 1025/2012, and leading practices; (l) the procedures to limit, lock, and terminate system and remote sessions after a specified period of inactivity; (m) for network services agreements: (i) the identification and specification of ICT and information security measures, service levels, and management requirements of all network services; (ii) whether those services are provided by an ICT intra-group service provider or by ICT third-party service providers. For the purposes of point (h), financial entities shall perform the review of firewall rules and connections filters on a regular basis in accordance with the classification established in accordance with Article 8(1) of Regulation (EU) 2022/2554 and the overall risk profile of ICT systems involved. For ICT systems that support critical or important functions, financial entities shall verify the adequacy of the existing firewall rules and connection filters at least every 6 months.",
      "outbound_relations": [
        {
          "edge_id": "article-Art13-Para1__article-Art6-Para2__references",
          "source": "article-Art13-Para1",
          "target": "article-Art6-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art13-Para1 expressly requires network-connection encryption to take account of the encryption of network connections governed by article-Art6-Para2.",
          "source_canonical_ref": "celex:32024R1774/article-Art13-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art6-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art8-Para2__article-Art13-Para1__references",
          "source": "article-Art8-Para2",
          "target": "article-Art13-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art8-Para2 expressly applies the segregation requirement in article-Art13-Para1 point (a) to all components of separated production and non-production environments.",
          "source_canonical_ref": "celex:32024R1774/article-Art8-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art13-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall, as part of the safeguards ensuring the security of networks against intrusions and data misuse, develop, document, and implement policies, procedures, protocols, and tools on network security management, including all of the following:",
          "source_line_start": 2646,
          "source_line_end": 2646
        },
        {
          "sequence": 2,
          "text": "For the purposes of point (h), financial entities shall perform the review of firewall rules and connections filters on a regular basis in accordance with the classification established in accordance with Article 8(1) of Regulation (EU) 2022/2554 and the overall risk profile of ICT systems involved. For ICT systems that support critical or important functions, financial entities shall verify the adequacy of the existing firewall rules and connection filters at least every 6 months.",
          "source_line_start": 2899,
          "source_line_end": 2899
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art13-Para1",
      "text_sha256": "5a0c5331b456d082d9e11d65272c3a3222067b945978874bab10e0fec3d64a9c"
    },
    {
      "id": "article-Art14-Para1",
      "type": "article_paragraph",
      "article_number": 14,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Securing information in transit",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "the availability, authenticity, integrity and confidentiality of data during network transmission, and the establishment of procedures to assess compliance with those requirements;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 2914,
          "source_line_end": 2917
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "the prevention and detection of data leakages and the secure transfer of information between the financial entity and external parties;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 2928,
          "source_line_end": 2931
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "that requirements on confidentiality or non-disclosure arrangements reflecting the financial entity’s needs for the protection of information for both the staff of the financial entity and of third parties are implemented, documented, and regularly reviewed.",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 2942,
          "source_line_end": 2945
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 6"
      ],
      "text": "As part of the safeguards to preserve the availability, authenticity, integrity and confidentiality of data, financial entities shall develop, document, and implement the policies, procedures, protocols, and tools to protect information in transit. Financial entities shall in particular ensure all of the following: (a) the availability, authenticity, integrity and confidentiality of data during network transmission, and the establishment of procedures to assess compliance with those requirements; (b) the prevention and detection of data leakages and the secure transfer of information between the financial entity and external parties; (c) that requirements on confidentiality or non-disclosure arrangements reflecting the financial entity’s needs for the protection of information for both the staff of the financial entity and of third parties are implemented, documented, and regularly reviewed.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art14-Para2__article-Art14-Para1__depends_on",
          "source": "article-Art14-Para2",
          "target": "article-Art14-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art14-Para2 expressly requires the information-in-transit policies and controls established by article-Art14-Para1 to be designed from the approved data classification and ICT risk assessment.",
          "source_canonical_ref": "celex:32024R1774/article-Art14-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art14-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "As part of the safeguards to preserve the availability, authenticity, integrity and confidentiality of data, financial entities shall develop, document, and implement the policies, procedures, protocols, and tools to protect information in transit. Financial entities shall in particular ensure all of the following:",
          "source_line_start": 2907,
          "source_line_end": 2907
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art14-Para1",
      "text_sha256": "916a5f1962a4ee08490dc750b2ab86ad72d2b4e98460f8d341aa92d729126d09"
    },
    {
      "id": "article-Art14-Para2",
      "type": "article_paragraph",
      "article_number": 14,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Securing information in transit",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 6"
      ],
      "text": "Financial entities shall design the policies, procedures, protocols, and tools to protect the information in transit referred to in paragraph 1 on the basis of the results of the approved data classification and of the ICT risk assessment.",
      "outbound_relations": [
        {
          "edge_id": "article-Art14-Para2__article-Art14-Para1__depends_on",
          "source": "article-Art14-Para2",
          "target": "article-Art14-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art14-Para2 expressly requires the information-in-transit policies and controls established by article-Art14-Para1 to be designed from the approved data classification and ICT risk assessment.",
          "source_canonical_ref": "celex:32024R1774/article-Art14-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art14-Para1"
        }
      ],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall design the policies, procedures, protocols, and tools to protect the information in transit referred to in paragraph 1 on the basis of the results of the approved data classification and of the ICT risk assessment.",
          "source_line_start": 2952,
          "source_line_end": 2952
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art14-Para2",
      "text_sha256": "3271c373dc7e70ce7ed582dd5be06087d2cff89a4a0a846a03c3d1458975d417"
    },
    {
      "id": "article-Art15-Para1",
      "type": "article_paragraph",
      "article_number": 15,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT project management",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 7"
      ],
      "text": "As part of the safeguards to preserve the availability, authenticity, integrity, and confidentiality of data, financial entities shall develop, document, and implement an ICT project management policy.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art15-Para2__article-Art15-Para1__depends_on",
          "source": "article-Art15-Para2",
          "target": "article-Art15-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art15-Para2 expressly defines the acquisition, maintenance and development projects that must be covered by the ICT project-management policy required in article-Art15-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art15-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art15-Para1"
        },
        {
          "edge_id": "article-Art15-Para3__article-Art15-Para1__depends_on",
          "source": "article-Art15-Para3",
          "target": "article-Art15-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art15-Para3 expressly enumerates the governance, planning, risk, change and testing contents of the ICT project-management policy required by article-Art15-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art15-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art15-Para1"
        },
        {
          "edge_id": "article-Art15-Para4__article-Art15-Para1__depends_on",
          "source": "article-Art15-Para4",
          "target": "article-Art15-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art15-Para4 expressly adds business-area information and expertise as a secure-implementation requirement of the ICT project-management policy established in article-Art15-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art15-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art15-Para1"
        },
        {
          "edge_id": "article-Art15-Para5__article-Art15-Para1__depends_on",
          "source": "article-Art15-Para5",
          "target": "article-Art15-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art15-Para5 expressly makes reporting on critical or important ICT projects and their risks a requirement of the project-management policy established in article-Art15-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art15-Para5",
          "target_canonical_ref": "celex:32024R1774/article-Art15-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "As part of the safeguards to preserve the availability, authenticity, integrity, and confidentiality of data, financial entities shall develop, document, and implement an ICT project management policy.",
          "source_line_start": 2973,
          "source_line_end": 2973
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art15-Para1",
      "text_sha256": "2b9c76e57b7daab3a5b6dec04cc5363d7ce15f40860d106957fc160a05a0981b"
    },
    {
      "id": "article-Art15-Para2",
      "type": "article_paragraph",
      "article_number": 15,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT project management",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 7"
      ],
      "text": "The ICT project management policy referred to in paragraph 1 shall specify the elements that ensure the effective management of the ICT projects related to the acquisition, maintenance and, where applicable, development of the financial entity’s ICT systems.",
      "outbound_relations": [
        {
          "edge_id": "article-Art15-Para2__article-Art15-Para1__depends_on",
          "source": "article-Art15-Para2",
          "target": "article-Art15-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art15-Para2 expressly defines the acquisition, maintenance and development projects that must be covered by the ICT project-management policy required in article-Art15-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art15-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art15-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-15__article-Art15-Para2__concretizes",
          "source": "recital-15",
          "target": "article-Art15-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-15 concretizes article-Art15-Para2 by identifying acquisition, maintenance, development and change of ICT systems as project-management subject matter regardless of the methodology selected by the financial entity.",
          "source_canonical_ref": "celex:32024R1774/recital-15",
          "target_canonical_ref": "celex:32024R1774/article-Art15-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The ICT project management policy referred to in paragraph 1 shall specify the elements that ensure the effective management of the ICT projects related to the acquisition, maintenance and, where applicable, development of the financial entity’s ICT systems.",
          "source_line_start": 2976,
          "source_line_end": 2976
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art15-Para2",
      "text_sha256": "fa395dbff845ef177b01e5377c25afb9244e0b30744646b226edf2def82ee7c5"
    },
    {
      "id": "article-Art15-Para3",
      "type": "article_paragraph",
      "article_number": 15,
      "paragraph_number": "3",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT project management",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "ICT project objectives;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 2986,
          "source_line_end": 2989
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "ICT project governance, including roles and responsibilities;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 3000,
          "source_line_end": 3003
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "ICT project planning, timeframe, and steps;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 3014,
          "source_line_end": 3017
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "ICT project risk assessment;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 3028,
          "source_line_end": 3031
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "relevant milestones;",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 3042,
          "source_line_end": 3045
        },
        {
          "type": "point",
          "marker": "(f)",
          "text": "change management requirements;",
          "depth": 1,
          "parent_marker": null,
          "path": "(f)",
          "source_line_start": 3056,
          "source_line_end": 3059
        },
        {
          "type": "point",
          "marker": "(g)",
          "text": "the testing of all requirements, including security requirements, and the respective approval process when deploying an ICT system in the production environment.",
          "depth": 1,
          "parent_marker": null,
          "path": "(g)",
          "source_line_start": 3070,
          "source_line_end": 3073
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 7"
      ],
      "text": "The ICT project management policy referred to in paragraph 1 shall contain all of the following: (a) ICT project objectives; (b) ICT project governance, including roles and responsibilities; (c) ICT project planning, timeframe, and steps; (d) ICT project risk assessment; (e) relevant milestones; (f) change management requirements; (g) the testing of all requirements, including security requirements, and the respective approval process when deploying an ICT system in the production environment.",
      "outbound_relations": [
        {
          "edge_id": "article-Art15-Para3__article-Art15-Para1__depends_on",
          "source": "article-Art15-Para3",
          "target": "article-Art15-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art15-Para3 expressly enumerates the governance, planning, risk, change and testing contents of the ICT project-management policy required by article-Art15-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art15-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art15-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art15-Para5__article-Art15-Para3__references",
          "source": "article-Art15-Para5",
          "target": "article-Art15-Para3",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art15-Para5 expressly bases management-body reporting on the ICT project risk assessment required by article-Art15-Para3, point (d).",
          "source_canonical_ref": "celex:32024R1774/article-Art15-Para5",
          "target_canonical_ref": "celex:32024R1774/article-Art15-Para3"
        },
        {
          "edge_id": "recital-15__article-Art15-Para3__provides_guidance_for",
          "source": "recital-15",
          "target": "article-Art15-Para3",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-15 provides guidance for article-Art15-Para3 by requiring project testing methods suited to the entity, applied on a risk basis, while preserving a secure, reliable and resilient ICT environment.",
          "source_canonical_ref": "celex:32024R1774/recital-15",
          "target_canonical_ref": "celex:32024R1774/article-Art15-Para3"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The ICT project management policy referred to in paragraph 1 shall contain all of the following:",
          "source_line_start": 2979,
          "source_line_end": 2979
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art15-Para3",
      "text_sha256": "6fc853b1508ee56979e02dbf337f408dffaf099e8eb30a25efb93530a2a4ee57"
    },
    {
      "id": "article-Art15-Para4",
      "type": "article_paragraph",
      "article_number": 15,
      "paragraph_number": "4",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT project management",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 7"
      ],
      "text": "The ICT project management policy referred to in paragraph 1 shall ensure the secure ICT project implementation through the provision of the necessary information and expertise from the business area or functions impacted by the ICT project.",
      "outbound_relations": [
        {
          "edge_id": "article-Art15-Para4__article-Art15-Para1__depends_on",
          "source": "article-Art15-Para4",
          "target": "article-Art15-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art15-Para4 expressly adds business-area information and expertise as a secure-implementation requirement of the ICT project-management policy established in article-Art15-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art15-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art15-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-15__article-Art15-Para4__concretizes",
          "source": "recital-15",
          "target": "article-Art15-Para4",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-15 concretizes article-Art15-Para4 by explaining that staff from business areas or roles affected by an ICT project must supply the information and expertise needed for secure implementation.",
          "source_canonical_ref": "celex:32024R1774/recital-15",
          "target_canonical_ref": "celex:32024R1774/article-Art15-Para4"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The ICT project management policy referred to in paragraph 1 shall ensure the secure ICT project implementation through the provision of the necessary information and expertise from the business area or functions impacted by the ICT project.",
          "source_line_start": 3080,
          "source_line_end": 3080
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art15-Para4",
      "text_sha256": "21f586c3214f09294d14e0ca6ee4473ca4865278ef1c68185ce6d6cbafb22744"
    },
    {
      "id": "article-Art15-Para5",
      "type": "article_paragraph",
      "article_number": 15,
      "paragraph_number": "5",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT project management",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "individually or in aggregation, depending on the importance and size of the ICT projects;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 3090,
          "source_line_end": 3093
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "periodically and, where necessary, on an event-driven basis.",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 3104,
          "source_line_end": 3107
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 7"
      ],
      "text": "In accordance with the ICT project risk assessment referred to in paragraph 3, point (d), the ICT project management policy referred to in paragraph 1 shall provide that the establishment and progress of ICT projects impacting critical or important functions of the financial entity and their associated risks are reported to the management body as follows: (a) individually or in aggregation, depending on the importance and size of the ICT projects; (b) periodically and, where necessary, on an event-driven basis.",
      "outbound_relations": [
        {
          "edge_id": "article-Art15-Para5__article-Art15-Para1__depends_on",
          "source": "article-Art15-Para5",
          "target": "article-Art15-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art15-Para5 expressly makes reporting on critical or important ICT projects and their risks a requirement of the project-management policy established in article-Art15-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art15-Para5",
          "target_canonical_ref": "celex:32024R1774/article-Art15-Para1"
        },
        {
          "edge_id": "article-Art15-Para5__article-Art15-Para3__references",
          "source": "article-Art15-Para5",
          "target": "article-Art15-Para3",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art15-Para5 expressly bases management-body reporting on the ICT project risk assessment required by article-Art15-Para3, point (d).",
          "source_canonical_ref": "celex:32024R1774/article-Art15-Para5",
          "target_canonical_ref": "celex:32024R1774/article-Art15-Para3"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-15__article-Art15-Para5__provides_guidance_for",
          "source": "recital-15",
          "target": "article-Art15-Para5",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-15 provides guidance for article-Art15-Para5 by linking management-body reporting to projects affecting critical or important functions and by tying report frequency and detail to each project’s importance and size.",
          "source_canonical_ref": "celex:32024R1774/recital-15",
          "target_canonical_ref": "celex:32024R1774/article-Art15-Para5"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "In accordance with the ICT project risk assessment referred to in paragraph 3, point (d), the ICT project management policy referred to in paragraph 1 shall provide that the establishment and progress of ICT projects impacting critical or important functions of the financial entity and their associated risks are reported to the management body as follows:",
          "source_line_start": 3083,
          "source_line_end": 3083
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art15-Para5",
      "text_sha256": "c30a21737385f99c77d33a49f10ff794fef71a2e4474a29ddbcaf87b2f55bacd"
    },
    {
      "id": "article-Art16-Para1",
      "type": "article_paragraph",
      "article_number": 16,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT systems acquisition, development, and maintenance",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "identify security practices and methodologies relating to the acquisition, development, and maintenance of ICT systems;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 3127,
          "source_line_end": 3130
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "require the identification of:",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 3141,
          "source_line_end": 3144
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "technical specifications and ICT technical specifications, as defined in Article 2, points (4) and (5), of Regulation (EU) No 1025/2012;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(i)",
          "source_line_start": 3151,
          "source_line_end": 3154
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "requirements relating to the acquisition, development, and maintenance of ICT systems, with a particular focus on ICT security requirements and on their approval by the relevant business function and ICT asset owner in accordance with the financial entity’s internal governance arrangements;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(ii)",
          "source_line_start": 3165,
          "source_line_end": 3168
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "specify measures to mitigate the risk of unintentional alteration or intentional manipulation of the ICT systems during the development, maintenance, and deployment of those ICT systems in the production environment.",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 3183,
          "source_line_end": 3186
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 7"
      ],
      "text": "As part of the safeguards to preserve the availability, authenticity, integrity, and confidentiality of data, financial entities shall develop, document and implement a policy governing the acquisition, development, and maintenance of ICT systems. That policy shall: (a) identify security practices and methodologies relating to the acquisition, development, and maintenance of ICT systems; (b) require the identification of: (i) technical specifications and ICT technical specifications, as defined in Article 2, points (4) and (5), of Regulation (EU) No 1025/2012; (ii) requirements relating to the acquisition, development, and maintenance of ICT systems, with a particular focus on ICT security requirements and on their approval by the relevant business function and ICT asset owner in accordance with the financial entity’s internal governance arrangements; (c) specify measures to mitigate the risk of unintentional alteration or intentional manipulation of the ICT systems during the development, maintenance, and deployment of those ICT systems in the production environment.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art16-Para9__article-Art16-Para1__depends_on",
          "source": "article-Art16-Para9",
          "target": "article-Art16-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para9 expressly extends the acquisition, development and maintenance policy duty in article-Art16-Para1 to ICT systems developed or managed by users outside the ICT function, subject to a risk-based approach.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "As part of the safeguards to preserve the availability, authenticity, integrity, and confidentiality of data, financial entities shall develop, document and implement a policy governing the acquisition, development, and maintenance of ICT systems. That policy shall:",
          "source_line_start": 3120,
          "source_line_end": 3120
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art16-Para1",
      "text_sha256": "bc91b53c25dcdaf6af35aea52a56f903eabb1f4c81d8c3e1aa3426fabf521dc6"
    },
    {
      "id": "article-Art16-Para2",
      "type": "article_paragraph",
      "article_number": 16,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT systems acquisition, development, and maintenance",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "clearing members and clients;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 3201,
          "source_line_end": 3204
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "interoperable central counterparties;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 3215,
          "source_line_end": 3218
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "other interested parties.",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 3229,
          "source_line_end": 3232
        },
        {
          "type": "point",
          "marker": "(a)",
          "text": "users;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 3244,
          "source_line_end": 3247
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "critical utilities and critical service providers;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 3258,
          "source_line_end": 3261
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "other central securities depositories;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 3272,
          "source_line_end": 3275
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "other market infrastructures;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 3286,
          "source_line_end": 3289
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "any other institutions with which central securities depositories have identified interdependencies in their business continuity policy.",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 3300,
          "source_line_end": 3303
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 7"
      ],
      "text": "Financial entities shall develop, document, and implement an ICT systems’ acquisition, development, and maintenance procedure for the testing and approval of all ICT systems prior to their use and after maintenance, in accordance with Article 8(2), point (b), points (v), (vi) and (vii). The level of testing shall be commensurate to the criticality of the business procedures and ICT assets concerned. The testing shall be designed to verify that new ICT systems are adequate to perform as intended, including the quality of the software developed internally. Central counterparties shall, in addition to the requirements laid down in the first subparagraph, involve, as appropriate, in the design and conduct of the testing referred to in the first subparagraph: (a) clearing members and clients; (b) interoperable central counterparties; (c) other interested parties. Central securities depositories shall, in addition to the requirements laid down in the first subparagraph, involve, as appropriate, in the design and conduct of the testing referred to in the first subparagraph: (a) users; (b) critical utilities and critical service providers; (c) other central securities depositories; (d) other market infrastructures; (e) any other institutions with which central securities depositories have identified interdependencies in their business continuity policy.",
      "outbound_relations": [
        {
          "edge_id": "article-Art16-Para2__article-Art8-Para2__references",
          "source": "article-Art16-Para2",
          "target": "article-Art8-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art16-Para2 expressly requires pre-use and post-maintenance ICT-system testing to follow the production-separation and testing controls in article-Art8-Para2, point (b)(v) to (vii).",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art8-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art16-Para3__article-Art16-Para2__depends_on",
          "source": "article-Art16-Para3",
          "target": "article-Art16-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para3 expressly makes source-code review and the resulting vulnerability action plan part of the acquisition, development and maintenance testing procedure established in article-Art16-Para2.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
        },
        {
          "edge_id": "article-Art16-Para4__article-Art16-Para2__depends_on",
          "source": "article-Art16-Para4",
          "target": "article-Art16-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para4 expressly adds integration-phase security testing of software packages to the testing procedure established in article-Art16-Para2.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
        },
        {
          "edge_id": "article-Art16-Para5__article-Art16-Para2__depends_on",
          "source": "article-Art16-Para5",
          "target": "article-Art16-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para5 expressly makes anonymisation, pseudonymisation or randomisation of production data and protection of non-production data part of the testing procedure established in article-Art16-Para2.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para5",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
        },
        {
          "edge_id": "article-Art16-Para6__article-Art16-Para2__depends_on",
          "source": "article-Art16-Para6",
          "target": "article-Art16-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para6 expressly places its tightly controlled production-data testing exception within the acquisition, development and maintenance procedure established in article-Art16-Para2.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para6",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
        },
        {
          "edge_id": "article-Art16-Para7__article-Art16-Para2__depends_on",
          "source": "article-Art16-Para7",
          "target": "article-Art16-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para7 expressly adds controls protecting source-code integrity, including code developed by ICT third-party providers, to the procedure established in article-Art16-Para2.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para7",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
        },
        {
          "edge_id": "article-Art16-Para8__article-Art16-Para2__depends_on",
          "source": "article-Art16-Para8",
          "target": "article-Art16-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para8 expressly makes pre-deployment analysis and testing of proprietary, third-party and open-source software part of the procedure established in article-Art16-Para2.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para8",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
        },
        {
          "edge_id": "article-Art16-Para9__article-Art16-Para2__depends_on",
          "source": "article-Art16-Para9",
          "target": "article-Art16-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para9 expressly extends the pre-use and post-maintenance testing and approval procedure in article-Art16-Para2 to ICT systems developed or managed outside the ICT function.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
        },
        {
          "edge_id": "recital-24__article-Art16-Para2__provides_guidance_for",
          "source": "recital-24",
          "target": "article-Art16-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-24 explains why article-Art16-Para2 adds sector-specific ICT-system testing participation for central counterparties and central securities depositories: the RTS builds project-management controls on the operational-risk rules already applicable to those infrastructures.",
          "source_canonical_ref": "celex:32024R1774/recital-24",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall develop, document, and implement an ICT systems’ acquisition, development, and maintenance procedure for the testing and approval of all ICT systems prior to their use and after maintenance, in accordance with Article 8(2), point (b), points (v), (vi) and (vii). The level of testing shall be commensurate to the criticality of the business procedures and ICT assets concerned. The testing shall be designed to verify that new ICT systems are adequate to perform as intended, including the quality of the software developed internally.",
          "source_line_start": 3193,
          "source_line_end": 3193
        },
        {
          "sequence": 2,
          "text": "Central counterparties shall, in addition to the requirements laid down in the first subparagraph, involve, as appropriate, in the design and conduct of the testing referred to in the first subparagraph:",
          "source_line_start": 3194,
          "source_line_end": 3194
        },
        {
          "sequence": 3,
          "text": "Central securities depositories shall, in addition to the requirements laid down in the first subparagraph, involve, as appropriate, in the design and conduct of the testing referred to in the first subparagraph:",
          "source_line_start": 3237,
          "source_line_end": 3237
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art16-Para2",
      "text_sha256": "049244fed44d97d65f70d31d3ed1c195acf85d1750eeaced1733cd7f090f3ef0"
    },
    {
      "id": "article-Art16-Para3",
      "type": "article_paragraph",
      "article_number": 16,
      "paragraph_number": "3",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT systems acquisition, development, and maintenance",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "identify and analyse vulnerabilities and anomalies in the source code;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 3317,
          "source_line_end": 3320
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "adopt an action plan to address those vulnerabilities and anomalies;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 3331,
          "source_line_end": 3334
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "monitor the implementation of that action plan.",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 3345,
          "source_line_end": 3348
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 7"
      ],
      "text": "The procedure referred to in paragraph 2 shall contain the performance of source code reviews covering both static and dynamic testing. That testing shall contain security testing for internet-exposed systems and applications in accordance with Article 8(2), point (b), points (v), (vi) and (vii). Financial entities shall: (a) identify and analyse vulnerabilities and anomalies in the source code; (b) adopt an action plan to address those vulnerabilities and anomalies; (c) monitor the implementation of that action plan.",
      "outbound_relations": [
        {
          "edge_id": "article-Art16-Para3__article-Art16-Para2__depends_on",
          "source": "article-Art16-Para3",
          "target": "article-Art16-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para3 expressly makes source-code review and the resulting vulnerability action plan part of the acquisition, development and maintenance testing procedure established in article-Art16-Para2.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
        },
        {
          "edge_id": "article-Art16-Para3__article-Art8-Para2__references",
          "source": "article-Art16-Para3",
          "target": "article-Art8-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art16-Para3 expressly subjects security testing for internet-exposed systems and applications to the environment-separation and production-testing requirements in article-Art8-Para2, point (b)(v) to (vii).",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art8-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art16-Para8__article-Art16-Para3__references",
          "source": "article-Art16-Para8",
          "target": "article-Art16-Para3",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art16-Para8 expressly requires proprietary, third-party and open-source software to be analysed and tested according to the static and dynamic source-code review regime in article-Art16-Para3.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para8",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para3"
        },
        {
          "edge_id": "article-Art16-Para9__article-Art16-Para3__depends_on",
          "source": "article-Art16-Para9",
          "target": "article-Art16-Para3",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para9 expressly extends the source-code review, vulnerability analysis and remediation regime in article-Art16-Para3 to user-developed or user-managed ICT systems.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para3"
        },
        {
          "edge_id": "recital-16__article-Art16-Para3__concretizes",
          "source": "recital-16",
          "target": "article-Art16-Para3",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-16 concretizes article-Art16-Para3 by requiring source-code review through both static and dynamic testing to reveal vulnerabilities and security gaps and to assess software integrity before operational use.",
          "source_canonical_ref": "celex:32024R1774/recital-16",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para3"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The procedure referred to in paragraph 2 shall contain the performance of source code reviews covering both static and dynamic testing. That testing shall contain security testing for internet-exposed systems and applications in accordance with Article 8(2), point (b), points (v), (vi) and (vii). Financial entities shall:",
          "source_line_start": 3310,
          "source_line_end": 3310
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art16-Para3",
      "text_sha256": "70db7c69e85106a1e85cdca3a5aa889c50b8b289887abd84d6c63621a49f2915"
    },
    {
      "id": "article-Art16-Para4",
      "type": "article_paragraph",
      "article_number": 16,
      "paragraph_number": "4",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT systems acquisition, development, and maintenance",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 7"
      ],
      "text": "The procedure referred to in paragraph 2 shall contain security testing of software packages no later than at the integration phase, in accordance with Article 8(2), points (b)(v), (vi) and(vii).",
      "outbound_relations": [
        {
          "edge_id": "article-Art16-Para4__article-Art16-Para2__depends_on",
          "source": "article-Art16-Para4",
          "target": "article-Art16-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para4 expressly adds integration-phase security testing of software packages to the testing procedure established in article-Art16-Para2.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
        },
        {
          "edge_id": "article-Art16-Para4__article-Art8-Para2__references",
          "source": "article-Art16-Para4",
          "target": "article-Art8-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art16-Para4 expressly subjects software-package security testing to the environment-separation and production-testing requirements in article-Art8-Para2, point (b)(v) to (vii).",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art8-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art16-Para9__article-Art16-Para4__depends_on",
          "source": "article-Art16-Para9",
          "target": "article-Art16-Para4",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para9 expressly extends the integration-phase software-package security testing required by article-Art16-Para4 to ICT systems developed or managed outside the ICT function.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para4"
        },
        {
          "edge_id": "recital-16__article-Art16-Para4__concretizes",
          "source": "recital-16",
          "target": "article-Art16-Para4",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-16 concretizes article-Art16-Para4 by explaining that acquired or developed software packages must undergo ICT security testing so that they can be integrated securely into the existing ICT environment.",
          "source_canonical_ref": "celex:32024R1774/recital-16",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para4"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The procedure referred to in paragraph 2 shall contain security testing of software packages no later than at the integration phase, in accordance with Article 8(2), points (b)(v), (vi) and(vii).",
          "source_line_start": 3355,
          "source_line_end": 3355
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art16-Para4",
      "text_sha256": "6507384d24e371d28563751dae67f9cf69dab55153a7e4fda6011faaad1999f6"
    },
    {
      "id": "article-Art16-Para5",
      "type": "article_paragraph",
      "article_number": 16,
      "paragraph_number": "5",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT systems acquisition, development, and maintenance",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "non-production environments only store anonymised, pseudonymised, or randomised production data;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 3365,
          "source_line_end": 3368
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "financial entities are to protect the integrity and confidentiality of data in non-production environments.",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 3379,
          "source_line_end": 3382
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 7"
      ],
      "text": "The procedure referred to in paragraph 2 shall provide that: (a) non-production environments only store anonymised, pseudonymised, or randomised production data; (b) financial entities are to protect the integrity and confidentiality of data in non-production environments.",
      "outbound_relations": [
        {
          "edge_id": "article-Art16-Para5__article-Art16-Para2__depends_on",
          "source": "article-Art16-Para5",
          "target": "article-Art16-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para5 expressly makes anonymisation, pseudonymisation or randomisation of production data and protection of non-production data part of the testing procedure established in article-Art16-Para2.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para5",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art16-Para6__article-Art16-Para5__qualifies",
          "source": "article-Art16-Para6",
          "target": "article-Art16-Para5",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "article-Art16-Para6 expressly derogates from article-Art16-Para5 by permitting production data for specific testing occasions only for limited periods, after approval and with reporting to the ICT risk-management function.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para6",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para5"
        },
        {
          "edge_id": "article-Art16-Para9__article-Art16-Para5__depends_on",
          "source": "article-Art16-Para9",
          "target": "article-Art16-Para5",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para9 expressly extends the non-production data safeguards in article-Art16-Para5 to ICT systems developed or managed by users outside the ICT function.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para5"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The procedure referred to in paragraph 2 shall provide that:",
          "source_line_start": 3358,
          "source_line_end": 3358
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art16-Para5",
      "text_sha256": "6d5a132c7e5f4ea70c653899a90b45d5ba1d69c5262fa75b0ab1b85cb1da590d"
    },
    {
      "id": "article-Art16-Para6",
      "type": "article_paragraph",
      "article_number": 16,
      "paragraph_number": "6",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT systems acquisition, development, and maintenance",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 7"
      ],
      "text": "By way of derogation from paragraph 5, the procedure referred to in paragraph 2 may provide that production data are stored only for specific testing occasions, for limited periods of time, and following the approval by the relevant function and the reporting of such occasions to the ICT risk management function.",
      "outbound_relations": [
        {
          "edge_id": "article-Art16-Para6__article-Art16-Para2__depends_on",
          "source": "article-Art16-Para6",
          "target": "article-Art16-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para6 expressly places its tightly controlled production-data testing exception within the acquisition, development and maintenance procedure established in article-Art16-Para2.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para6",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
        },
        {
          "edge_id": "article-Art16-Para6__article-Art16-Para5__qualifies",
          "source": "article-Art16-Para6",
          "target": "article-Art16-Para5",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "article-Art16-Para6 expressly derogates from article-Art16-Para5 by permitting production data for specific testing occasions only for limited periods, after approval and with reporting to the ICT risk-management function.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para6",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para5"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art16-Para9__article-Art16-Para6__depends_on",
          "source": "article-Art16-Para9",
          "target": "article-Art16-Para6",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para9 expressly extends the limited and approved production-data testing exception in article-Art16-Para6 to ICT systems developed or managed outside the ICT function.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para6"
        },
        {
          "edge_id": "article-Art8-Para2__article-Art16-Para6__references",
          "source": "article-Art8-Para2",
          "target": "article-Art16-Para6",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art8-Para2 expressly uses article-Art16-Para6 as the approval and limited-duration standard for testing in production environments.",
          "source_canonical_ref": "celex:32024R1774/article-Art8-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para6"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "By way of derogation from paragraph 5, the procedure referred to in paragraph 2 may provide that production data are stored only for specific testing occasions, for limited periods of time, and following the approval by the relevant function and the reporting of such occasions to the ICT risk management function.",
          "source_line_start": 3389,
          "source_line_end": 3389
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art16-Para6",
      "text_sha256": "622ef38436b253725cf84d67ca5f2165249ebde4c31219221becf765ab7dbab2"
    },
    {
      "id": "article-Art16-Para7",
      "type": "article_paragraph",
      "article_number": 16,
      "paragraph_number": "7",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT systems acquisition, development, and maintenance",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 7"
      ],
      "text": "The procedure referred to in paragraph 2 shall contain the implementation of controls to protect the integrity of the source code of ICT systems that are developed in-house or by an ICT third-party service provider and delivered to the financial entity by an ICT third-parties service provider.",
      "outbound_relations": [
        {
          "edge_id": "article-Art16-Para7__article-Art16-Para2__depends_on",
          "source": "article-Art16-Para7",
          "target": "article-Art16-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para7 expressly adds controls protecting source-code integrity, including code developed by ICT third-party providers, to the procedure established in article-Art16-Para2.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para7",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art16-Para9__article-Art16-Para7__depends_on",
          "source": "article-Art16-Para9",
          "target": "article-Art16-Para7",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para9 expressly extends the source-code integrity controls in article-Art16-Para7 to ICT systems developed or managed by users outside the ICT function.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para7"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The procedure referred to in paragraph 2 shall contain the implementation of controls to protect the integrity of the source code of ICT systems that are developed in-house or by an ICT third-party service provider and delivered to the financial entity by an ICT third-parties service provider.",
          "source_line_start": 3392,
          "source_line_end": 3392
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art16-Para7",
      "text_sha256": "3911aa1d910d48389320eecc1be13fb2888a4b14c83144a4183b2a69ba8f20be"
    },
    {
      "id": "article-Art16-Para8",
      "type": "article_paragraph",
      "article_number": 16,
      "paragraph_number": "8",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT systems acquisition, development, and maintenance",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 7"
      ],
      "text": "The procedure referred to in paragraph 2 shall provide that proprietary software and, where feasible, the source code provided by ICT third-party service providers or coming from open-source projects, are to be analysed and tested in accordance with paragraph 3 prior to their deployment in the production environment.",
      "outbound_relations": [
        {
          "edge_id": "article-Art16-Para8__article-Art16-Para2__depends_on",
          "source": "article-Art16-Para8",
          "target": "article-Art16-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para8 expressly makes pre-deployment analysis and testing of proprietary, third-party and open-source software part of the procedure established in article-Art16-Para2.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para8",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
        },
        {
          "edge_id": "article-Art16-Para8__article-Art16-Para3__references",
          "source": "article-Art16-Para8",
          "target": "article-Art16-Para3",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art16-Para8 expressly requires proprietary, third-party and open-source software to be analysed and tested according to the static and dynamic source-code review regime in article-Art16-Para3.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para8",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para3"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art16-Para9__article-Art16-Para8__depends_on",
          "source": "article-Art16-Para9",
          "target": "article-Art16-Para8",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para9 expressly extends the pre-deployment proprietary, third-party and open-source analysis required by article-Art16-Para8 to systems developed or managed outside the ICT function.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para8"
        },
        {
          "edge_id": "recital-16__article-Art16-Para8__provides_guidance_for",
          "source": "recital-16",
          "target": "article-Art16-Para8",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-16 provides guidance for article-Art16-Para8 by specifying that review should cover acquired software, including proprietary software and, where feasible, source code supplied by ICT third-party service providers.",
          "source_canonical_ref": "celex:32024R1774/recital-16",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para8"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The procedure referred to in paragraph 2 shall provide that proprietary software and, where feasible, the source code provided by ICT third-party service providers or coming from open-source projects, are to be analysed and tested in accordance with paragraph 3 prior to their deployment in the production environment.",
          "source_line_start": 3395,
          "source_line_end": 3395
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art16-Para8",
      "text_sha256": "2330c9ed873b24efea619740761c432d9ba5f38b98d59d6f24584730dacbdd27"
    },
    {
      "id": "article-Art16-Para9",
      "type": "article_paragraph",
      "article_number": 16,
      "paragraph_number": "9",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT systems acquisition, development, and maintenance",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 7"
      ],
      "text": "Paragraph 1 to 8 of this Article shall also apply to ICT systems developed or managed by users outside the ICT function, using a risk-based approach.",
      "outbound_relations": [
        {
          "edge_id": "article-Art16-Para9__article-Art16-Para1__depends_on",
          "source": "article-Art16-Para9",
          "target": "article-Art16-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para9 expressly extends the acquisition, development and maintenance policy duty in article-Art16-Para1 to ICT systems developed or managed by users outside the ICT function, subject to a risk-based approach.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para1"
        },
        {
          "edge_id": "article-Art16-Para9__article-Art16-Para2__depends_on",
          "source": "article-Art16-Para9",
          "target": "article-Art16-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para9 expressly extends the pre-use and post-maintenance testing and approval procedure in article-Art16-Para2 to ICT systems developed or managed outside the ICT function.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
        },
        {
          "edge_id": "article-Art16-Para9__article-Art16-Para3__depends_on",
          "source": "article-Art16-Para9",
          "target": "article-Art16-Para3",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para9 expressly extends the source-code review, vulnerability analysis and remediation regime in article-Art16-Para3 to user-developed or user-managed ICT systems.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para3"
        },
        {
          "edge_id": "article-Art16-Para9__article-Art16-Para4__depends_on",
          "source": "article-Art16-Para9",
          "target": "article-Art16-Para4",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para9 expressly extends the integration-phase software-package security testing required by article-Art16-Para4 to ICT systems developed or managed outside the ICT function.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para4"
        },
        {
          "edge_id": "article-Art16-Para9__article-Art16-Para5__depends_on",
          "source": "article-Art16-Para9",
          "target": "article-Art16-Para5",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para9 expressly extends the non-production data safeguards in article-Art16-Para5 to ICT systems developed or managed by users outside the ICT function.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para5"
        },
        {
          "edge_id": "article-Art16-Para9__article-Art16-Para6__depends_on",
          "source": "article-Art16-Para9",
          "target": "article-Art16-Para6",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para9 expressly extends the limited and approved production-data testing exception in article-Art16-Para6 to ICT systems developed or managed outside the ICT function.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para6"
        },
        {
          "edge_id": "article-Art16-Para9__article-Art16-Para7__depends_on",
          "source": "article-Art16-Para9",
          "target": "article-Art16-Para7",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para9 expressly extends the source-code integrity controls in article-Art16-Para7 to ICT systems developed or managed by users outside the ICT function.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para7"
        },
        {
          "edge_id": "article-Art16-Para9__article-Art16-Para8__depends_on",
          "source": "article-Art16-Para9",
          "target": "article-Art16-Para8",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art16-Para9 expressly extends the pre-deployment proprietary, third-party and open-source analysis required by article-Art16-Para8 to systems developed or managed outside the ICT function.",
          "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
          "target_canonical_ref": "celex:32024R1774/article-Art16-Para8"
        }
      ],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Paragraph 1 to 8 of this Article shall also apply to ICT systems developed or managed by users outside the ICT function, using a risk-based approach.",
          "source_line_start": 3398,
          "source_line_end": 3398
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art16-Para9",
      "text_sha256": "8f944f443d079b3a27b0f082f3fd7337431048ed5326e6064658fe247f62dda8"
    },
    {
      "id": "article-Art17-Para1",
      "type": "article_paragraph",
      "article_number": 17,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT change management",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "a verification of whether the ICT security requirements have been met;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 3414,
          "source_line_end": 3417
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "mechanisms to ensure the independence of the functions that approve changes and the functions responsible for requesting and implementing those changes;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 3428,
          "source_line_end": 3431
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "a clear description of the roles and responsibilities to ensure that:",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 3442,
          "source_line_end": 3445
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "changes are specified and planned;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(i)",
          "source_line_start": 3452,
          "source_line_end": 3455
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "an adequate transition is designed;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(ii)",
          "source_line_start": 3466,
          "source_line_end": 3469
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "the changes are tested and finalised in a controlled manner;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(iii)",
          "source_line_start": 3480,
          "source_line_end": 3483
        },
        {
          "type": "subpoint",
          "marker": "(iv)",
          "text": "there is an effective quality assurance;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(iv)",
          "source_line_start": 3494,
          "source_line_end": 3497
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "the documentation and communication of change details, including:",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 3512,
          "source_line_end": 3515
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "the purpose and scope of the change;",
          "depth": 2,
          "parent_marker": "(d)",
          "path": "(d)(i)",
          "source_line_start": 3522,
          "source_line_end": 3525
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "the timeline for the implementation of the change;",
          "depth": 2,
          "parent_marker": "(d)",
          "path": "(d)(ii)",
          "source_line_start": 3536,
          "source_line_end": 3539
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "the expected outcomes;",
          "depth": 2,
          "parent_marker": "(d)",
          "path": "(d)(iii)",
          "source_line_start": 3550,
          "source_line_end": 3553
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "the identification of fall-back procedures and responsibilities, including procedures and responsibilities for aborting changes or recovering from changes not successfully implemented;",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 3568,
          "source_line_end": 3571
        },
        {
          "type": "point",
          "marker": "(f)",
          "text": "procedures, protocols, and tools to manage emergency changes that provide adequate safeguards;",
          "depth": 1,
          "parent_marker": null,
          "path": "(f)",
          "source_line_start": 3582,
          "source_line_end": 3585
        },
        {
          "type": "point",
          "marker": "(g)",
          "text": "procedures to document, re-evaluate, assess, and approve emergency changes after their implementation, including workarounds and patches;",
          "depth": 1,
          "parent_marker": null,
          "path": "(g)",
          "source_line_start": 3596,
          "source_line_end": 3599
        },
        {
          "type": "point",
          "marker": "(h)",
          "text": "the identification of the potential impact of a change on existing ICT security measures and an assessment of whether such change requires the adoption of additional ICT security measures.",
          "depth": 1,
          "parent_marker": null,
          "path": "(h)",
          "source_line_start": 3610,
          "source_line_end": 3613
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 7"
      ],
      "text": "As part of the safeguards to preserve the availability, authenticity, integrity, and confidentiality of data, financial entities shall include in the ICT change management procedures referred to in Article 9(4), point (e), of Regulation (EU) 2022/2554, in respect of all changes to software, hardware, firmware components, systems, or security parameters, all of the following elements: (a) a verification of whether the ICT security requirements have been met; (b) mechanisms to ensure the independence of the functions that approve changes and the functions responsible for requesting and implementing those changes; (c) a clear description of the roles and responsibilities to ensure that: (i) changes are specified and planned; (ii) an adequate transition is designed; (iii) the changes are tested and finalised in a controlled manner; (iv) there is an effective quality assurance; (d) the documentation and communication of change details, including: (i) the purpose and scope of the change; (ii) the timeline for the implementation of the change; (iii) the expected outcomes; (e) the identification of fall-back procedures and responsibilities, including procedures and responsibilities for aborting changes or recovering from changes not successfully implemented; (f) procedures, protocols, and tools to manage emergency changes that provide adequate safeguards; (g) procedures to document, re-evaluate, assess, and approve emergency changes after their implementation, including workarounds and patches; (h) the identification of the potential impact of a change on existing ICT security measures and an assessment of whether such change requires the adoption of additional ICT security measures.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "recital-17__article-Art17-Para1__concretizes",
          "source": "recital-17",
          "target": "article-Art17-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-17 concretizes article-Art17-Para1 by explaining why change-security verification, separation of approval from request and implementation, assigned roles, controlled testing, quality assurance, and fall-back responsibilities are required to contain confidentiality, integrity, availability, and disruption risks.",
          "source_canonical_ref": "celex:32024R1774/recital-17",
          "target_canonical_ref": "celex:32024R1774/article-Art17-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "As part of the safeguards to preserve the availability, authenticity, integrity, and confidentiality of data, financial entities shall include in the ICT change management procedures referred to in Article 9(4), point (e), of Regulation (EU) 2022/2554, in respect of all changes to software, hardware, firmware components, systems, or security parameters, all of the following elements:",
          "source_line_start": 3407,
          "source_line_end": 3407
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art17-Para1",
      "text_sha256": "eb24d56e323776e1048161ff636cb918ddd01de9a3f3637b311832608e53b3af"
    },
    {
      "id": "article-Art17-Para2",
      "type": "article_paragraph",
      "article_number": 17,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT change management",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "clearing members and clients;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 3628,
          "source_line_end": 3631
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "interoperable central counterparties;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 3642,
          "source_line_end": 3645
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "other interested parties,",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 3656,
          "source_line_end": 3659
        },
        {
          "type": "point",
          "marker": "(a)",
          "text": "users;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 3671,
          "source_line_end": 3674
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "critical utilities and critical service providers;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 3685,
          "source_line_end": 3688
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "other central securities depositories;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 3699,
          "source_line_end": 3702
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "other market infrastructures;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 3713,
          "source_line_end": 3716
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "any other institutions with which central securities depositories have identified interdependencies in their ICT business continuity policy.",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 3727,
          "source_line_end": 3730
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 7"
      ],
      "text": "After having made significant changes to their ICT systems, central counterparties and central securities depositories shall submit their ICT systems to stringent testing by simulating stressed conditions. Central counterparties shall involve, as appropriate, in the design and conduct of the testing referred to in the first subparagraph: (a) clearing members and clients; (b) interoperable central counterparties; (c) other interested parties, Central securities depositories shall, as appropriate, involve in the design and conduct of the testing referred to in the first subparagraph: (a) users; (b) critical utilities and critical service providers; (c) other central securities depositories; (d) other market infrastructures; (e) any other institutions with which central securities depositories have identified interdependencies in their ICT business continuity policy.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "recital-24__article-Art17-Para2__provides_guidance_for",
          "source": "recital-24",
          "target": "article-Art17-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-24 supplies the sectoral rationale for article-Art17-Para2, whose stringent post-change testing duties specifically address central counterparties and central securities depositories under the ICT change-management requirements.",
          "source_canonical_ref": "celex:32024R1774/recital-24",
          "target_canonical_ref": "celex:32024R1774/article-Art17-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "After having made significant changes to their ICT systems, central counterparties and central securities depositories shall submit their ICT systems to stringent testing by simulating stressed conditions.",
          "source_line_start": 3620,
          "source_line_end": 3620
        },
        {
          "sequence": 2,
          "text": "Central counterparties shall involve, as appropriate, in the design and conduct of the testing referred to in the first subparagraph:",
          "source_line_start": 3621,
          "source_line_end": 3621
        },
        {
          "sequence": 3,
          "text": "Central securities depositories shall, as appropriate, involve in the design and conduct of the testing referred to in the first subparagraph:",
          "source_line_start": 3664,
          "source_line_end": 3664
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art17-Para2",
      "text_sha256": "705f8b0539ddf0ad8f1406851886050d1e12b9116719b41d1a4a7f8b4250d84b"
    },
    {
      "id": "article-Art18-Para1",
      "type": "article_paragraph",
      "article_number": 18,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Physical and environmental security",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 8"
      ],
      "text": "As part of the safeguards to preserve the availability, authenticity, integrity, and confidentiality of data, financial entities shall specify, document, and implement a physical and environmental security policy. Financial entities shall design that policy i light of the cyber threat landscape, in accordance with the classification established in accordance with Article 8(1) of Regulation (EU) 2022/2554, and in light of the overall risk profile of ICT assets and accessible information assets.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art18-Para2__article-Art18-Para1__depends_on",
          "source": "article-Art18-Para2",
          "target": "article-Art18-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art18-Para2 expressly enumerates the access, environmental, asset-protection and clear-desk controls that the physical and environmental security policy established in article-Art18-Para1 must contain.",
          "source_canonical_ref": "celex:32024R1774/article-Art18-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art18-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "As part of the safeguards to preserve the availability, authenticity, integrity, and confidentiality of data, financial entities shall specify, document, and implement a physical and environmental security policy. Financial entities shall design that policy i light of the cyber threat landscape, in accordance with the classification established in accordance with Article 8(1) of Regulation (EU) 2022/2554, and in light of the overall risk profile of ICT assets and accessible information assets.",
          "source_line_start": 3748,
          "source_line_end": 3748
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art18-Para1",
      "text_sha256": "4ad9a000fe4d6a7135aaa98a40193f3cd2856fab148cbcb20557c56fffc41623"
    },
    {
      "id": "article-Art18-Para2",
      "type": "article_paragraph",
      "article_number": 18,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Physical and environmental security",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "a reference to the section of the policy on control of access management rights referred to in Article 21, first paragraph, point (g);",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 3758,
          "source_line_end": 3761
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "measures to protect from attacks, accidents, and environmental threats and hazards, the premises, data centres of the financial entity, and sensitive designated areas identified by the financial entity, where ICT assets and information assets reside;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 3772,
          "source_line_end": 3775
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "measures to secure ICT assets, both within and outside the premises of the financial entity, taking into account the results of the ICT risk assessment related to the relevant ICT assets;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 3786,
          "source_line_end": 3789
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "measures to ensure the availability, authenticity, integrity, and confidentiality of ICT assets, information assets, and physical access control devices of the financial entity through the appropriate maintenance;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 3800,
          "source_line_end": 3803
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "measures to preserve the availability, authenticity, integrity, and confidentiality of the data, including:",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 3814,
          "source_line_end": 3817
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "a clear desk policy for papers;",
          "depth": 2,
          "parent_marker": "(e)",
          "path": "(e)(i)",
          "source_line_start": 3824,
          "source_line_end": 3827
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "a clear screen policy for information processing facilities.",
          "depth": 2,
          "parent_marker": "(e)",
          "path": "(e)(ii)",
          "source_line_start": 3838,
          "source_line_end": 3841
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER I",
        "Section 8"
      ],
      "text": "The physical and environmental security policy referred to in paragraph 1 shall contain all of the following: (a) a reference to the section of the policy on control of access management rights referred to in Article 21, first paragraph, point (g); (b) measures to protect from attacks, accidents, and environmental threats and hazards, the premises, data centres of the financial entity, and sensitive designated areas identified by the financial entity, where ICT assets and information assets reside; (c) measures to secure ICT assets, both within and outside the premises of the financial entity, taking into account the results of the ICT risk assessment related to the relevant ICT assets; (d) measures to ensure the availability, authenticity, integrity, and confidentiality of ICT assets, information assets, and physical access control devices of the financial entity through the appropriate maintenance; (e) measures to preserve the availability, authenticity, integrity, and confidentiality of the data, including: (i) a clear desk policy for papers; (ii) a clear screen policy for information processing facilities. For the purposes of point (b), the measures to protect from environmental threats and hazards shall be commensurate with the importance of the premises, data centres, sensitive designated areas, and the criticality of the operations or ICT systems located therein. For the purposes of point (c), the physical and environmental security policy referred to in paragraph 1 shall contain measures to provide appropriate protection to unattended ICT assets.",
      "outbound_relations": [
        {
          "edge_id": "article-Art18-Para2__article-Art18-Para1__depends_on",
          "source": "article-Art18-Para2",
          "target": "article-Art18-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art18-Para2 expressly enumerates the access, environmental, asset-protection and clear-desk controls that the physical and environmental security policy established in article-Art18-Para1 must contain.",
          "source_canonical_ref": "celex:32024R1774/article-Art18-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art18-Para1"
        },
        {
          "edge_id": "article-Art18-Para2__article-Art21-Para1__references",
          "source": "article-Art18-Para2",
          "target": "article-Art21-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art18-Para2 expressly imports the physical access-management controls in article-Art21-Para1, point (g), into the physical and environmental security policy.",
          "source_canonical_ref": "celex:32024R1774/article-Art18-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art21-Para1"
        }
      ],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The physical and environmental security policy referred to in paragraph 1 shall contain all of the following:",
          "source_line_start": 3751,
          "source_line_end": 3751
        },
        {
          "sequence": 2,
          "text": "For the purposes of point (b), the measures to protect from environmental threats and hazards shall be commensurate with the importance of the premises, data centres, sensitive designated areas, and the criticality of the operations or ICT systems located therein.",
          "source_line_start": 3850,
          "source_line_end": 3850
        },
        {
          "sequence": 3,
          "text": "For the purposes of point (c), the physical and environmental security policy referred to in paragraph 1 shall contain measures to provide appropriate protection to unattended ICT assets.",
          "source_line_start": 3851,
          "source_line_end": 3851
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art18-Para2",
      "text_sha256": "e4e08deb82acbf417dfa90216b46f03a49f118a1d4e531adae552f12178296a1"
    },
    {
      "id": "article-Art19-Para1",
      "type": "article_paragraph",
      "article_number": 19,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "single",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Human resources policy",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "the identification and assignment of any specific ICT security responsibilities;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 3879,
          "source_line_end": 3882
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "requirements for staff of the financial entity and of the ICT third-party service providers using or accessing ICT assets of the financial entity to:",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 3893,
          "source_line_end": 3896
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "be informed about, and adhere to, the financial entity’s ICT security policies, procedures, and protocols;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(i)",
          "source_line_start": 3903,
          "source_line_end": 3906
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "be aware of the reporting channels put in place by the financial entity for the detection of anomalous behaviour, including, where applicable, the reporting channels established in line with Directive (EU) 2019/1937 of the European Parliament and of the Council (11);",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(ii)",
          "source_line_start": 3917,
          "source_line_end": 3921
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "for the staff, to return to the financial entity, upon termination of employment, all ICT assets and tangible information assets in their possession that belong to the financial entity.",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(iii)",
          "source_line_start": 3932,
          "source_line_end": 3935
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER II"
      ],
      "text": "Financial entities shall include in their human resource policy or other relevant policies all of the following ICT security related elements: (a) the identification and assignment of any specific ICT security responsibilities; (b) requirements for staff of the financial entity and of the ICT third-party service providers using or accessing ICT assets of the financial entity to: (i) be informed about, and adhere to, the financial entity’s ICT security policies, procedures, and protocols; (ii) be aware of the reporting channels put in place by the financial entity for the detection of anomalous behaviour, including, where applicable, the reporting channels established in line with Directive (EU) 2019/1937 of the European Parliament and of the Council ( 11 ) ; (iii) for the staff, to return to the financial entity, upon termination of employment, all ICT assets and tangible information assets in their possession that belong to the financial entity.",
      "outbound_relations": [],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall include in their human resource policy or other relevant policies all of the following ICT security related elements:",
          "source_line_start": 3872,
          "source_line_end": 3872
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art19-Para1",
      "text_sha256": "b252c36d18070f0d63ef8bd0790d1ba404e9d037f5676e59aff8a7cfc5f6df77"
    },
    {
      "id": "article-Art20-Para1",
      "type": "article_paragraph",
      "article_number": 20,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Identity management",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER II"
      ],
      "text": "As part of their control of access management rights, financial entities shall develop, document, and implement identity management policies and procedures that ensure the unique identification and authentication of natural persons and systems accessing the financial entities’ information to enable assignment of user access rights in accordance with Article 21.",
      "outbound_relations": [
        {
          "edge_id": "article-Art20-Para1__article-Art21-Para1__references",
          "source": "article-Art20-Para1",
          "target": "article-Art21-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art20-Para1 expressly makes unique identification and authentication the prerequisite for assigning user access rights under article-Art21-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art20-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art21-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art20-Para2__article-Art20-Para1__depends_on",
          "source": "article-Art20-Para2",
          "target": "article-Art20-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art20-Para2 expressly specifies the unique-account and identity-lifecycle contents of the identity-management policies and procedures established in article-Art20-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art20-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art20-Para1"
        },
        {
          "edge_id": "recital-14__article-Art20-Para1__concretizes",
          "source": "recital-14",
          "target": "article-Art20-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-14 concretizes article-Art20-Para1 by explaining that unique identification must cover both individuals and systems so that user access rights can be assigned without exposing the entity to unauthorised access and untraceable activity.",
          "source_canonical_ref": "celex:32024R1774/recital-14",
          "target_canonical_ref": "celex:32024R1774/article-Art20-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "As part of their control of access management rights, financial entities shall develop, document, and implement identity management policies and procedures that ensure the unique identification and authentication of natural persons and systems accessing the financial entities’ information to enable assignment of user access rights in accordance with Article 21.",
          "source_line_start": 3951,
          "source_line_end": 3951
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art20-Para1",
      "text_sha256": "39a5af33448d2e0390e86c442d0cabb0bf2d7d7c240c393ab0c4ac732affd616"
    },
    {
      "id": "article-Art20-Para2",
      "type": "article_paragraph",
      "article_number": 20,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Identity management",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "without prejudice to Article 21, first paragraph, point (c), a unique identity corresponding to a unique user account shall be assigned to each staff member of the financial entity or staff of the ICT third-party service providers accessing the information assets and ICT assets of the financial entity;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 3961,
          "source_line_end": 3964
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "a lifecycle management process for identities and accounts managing the creation, change, review and update, temporary deactivation, and termination of all accounts.",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 3975,
          "source_line_end": 3978
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER II"
      ],
      "text": "The identity management policies and procedures referred to in paragraph 1 shall contain all of the following: (a) without prejudice to Article 21, first paragraph, point (c), a unique identity corresponding to a unique user account shall be assigned to each staff member of the financial entity or staff of the ICT third-party service providers accessing the information assets and ICT assets of the financial entity; (b) a lifecycle management process for identities and accounts managing the creation, change, review and update, temporary deactivation, and termination of all accounts. For the purposes of point (a), financial entities shall maintain records of all identity assignments. Those records shall be kept following a reorganisation of the financial entity or after the end of the contractual relationship without prejudice to the retention requirements laid down in applicable Union and national law. For the purposes of point (b), financial entities shall, where feasible and appropriate, deploy automated solutions for the lifecycle identity management process.",
      "outbound_relations": [
        {
          "edge_id": "article-Art20-Para2__article-Art20-Para1__depends_on",
          "source": "article-Art20-Para2",
          "target": "article-Art20-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art20-Para2 expressly specifies the unique-account and identity-lifecycle contents of the identity-management policies and procedures established in article-Art20-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art20-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art20-Para1"
        },
        {
          "edge_id": "article-Art20-Para2__article-Art21-Para1__references",
          "source": "article-Art20-Para2",
          "target": "article-Art21-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art20-Para2 expressly references article-Art21-Para1 through a without-prejudice clause that preserves the exceptional generic and shared-account regime in point (c) while imposing the one-identity-to-one-account rule.",
          "source_canonical_ref": "celex:32024R1774/article-Art20-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art21-Para1"
        }
      ],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The identity management policies and procedures referred to in paragraph 1 shall contain all of the following:",
          "source_line_start": 3954,
          "source_line_end": 3954
        },
        {
          "sequence": 2,
          "text": "For the purposes of point (a), financial entities shall maintain records of all identity assignments. Those records shall be kept following a reorganisation of the financial entity or after the end of the contractual relationship without prejudice to the retention requirements laid down in applicable Union and national law.",
          "source_line_start": 3983,
          "source_line_end": 3983
        },
        {
          "sequence": 3,
          "text": "For the purposes of point (b), financial entities shall, where feasible and appropriate, deploy automated solutions for the lifecycle identity management process.",
          "source_line_start": 3984,
          "source_line_end": 3984
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art20-Para2",
      "text_sha256": "fa535d8d3852bd613dc2060092cf94149bb23aa38ff460b60703808d358ba3e9"
    },
    {
      "id": "article-Art21-Para1",
      "type": "article_paragraph",
      "article_number": 21,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "single",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Access control",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "the assignment of access rights to ICT assets based on need-to-know, need-to-use and least privilege principles, including for remote and emergency access;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 3999,
          "source_line_end": 4002
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "the segregation of duties designed to prevent unjustified access to critical data or to prevent the allocation of combinations of access rights that may be used to circumvent controls;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 4013,
          "source_line_end": 4016
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "a provision on user accountability, by limiting to the extent possible the use of generic and shared user accounts and ensuring that users are identifiable for the actions performed in the ICT systems at all times;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 4027,
          "source_line_end": 4030
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "a provision on restrictions of access to ICT assets, setting out controls and tools to prevent unauthorised access;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 4041,
          "source_line_end": 4044
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "account management procedures to grant, change or revoke access rights for user and generic accounts, including generic administrator accounts, including provision on all of the following:",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 4055,
          "source_line_end": 4058
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "assignment of roles and responsibilities for granting, reviewing, and revoking access rights;",
          "depth": 2,
          "parent_marker": "(e)",
          "path": "(e)(i)",
          "source_line_start": 4065,
          "source_line_end": 4068
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "assignment of privileged, emergency, and administrator access on a need-to-use or an ad-hoc basis for all ICT systems;",
          "depth": 2,
          "parent_marker": "(e)",
          "path": "(e)(ii)",
          "source_line_start": 4079,
          "source_line_end": 4082
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "withdrawal of access rights without undue delay upon termination of the employment or when the access is no longer necessary;",
          "depth": 2,
          "parent_marker": "(e)",
          "path": "(e)(iii)",
          "source_line_start": 4093,
          "source_line_end": 4096
        },
        {
          "type": "subpoint",
          "marker": "(iv)",
          "text": "update of access rights where changes are necessary and at least once a year for all ICT systems, other than ICT systems supporting critical or important functions and at least every 6 months for ICT systems supporting critical or important functions;",
          "depth": 2,
          "parent_marker": "(e)",
          "path": "(e)(iv)",
          "source_line_start": 4107,
          "source_line_end": 4110
        },
        {
          "type": "point",
          "marker": "(f)",
          "text": "authentication methods, including all of the following:",
          "depth": 1,
          "parent_marker": null,
          "path": "(f)",
          "source_line_start": 4125,
          "source_line_end": 4128
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "the use of authentication methods commensurate to the classification established in accordance with Article 8(1) of Regulation (EU) 2022/2554 and to the overall risk profile of ICT assets and considering leading practices;",
          "depth": 2,
          "parent_marker": "(f)",
          "path": "(f)(i)",
          "source_line_start": 4135,
          "source_line_end": 4138
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "the use of strong authentication methods in accordance with leading practices and techniques for remote access to the financial entity’s network, for privileged access, for access to ICT assets supporting critical or important functions or ICT assets that are publicly accessible;",
          "depth": 2,
          "parent_marker": "(f)",
          "path": "(f)(ii)",
          "source_line_start": 4149,
          "source_line_end": 4152
        },
        {
          "type": "point",
          "marker": "(g)",
          "text": "physical access controls measures including:",
          "depth": 1,
          "parent_marker": null,
          "path": "(g)",
          "source_line_start": 4167,
          "source_line_end": 4170
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "the identification and logging of natural persons that are authorised to access premises, data centres, and sensitive designated areas identified by the financial entity where ICT and information assets reside;",
          "depth": 2,
          "parent_marker": "(g)",
          "path": "(g)(i)",
          "source_line_start": 4177,
          "source_line_end": 4180
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "the granting of physical access rights to critical ICT assets to authorised persons only, in accordance with the need-to-know and least privilege principles, and on an ad-hoc basis;",
          "depth": 2,
          "parent_marker": "(g)",
          "path": "(g)(ii)",
          "source_line_start": 4191,
          "source_line_end": 4194
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "the monitoring of physical access to premises, data centres, and sensitive designated areas identified by the financial entity where ICT and information assets or both reside;",
          "depth": 2,
          "parent_marker": "(g)",
          "path": "(g)(iii)",
          "source_line_start": 4205,
          "source_line_end": 4208
        },
        {
          "type": "subpoint",
          "marker": "(iv)",
          "text": "the review of physical access rights to ensure that unnecessary access rights are promptly revoked.",
          "depth": 2,
          "parent_marker": "(g)",
          "path": "(g)(iv)",
          "source_line_start": 4219,
          "source_line_end": 4222
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER II"
      ],
      "text": "As part of their control of access management rights, financial entities shall develop, document, and implement a policy that contains all of the following: (a) the assignment of access rights to ICT assets based on need-to-know, need-to-use and least privilege principles, including for remote and emergency access; (b) the segregation of duties designed to prevent unjustified access to critical data or to prevent the allocation of combinations of access rights that may be used to circumvent controls; (c) a provision on user accountability, by limiting to the extent possible the use of generic and shared user accounts and ensuring that users are identifiable for the actions performed in the ICT systems at all times; (d) a provision on restrictions of access to ICT assets, setting out controls and tools to prevent unauthorised access; (e) account management procedures to grant, change or revoke access rights for user and generic accounts, including generic administrator accounts, including provision on all of the following: (i) assignment of roles and responsibilities for granting, reviewing, and revoking access rights; (ii) assignment of privileged, emergency, and administrator access on a need-to-use or an ad-hoc basis for all ICT systems; (iii) withdrawal of access rights without undue delay upon termination of the employment or when the access is no longer necessary; (iv) update of access rights where changes are necessary and at least once a year for all ICT systems, other than ICT systems supporting critical or important functions and at least every 6 months for ICT systems supporting critical or important functions; (f) authentication methods, including all of the following: (i) the use of authentication methods commensurate to the classification established in accordance with Article 8(1) of Regulation (EU) 2022/2554 and to the overall risk profile of ICT assets and considering leading practices; (ii) the use of strong authentication methods in accordance with leading practices and techniques for remote access to the financial entity’s network, for privileged access, for access to ICT assets supporting critical or important functions or ICT assets that are publicly accessible; (g) physical access controls measures including: (i) the identification and logging of natural persons that are authorised to access premises, data centres, and sensitive designated areas identified by the financial entity where ICT and information assets reside; (ii) the granting of physical access rights to critical ICT assets to authorised persons only, in accordance with the need-to-know and least privilege principles, and on an ad-hoc basis; (iii) the monitoring of physical access to premises, data centres, and sensitive designated areas identified by the financial entity where ICT and information assets or both reside; (iv) the review of physical access rights to ensure that unnecessary access rights are promptly revoked. For the purposes of point (e)(i), financial entities shall establish the retention period taking into account the business and information security objectives, the reasons for recording the event in the logs, and the results of the ICT risk assessment. For the purposes of point (e)(ii), financial entities shall, where possible, use dedicated accounts for the performance of administrative tasks on ICT systems. Where feasible and appropriate, financial entities shall deploy automated solutions for the privilege access management. For the purposes of point (g)(i), the identification and logging shall be commensurate with the importance of the premises, data centres, sensitive designated areas, and the criticality of the operations or ICT systems located therein. For the purposes of point (g)(iii), the monitoring shall be commensurate to the classification established in accordance with Article 8(1) of Regulation (EU) 2022/2554 and the criticality of the area accessed.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art11-Para2__article-Art21-Para1__references",
          "source": "article-Art11-Para2",
          "target": "article-Art21-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art11-Para2 expressly imports the access restrictions laid down in article-Art21-Para1 as an element supporting the protection requirements attached to each data-classification level.",
          "source_canonical_ref": "celex:32024R1774/article-Art11-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art21-Para1"
        },
        {
          "edge_id": "article-Art12-Para2__article-Art21-Para1__references",
          "source": "article-Art12-Para2",
          "target": "article-Art21-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art12-Para2 expressly requires logs for logical and physical access-control events governed by article-Art21-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art12-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art21-Para1"
        },
        {
          "edge_id": "article-Art18-Para2__article-Art21-Para1__references",
          "source": "article-Art18-Para2",
          "target": "article-Art21-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art18-Para2 expressly imports the physical access-management controls in article-Art21-Para1, point (g), into the physical and environmental security policy.",
          "source_canonical_ref": "celex:32024R1774/article-Art18-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art21-Para1"
        },
        {
          "edge_id": "article-Art20-Para1__article-Art21-Para1__references",
          "source": "article-Art20-Para1",
          "target": "article-Art21-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art20-Para1 expressly makes unique identification and authentication the prerequisite for assigning user access rights under article-Art21-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art20-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art21-Para1"
        },
        {
          "edge_id": "article-Art20-Para2__article-Art21-Para1__references",
          "source": "article-Art20-Para2",
          "target": "article-Art21-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art20-Para2 expressly references article-Art21-Para1 through a without-prejudice clause that preserves the exceptional generic and shared-account regime in point (c) while imposing the one-identity-to-one-account rule.",
          "source_canonical_ref": "celex:32024R1774/article-Art20-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art21-Para1"
        },
        {
          "edge_id": "recital-14__article-Art21-Para1__restricts",
          "source": "recital-14",
          "target": "article-Art21-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "restricts",
          "confidence": "high",
          "reasoning": "recital-14 restricts article-Art21-Para1 by clarifying that generic or shared accounts are exceptional and may be used only under specified circumstances while preserving accountability for every action performed through them.",
          "source_canonical_ref": "celex:32024R1774/recital-14",
          "target_canonical_ref": "celex:32024R1774/article-Art21-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "As part of their control of access management rights, financial entities shall develop, document, and implement a policy that contains all of the following:",
          "source_line_start": 3992,
          "source_line_end": 3992
        },
        {
          "sequence": 2,
          "text": "For the purposes of point (e)(i), financial entities shall establish the retention period taking into account the business and information security objectives, the reasons for recording the event in the logs, and the results of the ICT risk assessment.",
          "source_line_start": 4231,
          "source_line_end": 4231
        },
        {
          "sequence": 3,
          "text": "For the purposes of point (e)(ii), financial entities shall, where possible, use dedicated accounts for the performance of administrative tasks on ICT systems. Where feasible and appropriate, financial entities shall deploy automated solutions for the privilege access management.",
          "source_line_start": 4232,
          "source_line_end": 4232
        },
        {
          "sequence": 4,
          "text": "For the purposes of point (g)(i), the identification and logging shall be commensurate with the importance of the premises, data centres, sensitive designated areas, and the criticality of the operations or ICT systems located therein.",
          "source_line_start": 4233,
          "source_line_end": 4233
        },
        {
          "sequence": 5,
          "text": "For the purposes of point (g)(iii), the monitoring shall be commensurate to the classification established in accordance with Article 8(1) of Regulation (EU) 2022/2554 and the criticality of the area accessed.",
          "source_line_start": 4234,
          "source_line_end": 4234
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art21-Para1",
      "text_sha256": "a2abaf2c7573bc8d97cbfb2ddcee773cb1d50a5e31a2cc4a80f2a1ba86beb010"
    },
    {
      "id": "article-Art22-Para1",
      "type": "article_paragraph",
      "article_number": 22,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "single",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT-related incident management policy",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "document the ICT-related incident management process referred to in Article 17 of Regulation (EU) 2022/2554;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 4260,
          "source_line_end": 4263
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "establish a list of relevant contacts with internal functions and external stakeholders that are directly involved in ICT operations security, including on:",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 4274,
          "source_line_end": 4277
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "the detection and monitoring of cyber threats;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(i)",
          "source_line_start": 4284,
          "source_line_end": 4287
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "the detection of anomalous activities;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(ii)",
          "source_line_start": 4298,
          "source_line_end": 4301
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "vulnerability management;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(iii)",
          "source_line_start": 4312,
          "source_line_end": 4315
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "establish, implement, and operate technical, organisational, and operational mechanisms to support the ICT-related incident management process, including mechanisms to enable a prompt detection of anomalous activities and behaviours in accordance with Article 23 of this Regulation;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 4330,
          "source_line_end": 4333
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "retain all evidence relating to ICT-related incidents for a period that shall be no longer than necessary for the purposes for which the data are collected, commensurate with the criticality of the affected business functions, supporting processes, and ICT and information assets, in accordance with Article 15 of Commission Delegated Regulation (EU) 2024/1772 (12) and with any applicable retention requirement pursuant to Union law;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 4344,
          "source_line_end": 4348
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "establish and implement mechanisms to analyse significant or recurring ICT-related incidents and patterns in the number and the occurrence of ICT-related incidents.",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 4359,
          "source_line_end": 4362
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER III"
      ],
      "text": "As part of the mechanisms to detect anomalous activities, including ICT network performance issues and ICT-related incidents, financial entities shall develop, document, and implement an ICT-related incident policy through which they shall: (a) document the ICT-related incident management process referred to in Article 17 of Regulation (EU) 2022/2554; (b) establish a list of relevant contacts with internal functions and external stakeholders that are directly involved in ICT operations security, including on: (i) the detection and monitoring of cyber threats; (ii) the detection of anomalous activities; (iii) vulnerability management; (c) establish, implement, and operate technical, organisational, and operational mechanisms to support the ICT-related incident management process, including mechanisms to enable a prompt detection of anomalous activities and behaviours in accordance with Article 23 of this Regulation; (d) retain all evidence relating to ICT-related incidents for a period that shall be no longer than necessary for the purposes for which the data are collected, commensurate with the criticality of the affected business functions, supporting processes, and ICT and information assets, in accordance with Article 15 of Commission Delegated Regulation (EU) 2024/1772 ( 12 ) and with any applicable retention requirement pursuant to Union law; (e) establish and implement mechanisms to analyse significant or recurring ICT-related incidents and patterns in the number and the occurrence of ICT-related incidents. For the purposes of point (d), financial entities shall retain the evidence referred to in that point in a secure manner.",
      "outbound_relations": [
        {
          "edge_id": "article-Art22-Para1__article-Art23-Para2__references",
          "source": "article-Art22-Para1",
          "target": "article-Art23-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art22-Para1 expressly requires its incident-policy mechanisms to enable prompt anomalous-activity detection in accordance with Article 23; article-Art23-Para2 is the narrow paragraph that defines that prompt-detection mechanism and its capabilities.",
          "source_canonical_ref": "celex:32024R1774/article-Art22-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art23-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-18__article-Art22-Para1__concretizes",
          "source": "recital-18",
          "target": "article-Art22-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-18 concretizes article-Art22-Para1 by identifying the incident-policy functions implemented there: an end-to-end management process, internal and external coordination contacts, and detailed analysis of significant or recurring incidents and patterns.",
          "source_canonical_ref": "celex:32024R1774/recital-18",
          "target_canonical_ref": "celex:32024R1774/article-Art22-Para1"
        },
        {
          "edge_id": "recital-20__article-Art22-Para1__concretizes",
          "source": "recital-20",
          "target": "article-Art22-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-20 concretizes the evidence-retention duty in article-Art22-Para1 by explaining that its period must balance effective incident detection against regulatory burden while reflecting data criticality and Union-law retention requirements.",
          "source_canonical_ref": "celex:32024R1774/recital-20",
          "target_canonical_ref": "celex:32024R1774/article-Art22-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "As part of the mechanisms to detect anomalous activities, including ICT network performance issues and ICT-related incidents, financial entities shall develop, document, and implement an ICT-related incident policy through which they shall:",
          "source_line_start": 4253,
          "source_line_end": 4253
        },
        {
          "sequence": 2,
          "text": "For the purposes of point (d), financial entities shall retain the evidence referred to in that point in a secure manner.",
          "source_line_start": 4367,
          "source_line_end": 4367
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art22-Para1",
      "text_sha256": "ecab46ac6336591d1ea9698dae1ceb9403235485ca8c3d40b7923ba810272d34"
    },
    {
      "id": "article-Art23-Para1",
      "type": "article_paragraph",
      "article_number": 23,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Anomalous activities detection and criteria for ICT-related incidents detection and response",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER III"
      ],
      "text": "Financial entities shall set clear roles and responsibilities to effectively detect and respond to ICT-related incidents and anomalous activities.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "recital-19__article-Art23-Para1__concretizes",
          "source": "recital-19",
          "target": "article-Art23-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-19 concretizes article-Art23-Para1 by tying that paragraph's clear-role requirement specifically to responsibility for collecting, monitoring, and analysing information used to detect anomalous activities early and effectively.",
          "source_canonical_ref": "celex:32024R1774/recital-19",
          "target_canonical_ref": "celex:32024R1774/article-Art23-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall set clear roles and responsibilities to effectively detect and respond to ICT-related incidents and anomalous activities.",
          "source_line_start": 4375,
          "source_line_end": 4375
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art23-Para1",
      "text_sha256": "615b879b4eb3761afbd4d4c146407c12455ec4cff5a64deb0e4c18a093c16f4c"
    },
    {
      "id": "article-Art23-Para2",
      "type": "article_paragraph",
      "article_number": 23,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Anomalous activities detection and criteria for ICT-related incidents detection and response",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "collect, monitor, and analyse all of the following:",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 4385,
          "source_line_end": 4388
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "internal and external factors, including at least the logs collected in accordance with Article 12 of this Regulation, information from business and ICT functions, and any problem reported by users of the financial entity;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(i)",
          "source_line_start": 4395,
          "source_line_end": 4398
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "potential internal and external cyber threats, considering scenarios commonly used by threat actors and scenarios based on threat intelligence activity;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(ii)",
          "source_line_start": 4409,
          "source_line_end": 4412
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "ICT-related incident notification from an ICT third-party service provider of the financial entity detected in the ICT systems and networks of the ICT third-party service provider and that may affect the financial entity;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(iii)",
          "source_line_start": 4423,
          "source_line_end": 4426
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "identify anomalous activities and behaviour, and implement tools generating alerts for anomalous activities and behaviour, at least for ICT assets and information assets supporting critical or important functions;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 4441,
          "source_line_end": 4444
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "prioritise the alerts referred to in point (b) to allow for the management of the detected ICT-related incidents within the expected resolution time, as specified by financial entities, both during and outside working hours;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 4455,
          "source_line_end": 4458
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "record, analyse, and evaluate any relevant information on all anomalous activities and behaviours automatically or manually.",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 4469,
          "source_line_end": 4472
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER III"
      ],
      "text": "The mechanism to promptly detect anomalous activities, including ICT network performance issues and ICT-related incidents, as referred to in Article 10(1) of Regulation (EU) 2022/2554, shall enable financial entities to: (a) collect, monitor, and analyse all of the following: (i) internal and external factors, including at least the logs collected in accordance with Article 12 of this Regulation, information from business and ICT functions, and any problem reported by users of the financial entity; (ii) potential internal and external cyber threats, considering scenarios commonly used by threat actors and scenarios based on threat intelligence activity; (iii) ICT-related incident notification from an ICT third-party service provider of the financial entity detected in the ICT systems and networks of the ICT third-party service provider and that may affect the financial entity; (b) identify anomalous activities and behaviour, and implement tools generating alerts for anomalous activities and behaviour, at least for ICT assets and information assets supporting critical or important functions; (c) prioritise the alerts referred to in point (b) to allow for the management of the detected ICT-related incidents within the expected resolution time, as specified by financial entities, both during and outside working hours; (d) record, analyse, and evaluate any relevant information on all anomalous activities and behaviours automatically or manually. For the purposes of point (b), the tools referred to in that point shall contain the tools that provide automated alerts based on pre-defined rules to identify anomalies affecting the completeness and integrity of the data sources or log collection.",
      "outbound_relations": [
        {
          "edge_id": "article-Art23-Para2__article-Art12-Para2__references",
          "source": "article-Art23-Para2",
          "target": "article-Art12-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art23-Para2 expressly includes logs collected under Article 12 among its detection inputs, and article-Art12-Para2 is the narrow target specifying the events, retention, protection, and handling requirements for those logs.",
          "source_canonical_ref": "celex:32024R1774/article-Art23-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art12-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art22-Para1__article-Art23-Para2__references",
          "source": "article-Art22-Para1",
          "target": "article-Art23-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art22-Para1 expressly requires its incident-policy mechanisms to enable prompt anomalous-activity detection in accordance with Article 23; article-Art23-Para2 is the narrow paragraph that defines that prompt-detection mechanism and its capabilities.",
          "source_canonical_ref": "celex:32024R1774/article-Art22-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art23-Para2"
        },
        {
          "edge_id": "recital-19__article-Art23-Para2__concretizes",
          "source": "recital-19",
          "target": "article-Art23-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-19 concretizes article-Art23-Para2 by explaining that its detection mechanism must combine logs with reports from internal functions, external information, and incident notices from ICT third-party providers rather than relying on logs alone.",
          "source_canonical_ref": "celex:32024R1774/recital-19",
          "target_canonical_ref": "celex:32024R1774/article-Art23-Para2"
        },
        {
          "edge_id": "recital-30__article-Art23-Para2__restricts",
          "source": "recital-30",
          "target": "article-Art23-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "restricts",
          "confidence": "high",
          "reasoning": "recital-30 restricts the collection and analysis required by article-Art23-Para2: where incident-detection information is personal data, the Union data-protection regime and data-minimisation principle continue to apply.",
          "source_canonical_ref": "celex:32024R1774/recital-30",
          "target_canonical_ref": "celex:32024R1774/article-Art23-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The mechanism to promptly detect anomalous activities, including ICT network performance issues and ICT-related incidents, as referred to in Article 10(1) of Regulation (EU) 2022/2554, shall enable financial entities to:",
          "source_line_start": 4378,
          "source_line_end": 4378
        },
        {
          "sequence": 2,
          "text": "For the purposes of point (b), the tools referred to in that point shall contain the tools that provide automated alerts based on pre-defined rules to identify anomalies affecting the completeness and integrity of the data sources or log collection.",
          "source_line_start": 4477,
          "source_line_end": 4477
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art23-Para2",
      "text_sha256": "7b53a79335e96b562c3d0e8e44b4bf38b53fd253a99cae4281c2058bcbb75ab7"
    },
    {
      "id": "article-Art23-Para3",
      "type": "article_paragraph",
      "article_number": 23,
      "paragraph_number": "3",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Anomalous activities detection and criteria for ICT-related incidents detection and response",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER III"
      ],
      "text": "Financial entities shall protect any recording of the anomalous activities against tampering and unauthorised access at rest, in transit and, where relevant, in use.",
      "outbound_relations": [],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall protect any recording of the anomalous activities against tampering and unauthorised access at rest, in transit and, where relevant, in use.",
          "source_line_start": 4480,
          "source_line_end": 4480
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art23-Para3",
      "text_sha256": "40fbb8c560adc59e66513375f87265715c6f493598d296ff1f0c30013b7466cd"
    },
    {
      "id": "article-Art23-Para4",
      "type": "article_paragraph",
      "article_number": 23,
      "paragraph_number": "4",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Anomalous activities detection and criteria for ICT-related incidents detection and response",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "the identification of the date and time of occurrence of the anomalous activity;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 4490,
          "source_line_end": 4493
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "the identification of the date and time of detection of the anomalous activity;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 4504,
          "source_line_end": 4507
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "the identification of the type of the anomalous activity.",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 4518,
          "source_line_end": 4521
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER III"
      ],
      "text": "Financial entities shall log all relevant information for each detected anomalous activity enabling: (a) the identification of the date and time of occurrence of the anomalous activity; (b) the identification of the date and time of detection of the anomalous activity; (c) the identification of the type of the anomalous activity.",
      "outbound_relations": [],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall log all relevant information for each detected anomalous activity enabling:",
          "source_line_start": 4483,
          "source_line_end": 4483
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art23-Para4",
      "text_sha256": "5da266f850f506d58d2e95d3d91031ae9b8d7f9f9e654ab50e085e4fc3296674"
    },
    {
      "id": "article-Art23-Para5",
      "type": "article_paragraph",
      "article_number": 23,
      "paragraph_number": "5",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Anomalous activities detection and criteria for ICT-related incidents detection and response",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "indications that malicious activity may have been carried out in an ICT system or network, or that such ICT system or network may have been compromised;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 4535,
          "source_line_end": 4538
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "data losses detected in relation to the availability, authenticity, integrity, and confidentiality of data;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 4549,
          "source_line_end": 4552
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "adverse impact detected on financial entity’s transactions and operations;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 4563,
          "source_line_end": 4566
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "ICT systems’ and network unavailability.",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 4577,
          "source_line_end": 4580
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER III"
      ],
      "text": "Financial entities shall consider all of the following criteria to trigger the ICT-related incident detection and response processes referred to in Article 10(2) of Regulation (EU) 2022/2554: (a) indications that malicious activity may have been carried out in an ICT system or network, or that such ICT system or network may have been compromised; (b) data losses detected in relation to the availability, authenticity, integrity, and confidentiality of data; (c) adverse impact detected on financial entity’s transactions and operations; (d) ICT systems’ and network unavailability.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art23-Para6__article-Art23-Para5__qualifies",
          "source": "article-Art23-Para6",
          "target": "article-Art23-Para5",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "article-Art23-Para6 expressly operates for the purposes of article-Art23-Para5 and qualifies its four trigger criteria by adding the criticality of the affected services as a required consideration.",
          "source_canonical_ref": "celex:32024R1774/article-Art23-Para6",
          "target_canonical_ref": "celex:32024R1774/article-Art23-Para5"
        },
        {
          "edge_id": "recital-21__article-Art23-Para5__provides_guidance_for",
          "source": "recital-21",
          "target": "article-Art23-Para5",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-21 provides guidance for article-Art23-Para5 by clarifying that every listed trigger criterion must be considered, but that the list is non-exhaustive and the listed circumstances need not occur simultaneously.",
          "source_canonical_ref": "celex:32024R1774/recital-21",
          "target_canonical_ref": "celex:32024R1774/article-Art23-Para5"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall consider all of the following criteria to trigger the ICT-related incident detection and response processes referred to in Article 10(2) of Regulation (EU) 2022/2554:",
          "source_line_start": 4528,
          "source_line_end": 4528
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art23-Para5",
      "text_sha256": "dc22f24f027f00f311ebba724d38d51c137ca4d8c66b8abdb8f1b3ee55de1117"
    },
    {
      "id": "article-Art23-Para6",
      "type": "article_paragraph",
      "article_number": 23,
      "paragraph_number": "6",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Anomalous activities detection and criteria for ICT-related incidents detection and response",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER III"
      ],
      "text": "For the purposes of paragraph 5, financial entities shall also consider the criticality of the services affected.",
      "outbound_relations": [
        {
          "edge_id": "article-Art23-Para6__article-Art23-Para5__qualifies",
          "source": "article-Art23-Para6",
          "target": "article-Art23-Para5",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "article-Art23-Para6 expressly operates for the purposes of article-Art23-Para5 and qualifies its four trigger criteria by adding the criticality of the affected services as a required consideration.",
          "source_canonical_ref": "celex:32024R1774/article-Art23-Para6",
          "target_canonical_ref": "celex:32024R1774/article-Art23-Para5"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-21__article-Art23-Para6__provides_guidance_for",
          "source": "recital-21",
          "target": "article-Art23-Para6",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-21 provides guidance for article-Art23-Para6 by explaining that the criticality assessment concerns the importance of the affected ICT services when deciding whether to trigger incident detection and response.",
          "source_canonical_ref": "celex:32024R1774/recital-21",
          "target_canonical_ref": "celex:32024R1774/article-Art23-Para6"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "For the purposes of paragraph 5, financial entities shall also consider the criticality of the services affected.",
          "source_line_start": 4587,
          "source_line_end": 4587
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art23-Para6",
      "text_sha256": "7864e578d082b5426e001d41eff7b796fd639578246ddbf8b8e0d6b0f76d2938"
    },
    {
      "id": "article-Art24-Para1",
      "type": "article_paragraph",
      "article_number": 24,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Components of the ICT business continuity policy",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "a description of:",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 4617,
          "source_line_end": 4620
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "the objectives of the ICT business continuity policy, including the interrelation of ICT and overall business continuity, and considering the results of the business impact analysis (BIA) referred to in Article 11(5) of Regulation (EU) 2022/2554;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(i)",
          "source_line_start": 4627,
          "source_line_end": 4630
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "the scope of the ICT business continuity arrangements, plans, procedures, and mechanisms, including limitations and exclusions;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(ii)",
          "source_line_start": 4641,
          "source_line_end": 4644
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "the timeframe to be covered by the ICT business continuity arrangements, plans, procedures, and mechanisms;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(iii)",
          "source_line_start": 4655,
          "source_line_end": 4658
        },
        {
          "type": "subpoint",
          "marker": "(iv)",
          "text": "the criteria to activate and deactivate ICT business continuity plans, ICT response and recovery plans, and crisis communications plans;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(iv)",
          "source_line_start": 4669,
          "source_line_end": 4672
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "provisions on:",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 4687,
          "source_line_end": 4690
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "the governance and organisation to implement the ICT business continuity policy, including roles, responsibilities and escalation procedures ensuring that sufficient resources are available;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(i)",
          "source_line_start": 4697,
          "source_line_end": 4700
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "the alignment between the ICT business continuity plans and the overall business continuity plans, concerning at least all of the following:",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(ii)",
          "source_line_start": 4711,
          "source_line_end": 4714
        },
        {
          "type": "subpoint",
          "marker": "(1)",
          "text": "potential failure scenarios, including the scenarios referred to in Article 26(2) of this Regulation;",
          "depth": 3,
          "parent_marker": "(ii)",
          "path": "(b)(ii)(1)",
          "source_line_start": 4721,
          "source_line_end": 4724
        },
        {
          "type": "subpoint",
          "marker": "(2)",
          "text": "recovery objectives, specifying that the financial entity shall be able to recover the operations of its critical or important functions after disruptions within a recovery time objective and a recovery point objective;",
          "depth": 3,
          "parent_marker": "(ii)",
          "path": "(b)(ii)(2)",
          "source_line_start": 4735,
          "source_line_end": 4738
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "the development of ICT business continuity plans for severe business disruptions as part of those plans, and the prioritisation of ICT business continuity actions using a risk-based approach;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(iii)",
          "source_line_start": 4753,
          "source_line_end": 4756
        },
        {
          "type": "subpoint",
          "marker": "(iv)",
          "text": "the development, testing and review of ICT response and recovery plans, in accordance with Articles 25 and 26 of this Regulation;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(iv)",
          "source_line_start": 4767,
          "source_line_end": 4770
        },
        {
          "type": "subpoint",
          "marker": "(v)",
          "text": "the review of the effectiveness of the implemented ICT business continuity arrangements, plans, procedures and mechanisms, in accordance with Article 26 of this Regulation;",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(v)",
          "source_line_start": 4781,
          "source_line_end": 4784
        },
        {
          "type": "subpoint",
          "marker": "(vi)",
          "text": "the alignment of the ICT business continuity policy to:",
          "depth": 2,
          "parent_marker": "(b)",
          "path": "(b)(vi)",
          "source_line_start": 4795,
          "source_line_end": 4798
        },
        {
          "type": "subpoint",
          "marker": "(1)",
          "text": "the communication policy referred to in Article 14(2) of Regulation (EU) 2022/2554;",
          "depth": 3,
          "parent_marker": "(vi)",
          "path": "(b)(vi)(1)",
          "source_line_start": 4805,
          "source_line_end": 4808
        },
        {
          "type": "subpoint",
          "marker": "(2)",
          "text": "the communication and crisis communication actions referred to in Article 11(2), point (e), of Regulation (EU) 2022/2554.",
          "depth": 3,
          "parent_marker": "(vi)",
          "path": "(b)(vi)(2)",
          "source_line_start": 4819,
          "source_line_end": 4822
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER IV"
      ],
      "text": "Financial entities shall include in their ICT business continuity policy referred to in Article 11(1) of Regulation (EU) 2022/2554 all of the following: (a) a description of: (i) the objectives of the ICT business continuity policy, including the interrelation of ICT and overall business continuity, and considering the results of the business impact analysis (BIA) referred to in Article 11(5) of Regulation (EU) 2022/2554; (ii) the scope of the ICT business continuity arrangements, plans, procedures, and mechanisms, including limitations and exclusions; (iii) the timeframe to be covered by the ICT business continuity arrangements, plans, procedures, and mechanisms; (iv) the criteria to activate and deactivate ICT business continuity plans, ICT response and recovery plans, and crisis communications plans; (b) provisions on: (i) the governance and organisation to implement the ICT business continuity policy, including roles, responsibilities and escalation procedures ensuring that sufficient resources are available; (ii) the alignment between the ICT business continuity plans and the overall business continuity plans, concerning at least all of the following: (1) potential failure scenarios, including the scenarios referred to in Article 26(2) of this Regulation; (2) recovery objectives, specifying that the financial entity shall be able to recover the operations of its critical or important functions after disruptions within a recovery time objective and a recovery point objective; (iii) the development of ICT business continuity plans for severe business disruptions as part of those plans, and the prioritisation of ICT business continuity actions using a risk-based approach; (iv) the development, testing and review of ICT response and recovery plans, in accordance with Articles 25 and 26 of this Regulation; (v) the review of the effectiveness of the implemented ICT business continuity arrangements, plans, procedures and mechanisms, in accordance with Article 26 of this Regulation; (vi) the alignment of the ICT business continuity policy to: (1) the communication policy referred to in Article 14(2) of Regulation (EU) 2022/2554; (2) the communication and crisis communication actions referred to in Article 11(2), point (e), of Regulation (EU) 2022/2554.",
      "outbound_relations": [
        {
          "edge_id": "article-Art24-Para1__article-Art25-Para1__references",
          "source": "article-Art24-Para1",
          "target": "article-Art25-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art24-Para1 expressly places testing and review within Article 25; article-Art25-Para1 is the narrow anchor that subjects ICT business continuity plan testing to the BIA and ICT risk assessment.",
          "source_canonical_ref": "celex:32024R1774/article-Art24-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para1"
        },
        {
          "edge_id": "article-Art24-Para1__article-Art26-Para1__references",
          "source": "article-Art24-Para1",
          "target": "article-Art26-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art24-Para1 expressly places development, testing, and review of ICT response and recovery plans under Article 26, and article-Art26-Para1 is the narrow anchor defining those plans' required content and recovery objectives.",
          "source_canonical_ref": "celex:32024R1774/article-Art24-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art26-Para1"
        },
        {
          "edge_id": "article-Art24-Para1__article-Art26-Para2__references",
          "source": "article-Art24-Para1",
          "target": "article-Art26-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art24-Para1 expressly requires business-continuity alignment to potential failure scenarios including those in article-Art26-Para2, the narrow paragraph containing the mandatory response-and-recovery scenario set.",
          "source_canonical_ref": "celex:32024R1774/article-Art24-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art26-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art24-Para2__article-Art24-Para1__qualifies",
          "source": "article-Art24-Para2",
          "target": "article-Art24-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "article-Art24-Para2 expressly adds central-counterparty-specific recovery times, interdependencies, and secondary-site arrangements to the general ICT business continuity policy requirements in article-Art24-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art24-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art24-Para1"
        },
        {
          "edge_id": "article-Art24-Para3__article-Art24-Para1__qualifies",
          "source": "article-Art24-Para3",
          "target": "article-Art24-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "article-Art24-Para3 expressly supplements article-Art24-Para1 for central securities depositories by adding infrastructure interdependencies and a two-hour recovery-time objective.",
          "source_canonical_ref": "celex:32024R1774/article-Art24-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art24-Para1"
        },
        {
          "edge_id": "article-Art24-Para4__article-Art24-Para1__qualifies",
          "source": "article-Art24-Para4",
          "target": "article-Art24-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "article-Art24-Para4 expressly supplements article-Art24-Para1 for trading venues by adding a near-two-hour resumption target and a near-zero maximum data-loss requirement.",
          "source_canonical_ref": "celex:32024R1774/article-Art24-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art24-Para1"
        },
        {
          "edge_id": "recital-22__article-Art24-Para1__provides_guidance_for",
          "source": "recital-22",
          "target": "article-Art24-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-22 provides guidance for article-Art24-Para1 by requiring the ICT business continuity policy assembled under that paragraph to integrate incident management, communication, change management, and ICT third-party-provider risk considerations.",
          "source_canonical_ref": "celex:32024R1774/recital-22",
          "target_canonical_ref": "celex:32024R1774/article-Art24-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall include in their ICT business continuity policy referred to in Article 11(1) of Regulation (EU) 2022/2554 all of the following:",
          "source_line_start": 4610,
          "source_line_end": 4610
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art24-Para1",
      "text_sha256": "fd8c76bfdf517a3b1eb0bba819e6f81faea7a1ac20d321f1bc5e01f240d9b579"
    },
    {
      "id": "article-Art24-Para2",
      "type": "article_paragraph",
      "article_number": 24,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Components of the ICT business continuity policy",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "contains a maximum recovery time for their critical functions that is not longer than 2 hours;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 4844,
          "source_line_end": 4847
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "takes into account external links and interdependencies within the financial infrastructures, including trading venues cleared by the central counterparty, securities settlement and payment systems, and credit institutions used by the central counterparty or a linked central counterparty;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 4858,
          "source_line_end": 4861
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "requires that arrangements are in place to:",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 4872,
          "source_line_end": 4875
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "ensure the continuity of critical or important functions of the central counterparty based on disaster scenarios;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(i)",
          "source_line_start": 4882,
          "source_line_end": 4885
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "maintain a secondary processing site capable of ensuring continuity of critical or important functions of the central counterparty identical to the primary site;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(ii)",
          "source_line_start": 4896,
          "source_line_end": 4899
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "maintain or have immediate access to a secondary business site, to allow staff to ensure continuity of the service if the primary location of business is not available;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(iii)",
          "source_line_start": 4910,
          "source_line_end": 4913
        },
        {
          "type": "subpoint",
          "marker": "(iv)",
          "text": "consider the need for additional processing sites, in particular where the diversity of the risk profiles of the primary and secondary sites does not provide sufficient confidence that the central counterparty’s business continuity objectives will be met in all scenarios.",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(iv)",
          "source_line_start": 4924,
          "source_line_end": 4927
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER IV"
      ],
      "text": "In addition to the requirements referred to in paragraph 1, central counterparties shall ensure that their ICT business continuity policy: (a) contains a maximum recovery time for their critical functions that is not longer than 2 hours; (b) takes into account external links and interdependencies within the financial infrastructures, including trading venues cleared by the central counterparty, securities settlement and payment systems, and credit institutions used by the central counterparty or a linked central counterparty; (c) requires that arrangements are in place to: (i) ensure the continuity of critical or important functions of the central counterparty based on disaster scenarios; (ii) maintain a secondary processing site capable of ensuring continuity of critical or important functions of the central counterparty identical to the primary site; (iii) maintain or have immediate access to a secondary business site, to allow staff to ensure continuity of the service if the primary location of business is not available; (iv) consider the need for additional processing sites, in particular where the diversity of the risk profiles of the primary and secondary sites does not provide sufficient confidence that the central counterparty’s business continuity objectives will be met in all scenarios. For the purposes of point (a), central counterparties shall complete end of day procedures and payments on the required time and day in all circumstances. For the purposes of point (c)(i), arrangements referred to in that point shall address the availability of adequate human resources, the maximum downtime of critical functions, and fail over and recovery to a secondary site. For the purposes of point (c)(ii), the secondary processing site referred to in that point shall have a geographical risk profile which is distinct from that of the primary site.",
      "outbound_relations": [
        {
          "edge_id": "article-Art24-Para2__article-Art24-Para1__qualifies",
          "source": "article-Art24-Para2",
          "target": "article-Art24-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "article-Art24-Para2 expressly adds central-counterparty-specific recovery times, interdependencies, and secondary-site arrangements to the general ICT business continuity policy requirements in article-Art24-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art24-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art24-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-24__article-Art24-Para2__provides_guidance_for",
          "source": "recital-24",
          "target": "article-Art24-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-24 explains the legislative basis for the central-counterparty-specific continuity requirements in article-Art24-Para2 by stating that the RTS builds on operational-risk rules already applicable to central counterparties.",
          "source_canonical_ref": "celex:32024R1774/recital-24",
          "target_canonical_ref": "celex:32024R1774/article-Art24-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "In addition to the requirements referred to in paragraph 1, central counterparties shall ensure that their ICT business continuity policy:",
          "source_line_start": 4837,
          "source_line_end": 4837
        },
        {
          "sequence": 2,
          "text": "For the purposes of point (a), central counterparties shall complete end of day procedures and payments on the required time and day in all circumstances.",
          "source_line_start": 4936,
          "source_line_end": 4936
        },
        {
          "sequence": 3,
          "text": "For the purposes of point (c)(i), arrangements referred to in that point shall address the availability of adequate human resources, the maximum downtime of critical functions, and fail over and recovery to a secondary site.",
          "source_line_start": 4937,
          "source_line_end": 4937
        },
        {
          "sequence": 4,
          "text": "For the purposes of point (c)(ii), the secondary processing site referred to in that point shall have a geographical risk profile which is distinct from that of the primary site.",
          "source_line_start": 4938,
          "source_line_end": 4938
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art24-Para2",
      "text_sha256": "97ed3921964e4504b354783d346cf0245c00c01b15c07f93fcd6d46915f158c5"
    },
    {
      "id": "article-Art24-Para3",
      "type": "article_paragraph",
      "article_number": 24,
      "paragraph_number": "3",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Components of the ICT business continuity policy",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "takes into account any links and interdependencies to users, critical utilities and critical service providers, other central securities depositories and other market infrastructures;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 4948,
          "source_line_end": 4951
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "requires its ICT business continuity arrangements to ensure that the recovery time objective for their critical or important functions shall not be longer than 2 hours.",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 4962,
          "source_line_end": 4965
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER IV"
      ],
      "text": "In addition to the requirements referred to in paragraph 1, central securities depositories shall ensure that their ICT business continuity policy: (a) takes into account any links and interdependencies to users, critical utilities and critical service providers, other central securities depositories and other market infrastructures; (b) requires its ICT business continuity arrangements to ensure that the recovery time objective for their critical or important functions shall not be longer than 2 hours.",
      "outbound_relations": [
        {
          "edge_id": "article-Art24-Para3__article-Art24-Para1__qualifies",
          "source": "article-Art24-Para3",
          "target": "article-Art24-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "article-Art24-Para3 expressly supplements article-Art24-Para1 for central securities depositories by adding infrastructure interdependencies and a two-hour recovery-time objective.",
          "source_canonical_ref": "celex:32024R1774/article-Art24-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art24-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-24__article-Art24-Para3__provides_guidance_for",
          "source": "recital-24",
          "target": "article-Art24-Para3",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-24 explains the legislative basis for the central-securities-depository-specific continuity requirements in article-Art24-Para3 by linking the RTS to pre-existing operational-risk rules for those depositories.",
          "source_canonical_ref": "celex:32024R1774/recital-24",
          "target_canonical_ref": "celex:32024R1774/article-Art24-Para3"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "In addition to the requirements referred to in paragraph 1, central securities depositories shall ensure that their ICT business continuity policy:",
          "source_line_start": 4941,
          "source_line_end": 4941
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art24-Para3",
      "text_sha256": "8e3d16ed1b037b4f99ced84061da050cd9a9acf6b27869e9527dcb63c2c6ac14"
    },
    {
      "id": "article-Art24-Para4",
      "type": "article_paragraph",
      "article_number": 24,
      "paragraph_number": "4",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Components of the ICT business continuity policy",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "trading can be resumed within or close to 2 hours of a disruptive incident;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 4979,
          "source_line_end": 4982
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "the maximum amount of data that may be lost from any IT service of the trading venue after a disruptive incident is close to zero.",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 4993,
          "source_line_end": 4996
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER IV"
      ],
      "text": "In addition to the requirements referred to in paragraph 1, trading venues shall ensure that their ICT business continuity policy ensures that: (a) trading can be resumed within or close to 2 hours of a disruptive incident; (b) the maximum amount of data that may be lost from any IT service of the trading venue after a disruptive incident is close to zero.",
      "outbound_relations": [
        {
          "edge_id": "article-Art24-Para4__article-Art24-Para1__qualifies",
          "source": "article-Art24-Para4",
          "target": "article-Art24-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "article-Art24-Para4 expressly supplements article-Art24-Para1 for trading venues by adding a near-two-hour resumption target and a near-zero maximum data-loss requirement.",
          "source_canonical_ref": "celex:32024R1774/article-Art24-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art24-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-24__article-Art24-Para4__provides_guidance_for",
          "source": "recital-24",
          "target": "article-Art24-Para4",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-24 explains why article-Art24-Para4 preserves trading-venue-specific recovery and data-loss requirements within the RTS business-continuity framework.",
          "source_canonical_ref": "celex:32024R1774/recital-24",
          "target_canonical_ref": "celex:32024R1774/article-Art24-Para4"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "In addition to the requirements referred to in paragraph 1, trading venues shall ensure that their ICT business continuity policy ensures that:",
          "source_line_start": 4972,
          "source_line_end": 4972
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art24-Para4",
      "text_sha256": "0c8b470087d68a564c63e134b94cb42757fcfb66076a6a54c00b25caa8a92b1d"
    },
    {
      "id": "article-Art25-Para1",
      "type": "article_paragraph",
      "article_number": 25,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Testing of the ICT business continuity plans",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER IV"
      ],
      "text": "When testing the ICT business continuity plans in accordance with Article 11(6), of Regulation (EU) 2022/2554, financial entities shall take into account the financial entity’s business impact analysis (BIA) and the ICT risk assessment referred to in Article 3(1), point (b), of this Regulation.",
      "outbound_relations": [
        {
          "edge_id": "article-Art25-Para1__article-Art3-Para1__references",
          "source": "article-Art25-Para1",
          "target": "article-Art3-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art25-Para1 expressly requires continuity-plan testing to take account of the ICT risk assessment in article-Art3-Para1, point (b), which defines the assessment procedure and methodology.",
          "source_canonical_ref": "celex:32024R1774/article-Art25-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art3-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art24-Para1__article-Art25-Para1__references",
          "source": "article-Art24-Para1",
          "target": "article-Art25-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art24-Para1 expressly places testing and review within Article 25; article-Art25-Para1 is the narrow anchor that subjects ICT business continuity plan testing to the BIA and ICT risk assessment.",
          "source_canonical_ref": "celex:32024R1774/article-Art24-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para1"
        },
        {
          "edge_id": "article-Art25-Para2__article-Art25-Para1__depends_on",
          "source": "article-Art25-Para2",
          "target": "article-Art25-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art25-Para2 repeatedly identifies its subject as the testing of ICT business continuity plans referred to in article-Art25-Para1, so its scenario, switchover, and response requirements depend on that testing obligation.",
          "source_canonical_ref": "celex:32024R1774/article-Art25-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para1"
        },
        {
          "edge_id": "article-Art25-Para3__article-Art25-Para1__depends_on",
          "source": "article-Art25-Para3",
          "target": "article-Art25-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art25-Para3 expressly identifies the plans whose testing must involve clearing members, external providers, and relevant infrastructure institutions as the plans referred to in article-Art25-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art25-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para1"
        },
        {
          "edge_id": "article-Art25-Para4__article-Art25-Para1__depends_on",
          "source": "article-Art25-Para4",
          "target": "article-Art25-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art25-Para4 expressly identifies the continuity plans whose testing must involve users, utilities, service providers, depositories, and market infrastructures as the plans referred to in article-Art25-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art25-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para1"
        },
        {
          "edge_id": "article-Art25-Para5__article-Art25-Para1__depends_on",
          "source": "article-Art25-Para5",
          "target": "article-Art25-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art25-Para5 makes documentation, analysis, remediation, and management-body reporting conditional on results of the testing defined in article-Art25-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art25-Para5",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "When testing the ICT business continuity plans in accordance with Article 11(6), of Regulation (EU) 2022/2554, financial entities shall take into account the financial entity’s business impact analysis (BIA) and the ICT risk assessment referred to in Article 3(1), point (b), of this Regulation.",
          "source_line_start": 5009,
          "source_line_end": 5009
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art25-Para1",
      "text_sha256": "a5c7b969cff9963b208a203b65d109f08b83803fb43b2664dddcb301ce11e574"
    },
    {
      "id": "article-Art25-Para2",
      "type": "article_paragraph",
      "article_number": 25,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Testing of the ICT business continuity plans",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "be performed on the basis of test scenarios that simulate potential disruptions, including an adequate set of severe but plausible scenarios;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 5019,
          "source_line_end": 5022
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "contain the testing of ICT services provided by ICT third-party service providers, where applicable;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 5033,
          "source_line_end": 5036
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "for financial entities, other than microenterprises, as referred to in Article 11(6), second subparagraph, of Regulation (EU) 2022/2554, contain scenarios of switchover from primary ICT infrastructure to the redundant capacity, backups and redundant facilities;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 5047,
          "source_line_end": 5050
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "be designed to challenge the assumptions on which the business continuity plans are based, including governance arrangements and crisis communication plans;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 5061,
          "source_line_end": 5064
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "contain procedures to verify the ability of the financial entities’ staff, of ICT third-party service providers, of ICT systems, and ICT services to respond adequately to the scenarios duly taken into account in accordance with Article 26(2).",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 5075,
          "source_line_end": 5078
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER IV"
      ],
      "text": "Financial entities shall assess through the testing of their ICT business continuity plans referred to in paragraph 1 whether they are able to ensure the continuity of the financial entity’s critical or important functions. That testing shall: (a) be performed on the basis of test scenarios that simulate potential disruptions, including an adequate set of severe but plausible scenarios; (b) contain the testing of ICT services provided by ICT third-party service providers, where applicable; (c) for financial entities, other than microenterprises, as referred to in Article 11(6), second subparagraph, of Regulation (EU) 2022/2554, contain scenarios of switchover from primary ICT infrastructure to the redundant capacity, backups and redundant facilities; (d) be designed to challenge the assumptions on which the business continuity plans are based, including governance arrangements and crisis communication plans; (e) contain procedures to verify the ability of the financial entities’ staff, of ICT third-party service providers, of ICT systems, and ICT services to respond adequately to the scenarios duly taken into account in accordance with Article 26(2). For the purposes of point (a), financial entities shall always include in the testing the scenarios considered for the development of the business continuity plans. For the purposes of point (b), financial entities shall duly consider scenarios linked to insolvency or failures of the ICT third-party service providers or linked to political risks in the ICT third-party service providers’ jurisdictions, where relevant. For the purposes of point (c), the testing shall verify whether at least critical or important functions can be operated appropriately for a sufficient period of time, and whether the normal functioning may be restored.",
      "outbound_relations": [
        {
          "edge_id": "article-Art25-Para2__article-Art25-Para1__depends_on",
          "source": "article-Art25-Para2",
          "target": "article-Art25-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art25-Para2 repeatedly identifies its subject as the testing of ICT business continuity plans referred to in article-Art25-Para1, so its scenario, switchover, and response requirements depend on that testing obligation.",
          "source_canonical_ref": "celex:32024R1774/article-Art25-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para1"
        },
        {
          "edge_id": "article-Art25-Para2__article-Art26-Para2__references",
          "source": "article-Art25-Para2",
          "target": "article-Art26-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art25-Para2 expressly requires testing staff, systems, and services against scenarios taken into account under article-Art26-Para2, the paragraph listing response-and-recovery scenarios.",
          "source_canonical_ref": "celex:32024R1774/article-Art25-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art26-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art25-Para3__article-Art25-Para2__qualifies",
          "source": "article-Art25-Para3",
          "target": "article-Art25-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "article-Art25-Para3 expressly adds central-counterparty participant requirements to the general continuity-plan testing requirements in article-Art25-Para2.",
          "source_canonical_ref": "celex:32024R1774/article-Art25-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para2"
        },
        {
          "edge_id": "article-Art25-Para4__article-Art25-Para2__qualifies",
          "source": "article-Art25-Para4",
          "target": "article-Art25-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "article-Art25-Para4 expressly adds central-securities-depository participant requirements to the general continuity-plan testing requirements in article-Art25-Para2.",
          "source_canonical_ref": "celex:32024R1774/article-Art25-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para2"
        },
        {
          "edge_id": "recital-23__article-Art25-Para2__provides_guidance_for",
          "source": "recital-23",
          "target": "article-Art25-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-23 provides guidance for article-Art25-Para2 by explaining the purpose of severe-but-plausible scenario testing and of switchover tests: verify redundant capacity, backups, and facilities over a sufficient period and restore normal operation to the recovery objectives.",
          "source_canonical_ref": "celex:32024R1774/recital-23",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall assess through the testing of their ICT business continuity plans referred to in paragraph 1 whether they are able to ensure the continuity of the financial entity’s critical or important functions. That testing shall:",
          "source_line_start": 5012,
          "source_line_end": 5012
        },
        {
          "sequence": 2,
          "text": "For the purposes of point (a), financial entities shall always include in the testing the scenarios considered for the development of the business continuity plans.",
          "source_line_start": 5083,
          "source_line_end": 5083
        },
        {
          "sequence": 3,
          "text": "For the purposes of point (b), financial entities shall duly consider scenarios linked to insolvency or failures of the ICT third-party service providers or linked to political risks in the ICT third-party service providers’ jurisdictions, where relevant.",
          "source_line_start": 5084,
          "source_line_end": 5084
        },
        {
          "sequence": 4,
          "text": "For the purposes of point (c), the testing shall verify whether at least critical or important functions can be operated appropriately for a sufficient period of time, and whether the normal functioning may be restored.",
          "source_line_start": 5085,
          "source_line_end": 5085
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art25-Para2",
      "text_sha256": "5d5b9740e1b5cb9b6080924eaee9ff53dbec934feec9de27bfa5eaaccf303e2d"
    },
    {
      "id": "article-Art25-Para3",
      "type": "article_paragraph",
      "article_number": 25,
      "paragraph_number": "3",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Testing of the ICT business continuity plans",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "clearing members;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 5095,
          "source_line_end": 5098
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "external providers;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 5109,
          "source_line_end": 5112
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "relevant institutions in the financial infrastructure with which central counterparties have identified interdependencies in their business continuity policies.",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 5123,
          "source_line_end": 5126
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER IV"
      ],
      "text": "In addition to the requirements referred to in paragraph 2, central counterparties shall involve in the testing of their ICT business continuity plans referred to in paragraph 1: (a) clearing members; (b) external providers; (c) relevant institutions in the financial infrastructure with which central counterparties have identified interdependencies in their business continuity policies.",
      "outbound_relations": [
        {
          "edge_id": "article-Art25-Para3__article-Art25-Para1__depends_on",
          "source": "article-Art25-Para3",
          "target": "article-Art25-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art25-Para3 expressly identifies the plans whose testing must involve clearing members, external providers, and relevant infrastructure institutions as the plans referred to in article-Art25-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art25-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para1"
        },
        {
          "edge_id": "article-Art25-Para3__article-Art25-Para2__qualifies",
          "source": "article-Art25-Para3",
          "target": "article-Art25-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "article-Art25-Para3 expressly adds central-counterparty participant requirements to the general continuity-plan testing requirements in article-Art25-Para2.",
          "source_canonical_ref": "celex:32024R1774/article-Art25-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-24__article-Art25-Para3__provides_guidance_for",
          "source": "recital-24",
          "target": "article-Art25-Para3",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-24 provides the sectoral context for article-Art25-Para3, which supplements general continuity-plan testing with participation duties tailored to central counterparties.",
          "source_canonical_ref": "celex:32024R1774/recital-24",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para3"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "In addition to the requirements referred to in paragraph 2, central counterparties shall involve in the testing of their ICT business continuity plans referred to in paragraph 1:",
          "source_line_start": 5088,
          "source_line_end": 5088
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art25-Para3",
      "text_sha256": "6738eab8e97e00f8100d36c383dafb701d06c35a7d27b41b17965bb0e8662509"
    },
    {
      "id": "article-Art25-Para4",
      "type": "article_paragraph",
      "article_number": 25,
      "paragraph_number": "4",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Testing of the ICT business continuity plans",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "users of the central securities depositories;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 5140,
          "source_line_end": 5143
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "critical utilities and critical service providers;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 5154,
          "source_line_end": 5157
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "other central securities depositories;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 5168,
          "source_line_end": 5171
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "other market infrastructures;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 5182,
          "source_line_end": 5185
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "any other institutions with which central securities depositories have identified interdependencies in their business continuity policy.",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 5196,
          "source_line_end": 5199
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER IV"
      ],
      "text": "In addition to the requirements referred to in paragraph 2, central securities depositories shall involve in the testing of their ICT business continuity plans referred to in paragraph 1, as appropriate: (a) users of the central securities depositories; (b) critical utilities and critical service providers; (c) other central securities depositories; (d) other market infrastructures; (e) any other institutions with which central securities depositories have identified interdependencies in their business continuity policy.",
      "outbound_relations": [
        {
          "edge_id": "article-Art25-Para4__article-Art25-Para1__depends_on",
          "source": "article-Art25-Para4",
          "target": "article-Art25-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art25-Para4 expressly identifies the continuity plans whose testing must involve users, utilities, service providers, depositories, and market infrastructures as the plans referred to in article-Art25-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art25-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para1"
        },
        {
          "edge_id": "article-Art25-Para4__article-Art25-Para2__qualifies",
          "source": "article-Art25-Para4",
          "target": "article-Art25-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "article-Art25-Para4 expressly adds central-securities-depository participant requirements to the general continuity-plan testing requirements in article-Art25-Para2.",
          "source_canonical_ref": "celex:32024R1774/article-Art25-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-24__article-Art25-Para4__provides_guidance_for",
          "source": "recital-24",
          "target": "article-Art25-Para4",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-24 provides the sectoral context for article-Art25-Para4, which supplements continuity-plan testing with participants and infrastructures relevant specifically to central securities depositories.",
          "source_canonical_ref": "celex:32024R1774/recital-24",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para4"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "In addition to the requirements referred to in paragraph 2, central securities depositories shall involve in the testing of their ICT business continuity plans referred to in paragraph 1, as appropriate:",
          "source_line_start": 5133,
          "source_line_end": 5133
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art25-Para4",
      "text_sha256": "72901c739dda10d9b32d65bf70382fe55fbeb32c441cd1fc7a4745ac2f72653c"
    },
    {
      "id": "article-Art25-Para5",
      "type": "article_paragraph",
      "article_number": 25,
      "paragraph_number": "5",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Testing of the ICT business continuity plans",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER IV"
      ],
      "text": "Financial entities shall document the results of the testing referred to in paragraph 1. Any identified deficiencies resulting from that testing shall be analysed, addressed, and reported to the management body.",
      "outbound_relations": [
        {
          "edge_id": "article-Art25-Para5__article-Art25-Para1__depends_on",
          "source": "article-Art25-Para5",
          "target": "article-Art25-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art25-Para5 makes documentation, analysis, remediation, and management-body reporting conditional on results of the testing defined in article-Art25-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art25-Para5",
          "target_canonical_ref": "celex:32024R1774/article-Art25-Para1"
        }
      ],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall document the results of the testing referred to in paragraph 1. Any identified deficiencies resulting from that testing shall be analysed, addressed, and reported to the management body.",
          "source_line_start": 5206,
          "source_line_end": 5206
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art25-Para5",
      "text_sha256": "b32aa9d2048f2c0a9ce3bb9cf1e0a09a8590bbd77be46c4330b97e95149f2b84"
    },
    {
      "id": "article-Art26-Para1",
      "type": "article_paragraph",
      "article_number": 26,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT response and recovery plans",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "specify the conditions prompting their activation or deactivation, and any exceptions for such activation or deactivation;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 5222,
          "source_line_end": 5225
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "describe what actions are to be taken to ensure the availability, integrity, continuity, and recovery of at least ICT systems and services supporting critical or important functions of the financial entity;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 5236,
          "source_line_end": 5239
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "be designed to meet the recovery objectives of the operations of the financial entities;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 5250,
          "source_line_end": 5253
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "be documented and made available to the staff involved in the execution of ICT response and recovery plans and be readily accessible in case of emergency;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 5264,
          "source_line_end": 5267
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "provide for both short-term and long-term recovery options, including partial systems recovery;",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 5278,
          "source_line_end": 5281
        },
        {
          "type": "point",
          "marker": "(f)",
          "text": "lay down the objectives of ICT response and recovery plans and the conditions to declare a successful execution of those plans.",
          "depth": 1,
          "parent_marker": null,
          "path": "(f)",
          "source_line_start": 5292,
          "source_line_end": 5295
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER IV"
      ],
      "text": "When developing the ICT response and recovery plans referred to in Article 11(3) of Regulation (EU) 2022/2554, financial entities shall take into account the results of the financial entity’s business impact analysis (BIA). Those ICT response and recovery plans shall: (a) specify the conditions prompting their activation or deactivation, and any exceptions for such activation or deactivation; (b) describe what actions are to be taken to ensure the availability, integrity, continuity, and recovery of at least ICT systems and services supporting critical or important functions of the financial entity; (c) be designed to meet the recovery objectives of the operations of the financial entities; (d) be documented and made available to the staff involved in the execution of ICT response and recovery plans and be readily accessible in case of emergency; (e) provide for both short-term and long-term recovery options, including partial systems recovery; (f) lay down the objectives of ICT response and recovery plans and the conditions to declare a successful execution of those plans. For the purposes of point (d), financial entities shall clearly specify roles and responsibilities.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art24-Para1__article-Art26-Para1__references",
          "source": "article-Art24-Para1",
          "target": "article-Art26-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art24-Para1 expressly places development, testing, and review of ICT response and recovery plans under Article 26, and article-Art26-Para1 is the narrow anchor defining those plans' required content and recovery objectives.",
          "source_canonical_ref": "celex:32024R1774/article-Art24-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art26-Para1"
        },
        {
          "edge_id": "article-Art26-Para2__article-Art26-Para1__depends_on",
          "source": "article-Art26-Para2",
          "target": "article-Art26-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art26-Para2 expressly applies its mandatory disruption scenarios to the ICT response and recovery plans referred to in article-Art26-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art26-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art26-Para1"
        },
        {
          "edge_id": "article-Art26-Para3__article-Art26-Para1__qualifies",
          "source": "article-Art26-Para3",
          "target": "article-Art26-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "article-Art26-Para3 qualifies the plans defined in article-Art26-Para1 by requiring alternative options where primary recovery measures may be infeasible in the short term because of cost, risk, logistics, or unforeseen circumstances.",
          "source_canonical_ref": "celex:32024R1774/article-Art26-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art26-Para1"
        },
        {
          "edge_id": "article-Art26-Para4__article-Art26-Para1__depends_on",
          "source": "article-Art26-Para4",
          "target": "article-Art26-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art26-Para4 expressly makes third-party-provider continuity measures part of the ICT response and recovery plans referred to in article-Art26-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art26-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art26-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "When developing the ICT response and recovery plans referred to in Article 11(3) of Regulation (EU) 2022/2554, financial entities shall take into account the results of the financial entity’s business impact analysis (BIA). Those ICT response and recovery plans shall:",
          "source_line_start": 5215,
          "source_line_end": 5215
        },
        {
          "sequence": 2,
          "text": "For the purposes of point (d), financial entities shall clearly specify roles and responsibilities.",
          "source_line_start": 5300,
          "source_line_end": 5300
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art26-Para1",
      "text_sha256": "3714d9fac063337333f6def38ebb9cea2f7371e806f407a73c3ebe8ad31ac267"
    },
    {
      "id": "article-Art26-Para2",
      "type": "article_paragraph",
      "article_number": 26,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT response and recovery plans",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "cyber-attacks and switchovers between the primary ICT infrastructure and the redundant capacity, backups, and redundant facilities;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 5310,
          "source_line_end": 5313
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "scenarios in which the quality of the provision of a critical or important function deteriorates to an unacceptable level or fails, and duly consider the potential impact of the insolvency, or other failures, of any relevant ICT third-party service provider;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 5324,
          "source_line_end": 5327
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "partial or total failure of premises, including office and business premises, and data centres;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 5338,
          "source_line_end": 5341
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "substantial failure of ICT assets or of the communication infrastructure;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 5352,
          "source_line_end": 5355
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "the non-availability of a critical number of staff or staff members in charge of guaranteeing the continuity of operations;",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 5366,
          "source_line_end": 5369
        },
        {
          "type": "point",
          "marker": "(f)",
          "text": "impact of climate change and environment degradation related events, natural disasters, pandemics, and physical attacks, including intrusions and terrorist attacks;",
          "depth": 1,
          "parent_marker": null,
          "path": "(f)",
          "source_line_start": 5380,
          "source_line_end": 5383
        },
        {
          "type": "point",
          "marker": "(g)",
          "text": "insider attacks;",
          "depth": 1,
          "parent_marker": null,
          "path": "(g)",
          "source_line_start": 5394,
          "source_line_end": 5397
        },
        {
          "type": "point",
          "marker": "(h)",
          "text": "political and social instability, including, where relevant, in the ICT third-party service provider’s jurisdiction and the location where the data are stored and processed;",
          "depth": 1,
          "parent_marker": null,
          "path": "(h)",
          "source_line_start": 5408,
          "source_line_end": 5411
        },
        {
          "type": "point",
          "marker": "(i)",
          "text": "widespread power outages.",
          "depth": 1,
          "parent_marker": null,
          "path": "(i)",
          "source_line_start": 5422,
          "source_line_end": 5425
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER IV"
      ],
      "text": "The ICT response and recovery plans referred to in paragraph 1 shall identify relevant scenarios, including scenarios of severe business disruptions and increased likelihood of occurrence of disruption. Those plans shall develop scenarios based on current information on threats and on lessons learned from previous occurrences of business disruptions. Financial entities shall duly take into account all of the following scenarios: (a) cyber-attacks and switchovers between the primary ICT infrastructure and the redundant capacity, backups, and redundant facilities; (b) scenarios in which the quality of the provision of a critical or important function deteriorates to an unacceptable level or fails, and duly consider the potential impact of the insolvency, or other failures, of any relevant ICT third-party service provider; (c) partial or total failure of premises, including office and business premises, and data centres; (d) substantial failure of ICT assets or of the communication infrastructure; (e) the non-availability of a critical number of staff or staff members in charge of guaranteeing the continuity of operations; (f) impact of climate change and environment degradation related events, natural disasters, pandemics, and physical attacks, including intrusions and terrorist attacks; (g) insider attacks; (h) political and social instability, including, where relevant, in the ICT third-party service provider’s jurisdiction and the location where the data are stored and processed; (i) widespread power outages.",
      "outbound_relations": [
        {
          "edge_id": "article-Art26-Para2__article-Art26-Para1__depends_on",
          "source": "article-Art26-Para2",
          "target": "article-Art26-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art26-Para2 expressly applies its mandatory disruption scenarios to the ICT response and recovery plans referred to in article-Art26-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art26-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art26-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art24-Para1__article-Art26-Para2__references",
          "source": "article-Art24-Para1",
          "target": "article-Art26-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art24-Para1 expressly requires business-continuity alignment to potential failure scenarios including those in article-Art26-Para2, the narrow paragraph containing the mandatory response-and-recovery scenario set.",
          "source_canonical_ref": "celex:32024R1774/article-Art24-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art26-Para2"
        },
        {
          "edge_id": "article-Art25-Para2__article-Art26-Para2__references",
          "source": "article-Art25-Para2",
          "target": "article-Art26-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art25-Para2 expressly requires testing staff, systems, and services against scenarios taken into account under article-Art26-Para2, the paragraph listing response-and-recovery scenarios.",
          "source_canonical_ref": "celex:32024R1774/article-Art25-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art26-Para2"
        },
        {
          "edge_id": "recital-23__article-Art26-Para2__provides_guidance_for",
          "source": "recital-23",
          "target": "article-Art26-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-23 provides guidance for article-Art26-Para2 by directing entities to assess the relevance and plausibility of the response-and-recovery scenarios listed there and to consider whether alternative scenarios are needed.",
          "source_canonical_ref": "celex:32024R1774/recital-23",
          "target_canonical_ref": "celex:32024R1774/article-Art26-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The ICT response and recovery plans referred to in paragraph 1 shall identify relevant scenarios, including scenarios of severe business disruptions and increased likelihood of occurrence of disruption. Those plans shall develop scenarios based on current information on threats and on lessons learned from previous occurrences of business disruptions. Financial entities shall duly take into account all of the following scenarios:",
          "source_line_start": 5303,
          "source_line_end": 5303
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art26-Para2",
      "text_sha256": "5665b1012a8549331c4e61eb8652abfe11100689f59de722cd875d6135b1527b"
    },
    {
      "id": "article-Art26-Para3",
      "type": "article_paragraph",
      "article_number": 26,
      "paragraph_number": "3",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT response and recovery plans",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER IV"
      ],
      "text": "Where the primary recovery measures may not be feasible in the short term because of costs, risks, logistics, or unforeseen circumstances, the ICT response and recovery plans referred to in paragraph 1 shall consider alternative options.",
      "outbound_relations": [
        {
          "edge_id": "article-Art26-Para3__article-Art26-Para1__qualifies",
          "source": "article-Art26-Para3",
          "target": "article-Art26-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "article-Art26-Para3 qualifies the plans defined in article-Art26-Para1 by requiring alternative options where primary recovery measures may be infeasible in the short term because of cost, risk, logistics, or unforeseen circumstances.",
          "source_canonical_ref": "celex:32024R1774/article-Art26-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art26-Para1"
        }
      ],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Where the primary recovery measures may not be feasible in the short term because of costs, risks, logistics, or unforeseen circumstances, the ICT response and recovery plans referred to in paragraph 1 shall consider alternative options.",
          "source_line_start": 5432,
          "source_line_end": 5432
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art26-Para3",
      "text_sha256": "5a1dcb31a0a170e55820a878c304852a2bb66f6ee9aa4f6cdd2b530cd14c1e95"
    },
    {
      "id": "article-Art26-Para4",
      "type": "article_paragraph",
      "article_number": 26,
      "paragraph_number": "4",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT response and recovery plans",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER IV"
      ],
      "text": "As part of the ICT response and recovery plans referred to in paragraph 1, financial entities shall consider and implement continuity measures to mitigate failures of ICT third-party service providers of ICT services supporting critical or important functions of the financial entity.",
      "outbound_relations": [
        {
          "edge_id": "article-Art26-Para4__article-Art26-Para1__depends_on",
          "source": "article-Art26-Para4",
          "target": "article-Art26-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art26-Para4 expressly makes third-party-provider continuity measures part of the ICT response and recovery plans referred to in article-Art26-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art26-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art26-Para1"
        }
      ],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "As part of the ICT response and recovery plans referred to in paragraph 1, financial entities shall consider and implement continuity measures to mitigate failures of ICT third-party service providers of ICT services supporting critical or important functions of the financial entity.",
          "source_line_start": 5435,
          "source_line_end": 5435
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art26-Para4",
      "text_sha256": "ec5f2660ec53025a0d030db4064d967bc61a96e52f82e061082272325fc1bb55"
    },
    {
      "id": "article-Art27-Para1",
      "type": "article_paragraph",
      "article_number": 27,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Format and content of the report on the review of the ICT risk management framework",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE II",
        "CHAPTER V"
      ],
      "text": "Financial entities shall submit the report on the review of the ICT risk management framework referred to in Article 6(5) of Regulation (EU) 2022/2554 in a searchable electronic format.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art27-Para2__article-Art27-Para1__depends_on",
          "source": "article-Art27-Para2",
          "target": "article-Art27-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art27-Para2 defines the mandatory information for the report referred to in article-Art27-Para1 and therefore depends on that paragraph's report and electronic-format obligation.",
          "source_canonical_ref": "celex:32024R1774/article-Art27-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art27-Para1"
        },
        {
          "edge_id": "recital-25__article-Art27-Para1__provides_guidance_for",
          "source": "recital-25",
          "target": "article-Art27-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "provides_guidance_for",
          "confidence": "high",
          "reasoning": "recital-25 explains the processing and transmission rationale for article-Art27-Para1 requiring the DORA Article 6(5) ICT-risk-framework review report to be submitted in a searchable electronic format.",
          "source_canonical_ref": "celex:32024R1774/recital-25",
          "target_canonical_ref": "celex:32024R1774/article-Art27-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall submit the report on the review of the ICT risk management framework referred to in Article 6(5) of Regulation (EU) 2022/2554 in a searchable electronic format.",
          "source_line_start": 5456,
          "source_line_end": 5456
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art27-Para1",
      "text_sha256": "a74292a9c5fd204fdf10fc073389300b77ca190e51049ccc5d0fc5cb42f761f9"
    },
    {
      "id": "article-Art27-Para2",
      "type": "article_paragraph",
      "article_number": 27,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Format and content of the report on the review of the ICT risk management framework",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "an introductory section that:",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 5466,
          "source_line_end": 5469
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "clearly identifies the financial entity that is the subject of the report, and describes its group structure, where relevant;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(i)",
          "source_line_start": 5476,
          "source_line_end": 5479
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "describes the context of the report in terms of the nature, scale, and complexity of the financial entity’s services, activities, and operations, its organisation, identified critical functions, strategy, major ongoing projects or activities, relationships and its dependence on in-house and contracted ICT services and systems or the implications that a total loss or severe degradation of such systems would have in terms of critical or important functions and market efficiency;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(ii)",
          "source_line_start": 5490,
          "source_line_end": 5493
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "summarises the major changes in the ICT risk management framework since the previous report submitted;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(iii)",
          "source_line_start": 5504,
          "source_line_end": 5507
        },
        {
          "type": "subpoint",
          "marker": "(iv)",
          "text": "provides an executive level summary of the current and near-term ICT risk profile, threat landscape, the assessed effectiveness of its controls, and the security posture of the financial entity;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(iv)",
          "source_line_start": 5518,
          "source_line_end": 5521
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "the date of the approval of the report by the management body of the financial entity;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 5536,
          "source_line_end": 5539
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "a description of the reason for the review of the ICT risk management framework in accordance with Article 6(5) of Regulation (EU) 2022/2554.;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 5550,
          "source_line_end": 5553
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "the start and end dates of the review period;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 5564,
          "source_line_end": 5567
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "an indication of the function responsible for the review;",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 5578,
          "source_line_end": 5581
        },
        {
          "type": "point",
          "marker": "(f)",
          "text": "a description of the major changes and improvements to the ICT risk management framework since the previous review;",
          "depth": 1,
          "parent_marker": null,
          "path": "(f)",
          "source_line_start": 5592,
          "source_line_end": 5595
        },
        {
          "type": "point",
          "marker": "(g)",
          "text": "a summary of the findings of the review and detailed analysis and assessment of the severity of the weaknesses, deficiencies, and gaps in the ICT risk management framework during the review period;",
          "depth": 1,
          "parent_marker": null,
          "path": "(g)",
          "source_line_start": 5606,
          "source_line_end": 5609
        },
        {
          "type": "point",
          "marker": "(h)",
          "text": "a description of the measures to address identified weaknesses, deficiencies, and gaps, including all of the following:",
          "depth": 1,
          "parent_marker": null,
          "path": "(h)",
          "source_line_start": 5620,
          "source_line_end": 5623
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "a summary of measures taken to remediate to identified weaknesses, deficiencies and gaps;",
          "depth": 2,
          "parent_marker": "(h)",
          "path": "(h)(i)",
          "source_line_start": 5630,
          "source_line_end": 5633
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "an expected date for implementing the measures and dates related to the internal control of the implementation, including information on the state of progress of the implementation of those measures as at the date of drafting of the report, explaining, where applicable, if there is a risk that deadlines may not be respected;",
          "depth": 2,
          "parent_marker": "(h)",
          "path": "(h)(ii)",
          "source_line_start": 5644,
          "source_line_end": 5647
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "tools to be used, and the identification of the function responsible for carrying out the measures, detailing whether the tools and functions are internal or external;",
          "depth": 2,
          "parent_marker": "(h)",
          "path": "(h)(iii)",
          "source_line_start": 5658,
          "source_line_end": 5661
        },
        {
          "type": "subpoint",
          "marker": "(iv)",
          "text": "a description of the impact of the changes envisaged in the measures on the financial entity’s budgetary, human, and material resources, including resources dedicated to the implementation of any corrective measures;",
          "depth": 2,
          "parent_marker": "(h)",
          "path": "(h)(iv)",
          "source_line_start": 5672,
          "source_line_end": 5675
        },
        {
          "type": "subpoint",
          "marker": "(v)",
          "text": "information on the process for informing the competent authority, where appropriate;",
          "depth": 2,
          "parent_marker": "(h)",
          "path": "(h)(v)",
          "source_line_start": 5686,
          "source_line_end": 5689
        },
        {
          "type": "subpoint",
          "marker": "(vi)",
          "text": "where the weaknesses, deficiencies, or gaps identified are not subject to corrective measures, a detailed explanation of the criteria used to analyse the impact of those weaknesses, deficiencies, or gaps, to evaluate the related residual ICT risk, and of the criteria used to accept the related residual risk;",
          "depth": 2,
          "parent_marker": "(h)",
          "path": "(h)(vi)",
          "source_line_start": 5700,
          "source_line_end": 5703
        },
        {
          "type": "point",
          "marker": "(i)",
          "text": "information on planned further developments of the ICT risk management framework;",
          "depth": 1,
          "parent_marker": null,
          "path": "(i)",
          "source_line_start": 5718,
          "source_line_end": 5721
        },
        {
          "type": "point",
          "marker": "(j)",
          "text": "conclusions resulting from the review of the ICT risk management framework;",
          "depth": 1,
          "parent_marker": null,
          "path": "(j)",
          "source_line_start": 5732,
          "source_line_end": 5735
        },
        {
          "type": "point",
          "marker": "(k)",
          "text": "information on past reviews, including:",
          "depth": 1,
          "parent_marker": null,
          "path": "(k)",
          "source_line_start": 5746,
          "source_line_end": 5749
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "a list of past reviews to date;",
          "depth": 2,
          "parent_marker": "(k)",
          "path": "(k)(i)",
          "source_line_start": 5756,
          "source_line_end": 5759
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "where applicable, a state of implementation of the corrective measures identified by the last report;",
          "depth": 2,
          "parent_marker": "(k)",
          "path": "(k)(ii)",
          "source_line_start": 5770,
          "source_line_end": 5773
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "where the proposed corrective measures in past reviews have proven ineffective or have created unexpected challenges, a description of how those corrective measures could be improved or of those unexpected challenges;",
          "depth": 2,
          "parent_marker": "(k)",
          "path": "(k)(iii)",
          "source_line_start": 5784,
          "source_line_end": 5787
        },
        {
          "type": "point",
          "marker": "(l)",
          "text": "sources of information used in the preparation of the report, including all of the following:",
          "depth": 1,
          "parent_marker": null,
          "path": "(l)",
          "source_line_start": 5802,
          "source_line_end": 5805
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "for financial entities other than microenterprises as referred to in Article 6(6) of Regulation (EU) 2022/2554, the results of internal audits;",
          "depth": 2,
          "parent_marker": "(l)",
          "path": "(l)(i)",
          "source_line_start": 5812,
          "source_line_end": 5815
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "the results of compliance assessments;",
          "depth": 2,
          "parent_marker": "(l)",
          "path": "(l)(ii)",
          "source_line_start": 5826,
          "source_line_end": 5829
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "results of digital operational resilience testing, and where applicable the results of advanced testing, based on threat-led penetration testing (TLPT), of ICT tools, systems, and processes;",
          "depth": 2,
          "parent_marker": "(l)",
          "path": "(l)(iii)",
          "source_line_start": 5840,
          "source_line_end": 5843
        },
        {
          "type": "subpoint",
          "marker": "(iv)",
          "text": "external sources.",
          "depth": 2,
          "parent_marker": "(l)",
          "path": "(l)(iv)",
          "source_line_start": 5854,
          "source_line_end": 5857
        }
      ],
      "ancestry": [
        "TITLE II",
        "CHAPTER V"
      ],
      "text": "Financial entities shall include all of the following information in the report referred to in paragraph 1: (a) an introductory section that: (i) clearly identifies the financial entity that is the subject of the report, and describes its group structure, where relevant; (ii) describes the context of the report in terms of the nature, scale, and complexity of the financial entity’s services, activities, and operations, its organisation, identified critical functions, strategy, major ongoing projects or activities, relationships and its dependence on in-house and contracted ICT services and systems or the implications that a total loss or severe degradation of such systems would have in terms of critical or important functions and market efficiency; (iii) summarises the major changes in the ICT risk management framework since the previous report submitted; (iv) provides an executive level summary of the current and near-term ICT risk profile, threat landscape, the assessed effectiveness of its controls, and the security posture of the financial entity; (b) the date of the approval of the report by the management body of the financial entity; (c) a description of the reason for the review of the ICT risk management framework in accordance with Article 6(5) of Regulation (EU) 2022/2554.; (d) the start and end dates of the review period; (e) an indication of the function responsible for the review; (f) a description of the major changes and improvements to the ICT risk management framework since the previous review; (g) a summary of the findings of the review and detailed analysis and assessment of the severity of the weaknesses, deficiencies, and gaps in the ICT risk management framework during the review period; (h) a description of the measures to address identified weaknesses, deficiencies, and gaps, including all of the following: (i) a summary of measures taken to remediate to identified weaknesses, deficiencies and gaps; (ii) an expected date for implementing the measures and dates related to the internal control of the implementation, including information on the state of progress of the implementation of those measures as at the date of drafting of the report, explaining, where applicable, if there is a risk that deadlines may not be respected; (iii) tools to be used, and the identification of the function responsible for carrying out the measures, detailing whether the tools and functions are internal or external; (iv) a description of the impact of the changes envisaged in the measures on the financial entity’s budgetary, human, and material resources, including resources dedicated to the implementation of any corrective measures; (v) information on the process for informing the competent authority, where appropriate; (vi) where the weaknesses, deficiencies, or gaps identified are not subject to corrective measures, a detailed explanation of the criteria used to analyse the impact of those weaknesses, deficiencies, or gaps, to evaluate the related residual ICT risk, and of the criteria used to accept the related residual risk; (i) information on planned further developments of the ICT risk management framework; (j) conclusions resulting from the review of the ICT risk management framework; (k) information on past reviews, including: (i) a list of past reviews to date; (ii) where applicable, a state of implementation of the corrective measures identified by the last report; (iii) where the proposed corrective measures in past reviews have proven ineffective or have created unexpected challenges, a description of how those corrective measures could be improved or of those unexpected challenges; (l) sources of information used in the preparation of the report, including all of the following: (i) for financial entities other than microenterprises as referred to in Article 6(6) of Regulation (EU) 2022/2554, the results of internal audits; (ii) the results of compliance assessments; (iii) results of digital operational resilience testing, and where applicable the results of advanced testing, based on threat-led penetration testing (TLPT), of ICT tools, systems, and processes; (iv) external sources. For the purposes of point (c), where the review was initiated following supervisory instructions, or conclusions derived from relevant digital operational resilience testing or audit processes, the report shall contain explicit references to such instructions or conclusions, allowing for the identification of the reason for initiating the review. Where the review was initiated following ICT-related incidents, the report shall contain the list of all ICT-related incidents with incident root-cause analysis. For the purposes of point (f), the description shall contain an analysis of the impact of the changes on the financial entity’s digital operational resilience strategy, on the financial entity’s ICT internal control framework, and on the financial entity’s ICT risk management governance.",
      "outbound_relations": [
        {
          "edge_id": "article-Art27-Para2__article-Art27-Para1__depends_on",
          "source": "article-Art27-Para2",
          "target": "article-Art27-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art27-Para2 defines the mandatory information for the report referred to in article-Art27-Para1 and therefore depends on that paragraph's report and electronic-format obligation.",
          "source_canonical_ref": "celex:32024R1774/article-Art27-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art27-Para1"
        }
      ],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Financial entities shall include all of the following information in the report referred to in paragraph 1:",
          "source_line_start": 5459,
          "source_line_end": 5459
        },
        {
          "sequence": 2,
          "text": "For the purposes of point (c), where the review was initiated following supervisory instructions, or conclusions derived from relevant digital operational resilience testing or audit processes, the report shall contain explicit references to such instructions or conclusions, allowing for the identification of the reason for initiating the review. Where the review was initiated following ICT-related incidents, the report shall contain the list of all ICT-related incidents with incident root-cause analysis.",
          "source_line_start": 5866,
          "source_line_end": 5866
        },
        {
          "sequence": 3,
          "text": "For the purposes of point (f), the description shall contain an analysis of the impact of the changes on the financial entity’s digital operational resilience strategy, on the financial entity’s ICT internal control framework, and on the financial entity’s ICT risk management governance.",
          "source_line_start": 5867,
          "source_line_end": 5867
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art27-Para2",
      "text_sha256": "7def705499812a2cf700950de847864e1469b89ebd01e81ce608cfccee0c556c"
    },
    {
      "id": "article-Art28-Para1",
      "type": "article_paragraph",
      "article_number": 28,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Governance and organisation",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER I"
      ],
      "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall have in place an internal governance and control framework that ensures an effective and prudent management of ICT risk to achieve a high level of digital operational resilience.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art28-Para2__article-Art28-Para1__depends_on",
          "source": "article-Art28-Para2",
          "target": "article-Art28-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art28-Para2 expressly applies its management-body duties to the financial entities identified in article-Art28-Para1 and to the simplified framework established there.",
          "source_canonical_ref": "celex:32024R1774/article-Art28-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art28-Para1"
        },
        {
          "edge_id": "article-Art28-Para3__article-Art28-Para1__depends_on",
          "source": "article-Art28-Para3",
          "target": "article-Art28-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art28-Para3 expressly applies its outsourcing option and retained-responsibility rule to the financial entities referred to in article-Art28-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art28-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art28-Para1"
        },
        {
          "edge_id": "article-Art28-Para4__article-Art28-Para1__depends_on",
          "source": "article-Art28-Para4",
          "target": "article-Art28-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art28-Para4 expressly applies segregation and independence requirements for control and internal-audit functions to the financial entities referred to in article-Art28-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art28-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art28-Para1"
        },
        {
          "edge_id": "article-Art28-Para5__article-Art28-Para1__depends_on",
          "source": "article-Art28-Para5",
          "target": "article-Art28-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art28-Para5 expressly subjects the simplified ICT risk management framework of the financial entities identified in article-Art28-Para1 to independent, risk-commensurate internal audit.",
          "source_canonical_ref": "celex:32024R1774/article-Art28-Para5",
          "target_canonical_ref": "celex:32024R1774/article-Art28-Para1"
        },
        {
          "edge_id": "article-Art28-Para6__article-Art28-Para1__depends_on",
          "source": "article-Art28-Para6",
          "target": "article-Art28-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art28-Para6 expressly assigns remediation of critical audit findings to the financial entities referred to in article-Art28-Para1, whose simplified governance framework supplies the rule's scope.",
          "source_canonical_ref": "celex:32024R1774/article-Art28-Para6",
          "target_canonical_ref": "celex:32024R1774/article-Art28-Para1"
        },
        {
          "edge_id": "recital-26__article-Art28-Para1__concretizes",
          "source": "recital-26",
          "target": "article-Art28-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-26 concretizes article-Art28-Para1 by identifying an internal governance and control framework as the organisational basis for effective and sound ICT risk management by simplified-framework entities.",
          "source_canonical_ref": "celex:32024R1774/recital-26",
          "target_canonical_ref": "celex:32024R1774/article-Art28-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall have in place an internal governance and control framework that ensures an effective and prudent management of ICT risk to achieve a high level of digital operational resilience.",
          "source_line_start": 5896,
          "source_line_end": 5896
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art28-Para1",
      "text_sha256": "7f92057f6a9ead57a572247ed4a8dfeb9ac277666303f2533e2582f6df8c801f"
    },
    {
      "id": "article-Art28-Para2",
      "type": "article_paragraph",
      "article_number": 28,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Governance and organisation",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "bears the overall responsibility for ensuring that the simplified ICT risk management framework allows for the achievement of the financial entity’s business strategy in accordance with the risk appetite of that financial entity, and ensures that ICT risk is considered in that context;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 5906,
          "source_line_end": 5909
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "sets clear roles and responsibilities for all ICT-related tasks;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 5920,
          "source_line_end": 5923
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "sets out information security objectives and ICT requirements;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 5934,
          "source_line_end": 5937
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "approves, oversees, and periodically reviews:",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 5948,
          "source_line_end": 5951
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "the classification of information assets of the financial entity as referred to in Article 30(1) of this Regulation, the list of main risks identified, and the business impact analysis and related policies;",
          "depth": 2,
          "parent_marker": "(d)",
          "path": "(d)(i)",
          "source_line_start": 5958,
          "source_line_end": 5961
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "the business continuity plans of the financial entity, and the response and recovery measures referred to in Article 16(1), point (f), of Regulation (EU) 2022/2554;",
          "depth": 2,
          "parent_marker": "(d)",
          "path": "(d)(ii)",
          "source_line_start": 5972,
          "source_line_end": 5975
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "allocates and reviews at least once a year the budget necessary to fulfil the financial entity’s digital operational resilience needs in respect of all types of resources, including relevant ICT security awareness programmes and digital operational resilience training and ICT skills for all staff;",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 5990,
          "source_line_end": 5993
        },
        {
          "type": "point",
          "marker": "(f)",
          "text": "specifies and implements the policies and measures included in Chapters I, II and III of this Title to identify, assess and manage the ICT risk the financial entity is exposed to;",
          "depth": 1,
          "parent_marker": null,
          "path": "(f)",
          "source_line_start": 6004,
          "source_line_end": 6007
        },
        {
          "type": "point",
          "marker": "(g)",
          "text": "identifies and implements procedures, ICT protocols, and tools that are necessary to protect all information assets and ICT assets;",
          "depth": 1,
          "parent_marker": null,
          "path": "(g)",
          "source_line_start": 6018,
          "source_line_end": 6021
        },
        {
          "type": "point",
          "marker": "(h)",
          "text": "ensures that the staff of the financial entity is kept up to date with sufficient knowledge and skills to understand and assess ICT risk and its impact on the operations of the financial entity, commensurate to the ICT risk being managed;",
          "depth": 1,
          "parent_marker": null,
          "path": "(h)",
          "source_line_start": 6032,
          "source_line_end": 6035
        },
        {
          "type": "point",
          "marker": "(i)",
          "text": "establishes reporting arrangements, including the frequency, form, and content of reporting to the management body on the information security and digital operational resilience.",
          "depth": 1,
          "parent_marker": null,
          "path": "(i)",
          "source_line_start": 6046,
          "source_line_end": 6049
        }
      ],
      "ancestry": [
        "TITLE III",
        "CHAPTER I"
      ],
      "text": "The financial entities referred to in paragraph 1 shall, as part of their simplified ICT risk management framework, ensure that their management body: (a) bears the overall responsibility for ensuring that the simplified ICT risk management framework allows for the achievement of the financial entity’s business strategy in accordance with the risk appetite of that financial entity, and ensures that ICT risk is considered in that context; (b) sets clear roles and responsibilities for all ICT-related tasks; (c) sets out information security objectives and ICT requirements; (d) approves, oversees, and periodically reviews: (i) the classification of information assets of the financial entity as referred to in Article 30(1) of this Regulation, the list of main risks identified, and the business impact analysis and related policies; (ii) the business continuity plans of the financial entity, and the response and recovery measures referred to in Article 16(1), point (f), of Regulation (EU) 2022/2554; (e) allocates and reviews at least once a year the budget necessary to fulfil the financial entity’s digital operational resilience needs in respect of all types of resources, including relevant ICT security awareness programmes and digital operational resilience training and ICT skills for all staff; (f) specifies and implements the policies and measures included in Chapters I, II and III of this Title to identify, assess and manage the ICT risk the financial entity is exposed to; (g) identifies and implements procedures, ICT protocols, and tools that are necessary to protect all information assets and ICT assets; (h) ensures that the staff of the financial entity is kept up to date with sufficient knowledge and skills to understand and assess ICT risk and its impact on the operations of the financial entity, commensurate to the ICT risk being managed; (i) establishes reporting arrangements, including the frequency, form, and content of reporting to the management body on the information security and digital operational resilience.",
      "outbound_relations": [
        {
          "edge_id": "article-Art28-Para2__article-Art28-Para1__depends_on",
          "source": "article-Art28-Para2",
          "target": "article-Art28-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art28-Para2 expressly applies its management-body duties to the financial entities identified in article-Art28-Para1 and to the simplified framework established there.",
          "source_canonical_ref": "celex:32024R1774/article-Art28-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art28-Para1"
        },
        {
          "edge_id": "article-Art28-Para2__article-Art30-Para1__references",
          "source": "article-Art28-Para2",
          "target": "article-Art30-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art28-Para2 expressly requires management-body approval and review of the information-asset classification in article-Art30-Para1, which is the narrow paragraph imposing identification and classification duties.",
          "source_canonical_ref": "celex:32024R1774/article-Art28-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "recital-26__article-Art28-Para2__concretizes",
          "source": "recital-26",
          "target": "article-Art28-Para2",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-26 concretizes the clear-responsibility element of article-Art28-Para2 by requiring governance arrangements with unambiguous responsibilities for the simplified ICT risk management framework.",
          "source_canonical_ref": "celex:32024R1774/recital-26",
          "target_canonical_ref": "celex:32024R1774/article-Art28-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in paragraph 1 shall, as part of their simplified ICT risk management framework, ensure that their management body:",
          "source_line_start": 5899,
          "source_line_end": 5899
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art28-Para2",
      "text_sha256": "855b20aab96e2178be6b60e8ffc1cd0c6c08bd5c7c2187298922da06d6570cdb"
    },
    {
      "id": "article-Art28-Para3",
      "type": "article_paragraph",
      "article_number": 28,
      "paragraph_number": "3",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Governance and organisation",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER I"
      ],
      "text": "The financial entities referred to in paragraph 1 may, in accordance with Union and national sectoral law, outsource the tasks of verifying compliance with ICT risk management requirements to ICT intra-group or ICT third-party service providers. In case of such outsourcing, financial entities shall remain fully responsible for the verification of compliance with the ICT risk management requirements.",
      "outbound_relations": [
        {
          "edge_id": "article-Art28-Para3__article-Art28-Para1__depends_on",
          "source": "article-Art28-Para3",
          "target": "article-Art28-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art28-Para3 expressly applies its outsourcing option and retained-responsibility rule to the financial entities referred to in article-Art28-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art28-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art28-Para1"
        }
      ],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in paragraph 1 may, in accordance with Union and national sectoral law, outsource the tasks of verifying compliance with ICT risk management requirements to ICT intra-group or ICT third-party service providers. In case of such outsourcing, financial entities shall remain fully responsible for the verification of compliance with the ICT risk management requirements.",
          "source_line_start": 6056,
          "source_line_end": 6056
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art28-Para3",
      "text_sha256": "67d80da3fa461b92078aaf75a80c43e3b8cf81b9024d1bfa04b6f957736cf72c"
    },
    {
      "id": "article-Art28-Para4",
      "type": "article_paragraph",
      "article_number": 28,
      "paragraph_number": "4",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Governance and organisation",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER I"
      ],
      "text": "The financial entities referred to in paragraph 1 shall ensure an appropriate segregation and the independence of control functions and internal audit functions.",
      "outbound_relations": [
        {
          "edge_id": "article-Art28-Para4__article-Art28-Para1__depends_on",
          "source": "article-Art28-Para4",
          "target": "article-Art28-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art28-Para4 expressly applies segregation and independence requirements for control and internal-audit functions to the financial entities referred to in article-Art28-Para1.",
          "source_canonical_ref": "celex:32024R1774/article-Art28-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art28-Para1"
        }
      ],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in paragraph 1 shall ensure an appropriate segregation and the independence of control functions and internal audit functions.",
          "source_line_start": 6059,
          "source_line_end": 6059
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art28-Para4",
      "text_sha256": "ddc601b3ffa2896a66e6856c9c564727cbbff71c197673691e167b9b24e1715e"
    },
    {
      "id": "article-Art28-Para5",
      "type": "article_paragraph",
      "article_number": 28,
      "paragraph_number": "5",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Governance and organisation",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER I"
      ],
      "text": "The financial entities referred to in paragraph 1 shall ensure that their simplified ICT risk management framework is subject to an internal audit by auditors, in line with the financial entities’ audit plan. The auditors shall have sufficient knowledge, skills, and expertise in ICT risk, and shall be independent. The frequency and focus of ICT audits shall be commensurate to the ICT risk of the financial entity.",
      "outbound_relations": [
        {
          "edge_id": "article-Art28-Para5__article-Art28-Para1__depends_on",
          "source": "article-Art28-Para5",
          "target": "article-Art28-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art28-Para5 expressly subjects the simplified ICT risk management framework of the financial entities identified in article-Art28-Para1 to independent, risk-commensurate internal audit.",
          "source_canonical_ref": "celex:32024R1774/article-Art28-Para5",
          "target_canonical_ref": "celex:32024R1774/article-Art28-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art28-Para6__article-Art28-Para5__depends_on",
          "source": "article-Art28-Para6",
          "target": "article-Art28-Para5",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art28-Para6 expressly bases timely verification and remediation of critical findings on the audit required by article-Art28-Para5.",
          "source_canonical_ref": "celex:32024R1774/article-Art28-Para6",
          "target_canonical_ref": "celex:32024R1774/article-Art28-Para5"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in paragraph 1 shall ensure that their simplified ICT risk management framework is subject to an internal audit by auditors, in line with the financial entities’ audit plan. The auditors shall have sufficient knowledge, skills, and expertise in ICT risk, and shall be independent. The frequency and focus of ICT audits shall be commensurate to the ICT risk of the financial entity.",
          "source_line_start": 6062,
          "source_line_end": 6062
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art28-Para5",
      "text_sha256": "cf151bfcefcede85339ead7afca1c5e499b10687bf6e991d69adbe8ff5282da3"
    },
    {
      "id": "article-Art28-Para6",
      "type": "article_paragraph",
      "article_number": 28,
      "paragraph_number": "6",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Governance and organisation",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER I"
      ],
      "text": "Based on the outcome of the audit referred to in paragraph 5, the financial entities referred to in paragraph 1 shall ensure the timely verification and remediation of critical ICT audit findings.",
      "outbound_relations": [
        {
          "edge_id": "article-Art28-Para6__article-Art28-Para1__depends_on",
          "source": "article-Art28-Para6",
          "target": "article-Art28-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art28-Para6 expressly assigns remediation of critical audit findings to the financial entities referred to in article-Art28-Para1, whose simplified governance framework supplies the rule's scope.",
          "source_canonical_ref": "celex:32024R1774/article-Art28-Para6",
          "target_canonical_ref": "celex:32024R1774/article-Art28-Para1"
        },
        {
          "edge_id": "article-Art28-Para6__article-Art28-Para5__depends_on",
          "source": "article-Art28-Para6",
          "target": "article-Art28-Para5",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art28-Para6 expressly bases timely verification and remediation of critical findings on the audit required by article-Art28-Para5.",
          "source_canonical_ref": "celex:32024R1774/article-Art28-Para6",
          "target_canonical_ref": "celex:32024R1774/article-Art28-Para5"
        }
      ],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Based on the outcome of the audit referred to in paragraph 5, the financial entities referred to in paragraph 1 shall ensure the timely verification and remediation of critical ICT audit findings.",
          "source_line_start": 6065,
          "source_line_end": 6065
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art28-Para6",
      "text_sha256": "b2545d5cf044d437b212f28ad64468d93786c78457f322b78219520e749023eb"
    },
    {
      "id": "article-Art29-Para1",
      "type": "article_paragraph",
      "article_number": 29,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Information security policy and measures",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER I"
      ],
      "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall develop, document, and implement an information security policy in the context of the simplified ICT risk management framework. That information security policy shall specify the high-level principles and rules to protect the confidentiality, integrity, availability, and authenticity of data and of the services those financial entities provide.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art29-Para2__article-Art29-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art29-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art29-Para1 because its ICT security measures must be established from the information security policy defined in paragraph 1.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art29-Para1"
        },
        {
          "edge_id": "recital-26__article-Art29-Para1__concretizes",
          "source": "recital-26",
          "target": "article-Art29-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "concretizes",
          "confidence": "high",
          "reasoning": "recital-26 directly concretizes article-Art29-Para1: simplified-framework entities use one information security policy containing high-level rules that protect confidentiality, integrity, availability and authenticity.",
          "source_canonical_ref": "celex:32024R1774/recital-26",
          "target_canonical_ref": "celex:32024R1774/article-Art29-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall develop, document, and implement an information security policy in the context of the simplified ICT risk management framework. That information security policy shall specify the high-level principles and rules to protect the confidentiality, integrity, availability, and authenticity of data and of the services those financial entities provide.",
          "source_line_start": 6074,
          "source_line_end": 6074
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art29-Para1",
      "text_sha256": "6d9e895cba5e0c0de53b50bf6d9a8579a3a1934f52e5fafbe24d5d23a9a1d90a"
    },
    {
      "id": "article-Art29-Para2",
      "type": "article_paragraph",
      "article_number": 29,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Information security policy and measures",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER I"
      ],
      "text": "Based on their information security policy referred to in paragraph 1, the financial entities referred to in paragraph 1 shall establish and implement ICT security measures to mitigate their exposure to ICT risk, including mitigating measures implemented by ICT third-party service providers. The ICT security measures shall include all of the measures referred to in Articles 30 to 38.",
      "outbound_relations": [
        {
          "edge_id": "article-Art29-Para2__article-Art29-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art29-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art29-Para1 because its ICT security measures must be established from the information security policy defined in paragraph 1.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art29-Para1"
        },
        {
          "edge_id": "article-Art29-Para2__article-Art30-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art30-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art30-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches that paragraph’s identification, classification and documentation of critical functions, supporting information and ICT assets, and their interdependencies.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
        },
        {
          "edge_id": "article-Art29-Para2__article-Art30-Para2__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art30-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art30-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches that paragraph’s identification of critical or important functions supported by ICT third-party service providers.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art30-Para2"
        },
        {
          "edge_id": "article-Art29-Para2__article-Art31-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art31-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art31-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches that paragraph’s risk-tolerance, risk-assessment, mitigation, effectiveness-monitoring and change-, test- and incident-driven assessment measures.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art31-Para1"
        },
        {
          "edge_id": "article-Art29-Para2__article-Art31-Para2__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art31-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art31-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the periodic documented ICT risk assessment calibrated to the entity’s ICT risk profile.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art31-Para2"
        },
        {
          "edge_id": "article-Art29-Para2__article-Art31-Para3__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art31-Para3",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art31-Para3 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches continuous monitoring of relevant threats and vulnerabilities and regular review of risk scenarios affecting critical or important functions.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art31-Para3"
        },
        {
          "edge_id": "article-Art29-Para2__article-Art31-Para4__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art31-Para4",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art31-Para4 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the alert thresholds and criteria that trigger and initiate ICT-related incident response processes.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art31-Para4"
        },
        {
          "edge_id": "article-Art29-Para2__article-Art32-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art32-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art32-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches threat- and classification-based physical security measures for ICT assets and accessible information assets.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art32-Para1"
        },
        {
          "edge_id": "article-Art29-Para2__article-Art32-Para2__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art32-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art32-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches protection of premises and applicable data centres against unauthorised access, attacks, accidents and environmental hazards.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art32-Para2"
        },
        {
          "edge_id": "article-Art29-Para2__article-Art32-Para3__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art32-Para3",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art32-Para3 because its express incorporation of all ICT security requirements in Articles 30 to 38 reaches the proportionality constraint linking environmental protection to premises importance and the criticality of operations or ICT systems located there.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art32-Para3"
        },
        {
          "edge_id": "article-Art29-Para2__article-Art33-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art33-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art33-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the logical and physical access-control procedure, including least-privilege, accountability, account-management, authentication and review controls.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art33-Para1"
        },
        {
          "edge_id": "article-Art29-Para2__article-Art34-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art34-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art34-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches ICT-operations controls for asset lifecycle, capacity, vulnerabilities and patches, logging, anomalous activity, cyber threats and information leakage.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art34-Para1"
        },
        {
          "edge_id": "article-Art29-Para2__article-Art35-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art35-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art35-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches network and data safeguards covering protection in use, transit and at rest, secure transfer, deletion and disposal, and teleworking and endpoint-device risks.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art35-Para1"
        },
        {
          "edge_id": "article-Art29-Para2__article-Art36-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art36-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art36-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the testing plan that validates their effectiveness and considers identified threats and vulnerabilities.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art36-Para1"
        },
        {
          "edge_id": "article-Art29-Para2__article-Art36-Para2__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art36-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art36-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches review, assessment and testing of those measures with regard to the overall ICT-asset risk profile.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art36-Para2"
        },
        {
          "edge_id": "article-Art29-Para2__article-Art36-Para3__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art36-Para3",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art36-Para3 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches monitoring and evaluation of security-test results and prompt updating of measures for systems supporting critical or important functions.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art36-Para3"
        },
        {
          "edge_id": "article-Art29-Para2__article-Art37-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art37-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art37-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the risk-based procedure and security controls for ICT-system acquisition, development, maintenance, pre-use testing and production changes.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art37-Para1"
        },
        {
          "edge_id": "article-Art29-Para2__article-Art38-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art38-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art38-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the documented ICT project-management procedure, assigned implementation roles and coverage of every project stage from initiation to closure.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art38-Para1"
        },
        {
          "edge_id": "article-Art29-Para2__article-Art38-Para2__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art38-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art38-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the controlled ICT change-management procedure covering recording, testing, assessment, approval, implementation and verification of changes.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art38-Para2"
        }
      ],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "Based on their information security policy referred to in paragraph 1, the financial entities referred to in paragraph 1 shall establish and implement ICT security measures to mitigate their exposure to ICT risk, including mitigating measures implemented by ICT third-party service providers.",
          "source_line_start": 6077,
          "source_line_end": 6077
        },
        {
          "sequence": 2,
          "text": "The ICT security measures shall include all of the measures referred to in Articles 30 to 38.",
          "source_line_start": 6078,
          "source_line_end": 6078
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "text_sha256": "cd4eda306e646f6f8bf1e9a864201ab1cf7ed67676a6b8f16f3513f3a7763a10"
    },
    {
      "id": "article-Art30-Para1",
      "type": "article_paragraph",
      "article_number": 30,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Classification of information assets and ICT assets",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER I"
      ],
      "text": "As part of the simplified ICT risk management framework referred to in Article 16(1), point (a), of Regulation (EU) 2022/2554, the financial entities referred to in paragraph 1 of that Article shall identify, classify, and document all critical or important functions, the information assets and ICT assets supporting them and their interdependencies. Financial entities shall review that identification and classification as needed.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art28-Para2__article-Art30-Para1__references",
          "source": "article-Art28-Para2",
          "target": "article-Art30-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art28-Para2 expressly requires management-body approval and review of the information-asset classification in article-Art30-Para1, which is the narrow paragraph imposing identification and classification duties.",
          "source_canonical_ref": "celex:32024R1774/article-Art28-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
        },
        {
          "edge_id": "article-Art29-Para2__article-Art30-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art30-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art30-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches that paragraph’s identification, classification and documentation of critical functions, supporting information and ICT assets, and their interdependencies.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
        },
        {
          "edge_id": "article-Art30-Para2__article-Art30-Para1__references",
          "source": "article-Art30-Para2",
          "target": "article-Art30-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art30-Para2 references article-Art30-Para1 to inherit the paragraph-1 entity scope before adding identification of critical or important functions supported by ICT third-party service providers.",
          "source_canonical_ref": "celex:32024R1774/article-Art30-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
        },
        {
          "edge_id": "article-Art32-Para1__article-Art30-Para1__depends_on",
          "source": "article-Art32-Para1",
          "target": "article-Art30-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art32-Para1 depends on article-Art30-Para1 because physical security measures must be designed in accordance with the information-asset and ICT-asset classification established there.",
          "source_canonical_ref": "celex:32024R1774/article-Art32-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
        },
        {
          "edge_id": "article-Art33-Para1__article-Art30-Para1__depends_on",
          "source": "article-Art33-Para1",
          "target": "article-Art30-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art33-Para1 depends on article-Art30-Para1 because authentication strength under the access-control procedure must be commensurate with the asset classification established in that paragraph.",
          "source_canonical_ref": "celex:32024R1774/article-Art33-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
        },
        {
          "edge_id": "article-Art34-Para1__article-Art30-Para1__depends_on",
          "source": "article-Art34-Para1",
          "target": "article-Art30-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art34-Para1 depends on article-Art30-Para1 because the required vulnerability scanning and assessments are calibrated to the asset classification defined in Article 30(1).",
          "source_canonical_ref": "celex:32024R1774/article-Art34-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
        },
        {
          "edge_id": "article-Art35-Para1__article-Art30-Para1__depends_on",
          "source": "article-Art35-Para1",
          "target": "article-Art30-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art35-Para1 depends on article-Art30-Para1 because its data, system and network safeguards must be selected while taking the Article 30(1) asset classification into account.",
          "source_canonical_ref": "celex:32024R1774/article-Art35-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "As part of the simplified ICT risk management framework referred to in Article 16(1), point (a), of Regulation (EU) 2022/2554, the financial entities referred to in paragraph 1 of that Article shall identify, classify, and document all critical or important functions, the information assets and ICT assets supporting them and their interdependencies. Financial entities shall review that identification and classification as needed.",
          "source_line_start": 6087,
          "source_line_end": 6087
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art30-Para1",
      "text_sha256": "244201c9c24a2c8036468af7e65078859900ad4fa2a0f085536d1bfa4f61d7f2"
    },
    {
      "id": "article-Art30-Para2",
      "type": "article_paragraph",
      "article_number": 30,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Classification of information assets and ICT assets",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER I"
      ],
      "text": "The financial entities referred to in paragraph 1 shall identify all critical or important functions supported by ICT third-party service providers.",
      "outbound_relations": [
        {
          "edge_id": "article-Art30-Para2__article-Art30-Para1__references",
          "source": "article-Art30-Para2",
          "target": "article-Art30-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art30-Para2 references article-Art30-Para1 to inherit the paragraph-1 entity scope before adding identification of critical or important functions supported by ICT third-party service providers.",
          "source_canonical_ref": "celex:32024R1774/article-Art30-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art29-Para2__article-Art30-Para2__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art30-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art30-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches that paragraph’s identification of critical or important functions supported by ICT third-party service providers.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art30-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in paragraph 1 shall identify all critical or important functions supported by ICT third-party service providers.",
          "source_line_start": 6090,
          "source_line_end": 6090
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art30-Para2",
      "text_sha256": "78b692974c7d605f258cf36836c77ef2b4bf9e943d5949e026e6a6f18838419a"
    },
    {
      "id": "article-Art31-Para1",
      "type": "article_paragraph",
      "article_number": 31,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT risk management",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "a determination of the risk tolerance levels for ICT risk, in accordance with the risk appetite of the financial entity;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 6106,
          "source_line_end": 6109
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "the identification and assessment of the ICT risks to which the financial entity is exposed;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 6120,
          "source_line_end": 6123
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "the specification of mitigation strategies at least for the ICT risks that are not within the risk tolerance levels of the financial entity;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 6134,
          "source_line_end": 6137
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "the monitoring of the effectiveness of the mitigation strategies referred to in point (c);",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 6148,
          "source_line_end": 6151
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "the identification and assessment of any ICT and information security risks resulting from any major change in ICT system or ICT services, processes, or procedures, and from ICT security testing results and after any major ICT-related incident.",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 6162,
          "source_line_end": 6165
        }
      ],
      "ancestry": [
        "TITLE III",
        "CHAPTER I"
      ],
      "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall include in their simplified ICT risk management framework all of the following: (a) a determination of the risk tolerance levels for ICT risk, in accordance with the risk appetite of the financial entity; (b) the identification and assessment of the ICT risks to which the financial entity is exposed; (c) the specification of mitigation strategies at least for the ICT risks that are not within the risk tolerance levels of the financial entity; (d) the monitoring of the effectiveness of the mitigation strategies referred to in point (c); (e) the identification and assessment of any ICT and information security risks resulting from any major change in ICT system or ICT services, processes, or procedures, and from ICT security testing results and after any major ICT-related incident.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art29-Para2__article-Art31-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art31-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art31-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches that paragraph’s risk-tolerance, risk-assessment, mitigation, effectiveness-monitoring and change-, test- and incident-driven assessment measures.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art31-Para1"
        },
        {
          "edge_id": "article-Art31-Para2__article-Art31-Para1__depends_on",
          "source": "article-Art31-Para2",
          "target": "article-Art31-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art31-Para2 depends on article-Art31-Para1 because the periodic documented assessment in paragraph 2 is the ICT risk assessment established as part of the paragraph-1 simplified risk framework.",
          "source_canonical_ref": "celex:32024R1774/article-Art31-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art31-Para1"
        },
        {
          "edge_id": "article-Art31-Para3__article-Art31-Para1__references",
          "source": "article-Art31-Para3",
          "target": "article-Art31-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art31-Para3 references article-Art31-Para1 to carry its financial-entity scope into continuous threat and vulnerability monitoring for critical functions and supporting assets.",
          "source_canonical_ref": "celex:32024R1774/article-Art31-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art31-Para1"
        },
        {
          "edge_id": "article-Art31-Para4__article-Art31-Para1__references",
          "source": "article-Art31-Para4",
          "target": "article-Art31-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art31-Para4 references article-Art31-Para1 to apply alert-threshold and incident-response-trigger duties to the financial entities defined in paragraph 1.",
          "source_canonical_ref": "celex:32024R1774/article-Art31-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art31-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall include in their simplified ICT risk management framework all of the following:",
          "source_line_start": 6099,
          "source_line_end": 6099
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art31-Para1",
      "text_sha256": "db4a58af966786377b0be77b93606bc6b62e60b17e283847959077c74541ee20"
    },
    {
      "id": "article-Art31-Para2",
      "type": "article_paragraph",
      "article_number": 31,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT risk management",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER I"
      ],
      "text": "The financial entities referred to in paragraph 1 shall carry out and document the ICT risk assessment periodically commensurate to the financial entities’ ICT risk profile.",
      "outbound_relations": [
        {
          "edge_id": "article-Art31-Para2__article-Art31-Para1__depends_on",
          "source": "article-Art31-Para2",
          "target": "article-Art31-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art31-Para2 depends on article-Art31-Para1 because the periodic documented assessment in paragraph 2 is the ICT risk assessment established as part of the paragraph-1 simplified risk framework.",
          "source_canonical_ref": "celex:32024R1774/article-Art31-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art31-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art29-Para2__article-Art31-Para2__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art31-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art31-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the periodic documented ICT risk assessment calibrated to the entity’s ICT risk profile.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art31-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in paragraph 1 shall carry out and document the ICT risk assessment periodically commensurate to the financial entities’ ICT risk profile.",
          "source_line_start": 6172,
          "source_line_end": 6172
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art31-Para2",
      "text_sha256": "cc9d17b010345084a08ce49928d12decabd652870c4e17d9df69cbb033ac805b"
    },
    {
      "id": "article-Art31-Para3",
      "type": "article_paragraph",
      "article_number": 31,
      "paragraph_number": "3",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT risk management",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER I"
      ],
      "text": "The financial entities referred to in paragraph 1 shall continuously monitor threats and vulnerabilities that are relevant to their critical or important functions, and information assets and ICT assets, and shall regularly review the risk scenarios impacting those critical or important functions.",
      "outbound_relations": [
        {
          "edge_id": "article-Art31-Para3__article-Art31-Para1__references",
          "source": "article-Art31-Para3",
          "target": "article-Art31-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art31-Para3 references article-Art31-Para1 to carry its financial-entity scope into continuous threat and vulnerability monitoring for critical functions and supporting assets.",
          "source_canonical_ref": "celex:32024R1774/article-Art31-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art31-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art29-Para2__article-Art31-Para3__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art31-Para3",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art31-Para3 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches continuous monitoring of relevant threats and vulnerabilities and regular review of risk scenarios affecting critical or important functions.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art31-Para3"
        },
        {
          "edge_id": "article-Art36-Para1__article-Art31-Para3__depends_on",
          "source": "article-Art36-Para1",
          "target": "article-Art31-Para3",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art36-Para1 depends on article-Art31-Para3 because its testing plan must consider the threats and vulnerabilities continuously identified under the simplified ICT risk management framework.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art31-Para3"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in paragraph 1 shall continuously monitor threats and vulnerabilities that are relevant to their critical or important functions, and information assets and ICT assets, and shall regularly review the risk scenarios impacting those critical or important functions.",
          "source_line_start": 6175,
          "source_line_end": 6175
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art31-Para3",
      "text_sha256": "8e3d84708ee93ddc9ec381bfb58dd089f7f3476e2e14ee4ab5935edaf65a8ada"
    },
    {
      "id": "article-Art31-Para4",
      "type": "article_paragraph",
      "article_number": 31,
      "paragraph_number": "4",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT risk management",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER I"
      ],
      "text": "The financial entities referred to in paragraph 1 shall set out alert thresholds and criteria to trigger and initiate ICT-related incident response processes.",
      "outbound_relations": [
        {
          "edge_id": "article-Art31-Para4__article-Art31-Para1__references",
          "source": "article-Art31-Para4",
          "target": "article-Art31-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art31-Para4 references article-Art31-Para1 to apply alert-threshold and incident-response-trigger duties to the financial entities defined in paragraph 1.",
          "source_canonical_ref": "celex:32024R1774/article-Art31-Para4",
          "target_canonical_ref": "celex:32024R1774/article-Art31-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art29-Para2__article-Art31-Para4__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art31-Para4",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art31-Para4 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the alert thresholds and criteria that trigger and initiate ICT-related incident response processes.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art31-Para4"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in paragraph 1 shall set out alert thresholds and criteria to trigger and initiate ICT-related incident response processes.",
          "source_line_start": 6178,
          "source_line_end": 6178
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art31-Para4",
      "text_sha256": "1686b0d5b1fbcd3f341c9644a1b57ccc1b3049ca4883dbcfd8235c1cf20266ab"
    },
    {
      "id": "article-Art32-Para1",
      "type": "article_paragraph",
      "article_number": 32,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Physical and environmental security",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER I"
      ],
      "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall identify and implement physical security measures designed on the basis of the threat landscape and in accordance with the classification referred to in Article 30(1) of this Regulation, the overall risk profile of ICT assets, and accessible information assets.",
      "outbound_relations": [
        {
          "edge_id": "article-Art32-Para1__article-Art30-Para1__depends_on",
          "source": "article-Art32-Para1",
          "target": "article-Art30-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art32-Para1 depends on article-Art30-Para1 because physical security measures must be designed in accordance with the information-asset and ICT-asset classification established there.",
          "source_canonical_ref": "celex:32024R1774/article-Art32-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art29-Para2__article-Art32-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art32-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art32-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches threat- and classification-based physical security measures for ICT assets and accessible information assets.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art32-Para1"
        },
        {
          "edge_id": "article-Art32-Para2__article-Art32-Para1__depends_on",
          "source": "article-Art32-Para2",
          "target": "article-Art32-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art32-Para2 depends on article-Art32-Para1 because it specifies the premises, data centres, threats and hazards against which the paragraph-1 physical security measures must protect.",
          "source_canonical_ref": "celex:32024R1774/article-Art32-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art32-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall identify and implement physical security measures designed on the basis of the threat landscape and in accordance with the classification referred to in Article 30(1) of this Regulation, the overall risk profile of ICT assets, and accessible information assets.",
          "source_line_start": 6187,
          "source_line_end": 6187
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art32-Para1",
      "text_sha256": "fb129ba6a9c131ee187186597d71f317d0995ea576de4b5ada543a7ef31aefd0"
    },
    {
      "id": "article-Art32-Para2",
      "type": "article_paragraph",
      "article_number": 32,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Physical and environmental security",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER I"
      ],
      "text": "The measures referred to in paragraph 1 shall protect the premises of financial entities and, where applicable, data centres of financial entities where ICT assets and information assets reside from unauthorised access, attacks, and accidents, and from environmental threats and hazards.",
      "outbound_relations": [
        {
          "edge_id": "article-Art32-Para2__article-Art32-Para1__depends_on",
          "source": "article-Art32-Para2",
          "target": "article-Art32-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art32-Para2 depends on article-Art32-Para1 because it specifies the premises, data centres, threats and hazards against which the paragraph-1 physical security measures must protect.",
          "source_canonical_ref": "celex:32024R1774/article-Art32-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art32-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art29-Para2__article-Art32-Para2__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art32-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art32-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches protection of premises and applicable data centres against unauthorised access, attacks, accidents and environmental hazards.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art32-Para2"
        },
        {
          "edge_id": "article-Art32-Para3__article-Art32-Para2__qualifies",
          "source": "article-Art32-Para3",
          "target": "article-Art32-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "article-Art32-Para3 qualifies article-Art32-Para2 by making its environmental-threat protection proportionate to premises importance and the criticality of operations or ICT systems located there.",
          "source_canonical_ref": "celex:32024R1774/article-Art32-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art32-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The measures referred to in paragraph 1 shall protect the premises of financial entities and, where applicable, data centres of financial entities where ICT assets and information assets reside from unauthorised access, attacks, and accidents, and from environmental threats and hazards.",
          "source_line_start": 6190,
          "source_line_end": 6190
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art32-Para2",
      "text_sha256": "b7870e4c5e015e9b7e556366430dd3dad0a6b5cf4ea309d54de8a631812e0795"
    },
    {
      "id": "article-Art32-Para3",
      "type": "article_paragraph",
      "article_number": 32,
      "paragraph_number": "3",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Physical and environmental security",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER I"
      ],
      "text": "The protection from environmental threats and hazards shall be commensurate with the importance of the premises concerned and, where applicable, the data centres and the criticality of the operations or ICT systems located therein.",
      "outbound_relations": [
        {
          "edge_id": "article-Art32-Para3__article-Art32-Para2__qualifies",
          "source": "article-Art32-Para3",
          "target": "article-Art32-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "qualifies",
          "confidence": "high",
          "reasoning": "article-Art32-Para3 qualifies article-Art32-Para2 by making its environmental-threat protection proportionate to premises importance and the criticality of operations or ICT systems located there.",
          "source_canonical_ref": "celex:32024R1774/article-Art32-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art32-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art29-Para2__article-Art32-Para3__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art32-Para3",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art32-Para3 because its express incorporation of all ICT security requirements in Articles 30 to 38 reaches the proportionality constraint linking environmental protection to premises importance and the criticality of operations or ICT systems located there.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art32-Para3"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The protection from environmental threats and hazards shall be commensurate with the importance of the premises concerned and, where applicable, the data centres and the criticality of the operations or ICT systems located therein.",
          "source_line_start": 6193,
          "source_line_end": 6193
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art32-Para3",
      "text_sha256": "29db983f5102f9524618870688840506836ac42dffcf886149f27bc06d830dc0"
    },
    {
      "id": "article-Art33-Para1",
      "type": "article_paragraph",
      "article_number": 33,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "single",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Access Control",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "access rights to information assets, ICT assets, and their supported functions, and to critical locations of operation of the financial entity, are managed on a need-to-know, need-to-use and least privileges basis, including for remote and emergency access;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 6220,
          "source_line_end": 6223
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "user accountability, which ensures that users can be identified for the actions performed in the ICT systems;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 6234,
          "source_line_end": 6237
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "account management procedures to grant, change, or revoke access rights for user and generic accounts, including generic administrator accounts;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 6248,
          "source_line_end": 6251
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "authentication methods that are commensurate to the classification referred to in Article 30(1) and to the overall risk profile of ICT assets, and which are based on leading practices;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 6262,
          "source_line_end": 6265
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "access rights are periodically reviewed and are withdrawn when no longer required.",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 6276,
          "source_line_end": 6279
        }
      ],
      "ancestry": [
        "TITLE III",
        "CHAPTER II"
      ],
      "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall develop, document, and implement procedures for the control of logical and physical access and shall enforce, monitor, and periodically review those procedures. Those procedures shall contain the following elements of control of logical and physical access: (a) access rights to information assets, ICT assets, and their supported functions, and to critical locations of operation of the financial entity, are managed on a need-to-know, need-to-use and least privileges basis, including for remote and emergency access; (b) user accountability, which ensures that users can be identified for the actions performed in the ICT systems; (c) account management procedures to grant, change, or revoke access rights for user and generic accounts, including generic administrator accounts; (d) authentication methods that are commensurate to the classification referred to in Article 30(1) and to the overall risk profile of ICT assets, and which are based on leading practices; (e) access rights are periodically reviewed and are withdrawn when no longer required. For the purposes of point (c), the financial entity shall assign privileged, emergency, and administrator access on a need-to-use or an ad-hoc basis for all ICT systems, and shall be logged in accordance with Article 34, first paragraph, point (f). For the purposes of point (d), financial entities shall use strong authentication methods that are based on leading practices for remote access to the financial entities’ network, for privileged access, and for access to ICT assets supporting critical or important functions that are publicly available.",
      "outbound_relations": [
        {
          "edge_id": "article-Art33-Para1__article-Art30-Para1__depends_on",
          "source": "article-Art33-Para1",
          "target": "article-Art30-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art33-Para1 depends on article-Art30-Para1 because authentication strength under the access-control procedure must be commensurate with the asset classification established in that paragraph.",
          "source_canonical_ref": "celex:32024R1774/article-Art33-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
        },
        {
          "edge_id": "article-Art33-Para1__article-Art34-Para1__references",
          "source": "article-Art33-Para1",
          "target": "article-Art34-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art33-Para1 references article-Art34-Para1 because privileged, emergency and administrator access assigned under Article 33 must be logged under the Article 34 first-paragraph point-(f) logging control.",
          "source_canonical_ref": "celex:32024R1774/article-Art33-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art34-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art29-Para2__article-Art33-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art33-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art33-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the logical and physical access-control procedure, including least-privilege, accountability, account-management, authentication and review controls.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art33-Para1"
        },
        {
          "edge_id": "article-Art36-Para1__article-Art33-Para1__depends_on",
          "source": "article-Art36-Para1",
          "target": "article-Art33-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art36-Para1 depends on article-Art33-Para1 because the security testing plan expressly validates the effectiveness of the access-control measures required by that paragraph.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art33-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall develop, document, and implement procedures for the control of logical and physical access and shall enforce, monitor, and periodically review those procedures. Those procedures shall contain the following elements of control of logical and physical access:",
          "source_line_start": 6213,
          "source_line_end": 6213
        },
        {
          "sequence": 2,
          "text": "For the purposes of point (c), the financial entity shall assign privileged, emergency, and administrator access on a need-to-use or an ad-hoc basis for all ICT systems, and shall be logged in accordance with Article 34, first paragraph, point (f).",
          "source_line_start": 6284,
          "source_line_end": 6284
        },
        {
          "sequence": 3,
          "text": "For the purposes of point (d), financial entities shall use strong authentication methods that are based on leading practices for remote access to the financial entities’ network, for privileged access, and for access to ICT assets supporting critical or important functions that are publicly available.",
          "source_line_start": 6285,
          "source_line_end": 6285
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art33-Para1",
      "text_sha256": "5840bd0b303bea76d576cfb7cd61cbd3a36b22812e683353f1137d00c863c69f"
    },
    {
      "id": "article-Art34-Para1",
      "type": "article_paragraph",
      "article_number": 34,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "single",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT operations security",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "monitor and manage the lifecycle of all ICT assets;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 6299,
          "source_line_end": 6302
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "monitor whether the ICT assets are supported by ICT third-party service providers of financial entities, where applicable;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 6313,
          "source_line_end": 6316
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "identify capacity requirements of their ICT assets and measures to maintain and improve the availability and efficiency of ICT systems and prevent ICT capacity shortages before they materialise;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 6327,
          "source_line_end": 6330
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "perform automated vulnerability scanning and assessments of ICT assets commensurate to their classification as referred to in Article 30(1) and to the overall risk profile of the ICT asset, and deploy patches to address identified vulnerabilities;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 6341,
          "source_line_end": 6344
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "manage the risks related to outdated, unsupported, or legacy ICT assets;",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 6355,
          "source_line_end": 6358
        },
        {
          "type": "point",
          "marker": "(f)",
          "text": "log events related to logical and physical access control, ICT operations, including system and network traffic activities, and ICT change management;",
          "depth": 1,
          "parent_marker": null,
          "path": "(f)",
          "source_line_start": 6369,
          "source_line_end": 6372
        },
        {
          "type": "point",
          "marker": "(g)",
          "text": "identify and implement measures to monitor and analyse information on anomalous activities and behaviour for critical or important ICT operations;",
          "depth": 1,
          "parent_marker": null,
          "path": "(g)",
          "source_line_start": 6383,
          "source_line_end": 6386
        },
        {
          "type": "point",
          "marker": "(h)",
          "text": "implement measures to monitor relevant and up-to-date information about cyber threats;",
          "depth": 1,
          "parent_marker": null,
          "path": "(h)",
          "source_line_start": 6397,
          "source_line_end": 6400
        },
        {
          "type": "point",
          "marker": "(i)",
          "text": "implement measures to identify possible information leakages, malicious code and other security threats, and publicly known vulnerabilities in software and hardware, and check for corresponding new security updates.",
          "depth": 1,
          "parent_marker": null,
          "path": "(i)",
          "source_line_start": 6411,
          "source_line_end": 6414
        }
      ],
      "ancestry": [
        "TITLE III",
        "CHAPTER II"
      ],
      "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall, as part of their systems, protocols, and tools, and for all ICT assets: (a) monitor and manage the lifecycle of all ICT assets; (b) monitor whether the ICT assets are supported by ICT third-party service providers of financial entities, where applicable; (c) identify capacity requirements of their ICT assets and measures to maintain and improve the availability and efficiency of ICT systems and prevent ICT capacity shortages before they materialise; (d) perform automated vulnerability scanning and assessments of ICT assets commensurate to their classification as referred to in Article 30(1) and to the overall risk profile of the ICT asset, and deploy patches to address identified vulnerabilities; (e) manage the risks related to outdated, unsupported, or legacy ICT assets; (f) log events related to logical and physical access control, ICT operations, including system and network traffic activities, and ICT change management; (g) identify and implement measures to monitor and analyse information on anomalous activities and behaviour for critical or important ICT operations; (h) implement measures to monitor relevant and up-to-date information about cyber threats; (i) implement measures to identify possible information leakages, malicious code and other security threats, and publicly known vulnerabilities in software and hardware, and check for corresponding new security updates. For the purposes of point (f), financial entities shall align the level of detail of the logs with their purpose and usage of the ICT asset producing those logs.",
      "outbound_relations": [
        {
          "edge_id": "article-Art34-Para1__article-Art30-Para1__depends_on",
          "source": "article-Art34-Para1",
          "target": "article-Art30-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art34-Para1 depends on article-Art30-Para1 because the required vulnerability scanning and assessments are calibrated to the asset classification defined in Article 30(1).",
          "source_canonical_ref": "celex:32024R1774/article-Art34-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art29-Para2__article-Art34-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art34-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art34-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches ICT-operations controls for asset lifecycle, capacity, vulnerabilities and patches, logging, anomalous activity, cyber threats and information leakage.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art34-Para1"
        },
        {
          "edge_id": "article-Art33-Para1__article-Art34-Para1__references",
          "source": "article-Art33-Para1",
          "target": "article-Art34-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art33-Para1 references article-Art34-Para1 because privileged, emergency and administrator access assigned under Article 33 must be logged under the Article 34 first-paragraph point-(f) logging control.",
          "source_canonical_ref": "celex:32024R1774/article-Art33-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art34-Para1"
        },
        {
          "edge_id": "article-Art36-Para1__article-Art34-Para1__depends_on",
          "source": "article-Art36-Para1",
          "target": "article-Art34-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art36-Para1 depends on article-Art34-Para1 because the security testing plan expressly validates the effectiveness of the ICT-operations security measures required by that paragraph.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art34-Para1"
        },
        {
          "edge_id": "recital-30__article-Art34-Para1__restricts",
          "source": "recital-30",
          "target": "article-Art34-Para1",
          "source_type": "recital",
          "target_type": "article_paragraph",
          "relation": "restricts",
          "confidence": "high",
          "reasoning": "recital-30 restricts the anomalous-activity monitoring and security-information measures in article-Art34-Para1 by requiring any personal-data processing for incident detection to comply fully with Union data-protection law and data minimisation.",
          "source_canonical_ref": "celex:32024R1774/recital-30",
          "target_canonical_ref": "celex:32024R1774/article-Art34-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall, as part of their systems, protocols, and tools, and for all ICT assets:",
          "source_line_start": 6292,
          "source_line_end": 6292
        },
        {
          "sequence": 2,
          "text": "For the purposes of point (f), financial entities shall align the level of detail of the logs with their purpose and usage of the ICT asset producing those logs.",
          "source_line_start": 6419,
          "source_line_end": 6419
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art34-Para1",
      "text_sha256": "4e8a50c8a980b98d524b5ae5ba4da924a2d7c71e2214d05cff955fa57ea132b2"
    },
    {
      "id": "article-Art35-Para1",
      "type": "article_paragraph",
      "article_number": 35,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "single",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Data, system and network security",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "the identification and implementation of measures to protect data in use, in transit, and at rest;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 6433,
          "source_line_end": 6436
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "the identification and implementation of security measures regarding the use of software, data storage media, systems and endpoint devices that transfer and store data of the financial entity;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 6447,
          "source_line_end": 6450
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "the identification and implementation of measures to prevent and detect unauthorised connections to the financial entity’s network, and to secure the network traffic between the financial entity’s internal networks and the internet and other external connections;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 6461,
          "source_line_end": 6464
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "the identification and implementation of measures that ensure the availability, authenticity, integrity, and confidentiality of data during network transmissions;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 6475,
          "source_line_end": 6478
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "a process to securely delete data on premises, or that are stored externally, that the financial entity no longer needs to collect or store;",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 6489,
          "source_line_end": 6492
        },
        {
          "type": "point",
          "marker": "(f)",
          "text": "a process to securely dispose of, or decommission, data storage devices on premises, or data storage devices that are stored externally, that contain confidential information;",
          "depth": 1,
          "parent_marker": null,
          "path": "(f)",
          "source_line_start": 6503,
          "source_line_end": 6506
        },
        {
          "type": "point",
          "marker": "(g)",
          "text": "the identification and implementation of measures to ensure that teleworking and the use of private endpoint devices does not adversely impact the financial entity’s ability to carry out its critical activities in an adequate, timely, and secure manner.",
          "depth": 1,
          "parent_marker": null,
          "path": "(g)",
          "source_line_start": 6517,
          "source_line_end": 6520
        }
      ],
      "ancestry": [
        "TITLE III",
        "CHAPTER II"
      ],
      "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall, as part of their systems, protocols, and tools, develop and implement safeguards that ensure the security of networks against intrusions and data misuse and that preserve the availability, authenticity, integrity, and confidentiality of data. In particular, financial entities shall, taking into account the classification referred to in Article 30(1) of this Regulation, establish all of the following: (a) the identification and implementation of measures to protect data in use, in transit, and at rest; (b) the identification and implementation of security measures regarding the use of software, data storage media, systems and endpoint devices that transfer and store data of the financial entity; (c) the identification and implementation of measures to prevent and detect unauthorised connections to the financial entity’s network, and to secure the network traffic between the financial entity’s internal networks and the internet and other external connections; (d) the identification and implementation of measures that ensure the availability, authenticity, integrity, and confidentiality of data during network transmissions; (e) a process to securely delete data on premises, or that are stored externally, that the financial entity no longer needs to collect or store; (f) a process to securely dispose of, or decommission, data storage devices on premises, or data storage devices that are stored externally, that contain confidential information; (g) the identification and implementation of measures to ensure that teleworking and the use of private endpoint devices does not adversely impact the financial entity’s ability to carry out its critical activities in an adequate, timely, and secure manner.",
      "outbound_relations": [
        {
          "edge_id": "article-Art35-Para1__article-Art30-Para1__depends_on",
          "source": "article-Art35-Para1",
          "target": "article-Art30-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art35-Para1 depends on article-Art30-Para1 because its data, system and network safeguards must be selected while taking the Article 30(1) asset classification into account.",
          "source_canonical_ref": "celex:32024R1774/article-Art35-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art29-Para2__article-Art35-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art35-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art35-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches network and data safeguards covering protection in use, transit and at rest, secure transfer, deletion and disposal, and teleworking and endpoint-device risks.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art35-Para1"
        },
        {
          "edge_id": "article-Art36-Para1__article-Art35-Para1__depends_on",
          "source": "article-Art36-Para1",
          "target": "article-Art35-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art36-Para1 depends on article-Art35-Para1 because the security testing plan expressly validates the effectiveness of the data, system and network safeguards required by that paragraph.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art35-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall, as part of their systems, protocols, and tools, develop and implement safeguards that ensure the security of networks against intrusions and data misuse and that preserve the availability, authenticity, integrity, and confidentiality of data. In particular, financial entities shall, taking into account the classification referred to in Article 30(1) of this Regulation, establish all of the following:",
          "source_line_start": 6426,
          "source_line_end": 6426
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art35-Para1",
      "text_sha256": "1a2ef40595b69bcfa1f5840fd43715db0ae471527ced4302e3827cecccf57f62"
    },
    {
      "id": "article-Art36-Para1",
      "type": "article_paragraph",
      "article_number": 36,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT security testing",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER II"
      ],
      "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall establish and implement an ICT security testing plan to validate the effectiveness of their ICT security measures developed in accordance with Articles 33, 34 and 35 and Articles 37 and 38 of this Regulation. Financial entities shall ensure that that plan considers threats and vulnerabilities identified as part of the simplified ICT risk management framework referred to in Article 31 of this Regulation.",
      "outbound_relations": [
        {
          "edge_id": "article-Art36-Para1__article-Art31-Para3__depends_on",
          "source": "article-Art36-Para1",
          "target": "article-Art31-Para3",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art36-Para1 depends on article-Art31-Para3 because its testing plan must consider the threats and vulnerabilities continuously identified under the simplified ICT risk management framework.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art31-Para3"
        },
        {
          "edge_id": "article-Art36-Para1__article-Art33-Para1__depends_on",
          "source": "article-Art36-Para1",
          "target": "article-Art33-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art36-Para1 depends on article-Art33-Para1 because the security testing plan expressly validates the effectiveness of the access-control measures required by that paragraph.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art33-Para1"
        },
        {
          "edge_id": "article-Art36-Para1__article-Art34-Para1__depends_on",
          "source": "article-Art36-Para1",
          "target": "article-Art34-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art36-Para1 depends on article-Art34-Para1 because the security testing plan expressly validates the effectiveness of the ICT-operations security measures required by that paragraph.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art34-Para1"
        },
        {
          "edge_id": "article-Art36-Para1__article-Art35-Para1__depends_on",
          "source": "article-Art36-Para1",
          "target": "article-Art35-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art36-Para1 depends on article-Art35-Para1 because the security testing plan expressly validates the effectiveness of the data, system and network safeguards required by that paragraph.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art35-Para1"
        },
        {
          "edge_id": "article-Art36-Para1__article-Art37-Para1__depends_on",
          "source": "article-Art36-Para1",
          "target": "article-Art37-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art36-Para1 depends on article-Art37-Para1 because the security testing plan expressly validates the effectiveness of the acquisition, development and maintenance controls required by that paragraph.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art37-Para1"
        },
        {
          "edge_id": "article-Art36-Para1__article-Art38-Para1__depends_on",
          "source": "article-Art36-Para1",
          "target": "article-Art38-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art36-Para1 depends on article-Art38-Para1 because the security testing plan expressly validates the effectiveness of the ICT project-management procedure required by that paragraph.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art38-Para1"
        },
        {
          "edge_id": "article-Art36-Para1__article-Art38-Para2__depends_on",
          "source": "article-Art36-Para1",
          "target": "article-Art38-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art36-Para1 depends on article-Art38-Para2 because the security testing plan expressly validates the effectiveness of the ICT change-management procedure required by that paragraph.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art38-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art29-Para2__article-Art36-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art36-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art36-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the testing plan that validates their effectiveness and considers identified threats and vulnerabilities.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art36-Para1"
        },
        {
          "edge_id": "article-Art36-Para2__article-Art36-Para1__depends_on",
          "source": "article-Art36-Para2",
          "target": "article-Art36-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art36-Para2 depends on article-Art36-Para1 because its review, assessment and testing of ICT security measures operationalise the testing plan and entity scope established in paragraph 1.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art36-Para1"
        },
        {
          "edge_id": "article-Art36-Para3__article-Art36-Para1__references",
          "source": "article-Art36-Para3",
          "target": "article-Art36-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art36-Para3 references article-Art36-Para1 to inherit the financial-entity scope and testing-plan context for monitoring and evaluating security-test results.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art36-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall establish and implement an ICT security testing plan to validate the effectiveness of their ICT security measures developed in accordance with Articles 33, 34 and 35 and Articles 37 and 38 of this Regulation. Financial entities shall ensure that that plan considers threats and vulnerabilities identified as part of the simplified ICT risk management framework referred to in Article 31 of this Regulation.",
          "source_line_start": 6532,
          "source_line_end": 6532
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art36-Para1",
      "text_sha256": "aae3d4f41b5938adef0b065face54a28266267d55157109712f7b5b4ec3d6ad8"
    },
    {
      "id": "article-Art36-Para2",
      "type": "article_paragraph",
      "article_number": 36,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT security testing",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER II"
      ],
      "text": "The financial entities referred to in paragraph 1 shall review, asses and test ICT security measures, taking into consideration the overall risk profile of the ICT assets of the financial entity.",
      "outbound_relations": [
        {
          "edge_id": "article-Art36-Para2__article-Art36-Para1__depends_on",
          "source": "article-Art36-Para2",
          "target": "article-Art36-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art36-Para2 depends on article-Art36-Para1 because its review, assessment and testing of ICT security measures operationalise the testing plan and entity scope established in paragraph 1.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art36-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art29-Para2__article-Art36-Para2__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art36-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art36-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches review, assessment and testing of those measures with regard to the overall ICT-asset risk profile.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art36-Para2"
        },
        {
          "edge_id": "article-Art36-Para3__article-Art36-Para2__depends_on",
          "source": "article-Art36-Para3",
          "target": "article-Art36-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art36-Para3 depends on article-Art36-Para2 because the results that paragraph 3 requires entities to evaluate arise from the review, assessment and testing mandated in paragraph 2.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art36-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in paragraph 1 shall review, asses and test ICT security measures, taking into consideration the overall risk profile of the ICT assets of the financial entity.",
          "source_line_start": 6535,
          "source_line_end": 6535
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art36-Para2",
      "text_sha256": "ffe538e66946d466308523d05a4e515e90f08dee09f8a466fa3152529b81a22e"
    },
    {
      "id": "article-Art36-Para3",
      "type": "article_paragraph",
      "article_number": 36,
      "paragraph_number": "3",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT security testing",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER II"
      ],
      "text": "The financial entities referred to in paragraph 1 shall monitor and evaluate the results of the security tests and update their security measures accordingly without undue delay in the case of ICT systems supporting critical or important functions.",
      "outbound_relations": [
        {
          "edge_id": "article-Art36-Para3__article-Art36-Para1__references",
          "source": "article-Art36-Para3",
          "target": "article-Art36-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art36-Para3 references article-Art36-Para1 to inherit the financial-entity scope and testing-plan context for monitoring and evaluating security-test results.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art36-Para1"
        },
        {
          "edge_id": "article-Art36-Para3__article-Art36-Para2__depends_on",
          "source": "article-Art36-Para3",
          "target": "article-Art36-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art36-Para3 depends on article-Art36-Para2 because the results that paragraph 3 requires entities to evaluate arise from the review, assessment and testing mandated in paragraph 2.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art36-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art29-Para2__article-Art36-Para3__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art36-Para3",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art36-Para3 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches monitoring and evaluation of security-test results and prompt updating of measures for systems supporting critical or important functions.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art36-Para3"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in paragraph 1 shall monitor and evaluate the results of the security tests and update their security measures accordingly without undue delay in the case of ICT systems supporting critical or important functions.",
          "source_line_start": 6538,
          "source_line_end": 6538
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art36-Para3",
      "text_sha256": "f3bf0762b24be7e7299f3a7697f71a841690db54ec155010a7c437ba7a344c45"
    },
    {
      "id": "article-Art37-Para1",
      "type": "article_paragraph",
      "article_number": 37,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "single",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT systems acquisition, development, and maintenance",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "ensure that, before any acquisition or development of ICT systems takes place, the functional and non-functional requirements, including information security requirements, are clearly specified and approved by the business function concerned;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 6553,
          "source_line_end": 6556
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "ensure the testing and approval of ICT systems prior to their first use and before introducing changes to the production environment;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 6567,
          "source_line_end": 6570
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "identify measures to mitigate the risk of unintentional alteration or intentional manipulation of the ICT systems during development and implementation in the production environment.",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 6581,
          "source_line_end": 6584
        }
      ],
      "ancestry": [
        "TITLE III",
        "CHAPTER II"
      ],
      "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall design and implement, where appropriate, a procedure governing the acquisition, development, and maintenance of ICT systems following a risk-based approach. That procedure shall: (a) ensure that, before any acquisition or development of ICT systems takes place, the functional and non-functional requirements, including information security requirements, are clearly specified and approved by the business function concerned; (b) ensure the testing and approval of ICT systems prior to their first use and before introducing changes to the production environment; (c) identify measures to mitigate the risk of unintentional alteration or intentional manipulation of the ICT systems during development and implementation in the production environment.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art29-Para2__article-Art37-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art37-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art37-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the risk-based procedure and security controls for ICT-system acquisition, development, maintenance, pre-use testing and production changes.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art37-Para1"
        },
        {
          "edge_id": "article-Art36-Para1__article-Art37-Para1__depends_on",
          "source": "article-Art36-Para1",
          "target": "article-Art37-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art36-Para1 depends on article-Art37-Para1 because the security testing plan expressly validates the effectiveness of the acquisition, development and maintenance controls required by that paragraph.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art37-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall design and implement, where appropriate, a procedure governing the acquisition, development, and maintenance of ICT systems following a risk-based approach. That procedure shall:",
          "source_line_start": 6546,
          "source_line_end": 6546
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art37-Para1",
      "text_sha256": "ca3f7704d3ce38b7c61700c3b4be51596abc8450e3ce06e95c80aa230de621ae"
    },
    {
      "id": "article-Art38-Para1",
      "type": "article_paragraph",
      "article_number": 38,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT project and change management",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER II"
      ],
      "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall develop, document, and implement an ICT project management procedure and shall specify the roles and responsibilities for its implementation. That procedure shall cover all stages of the ICT projects from their initiation to their closure.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art29-Para2__article-Art38-Para1__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art38-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art38-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the documented ICT project-management procedure, assigned implementation roles and coverage of every project stage from initiation to closure.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art38-Para1"
        },
        {
          "edge_id": "article-Art36-Para1__article-Art38-Para1__depends_on",
          "source": "article-Art36-Para1",
          "target": "article-Art38-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art36-Para1 depends on article-Art38-Para1 because the security testing plan expressly validates the effectiveness of the ICT project-management procedure required by that paragraph.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art38-Para1"
        },
        {
          "edge_id": "article-Art38-Para2__article-Art38-Para1__references",
          "source": "article-Art38-Para2",
          "target": "article-Art38-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art38-Para2 references article-Art38-Para1 to inherit its financial-entity scope before imposing the separate controlled ICT change-management procedure.",
          "source_canonical_ref": "celex:32024R1774/article-Art38-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art38-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall develop, document, and implement an ICT project management procedure and shall specify the roles and responsibilities for its implementation. That procedure shall cover all stages of the ICT projects from their initiation to their closure.",
          "source_line_start": 6596,
          "source_line_end": 6596
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art38-Para1",
      "text_sha256": "ffff485c58d5245121aa1811bfe887fc743ca27a9c9ffed1bcc9b44fdefba73c"
    },
    {
      "id": "article-Art38-Para2",
      "type": "article_paragraph",
      "article_number": 38,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "ICT project and change management",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER II"
      ],
      "text": "The financial entities referred to in paragraph 1 shall develop, document, and implement an ICT change management procedure to ensure that all changes to ICT systems are recorded, tested, assessed, approved, implemented, and verified in a controlled manner and with the adequate safeguards to preserve the financial entity’s digital operational resilience.",
      "outbound_relations": [
        {
          "edge_id": "article-Art38-Para2__article-Art38-Para1__references",
          "source": "article-Art38-Para2",
          "target": "article-Art38-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art38-Para2 references article-Art38-Para1 to inherit its financial-entity scope before imposing the separate controlled ICT change-management procedure.",
          "source_canonical_ref": "celex:32024R1774/article-Art38-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art38-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art29-Para2__article-Art38-Para2__depends_on",
          "source": "article-Art29-Para2",
          "target": "article-Art38-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art29-Para2 depends on article-Art38-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the controlled ICT change-management procedure covering recording, testing, assessment, approval, implementation and verification of changes.",
          "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art38-Para2"
        },
        {
          "edge_id": "article-Art36-Para1__article-Art38-Para2__depends_on",
          "source": "article-Art36-Para1",
          "target": "article-Art38-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art36-Para1 depends on article-Art38-Para2 because the security testing plan expressly validates the effectiveness of the ICT change-management procedure required by that paragraph.",
          "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art38-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in paragraph 1 shall develop, document, and implement an ICT change management procedure to ensure that all changes to ICT systems are recorded, tested, assessed, approved, implemented, and verified in a controlled manner and with the adequate safeguards to preserve the financial entity’s digital operational resilience.",
          "source_line_start": 6599,
          "source_line_end": 6599
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art38-Para2",
      "text_sha256": "729ccc5e5a002402d9a159a4cfbf3427e1680d4d2aad72831f98c51a10cd8173"
    },
    {
      "id": "article-Art39-Para1",
      "type": "article_paragraph",
      "article_number": 39,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Components of the ICT business continuity plan",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER III"
      ],
      "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall develop their ICT business continuity plans considering the results of the analysis of their exposures to and potential impact of severe business disruptions and scenarios to which their ICT assets supporting critical or important functions might be exposed, including a cyber-attack scenario.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art39-Para2__article-Art39-Para1__depends_on",
          "source": "article-Art39-Para2",
          "target": "article-Art39-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art39-Para2 depends on article-Art39-Para1 because it prescribes the approval, resources, recovery, backup and communication content of the business continuity plans developed under paragraph 1.",
          "source_canonical_ref": "celex:32024R1774/article-Art39-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art39-Para1"
        },
        {
          "edge_id": "article-Art40-Para1__article-Art39-Para1__depends_on",
          "source": "article-Art40-Para1",
          "target": "article-Art39-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art40-Para1 depends on article-Art39-Para1 because the annual or major-change test covers the business continuity plans and severe-disruption scenarios established in Article 39(1).",
          "source_canonical_ref": "celex:32024R1774/article-Art40-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art39-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall develop their ICT business continuity plans considering the results of the analysis of their exposures to and potential impact of severe business disruptions and scenarios to which their ICT assets supporting critical or important functions might be exposed, including a cyber-attack scenario.",
          "source_line_start": 6620,
          "source_line_end": 6620
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art39-Para1",
      "text_sha256": "fa29ddb73ab9c8037a1ca8db3423545c70566194943f95ad27d51d23cf4b5384"
    },
    {
      "id": "article-Art39-Para2",
      "type": "article_paragraph",
      "article_number": 39,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Components of the ICT business continuity plan",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "be approved by the management body of the financial entity;",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 6630,
          "source_line_end": 6633
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "be documented and readily accessible in the event of an emergency or crisis;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 6644,
          "source_line_end": 6647
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "allocate sufficient resources for their execution;",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 6658,
          "source_line_end": 6661
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "establish planned recovery levels and timeframes for the recovery and resumption of functions and key internal and external dependencies, including ICT third-party service providers;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 6672,
          "source_line_end": 6675
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "identify the conditions that may prompt the activation of the ICT business continuity plans and what actions are to be taken to ensure the availability, continuity, and recovery of the financial entities’ ICT assets supporting critical or important functions;",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 6686,
          "source_line_end": 6689
        },
        {
          "type": "point",
          "marker": "(f)",
          "text": "identify the restoration and recovery measures for critical or important business functions, supporting processes, information assets, and their interdependencies to avoid adverse effects on the functioning of the financial entities;",
          "depth": 1,
          "parent_marker": null,
          "path": "(f)",
          "source_line_start": 6700,
          "source_line_end": 6703
        },
        {
          "type": "point",
          "marker": "(g)",
          "text": "identify backup procedures and measures that specify the scope of the data that are subject to the backup, and the minimum frequency of the backup, based on the criticality of the function using those data;",
          "depth": 1,
          "parent_marker": null,
          "path": "(g)",
          "source_line_start": 6714,
          "source_line_end": 6717
        },
        {
          "type": "point",
          "marker": "(h)",
          "text": "consider alternative options where recovery may not be feasible in the short term because of costs, risks, logistics, or unforeseen circumstances;",
          "depth": 1,
          "parent_marker": null,
          "path": "(h)",
          "source_line_start": 6728,
          "source_line_end": 6731
        },
        {
          "type": "point",
          "marker": "(i)",
          "text": "specify the internal and external communication arrangements, including escalation plans;",
          "depth": 1,
          "parent_marker": null,
          "path": "(i)",
          "source_line_start": 6742,
          "source_line_end": 6745
        },
        {
          "type": "point",
          "marker": "(j)",
          "text": "be updated in line with lessons learned from incidents, tests, new risks, and threats identified, changed recovery objectives, major changes to the financial entity’s organisation, and to the ICT assets supporting critical or business functions.",
          "depth": 1,
          "parent_marker": null,
          "path": "(j)",
          "source_line_start": 6756,
          "source_line_end": 6759
        }
      ],
      "ancestry": [
        "TITLE III",
        "CHAPTER III"
      ],
      "text": "The ICT business continuity plans referred to in paragraph 1 shall: (a) be approved by the management body of the financial entity; (b) be documented and readily accessible in the event of an emergency or crisis; (c) allocate sufficient resources for their execution; (d) establish planned recovery levels and timeframes for the recovery and resumption of functions and key internal and external dependencies, including ICT third-party service providers; (e) identify the conditions that may prompt the activation of the ICT business continuity plans and what actions are to be taken to ensure the availability, continuity, and recovery of the financial entities’ ICT assets supporting critical or important functions; (f) identify the restoration and recovery measures for critical or important business functions, supporting processes, information assets, and their interdependencies to avoid adverse effects on the functioning of the financial entities; (g) identify backup procedures and measures that specify the scope of the data that are subject to the backup, and the minimum frequency of the backup, based on the criticality of the function using those data; (h) consider alternative options where recovery may not be feasible in the short term because of costs, risks, logistics, or unforeseen circumstances; (i) specify the internal and external communication arrangements, including escalation plans; (j) be updated in line with lessons learned from incidents, tests, new risks, and threats identified, changed recovery objectives, major changes to the financial entity’s organisation, and to the ICT assets supporting critical or business functions. For the purposes of point (f), the measures referred to in that point shall provide for the mitigation of failures of critical third-party providers.",
      "outbound_relations": [
        {
          "edge_id": "article-Art39-Para2__article-Art39-Para1__depends_on",
          "source": "article-Art39-Para2",
          "target": "article-Art39-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art39-Para2 depends on article-Art39-Para1 because it prescribes the approval, resources, recovery, backup and communication content of the business continuity plans developed under paragraph 1.",
          "source_canonical_ref": "celex:32024R1774/article-Art39-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art39-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art40-Para1__article-Art39-Para2__depends_on",
          "source": "article-Art40-Para1",
          "target": "article-Art39-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art40-Para1 depends on article-Art39-Para2 because its express requirement to test the Article 39 business continuity plans at least annually for backup and restore procedures reaches the paragraph that specifies backup procedures, restoration and recovery measures, recovery levels and timeframes.",
          "source_canonical_ref": "celex:32024R1774/article-Art40-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art39-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The ICT business continuity plans referred to in paragraph 1 shall:",
          "source_line_start": 6623,
          "source_line_end": 6623
        },
        {
          "sequence": 2,
          "text": "For the purposes of point (f), the measures referred to in that point shall provide for the mitigation of failures of critical third-party providers.",
          "source_line_start": 6764,
          "source_line_end": 6764
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art39-Para2",
      "text_sha256": "b15349783f755bd05fab47a0fb8d55eb3e46b9648c5c3b48b1e5c6edb5d505bf"
    },
    {
      "id": "article-Art40-Para1",
      "type": "article_paragraph",
      "article_number": 40,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Testing of business continuity plans",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER III"
      ],
      "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall test their business continuity plans referred to in Article 39 of this Regulation, including the scenarios referred to in that Article, at least once every year for the back-up and restore procedures, or upon every major change of the business continuity plan.",
      "outbound_relations": [
        {
          "edge_id": "article-Art40-Para1__article-Art39-Para1__depends_on",
          "source": "article-Art40-Para1",
          "target": "article-Art39-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art40-Para1 depends on article-Art39-Para1 because the annual or major-change test covers the business continuity plans and severe-disruption scenarios established in Article 39(1).",
          "source_canonical_ref": "celex:32024R1774/article-Art40-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art39-Para1"
        },
        {
          "edge_id": "article-Art40-Para1__article-Art39-Para2__depends_on",
          "source": "article-Art40-Para1",
          "target": "article-Art39-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art40-Para1 depends on article-Art39-Para2 because its express requirement to test the Article 39 business continuity plans at least annually for backup and restore procedures reaches the paragraph that specifies backup procedures, restoration and recovery measures, recovery levels and timeframes.",
          "source_canonical_ref": "celex:32024R1774/article-Art40-Para1",
          "target_canonical_ref": "celex:32024R1774/article-Art39-Para2"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art40-Para2__article-Art40-Para1__depends_on",
          "source": "article-Art40-Para2",
          "target": "article-Art40-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art40-Para2 depends on article-Art40-Para1 because it defines what the paragraph-1 testing must demonstrate about business viability, operational re-establishment and plan deficiencies.",
          "source_canonical_ref": "celex:32024R1774/article-Art40-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art40-Para1"
        },
        {
          "edge_id": "article-Art40-Para3__article-Art40-Para1__references",
          "source": "article-Art40-Para3",
          "target": "article-Art40-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art40-Para3 references article-Art40-Para1 to inherit the financial-entity scope and the business-continuity-plan testing whose results must be documented.",
          "source_canonical_ref": "celex:32024R1774/article-Art40-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art40-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall test their business continuity plans referred to in Article 39 of this Regulation, including the scenarios referred to in that Article, at least once every year for the back-up and restore procedures, or upon every major change of the business continuity plan.",
          "source_line_start": 6773,
          "source_line_end": 6773
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art40-Para1",
      "text_sha256": "20837b356261c438efaa433e096c33de1a5a999dcdf30e7d8e57decef7a7e013"
    },
    {
      "id": "article-Art40-Para2",
      "type": "article_paragraph",
      "article_number": 40,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Testing of business continuity plans",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER III"
      ],
      "text": "The testing of business continuity plans referred to in paragraph 1 shall demonstrate that the financial entities referred to in that paragraph are able to sustain the viability of their businesses until critical operations are re-established and identify any deficiencies in those plans.",
      "outbound_relations": [
        {
          "edge_id": "article-Art40-Para2__article-Art40-Para1__depends_on",
          "source": "article-Art40-Para2",
          "target": "article-Art40-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art40-Para2 depends on article-Art40-Para1 because it defines what the paragraph-1 testing must demonstrate about business viability, operational re-establishment and plan deficiencies.",
          "source_canonical_ref": "celex:32024R1774/article-Art40-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art40-Para1"
        }
      ],
      "inbound_relations": [
        {
          "edge_id": "article-Art40-Para3__article-Art40-Para2__depends_on",
          "source": "article-Art40-Para3",
          "target": "article-Art40-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art40-Para3 depends on article-Art40-Para2 because the deficiencies to be analysed, addressed and reported are those the paragraph-2 test is required to identify.",
          "source_canonical_ref": "celex:32024R1774/article-Art40-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art40-Para2"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The testing of business continuity plans referred to in paragraph 1 shall demonstrate that the financial entities referred to in that paragraph are able to sustain the viability of their businesses until critical operations are re-established and identify any deficiencies in those plans.",
          "source_line_start": 6776,
          "source_line_end": 6776
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art40-Para2",
      "text_sha256": "f061dddbcadf3f73acb7ac50226aabbc194818b268760fc9b7fd5305edf97ec5"
    },
    {
      "id": "article-Art40-Para3",
      "type": "article_paragraph",
      "article_number": 40,
      "paragraph_number": "3",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Testing of business continuity plans",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER III"
      ],
      "text": "The financial entities referred to in paragraph 1 shall document the results of the testing of business continuity plans and any identified deficiencies resulting from that testing shall be analysed, addressed, and reported to the management body.",
      "outbound_relations": [
        {
          "edge_id": "article-Art40-Para3__article-Art40-Para1__references",
          "source": "article-Art40-Para3",
          "target": "article-Art40-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "references",
          "confidence": "high",
          "reasoning": "article-Art40-Para3 references article-Art40-Para1 to inherit the financial-entity scope and the business-continuity-plan testing whose results must be documented.",
          "source_canonical_ref": "celex:32024R1774/article-Art40-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art40-Para1"
        },
        {
          "edge_id": "article-Art40-Para3__article-Art40-Para2__depends_on",
          "source": "article-Art40-Para3",
          "target": "article-Art40-Para2",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art40-Para3 depends on article-Art40-Para2 because the deficiencies to be analysed, addressed and reported are those the paragraph-2 test is required to identify.",
          "source_canonical_ref": "celex:32024R1774/article-Art40-Para3",
          "target_canonical_ref": "celex:32024R1774/article-Art40-Para2"
        }
      ],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in paragraph 1 shall document the results of the testing of business continuity plans and any identified deficiencies resulting from that testing shall be analysed, addressed, and reported to the management body.",
          "source_line_start": 6779,
          "source_line_end": 6779
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art40-Para3",
      "text_sha256": "93e924c608d8ca157372d1132e8aed6ac424c82660e980aff4204e3297887189"
    },
    {
      "id": "article-Art41-Para1",
      "type": "article_paragraph",
      "article_number": 41,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Format and content of the report on the review of the simplified ICT risk management framework",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE III",
        "CHAPTER IV"
      ],
      "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall submit the report on the review of the ICT risk management framework referred to in paragraph 2 of that Article in a searchable electronic format.",
      "outbound_relations": [],
      "inbound_relations": [
        {
          "edge_id": "article-Art41-Para2__article-Art41-Para1__depends_on",
          "source": "article-Art41-Para2",
          "target": "article-Art41-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art41-Para2 depends on article-Art41-Para1 because it specifies the mandatory content of the searchable electronic simplified-framework review report introduced in paragraph 1.",
          "source_canonical_ref": "celex:32024R1774/article-Art41-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art41-Para1"
        }
      ],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The financial entities referred to in Article 16(1) of Regulation (EU) 2022/2554 shall submit the report on the review of the ICT risk management framework referred to in paragraph 2 of that Article in a searchable electronic format.",
          "source_line_start": 6800,
          "source_line_end": 6800
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art41-Para1",
      "text_sha256": "96a40cc9ab9c42e2d14fdd88599878c36c193318e53f4e50f9333399dbb13a16"
    },
    {
      "id": "article-Art41-Para2",
      "type": "article_paragraph",
      "article_number": 41,
      "paragraph_number": "2",
      "akn4eu_paragraph_kind": "numbered",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Format and content of the report on the review of the simplified ICT risk management framework",
      "akn4eu_sub_units": [
        {
          "type": "point",
          "marker": "(a)",
          "text": "an introductory section providing:",
          "depth": 1,
          "parent_marker": null,
          "path": "(a)",
          "source_line_start": 6810,
          "source_line_end": 6813
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "a description of the context of the report in terms of the nature, scale, and complexity of the financial entity’s services, activities, and operations, the financial entity’s organisation, identified critical functions, strategy, major ongoing projects or activities, and relationships, and the financial entity’s dependence on in-house and outsourced ICT services and systems, or the implications that a total loss or severe degradation of such systems would have on critical or important functions and market efficiency;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(i)",
          "source_line_start": 6820,
          "source_line_end": 6823
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "an executive level summary of the current and near-term ICT risk identified, threat landscape, the assessed effectiveness of its controls, and the security posture of the financial entity;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(ii)",
          "source_line_start": 6834,
          "source_line_end": 6837
        },
        {
          "type": "subpoint",
          "marker": "(iii)",
          "text": "information about the reported area;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(iii)",
          "source_line_start": 6848,
          "source_line_end": 6851
        },
        {
          "type": "subpoint",
          "marker": "(iv)",
          "text": "a summary of the major changes in the ICT risk management framework since the previous report;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(iv)",
          "source_line_start": 6862,
          "source_line_end": 6865
        },
        {
          "type": "subpoint",
          "marker": "(v)",
          "text": "a summary and a description of the impact of major changes to the simplified ICT risk management framework since the previous report;",
          "depth": 2,
          "parent_marker": "(a)",
          "path": "(a)(v)",
          "source_line_start": 6876,
          "source_line_end": 6879
        },
        {
          "type": "point",
          "marker": "(b)",
          "text": "where applicable, the date of the approval of the report by the management body of the financial entity;",
          "depth": 1,
          "parent_marker": null,
          "path": "(b)",
          "source_line_start": 6894,
          "source_line_end": 6897
        },
        {
          "type": "point",
          "marker": "(c)",
          "text": "a description of the reasons for the review, including:",
          "depth": 1,
          "parent_marker": null,
          "path": "(c)",
          "source_line_start": 6908,
          "source_line_end": 6911
        },
        {
          "type": "subpoint",
          "marker": "(i)",
          "text": "where the review has been initiated following supervisory instructions, evidence of such instructions;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(i)",
          "source_line_start": 6918,
          "source_line_end": 6921
        },
        {
          "type": "subpoint",
          "marker": "(ii)",
          "text": "where the review has been initiated following the occurrence of ICT-related incidents, the list of all those ICT-related incidents with related incident root-cause analysis;",
          "depth": 2,
          "parent_marker": "(c)",
          "path": "(c)(ii)",
          "source_line_start": 6932,
          "source_line_end": 6935
        },
        {
          "type": "point",
          "marker": "(d)",
          "text": "the start and end date of the review period;",
          "depth": 1,
          "parent_marker": null,
          "path": "(d)",
          "source_line_start": 6950,
          "source_line_end": 6953
        },
        {
          "type": "point",
          "marker": "(e)",
          "text": "the person responsible for the review;",
          "depth": 1,
          "parent_marker": null,
          "path": "(e)",
          "source_line_start": 6964,
          "source_line_end": 6967
        },
        {
          "type": "point",
          "marker": "(f)",
          "text": "a summary of findings, and a self-assessment of the severity of the weaknesses, deficiencies, and gaps identified in ICT risk management framework for the review period, including a detailed analysis thereof;",
          "depth": 1,
          "parent_marker": null,
          "path": "(f)",
          "source_line_start": 6978,
          "source_line_end": 6981
        },
        {
          "type": "point",
          "marker": "(g)",
          "text": "remedying measures identified to address weaknesses, deficiencies, and gaps in the simplified ICT risk management framework, and the expected date for implementing those measures, including the follow-up on weaknesses, deficiencies, and gaps identified in previous reports, where those weaknesses, deficiencies, and gaps have not yet been remedied;",
          "depth": 1,
          "parent_marker": null,
          "path": "(g)",
          "source_line_start": 6992,
          "source_line_end": 6995
        },
        {
          "type": "point",
          "marker": "(h)",
          "text": "overall conclusions on the review of the simplified ICT risk management framework, including any further planned developments.",
          "depth": 1,
          "parent_marker": null,
          "path": "(h)",
          "source_line_start": 7006,
          "source_line_end": 7009
        }
      ],
      "ancestry": [
        "TITLE III",
        "CHAPTER IV"
      ],
      "text": "The report referred to in paragraph 1 shall contain all of the following information: (a) an introductory section providing: (i) a description of the context of the report in terms of the nature, scale, and complexity of the financial entity’s services, activities, and operations, the financial entity’s organisation, identified critical functions, strategy, major ongoing projects or activities, and relationships, and the financial entity’s dependence on in-house and outsourced ICT services and systems, or the implications that a total loss or severe degradation of such systems would have on critical or important functions and market efficiency; (ii) an executive level summary of the current and near-term ICT risk identified, threat landscape, the assessed effectiveness of its controls, and the security posture of the financial entity; (iii) information about the reported area; (iv) a summary of the major changes in the ICT risk management framework since the previous report; (v) a summary and a description of the impact of major changes to the simplified ICT risk management framework since the previous report; (b) where applicable, the date of the approval of the report by the management body of the financial entity; (c) a description of the reasons for the review, including: (i) where the review has been initiated following supervisory instructions, evidence of such instructions; (ii) where the review has been initiated following the occurrence of ICT-related incidents, the list of all those ICT-related incidents with related incident root-cause analysis; (d) the start and end date of the review period; (e) the person responsible for the review; (f) a summary of findings, and a self-assessment of the severity of the weaknesses, deficiencies, and gaps identified in ICT risk management framework for the review period, including a detailed analysis thereof; (g) remedying measures identified to address weaknesses, deficiencies, and gaps in the simplified ICT risk management framework, and the expected date for implementing those measures, including the follow-up on weaknesses, deficiencies, and gaps identified in previous reports, where those weaknesses, deficiencies, and gaps have not yet been remedied; (h) overall conclusions on the review of the simplified ICT risk management framework, including any further planned developments.",
      "outbound_relations": [
        {
          "edge_id": "article-Art41-Para2__article-Art41-Para1__depends_on",
          "source": "article-Art41-Para2",
          "target": "article-Art41-Para1",
          "source_type": "article_paragraph",
          "target_type": "article_paragraph",
          "relation": "depends_on",
          "confidence": "high",
          "reasoning": "article-Art41-Para2 depends on article-Art41-Para1 because it specifies the mandatory content of the searchable electronic simplified-framework review report introduced in paragraph 1.",
          "source_canonical_ref": "celex:32024R1774/article-Art41-Para2",
          "target_canonical_ref": "celex:32024R1774/article-Art41-Para1"
        }
      ],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "The report referred to in paragraph 1 shall contain all of the following information:",
          "source_line_start": 6803,
          "source_line_end": 6803
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art41-Para2",
      "text_sha256": "de11315732de2c4d50f99631fd389dae0943da1b3023dc9347e6967c4bdc4e44"
    },
    {
      "id": "article-Art42-Para1",
      "type": "article_paragraph",
      "article_number": 42,
      "paragraph_number": "1",
      "akn4eu_paragraph_kind": "single",
      "akn4eu_article_kind": "regular",
      "akn4eu_heading": "Entry into force",
      "akn4eu_sub_units": [],
      "ancestry": [
        "TITLE IV"
      ],
      "text": "This Regulation shall enter into force on the twentieth day following that of its publication in the Official Journal of the European Union .",
      "outbound_relations": [],
      "inbound_relations": [],
      "akn4eu_source_paragraphs": [
        {
          "sequence": 1,
          "text": "This Regulation shall enter into force on the twentieth day following that of its publication in the Official Journal of the European Union.",
          "source_line_start": 7030,
          "source_line_end": 7030
        }
      ],
      "akn4eu_article_type_uri": "http://publications.europa.eu/resource/authority/resource-type/ART",
      "canonical_ref": "celex:32024R1774/article-Art42-Para1",
      "text_sha256": "1bf0e7175a7bcc082e16d3f0989df2463f5335c79522f61c6297e2b6faf20be3"
    }
  ],
  "annex_points": [],
  "recital_to_recital": [
    {
      "edge_id": "recital-12__recital-11__builds_on",
      "from_recital": 12,
      "to_recital": 11,
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-12 builds on recital-11 by presenting controlled patch testing and deployment as the remediation step for the vulnerabilities that recital-11 requires financial entities and their ICT providers to identify and address."
    },
    {
      "edge_id": "recital-17__recital-15__builds_on",
      "from_recital": 17,
      "to_recital": 15,
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-17 builds on recital-15 because recital-15 places ICT changes within project management and testing, while recital-17 develops that change strand into dedicated approval-separation, transition, quality, and fall-back controls."
    },
    {
      "edge_id": "recital-19__recital-18__builds_on",
      "from_recital": 19,
      "to_recital": 18,
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-19 builds on recital-18 by developing the detection phase of recital-18's incident-management process into concrete internal, log, external, and ICT-provider information sources with assigned responsibilities."
    },
    {
      "edge_id": "recital-19__recital-30__provides_context_for",
      "from_recital": 19,
      "to_recital": 30,
      "relation": "provides_context_for",
      "confidence": "high",
      "reasoning": "recital-19 provides context for recital-30 because its incident-detection data collection is the concrete setting in which recital-30 reiterates full data-protection application and uses data minimisation for incident detection as its example."
    },
    {
      "edge_id": "recital-20__recital-18__builds_on",
      "from_recital": 20,
      "to_recital": 18,
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-20 builds on recital-18 by adding evidence retention and a calibrated retention period to the incident-policy and incident-management process introduced in recital-18."
    },
    {
      "edge_id": "recital-21__recital-18__builds_on",
      "from_recital": 21,
      "to_recital": 18,
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-21 builds on recital-18 by specifying how trigger criteria are to operate within the detection and response phases of the incident-management process established in recital-18."
    },
    {
      "edge_id": "recital-22__recital-17__builds_on",
      "from_recital": 22,
      "to_recital": 17,
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-22 builds on recital-17 by expressly making the ICT change-management process developed in recital-17 an input to the design of the ICT business continuity policy."
    },
    {
      "edge_id": "recital-22__recital-18__builds_on",
      "from_recital": 22,
      "to_recital": 18,
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-22 builds on recital-18 by expressly incorporating ICT-related incident management and its communication dimension into the ICT business continuity policy."
    },
    {
      "edge_id": "recital-23__recital-22__builds_on",
      "from_recital": 23,
      "to_recital": 22,
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-23 builds on recital-22 by moving from the components to be integrated into an ICT business continuity policy to the scenarios used to implement response and recovery plans and test continuity plans."
    },
    {
      "edge_id": "recital-26__recital-2__builds_on",
      "from_recital": 26,
      "to_recital": 2,
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-26 builds_on recital-2 by turning recital-2’s flexibility and essential-policy premise into the simplified-framework rule that entities maintain one high-level information security policy proportionate to scale and risk."
    },
    {
      "edge_id": "recital-29__recital-28__builds_on",
      "from_recital": 29,
      "to_recital": 28,
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-29 builds_on recital-28: recital-28 identifies the ESAs’ draft regulatory technical standards, while recital-29 records the Joint Committee consultation, cost-benefit analysis and stakeholder advice for that same draft."
    },
    {
      "edge_id": "recital-2__recital-1__builds_on",
      "from_recital": 2,
      "to_recital": 1,
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-2 expressly proceeds 'for the same reason' from recital-1's proportionality rationale and develops that rationale into flexibility and documentation reuse."
    },
    {
      "edge_id": "recital-4__recital-3__qualifies",
      "from_recital": 4,
      "to_recital": 3,
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "recital-4 qualifies recital-3's general assignment of ICT roles by requiring segregation of duties where needed to avoid conflicts of interest."
    },
    {
      "edge_id": "recital-5__recital-3__qualifies",
      "from_recital": 5,
      "to_recital": 3,
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "recital-5 qualifies recital-3's requirement for non-compliance consequences by creating an exception when another policy or procedure already states them."
    },
    {
      "edge_id": "recital-6__recital-2__builds_on",
      "from_recital": 6,
      "to_recital": 2,
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-6 builds on recital-2's leading-practice and standards principle by explaining its continuing importance in an evolving ICT-risk landscape."
    },
    {
      "edge_id": "recital-7__recital-2__builds_on",
      "from_recital": 7,
      "to_recital": 2,
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-7 builds on recital-2's identification of technical procedure domains by explaining the operational purposes of asset, capacity and ICT-operations controls."
    },
    {
      "edge_id": "recital-8__recital-7__builds_on",
      "from_recital": 8,
      "to_recital": 7,
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-8 builds on recital-7's lifecycle-based asset-management rationale by addressing the specific legacy-system risk created when third-party support expires."
    }
  ],
  "article_to_article": [
    {
      "edge_id": "article-Art10-Para2__article-Art10-Para1__depends_on",
      "from_article": 10,
      "from_paragraph": "2",
      "to_article": 10,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art10-Para2 enumerates the scanning, third-party, remediation and recording controls for the vulnerability-management procedures mandated by article-Art10-Para1."
    },
    {
      "edge_id": "article-Art10-Para4__article-Art10-Para3__depends_on",
      "from_article": 10,
      "from_paragraph": "4",
      "to_article": 10,
      "to_paragraph": "3",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art10-Para4 sets the evaluation, emergency, testing, deployment and deadline requirements for the patch-management procedures established by article-Art10-Para3."
    },
    {
      "edge_id": "article-Art10-Para4__article-Art8-Para2__references",
      "from_article": 10,
      "from_paragraph": "4",
      "to_article": 8,
      "to_paragraph": "2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art10-Para4 expressly refers patch and update testing and deployment to the production and non-production testing controls in article-Art8-Para2 points (b)(v) to (vii)."
    },
    {
      "edge_id": "article-Art11-Para2__article-Art11-Para1__depends_on",
      "from_article": 11,
      "from_paragraph": "2",
      "to_article": 11,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art11-Para2 expressly takes the data and system security procedure established by article-Art11-Para1 as the procedure whose mandatory security elements it enumerates."
    },
    {
      "edge_id": "article-Art11-Para2__article-Art21-Para1__references",
      "from_article": 11,
      "from_paragraph": "2",
      "to_article": 21,
      "to_paragraph": "1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art11-Para2 expressly imports the access restrictions laid down in article-Art21-Para1 as an element supporting the protection requirements attached to each data-classification level."
    },
    {
      "edge_id": "article-Art11-Para2__article-Art3-Para1__references",
      "from_article": 11,
      "from_paragraph": "2",
      "to_article": 3,
      "to_paragraph": "1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art11-Para2 conditions use of removable data-storage devices on residual ICT risk remaining within the risk-tolerance level established in article-Art3-Para1, first subparagraph, point (a)."
    },
    {
      "edge_id": "article-Art12-Para2__article-Art12-Para1__depends_on",
      "from_article": 12,
      "from_paragraph": "2",
      "to_article": 12,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art12-Para2 expressly specifies the mandatory contents of the logging procedures, protocols and tools that article-Art12-Para1 requires financial entities to establish."
    },
    {
      "edge_id": "article-Art12-Para2__article-Art21-Para1__references",
      "from_article": 12,
      "from_paragraph": "2",
      "to_article": 21,
      "to_paragraph": "1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art12-Para2 expressly requires logs for logical and physical access-control events governed by article-Art21-Para1."
    },
    {
      "edge_id": "article-Art13-Para1__article-Art6-Para2__references",
      "from_article": 13,
      "from_paragraph": "1",
      "to_article": 6,
      "to_paragraph": "2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art13-Para1 expressly requires network-connection encryption to take account of the encryption of network connections governed by article-Art6-Para2."
    },
    {
      "edge_id": "article-Art14-Para2__article-Art14-Para1__depends_on",
      "from_article": 14,
      "from_paragraph": "2",
      "to_article": 14,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art14-Para2 expressly requires the information-in-transit policies and controls established by article-Art14-Para1 to be designed from the approved data classification and ICT risk assessment."
    },
    {
      "edge_id": "article-Art15-Para2__article-Art15-Para1__depends_on",
      "from_article": 15,
      "from_paragraph": "2",
      "to_article": 15,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art15-Para2 expressly defines the acquisition, maintenance and development projects that must be covered by the ICT project-management policy required in article-Art15-Para1."
    },
    {
      "edge_id": "article-Art15-Para3__article-Art15-Para1__depends_on",
      "from_article": 15,
      "from_paragraph": "3",
      "to_article": 15,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art15-Para3 expressly enumerates the governance, planning, risk, change and testing contents of the ICT project-management policy required by article-Art15-Para1."
    },
    {
      "edge_id": "article-Art15-Para4__article-Art15-Para1__depends_on",
      "from_article": 15,
      "from_paragraph": "4",
      "to_article": 15,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art15-Para4 expressly adds business-area information and expertise as a secure-implementation requirement of the ICT project-management policy established in article-Art15-Para1."
    },
    {
      "edge_id": "article-Art15-Para5__article-Art15-Para1__depends_on",
      "from_article": 15,
      "from_paragraph": "5",
      "to_article": 15,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art15-Para5 expressly makes reporting on critical or important ICT projects and their risks a requirement of the project-management policy established in article-Art15-Para1."
    },
    {
      "edge_id": "article-Art15-Para5__article-Art15-Para3__references",
      "from_article": 15,
      "from_paragraph": "5",
      "to_article": 15,
      "to_paragraph": "3",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art15-Para5 expressly bases management-body reporting on the ICT project risk assessment required by article-Art15-Para3, point (d)."
    },
    {
      "edge_id": "article-Art16-Para2__article-Art8-Para2__references",
      "from_article": 16,
      "from_paragraph": "2",
      "to_article": 8,
      "to_paragraph": "2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art16-Para2 expressly requires pre-use and post-maintenance ICT-system testing to follow the production-separation and testing controls in article-Art8-Para2, point (b)(v) to (vii)."
    },
    {
      "edge_id": "article-Art16-Para3__article-Art16-Para2__depends_on",
      "from_article": 16,
      "from_paragraph": "3",
      "to_article": 16,
      "to_paragraph": "2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para3 expressly makes source-code review and the resulting vulnerability action plan part of the acquisition, development and maintenance testing procedure established in article-Art16-Para2."
    },
    {
      "edge_id": "article-Art16-Para3__article-Art8-Para2__references",
      "from_article": 16,
      "from_paragraph": "3",
      "to_article": 8,
      "to_paragraph": "2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art16-Para3 expressly subjects security testing for internet-exposed systems and applications to the environment-separation and production-testing requirements in article-Art8-Para2, point (b)(v) to (vii)."
    },
    {
      "edge_id": "article-Art16-Para4__article-Art16-Para2__depends_on",
      "from_article": 16,
      "from_paragraph": "4",
      "to_article": 16,
      "to_paragraph": "2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para4 expressly adds integration-phase security testing of software packages to the testing procedure established in article-Art16-Para2."
    },
    {
      "edge_id": "article-Art16-Para4__article-Art8-Para2__references",
      "from_article": 16,
      "from_paragraph": "4",
      "to_article": 8,
      "to_paragraph": "2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art16-Para4 expressly subjects software-package security testing to the environment-separation and production-testing requirements in article-Art8-Para2, point (b)(v) to (vii)."
    },
    {
      "edge_id": "article-Art16-Para5__article-Art16-Para2__depends_on",
      "from_article": 16,
      "from_paragraph": "5",
      "to_article": 16,
      "to_paragraph": "2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para5 expressly makes anonymisation, pseudonymisation or randomisation of production data and protection of non-production data part of the testing procedure established in article-Art16-Para2."
    },
    {
      "edge_id": "article-Art16-Para6__article-Art16-Para2__depends_on",
      "from_article": 16,
      "from_paragraph": "6",
      "to_article": 16,
      "to_paragraph": "2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para6 expressly places its tightly controlled production-data testing exception within the acquisition, development and maintenance procedure established in article-Art16-Para2."
    },
    {
      "edge_id": "article-Art16-Para6__article-Art16-Para5__qualifies",
      "from_article": 16,
      "from_paragraph": "6",
      "to_article": 16,
      "to_paragraph": "5",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "article-Art16-Para6 expressly derogates from article-Art16-Para5 by permitting production data for specific testing occasions only for limited periods, after approval and with reporting to the ICT risk-management function."
    },
    {
      "edge_id": "article-Art16-Para7__article-Art16-Para2__depends_on",
      "from_article": 16,
      "from_paragraph": "7",
      "to_article": 16,
      "to_paragraph": "2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para7 expressly adds controls protecting source-code integrity, including code developed by ICT third-party providers, to the procedure established in article-Art16-Para2."
    },
    {
      "edge_id": "article-Art16-Para8__article-Art16-Para2__depends_on",
      "from_article": 16,
      "from_paragraph": "8",
      "to_article": 16,
      "to_paragraph": "2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para8 expressly makes pre-deployment analysis and testing of proprietary, third-party and open-source software part of the procedure established in article-Art16-Para2."
    },
    {
      "edge_id": "article-Art16-Para8__article-Art16-Para3__references",
      "from_article": 16,
      "from_paragraph": "8",
      "to_article": 16,
      "to_paragraph": "3",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art16-Para8 expressly requires proprietary, third-party and open-source software to be analysed and tested according to the static and dynamic source-code review regime in article-Art16-Para3."
    },
    {
      "edge_id": "article-Art16-Para9__article-Art16-Para1__depends_on",
      "from_article": 16,
      "from_paragraph": "9",
      "to_article": 16,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para9 expressly extends the acquisition, development and maintenance policy duty in article-Art16-Para1 to ICT systems developed or managed by users outside the ICT function, subject to a risk-based approach."
    },
    {
      "edge_id": "article-Art16-Para9__article-Art16-Para2__depends_on",
      "from_article": 16,
      "from_paragraph": "9",
      "to_article": 16,
      "to_paragraph": "2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para9 expressly extends the pre-use and post-maintenance testing and approval procedure in article-Art16-Para2 to ICT systems developed or managed outside the ICT function."
    },
    {
      "edge_id": "article-Art16-Para9__article-Art16-Para3__depends_on",
      "from_article": 16,
      "from_paragraph": "9",
      "to_article": 16,
      "to_paragraph": "3",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para9 expressly extends the source-code review, vulnerability analysis and remediation regime in article-Art16-Para3 to user-developed or user-managed ICT systems."
    },
    {
      "edge_id": "article-Art16-Para9__article-Art16-Para4__depends_on",
      "from_article": 16,
      "from_paragraph": "9",
      "to_article": 16,
      "to_paragraph": "4",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para9 expressly extends the integration-phase software-package security testing required by article-Art16-Para4 to ICT systems developed or managed outside the ICT function."
    },
    {
      "edge_id": "article-Art16-Para9__article-Art16-Para5__depends_on",
      "from_article": 16,
      "from_paragraph": "9",
      "to_article": 16,
      "to_paragraph": "5",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para9 expressly extends the non-production data safeguards in article-Art16-Para5 to ICT systems developed or managed by users outside the ICT function."
    },
    {
      "edge_id": "article-Art16-Para9__article-Art16-Para6__depends_on",
      "from_article": 16,
      "from_paragraph": "9",
      "to_article": 16,
      "to_paragraph": "6",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para9 expressly extends the limited and approved production-data testing exception in article-Art16-Para6 to ICT systems developed or managed outside the ICT function."
    },
    {
      "edge_id": "article-Art16-Para9__article-Art16-Para7__depends_on",
      "from_article": 16,
      "from_paragraph": "9",
      "to_article": 16,
      "to_paragraph": "7",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para9 expressly extends the source-code integrity controls in article-Art16-Para7 to ICT systems developed or managed by users outside the ICT function."
    },
    {
      "edge_id": "article-Art16-Para9__article-Art16-Para8__depends_on",
      "from_article": 16,
      "from_paragraph": "9",
      "to_article": 16,
      "to_paragraph": "8",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para9 expressly extends the pre-deployment proprietary, third-party and open-source analysis required by article-Art16-Para8 to systems developed or managed outside the ICT function."
    },
    {
      "edge_id": "article-Art18-Para2__article-Art18-Para1__depends_on",
      "from_article": 18,
      "from_paragraph": "2",
      "to_article": 18,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art18-Para2 expressly enumerates the access, environmental, asset-protection and clear-desk controls that the physical and environmental security policy established in article-Art18-Para1 must contain."
    },
    {
      "edge_id": "article-Art18-Para2__article-Art21-Para1__references",
      "from_article": 18,
      "from_paragraph": "2",
      "to_article": 21,
      "to_paragraph": "1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art18-Para2 expressly imports the physical access-management controls in article-Art21-Para1, point (g), into the physical and environmental security policy."
    },
    {
      "edge_id": "article-Art2-Para2__article-Art2-Para1__depends_on",
      "from_article": 2,
      "from_paragraph": "2",
      "to_article": 2,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art2-Para2 expressly applies its governance and content requirements to the ICT security policies established under article-Art2-Para1."
    },
    {
      "edge_id": "article-Art20-Para1__article-Art21-Para1__references",
      "from_article": 20,
      "from_paragraph": "1",
      "to_article": 21,
      "to_paragraph": "1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art20-Para1 expressly makes unique identification and authentication the prerequisite for assigning user access rights under article-Art21-Para1."
    },
    {
      "edge_id": "article-Art20-Para2__article-Art20-Para1__depends_on",
      "from_article": 20,
      "from_paragraph": "2",
      "to_article": 20,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art20-Para2 expressly specifies the unique-account and identity-lifecycle contents of the identity-management policies and procedures established in article-Art20-Para1."
    },
    {
      "edge_id": "article-Art20-Para2__article-Art21-Para1__references",
      "from_article": 20,
      "from_paragraph": "2",
      "to_article": 21,
      "to_paragraph": "1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art20-Para2 expressly references article-Art21-Para1 through a without-prejudice clause that preserves the exceptional generic and shared-account regime in point (c) while imposing the one-identity-to-one-account rule."
    },
    {
      "edge_id": "article-Art22-Para1__article-Art23-Para2__references",
      "from_article": 22,
      "from_paragraph": "1",
      "to_article": 23,
      "to_paragraph": "2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art22-Para1 expressly requires its incident-policy mechanisms to enable prompt anomalous-activity detection in accordance with Article 23; article-Art23-Para2 is the narrow paragraph that defines that prompt-detection mechanism and its capabilities."
    },
    {
      "edge_id": "article-Art23-Para2__article-Art12-Para2__references",
      "from_article": 23,
      "from_paragraph": "2",
      "to_article": 12,
      "to_paragraph": "2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art23-Para2 expressly includes logs collected under Article 12 among its detection inputs, and article-Art12-Para2 is the narrow target specifying the events, retention, protection, and handling requirements for those logs."
    },
    {
      "edge_id": "article-Art23-Para6__article-Art23-Para5__qualifies",
      "from_article": 23,
      "from_paragraph": "6",
      "to_article": 23,
      "to_paragraph": "5",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "article-Art23-Para6 expressly operates for the purposes of article-Art23-Para5 and qualifies its four trigger criteria by adding the criticality of the affected services as a required consideration."
    },
    {
      "edge_id": "article-Art24-Para1__article-Art25-Para1__references",
      "from_article": 24,
      "from_paragraph": "1",
      "to_article": 25,
      "to_paragraph": "1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art24-Para1 expressly places testing and review within Article 25; article-Art25-Para1 is the narrow anchor that subjects ICT business continuity plan testing to the BIA and ICT risk assessment."
    },
    {
      "edge_id": "article-Art24-Para1__article-Art26-Para1__references",
      "from_article": 24,
      "from_paragraph": "1",
      "to_article": 26,
      "to_paragraph": "1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art24-Para1 expressly places development, testing, and review of ICT response and recovery plans under Article 26, and article-Art26-Para1 is the narrow anchor defining those plans' required content and recovery objectives."
    },
    {
      "edge_id": "article-Art24-Para1__article-Art26-Para2__references",
      "from_article": 24,
      "from_paragraph": "1",
      "to_article": 26,
      "to_paragraph": "2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art24-Para1 expressly requires business-continuity alignment to potential failure scenarios including those in article-Art26-Para2, the narrow paragraph containing the mandatory response-and-recovery scenario set."
    },
    {
      "edge_id": "article-Art24-Para2__article-Art24-Para1__qualifies",
      "from_article": 24,
      "from_paragraph": "2",
      "to_article": 24,
      "to_paragraph": "1",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "article-Art24-Para2 expressly adds central-counterparty-specific recovery times, interdependencies, and secondary-site arrangements to the general ICT business continuity policy requirements in article-Art24-Para1."
    },
    {
      "edge_id": "article-Art24-Para3__article-Art24-Para1__qualifies",
      "from_article": 24,
      "from_paragraph": "3",
      "to_article": 24,
      "to_paragraph": "1",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "article-Art24-Para3 expressly supplements article-Art24-Para1 for central securities depositories by adding infrastructure interdependencies and a two-hour recovery-time objective."
    },
    {
      "edge_id": "article-Art24-Para4__article-Art24-Para1__qualifies",
      "from_article": 24,
      "from_paragraph": "4",
      "to_article": 24,
      "to_paragraph": "1",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "article-Art24-Para4 expressly supplements article-Art24-Para1 for trading venues by adding a near-two-hour resumption target and a near-zero maximum data-loss requirement."
    },
    {
      "edge_id": "article-Art25-Para1__article-Art3-Para1__references",
      "from_article": 25,
      "from_paragraph": "1",
      "to_article": 3,
      "to_paragraph": "1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art25-Para1 expressly requires continuity-plan testing to take account of the ICT risk assessment in article-Art3-Para1, point (b), which defines the assessment procedure and methodology."
    },
    {
      "edge_id": "article-Art25-Para2__article-Art25-Para1__depends_on",
      "from_article": 25,
      "from_paragraph": "2",
      "to_article": 25,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art25-Para2 repeatedly identifies its subject as the testing of ICT business continuity plans referred to in article-Art25-Para1, so its scenario, switchover, and response requirements depend on that testing obligation."
    },
    {
      "edge_id": "article-Art25-Para2__article-Art26-Para2__references",
      "from_article": 25,
      "from_paragraph": "2",
      "to_article": 26,
      "to_paragraph": "2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art25-Para2 expressly requires testing staff, systems, and services against scenarios taken into account under article-Art26-Para2, the paragraph listing response-and-recovery scenarios."
    },
    {
      "edge_id": "article-Art25-Para3__article-Art25-Para1__depends_on",
      "from_article": 25,
      "from_paragraph": "3",
      "to_article": 25,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art25-Para3 expressly identifies the plans whose testing must involve clearing members, external providers, and relevant infrastructure institutions as the plans referred to in article-Art25-Para1."
    },
    {
      "edge_id": "article-Art25-Para3__article-Art25-Para2__qualifies",
      "from_article": 25,
      "from_paragraph": "3",
      "to_article": 25,
      "to_paragraph": "2",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "article-Art25-Para3 expressly adds central-counterparty participant requirements to the general continuity-plan testing requirements in article-Art25-Para2."
    },
    {
      "edge_id": "article-Art25-Para4__article-Art25-Para1__depends_on",
      "from_article": 25,
      "from_paragraph": "4",
      "to_article": 25,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art25-Para4 expressly identifies the continuity plans whose testing must involve users, utilities, service providers, depositories, and market infrastructures as the plans referred to in article-Art25-Para1."
    },
    {
      "edge_id": "article-Art25-Para4__article-Art25-Para2__qualifies",
      "from_article": 25,
      "from_paragraph": "4",
      "to_article": 25,
      "to_paragraph": "2",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "article-Art25-Para4 expressly adds central-securities-depository participant requirements to the general continuity-plan testing requirements in article-Art25-Para2."
    },
    {
      "edge_id": "article-Art25-Para5__article-Art25-Para1__depends_on",
      "from_article": 25,
      "from_paragraph": "5",
      "to_article": 25,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art25-Para5 makes documentation, analysis, remediation, and management-body reporting conditional on results of the testing defined in article-Art25-Para1."
    },
    {
      "edge_id": "article-Art26-Para2__article-Art26-Para1__depends_on",
      "from_article": 26,
      "from_paragraph": "2",
      "to_article": 26,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art26-Para2 expressly applies its mandatory disruption scenarios to the ICT response and recovery plans referred to in article-Art26-Para1."
    },
    {
      "edge_id": "article-Art26-Para3__article-Art26-Para1__qualifies",
      "from_article": 26,
      "from_paragraph": "3",
      "to_article": 26,
      "to_paragraph": "1",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "article-Art26-Para3 qualifies the plans defined in article-Art26-Para1 by requiring alternative options where primary recovery measures may be infeasible in the short term because of cost, risk, logistics, or unforeseen circumstances."
    },
    {
      "edge_id": "article-Art26-Para4__article-Art26-Para1__depends_on",
      "from_article": 26,
      "from_paragraph": "4",
      "to_article": 26,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art26-Para4 expressly makes third-party-provider continuity measures part of the ICT response and recovery plans referred to in article-Art26-Para1."
    },
    {
      "edge_id": "article-Art27-Para2__article-Art27-Para1__depends_on",
      "from_article": 27,
      "from_paragraph": "2",
      "to_article": 27,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art27-Para2 defines the mandatory information for the report referred to in article-Art27-Para1 and therefore depends on that paragraph's report and electronic-format obligation."
    },
    {
      "edge_id": "article-Art28-Para2__article-Art28-Para1__depends_on",
      "from_article": 28,
      "from_paragraph": "2",
      "to_article": 28,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art28-Para2 expressly applies its management-body duties to the financial entities identified in article-Art28-Para1 and to the simplified framework established there."
    },
    {
      "edge_id": "article-Art28-Para2__article-Art30-Para1__references",
      "from_article": 28,
      "from_paragraph": "2",
      "to_article": 30,
      "to_paragraph": "1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art28-Para2 expressly requires management-body approval and review of the information-asset classification in article-Art30-Para1, which is the narrow paragraph imposing identification and classification duties."
    },
    {
      "edge_id": "article-Art28-Para3__article-Art28-Para1__depends_on",
      "from_article": 28,
      "from_paragraph": "3",
      "to_article": 28,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art28-Para3 expressly applies its outsourcing option and retained-responsibility rule to the financial entities referred to in article-Art28-Para1."
    },
    {
      "edge_id": "article-Art28-Para4__article-Art28-Para1__depends_on",
      "from_article": 28,
      "from_paragraph": "4",
      "to_article": 28,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art28-Para4 expressly applies segregation and independence requirements for control and internal-audit functions to the financial entities referred to in article-Art28-Para1."
    },
    {
      "edge_id": "article-Art28-Para5__article-Art28-Para1__depends_on",
      "from_article": 28,
      "from_paragraph": "5",
      "to_article": 28,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art28-Para5 expressly subjects the simplified ICT risk management framework of the financial entities identified in article-Art28-Para1 to independent, risk-commensurate internal audit."
    },
    {
      "edge_id": "article-Art28-Para6__article-Art28-Para1__depends_on",
      "from_article": 28,
      "from_paragraph": "6",
      "to_article": 28,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art28-Para6 expressly assigns remediation of critical audit findings to the financial entities referred to in article-Art28-Para1, whose simplified governance framework supplies the rule's scope."
    },
    {
      "edge_id": "article-Art28-Para6__article-Art28-Para5__depends_on",
      "from_article": 28,
      "from_paragraph": "6",
      "to_article": 28,
      "to_paragraph": "5",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art28-Para6 expressly bases timely verification and remediation of critical findings on the audit required by article-Art28-Para5."
    },
    {
      "edge_id": "article-Art29-Para2__article-Art29-Para1__depends_on",
      "from_article": 29,
      "from_paragraph": "2",
      "to_article": 29,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art29-Para1 because its ICT security measures must be established from the information security policy defined in paragraph 1."
    },
    {
      "edge_id": "article-Art29-Para2__article-Art30-Para1__depends_on",
      "from_article": 29,
      "from_paragraph": "2",
      "to_article": 30,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art30-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches that paragraph’s identification, classification and documentation of critical functions, supporting information and ICT assets, and their interdependencies."
    },
    {
      "edge_id": "article-Art29-Para2__article-Art30-Para2__depends_on",
      "from_article": 29,
      "from_paragraph": "2",
      "to_article": 30,
      "to_paragraph": "2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art30-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches that paragraph’s identification of critical or important functions supported by ICT third-party service providers."
    },
    {
      "edge_id": "article-Art29-Para2__article-Art31-Para1__depends_on",
      "from_article": 29,
      "from_paragraph": "2",
      "to_article": 31,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art31-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches that paragraph’s risk-tolerance, risk-assessment, mitigation, effectiveness-monitoring and change-, test- and incident-driven assessment measures."
    },
    {
      "edge_id": "article-Art29-Para2__article-Art31-Para2__depends_on",
      "from_article": 29,
      "from_paragraph": "2",
      "to_article": 31,
      "to_paragraph": "2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art31-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the periodic documented ICT risk assessment calibrated to the entity’s ICT risk profile."
    },
    {
      "edge_id": "article-Art29-Para2__article-Art31-Para3__depends_on",
      "from_article": 29,
      "from_paragraph": "2",
      "to_article": 31,
      "to_paragraph": "3",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art31-Para3 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches continuous monitoring of relevant threats and vulnerabilities and regular review of risk scenarios affecting critical or important functions."
    },
    {
      "edge_id": "article-Art29-Para2__article-Art31-Para4__depends_on",
      "from_article": 29,
      "from_paragraph": "2",
      "to_article": 31,
      "to_paragraph": "4",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art31-Para4 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the alert thresholds and criteria that trigger and initiate ICT-related incident response processes."
    },
    {
      "edge_id": "article-Art29-Para2__article-Art32-Para1__depends_on",
      "from_article": 29,
      "from_paragraph": "2",
      "to_article": 32,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art32-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches threat- and classification-based physical security measures for ICT assets and accessible information assets."
    },
    {
      "edge_id": "article-Art29-Para2__article-Art32-Para2__depends_on",
      "from_article": 29,
      "from_paragraph": "2",
      "to_article": 32,
      "to_paragraph": "2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art32-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches protection of premises and applicable data centres against unauthorised access, attacks, accidents and environmental hazards."
    },
    {
      "edge_id": "article-Art29-Para2__article-Art32-Para3__depends_on",
      "from_article": 29,
      "from_paragraph": "2",
      "to_article": 32,
      "to_paragraph": "3",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art32-Para3 because its express incorporation of all ICT security requirements in Articles 30 to 38 reaches the proportionality constraint linking environmental protection to premises importance and the criticality of operations or ICT systems located there."
    },
    {
      "edge_id": "article-Art29-Para2__article-Art33-Para1__depends_on",
      "from_article": 29,
      "from_paragraph": "2",
      "to_article": 33,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art33-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the logical and physical access-control procedure, including least-privilege, accountability, account-management, authentication and review controls."
    },
    {
      "edge_id": "article-Art29-Para2__article-Art34-Para1__depends_on",
      "from_article": 29,
      "from_paragraph": "2",
      "to_article": 34,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art34-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches ICT-operations controls for asset lifecycle, capacity, vulnerabilities and patches, logging, anomalous activity, cyber threats and information leakage."
    },
    {
      "edge_id": "article-Art29-Para2__article-Art35-Para1__depends_on",
      "from_article": 29,
      "from_paragraph": "2",
      "to_article": 35,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art35-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches network and data safeguards covering protection in use, transit and at rest, secure transfer, deletion and disposal, and teleworking and endpoint-device risks."
    },
    {
      "edge_id": "article-Art29-Para2__article-Art36-Para1__depends_on",
      "from_article": 29,
      "from_paragraph": "2",
      "to_article": 36,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art36-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the testing plan that validates their effectiveness and considers identified threats and vulnerabilities."
    },
    {
      "edge_id": "article-Art29-Para2__article-Art36-Para2__depends_on",
      "from_article": 29,
      "from_paragraph": "2",
      "to_article": 36,
      "to_paragraph": "2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art36-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches review, assessment and testing of those measures with regard to the overall ICT-asset risk profile."
    },
    {
      "edge_id": "article-Art29-Para2__article-Art36-Para3__depends_on",
      "from_article": 29,
      "from_paragraph": "2",
      "to_article": 36,
      "to_paragraph": "3",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art36-Para3 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches monitoring and evaluation of security-test results and prompt updating of measures for systems supporting critical or important functions."
    },
    {
      "edge_id": "article-Art29-Para2__article-Art37-Para1__depends_on",
      "from_article": 29,
      "from_paragraph": "2",
      "to_article": 37,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art37-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the risk-based procedure and security controls for ICT-system acquisition, development, maintenance, pre-use testing and production changes."
    },
    {
      "edge_id": "article-Art29-Para2__article-Art38-Para1__depends_on",
      "from_article": 29,
      "from_paragraph": "2",
      "to_article": 38,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art38-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the documented ICT project-management procedure, assigned implementation roles and coverage of every project stage from initiation to closure."
    },
    {
      "edge_id": "article-Art29-Para2__article-Art38-Para2__depends_on",
      "from_article": 29,
      "from_paragraph": "2",
      "to_article": 38,
      "to_paragraph": "2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art38-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the controlled ICT change-management procedure covering recording, testing, assessment, approval, implementation and verification of changes."
    },
    {
      "edge_id": "article-Art30-Para2__article-Art30-Para1__references",
      "from_article": 30,
      "from_paragraph": "2",
      "to_article": 30,
      "to_paragraph": "1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art30-Para2 references article-Art30-Para1 to inherit the paragraph-1 entity scope before adding identification of critical or important functions supported by ICT third-party service providers."
    },
    {
      "edge_id": "article-Art31-Para2__article-Art31-Para1__depends_on",
      "from_article": 31,
      "from_paragraph": "2",
      "to_article": 31,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art31-Para2 depends on article-Art31-Para1 because the periodic documented assessment in paragraph 2 is the ICT risk assessment established as part of the paragraph-1 simplified risk framework."
    },
    {
      "edge_id": "article-Art31-Para3__article-Art31-Para1__references",
      "from_article": 31,
      "from_paragraph": "3",
      "to_article": 31,
      "to_paragraph": "1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art31-Para3 references article-Art31-Para1 to carry its financial-entity scope into continuous threat and vulnerability monitoring for critical functions and supporting assets."
    },
    {
      "edge_id": "article-Art31-Para4__article-Art31-Para1__references",
      "from_article": 31,
      "from_paragraph": "4",
      "to_article": 31,
      "to_paragraph": "1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art31-Para4 references article-Art31-Para1 to apply alert-threshold and incident-response-trigger duties to the financial entities defined in paragraph 1."
    },
    {
      "edge_id": "article-Art32-Para1__article-Art30-Para1__depends_on",
      "from_article": 32,
      "from_paragraph": "1",
      "to_article": 30,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art32-Para1 depends on article-Art30-Para1 because physical security measures must be designed in accordance with the information-asset and ICT-asset classification established there."
    },
    {
      "edge_id": "article-Art32-Para2__article-Art32-Para1__depends_on",
      "from_article": 32,
      "from_paragraph": "2",
      "to_article": 32,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art32-Para2 depends on article-Art32-Para1 because it specifies the premises, data centres, threats and hazards against which the paragraph-1 physical security measures must protect."
    },
    {
      "edge_id": "article-Art32-Para3__article-Art32-Para2__qualifies",
      "from_article": 32,
      "from_paragraph": "3",
      "to_article": 32,
      "to_paragraph": "2",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "article-Art32-Para3 qualifies article-Art32-Para2 by making its environmental-threat protection proportionate to premises importance and the criticality of operations or ICT systems located there."
    },
    {
      "edge_id": "article-Art33-Para1__article-Art30-Para1__depends_on",
      "from_article": 33,
      "from_paragraph": "1",
      "to_article": 30,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art33-Para1 depends on article-Art30-Para1 because authentication strength under the access-control procedure must be commensurate with the asset classification established in that paragraph."
    },
    {
      "edge_id": "article-Art33-Para1__article-Art34-Para1__references",
      "from_article": 33,
      "from_paragraph": "1",
      "to_article": 34,
      "to_paragraph": "1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art33-Para1 references article-Art34-Para1 because privileged, emergency and administrator access assigned under Article 33 must be logged under the Article 34 first-paragraph point-(f) logging control."
    },
    {
      "edge_id": "article-Art34-Para1__article-Art30-Para1__depends_on",
      "from_article": 34,
      "from_paragraph": "1",
      "to_article": 30,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art34-Para1 depends on article-Art30-Para1 because the required vulnerability scanning and assessments are calibrated to the asset classification defined in Article 30(1)."
    },
    {
      "edge_id": "article-Art35-Para1__article-Art30-Para1__depends_on",
      "from_article": 35,
      "from_paragraph": "1",
      "to_article": 30,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art35-Para1 depends on article-Art30-Para1 because its data, system and network safeguards must be selected while taking the Article 30(1) asset classification into account."
    },
    {
      "edge_id": "article-Art36-Para1__article-Art31-Para3__depends_on",
      "from_article": 36,
      "from_paragraph": "1",
      "to_article": 31,
      "to_paragraph": "3",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art36-Para1 depends on article-Art31-Para3 because its testing plan must consider the threats and vulnerabilities continuously identified under the simplified ICT risk management framework."
    },
    {
      "edge_id": "article-Art36-Para1__article-Art33-Para1__depends_on",
      "from_article": 36,
      "from_paragraph": "1",
      "to_article": 33,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art36-Para1 depends on article-Art33-Para1 because the security testing plan expressly validates the effectiveness of the access-control measures required by that paragraph."
    },
    {
      "edge_id": "article-Art36-Para1__article-Art34-Para1__depends_on",
      "from_article": 36,
      "from_paragraph": "1",
      "to_article": 34,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art36-Para1 depends on article-Art34-Para1 because the security testing plan expressly validates the effectiveness of the ICT-operations security measures required by that paragraph."
    },
    {
      "edge_id": "article-Art36-Para1__article-Art35-Para1__depends_on",
      "from_article": 36,
      "from_paragraph": "1",
      "to_article": 35,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art36-Para1 depends on article-Art35-Para1 because the security testing plan expressly validates the effectiveness of the data, system and network safeguards required by that paragraph."
    },
    {
      "edge_id": "article-Art36-Para1__article-Art37-Para1__depends_on",
      "from_article": 36,
      "from_paragraph": "1",
      "to_article": 37,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art36-Para1 depends on article-Art37-Para1 because the security testing plan expressly validates the effectiveness of the acquisition, development and maintenance controls required by that paragraph."
    },
    {
      "edge_id": "article-Art36-Para1__article-Art38-Para1__depends_on",
      "from_article": 36,
      "from_paragraph": "1",
      "to_article": 38,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art36-Para1 depends on article-Art38-Para1 because the security testing plan expressly validates the effectiveness of the ICT project-management procedure required by that paragraph."
    },
    {
      "edge_id": "article-Art36-Para1__article-Art38-Para2__depends_on",
      "from_article": 36,
      "from_paragraph": "1",
      "to_article": 38,
      "to_paragraph": "2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art36-Para1 depends on article-Art38-Para2 because the security testing plan expressly validates the effectiveness of the ICT change-management procedure required by that paragraph."
    },
    {
      "edge_id": "article-Art36-Para2__article-Art36-Para1__depends_on",
      "from_article": 36,
      "from_paragraph": "2",
      "to_article": 36,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art36-Para2 depends on article-Art36-Para1 because its review, assessment and testing of ICT security measures operationalise the testing plan and entity scope established in paragraph 1."
    },
    {
      "edge_id": "article-Art36-Para3__article-Art36-Para1__references",
      "from_article": 36,
      "from_paragraph": "3",
      "to_article": 36,
      "to_paragraph": "1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art36-Para3 references article-Art36-Para1 to inherit the financial-entity scope and testing-plan context for monitoring and evaluating security-test results."
    },
    {
      "edge_id": "article-Art36-Para3__article-Art36-Para2__depends_on",
      "from_article": 36,
      "from_paragraph": "3",
      "to_article": 36,
      "to_paragraph": "2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art36-Para3 depends on article-Art36-Para2 because the results that paragraph 3 requires entities to evaluate arise from the review, assessment and testing mandated in paragraph 2."
    },
    {
      "edge_id": "article-Art38-Para2__article-Art38-Para1__references",
      "from_article": 38,
      "from_paragraph": "2",
      "to_article": 38,
      "to_paragraph": "1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art38-Para2 references article-Art38-Para1 to inherit its financial-entity scope before imposing the separate controlled ICT change-management procedure."
    },
    {
      "edge_id": "article-Art39-Para2__article-Art39-Para1__depends_on",
      "from_article": 39,
      "from_paragraph": "2",
      "to_article": 39,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art39-Para2 depends on article-Art39-Para1 because it prescribes the approval, resources, recovery, backup and communication content of the business continuity plans developed under paragraph 1."
    },
    {
      "edge_id": "article-Art4-Para2__article-Art4-Para1__depends_on",
      "from_article": 4,
      "from_paragraph": "2",
      "to_article": 4,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art4-Para2 defines the mandatory contents of the ICT asset-management policy that article-Art4-Para1 requires financial entities to establish."
    },
    {
      "edge_id": "article-Art40-Para1__article-Art39-Para1__depends_on",
      "from_article": 40,
      "from_paragraph": "1",
      "to_article": 39,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art40-Para1 depends on article-Art39-Para1 because the annual or major-change test covers the business continuity plans and severe-disruption scenarios established in Article 39(1)."
    },
    {
      "edge_id": "article-Art40-Para1__article-Art39-Para2__depends_on",
      "from_article": 40,
      "from_paragraph": "1",
      "to_article": 39,
      "to_paragraph": "2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art40-Para1 depends on article-Art39-Para2 because its express requirement to test the Article 39 business continuity plans at least annually for backup and restore procedures reaches the paragraph that specifies backup procedures, restoration and recovery measures, recovery levels and timeframes."
    },
    {
      "edge_id": "article-Art40-Para2__article-Art40-Para1__depends_on",
      "from_article": 40,
      "from_paragraph": "2",
      "to_article": 40,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art40-Para2 depends on article-Art40-Para1 because it defines what the paragraph-1 testing must demonstrate about business viability, operational re-establishment and plan deficiencies."
    },
    {
      "edge_id": "article-Art40-Para3__article-Art40-Para1__references",
      "from_article": 40,
      "from_paragraph": "3",
      "to_article": 40,
      "to_paragraph": "1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art40-Para3 references article-Art40-Para1 to inherit the financial-entity scope and the business-continuity-plan testing whose results must be documented."
    },
    {
      "edge_id": "article-Art40-Para3__article-Art40-Para2__depends_on",
      "from_article": 40,
      "from_paragraph": "3",
      "to_article": 40,
      "to_paragraph": "2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art40-Para3 depends on article-Art40-Para2 because the deficiencies to be analysed, addressed and reported are those the paragraph-2 test is required to identify."
    },
    {
      "edge_id": "article-Art41-Para2__article-Art41-Para1__depends_on",
      "from_article": 41,
      "from_paragraph": "2",
      "to_article": 41,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art41-Para2 depends on article-Art41-Para1 because it specifies the mandatory content of the searchable electronic simplified-framework review report introduced in paragraph 1."
    },
    {
      "edge_id": "article-Art5-Para2__article-Art5-Para1__depends_on",
      "from_article": 5,
      "from_paragraph": "2",
      "to_article": 5,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art5-Para2 supplies the criticality-assessment criteria for the ICT asset-management procedure created by article-Art5-Para1."
    },
    {
      "edge_id": "article-Art6-Para2__article-Art6-Para1__depends_on",
      "from_article": 6,
      "from_paragraph": "2",
      "to_article": 6,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art6-Para2 prescribes the design and rules of the encryption and cryptographic-controls policy mandated by article-Art6-Para1."
    },
    {
      "edge_id": "article-Art6-Para2__article-Art7-Para1__references",
      "from_article": 6,
      "from_paragraph": "2",
      "to_article": 7,
      "to_paragraph": "1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art6-Para2 refers cryptographic-key management to Article 7, and article-Art7-Para1 is the narrow paragraph specifying whole-lifecycle key management."
    },
    {
      "edge_id": "article-Art6-Para2__article-Art7-Para2__references",
      "from_article": 6,
      "from_paragraph": "2",
      "to_article": 7,
      "to_paragraph": "2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art6-Para2's express Article 7 reference includes protection of cryptographic keys, which article-Art7-Para2 specifically regulates throughout the key lifecycle."
    },
    {
      "edge_id": "article-Art6-Para3__article-Art6-Para1__depends_on",
      "from_article": 6,
      "from_paragraph": "3",
      "to_article": 6,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art6-Para3 adds technique-selection and mitigation criteria to the cryptographic-controls policy established by article-Art6-Para1."
    },
    {
      "edge_id": "article-Art6-Para4__article-Art10-Para2__references",
      "from_article": 6,
      "from_paragraph": "4",
      "to_article": 10,
      "to_paragraph": "2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art6-Para4 expressly invokes article-Art10-Para2 point (a) when requiring awareness-driven updates that keep cryptographic technology resilient to cyber threats."
    },
    {
      "edge_id": "article-Art6-Para4__article-Art6-Para1__depends_on",
      "from_article": 6,
      "from_paragraph": "4",
      "to_article": 6,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art6-Para4 requires technology-update provisions within the encryption and cryptographic-controls policy mandated by article-Art6-Para1."
    },
    {
      "edge_id": "article-Art6-Para5__article-Art6-Para1__depends_on",
      "from_article": 6,
      "from_paragraph": "5",
      "to_article": 6,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art6-Para5 places recording and explanation duties inside the cryptographic-controls policy first required by article-Art6-Para1."
    },
    {
      "edge_id": "article-Art6-Para5__article-Art6-Para3__depends_on",
      "from_article": 6,
      "from_paragraph": "5",
      "to_article": 6,
      "to_paragraph": "3",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art6-Para5 expressly requires records for mitigation and monitoring measures adopted under article-Art6-Para3 when leading practices or reliable techniques cannot be followed."
    },
    {
      "edge_id": "article-Art6-Para5__article-Art6-Para4__depends_on",
      "from_article": 6,
      "from_paragraph": "5",
      "to_article": 6,
      "to_paragraph": "4",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art6-Para5 expressly requires a reasoned record of the mitigation and monitoring measures adopted under article-Art6-Para4 when cryptographic technology cannot be updated."
    },
    {
      "edge_id": "article-Art7-Para1__article-Art6-Para2__depends_on",
      "from_article": 7,
      "from_paragraph": "1",
      "to_article": 6,
      "to_paragraph": "2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art7-Para1 expressly makes its whole-lifecycle key requirements part of the cryptographic-key management policy specified in article-Art6-Para2 point (d)."
    },
    {
      "edge_id": "article-Art8-Para2__article-Art13-Para1__references",
      "from_article": 8,
      "from_paragraph": "2",
      "to_article": 13,
      "to_paragraph": "1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art8-Para2 expressly applies the segregation requirement in article-Art13-Para1 point (a) to all components of separated production and non-production environments."
    },
    {
      "edge_id": "article-Art8-Para2__article-Art16-Para6__references",
      "from_article": 8,
      "from_paragraph": "2",
      "to_article": 16,
      "to_paragraph": "6",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art8-Para2 expressly uses article-Art16-Para6 as the approval and limited-duration standard for testing in production environments."
    },
    {
      "edge_id": "article-Art8-Para2__article-Art8-Para1__depends_on",
      "from_article": 8,
      "from_paragraph": "2",
      "to_article": 8,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art8-Para2 prescribes the required operational, monitoring and error-handling contents of the ICT-operations policies created by article-Art8-Para1."
    },
    {
      "edge_id": "article-Art9-Para2__article-Art9-Para1__depends_on",
      "from_article": 9,
      "from_paragraph": "2",
      "to_article": 9,
      "to_paragraph": "1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art9-Para2 adds system-specific proportional measures to the capacity and performance management procedures required by article-Art9-Para1."
    }
  ],
  "annex_hierarchy": [],
  "annex_to_article": [],
  "case_law": [],
  "canonical_edges": [
    {
      "source": "article-Art10-Para2",
      "target": "article-Art10-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art10-Para2 enumerates the scanning, third-party, remediation and recording controls for the vulnerability-management procedures mandated by article-Art10-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art10-Para2__article-Art10-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art10-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art10-Para1"
    },
    {
      "source": "article-Art10-Para4",
      "target": "article-Art10-Para3",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art10-Para4 sets the evaluation, emergency, testing, deployment and deadline requirements for the patch-management procedures established by article-Art10-Para3.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art10-Para4__article-Art10-Para3__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art10-Para4",
      "target_canonical_ref": "celex:32024R1774/article-Art10-Para3"
    },
    {
      "source": "article-Art10-Para4",
      "target": "article-Art8-Para2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art10-Para4 expressly refers patch and update testing and deployment to the production and non-production testing controls in article-Art8-Para2 points (b)(v) to (vii).",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art10-Para4__article-Art8-Para2__references",
      "source_canonical_ref": "celex:32024R1774/article-Art10-Para4",
      "target_canonical_ref": "celex:32024R1774/article-Art8-Para2"
    },
    {
      "source": "article-Art11-Para2",
      "target": "article-Art11-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art11-Para2 expressly takes the data and system security procedure established by article-Art11-Para1 as the procedure whose mandatory security elements it enumerates.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art11-Para2__article-Art11-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art11-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art11-Para1"
    },
    {
      "source": "article-Art11-Para2",
      "target": "article-Art21-Para1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art11-Para2 expressly imports the access restrictions laid down in article-Art21-Para1 as an element supporting the protection requirements attached to each data-classification level.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art11-Para2__article-Art21-Para1__references",
      "source_canonical_ref": "celex:32024R1774/article-Art11-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art21-Para1"
    },
    {
      "source": "article-Art11-Para2",
      "target": "article-Art3-Para1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art11-Para2 conditions use of removable data-storage devices on residual ICT risk remaining within the risk-tolerance level established in article-Art3-Para1, first subparagraph, point (a).",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art11-Para2__article-Art3-Para1__references",
      "source_canonical_ref": "celex:32024R1774/article-Art11-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art3-Para1"
    },
    {
      "source": "article-Art12-Para2",
      "target": "article-Art12-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art12-Para2 expressly specifies the mandatory contents of the logging procedures, protocols and tools that article-Art12-Para1 requires financial entities to establish.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art12-Para2__article-Art12-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art12-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art12-Para1"
    },
    {
      "source": "article-Art12-Para2",
      "target": "article-Art21-Para1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art12-Para2 expressly requires logs for logical and physical access-control events governed by article-Art21-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art12-Para2__article-Art21-Para1__references",
      "source_canonical_ref": "celex:32024R1774/article-Art12-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art21-Para1"
    },
    {
      "source": "article-Art13-Para1",
      "target": "article-Art6-Para2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art13-Para1 expressly requires network-connection encryption to take account of the encryption of network connections governed by article-Art6-Para2.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art13-Para1__article-Art6-Para2__references",
      "source_canonical_ref": "celex:32024R1774/article-Art13-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art6-Para2"
    },
    {
      "source": "article-Art14-Para2",
      "target": "article-Art14-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art14-Para2 expressly requires the information-in-transit policies and controls established by article-Art14-Para1 to be designed from the approved data classification and ICT risk assessment.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art14-Para2__article-Art14-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art14-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art14-Para1"
    },
    {
      "source": "article-Art15-Para2",
      "target": "article-Art15-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art15-Para2 expressly defines the acquisition, maintenance and development projects that must be covered by the ICT project-management policy required in article-Art15-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art15-Para2__article-Art15-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art15-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art15-Para1"
    },
    {
      "source": "article-Art15-Para3",
      "target": "article-Art15-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art15-Para3 expressly enumerates the governance, planning, risk, change and testing contents of the ICT project-management policy required by article-Art15-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art15-Para3__article-Art15-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art15-Para3",
      "target_canonical_ref": "celex:32024R1774/article-Art15-Para1"
    },
    {
      "source": "article-Art15-Para4",
      "target": "article-Art15-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art15-Para4 expressly adds business-area information and expertise as a secure-implementation requirement of the ICT project-management policy established in article-Art15-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art15-Para4__article-Art15-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art15-Para4",
      "target_canonical_ref": "celex:32024R1774/article-Art15-Para1"
    },
    {
      "source": "article-Art15-Para5",
      "target": "article-Art15-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art15-Para5 expressly makes reporting on critical or important ICT projects and their risks a requirement of the project-management policy established in article-Art15-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art15-Para5__article-Art15-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art15-Para5",
      "target_canonical_ref": "celex:32024R1774/article-Art15-Para1"
    },
    {
      "source": "article-Art15-Para5",
      "target": "article-Art15-Para3",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art15-Para5 expressly bases management-body reporting on the ICT project risk assessment required by article-Art15-Para3, point (d).",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art15-Para5__article-Art15-Para3__references",
      "source_canonical_ref": "celex:32024R1774/article-Art15-Para5",
      "target_canonical_ref": "celex:32024R1774/article-Art15-Para3"
    },
    {
      "source": "article-Art16-Para2",
      "target": "article-Art8-Para2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art16-Para2 expressly requires pre-use and post-maintenance ICT-system testing to follow the production-separation and testing controls in article-Art8-Para2, point (b)(v) to (vii).",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art16-Para2__article-Art8-Para2__references",
      "source_canonical_ref": "celex:32024R1774/article-Art16-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art8-Para2"
    },
    {
      "source": "article-Art16-Para3",
      "target": "article-Art16-Para2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para3 expressly makes source-code review and the resulting vulnerability action plan part of the acquisition, development and maintenance testing procedure established in article-Art16-Para2.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art16-Para3__article-Art16-Para2__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art16-Para3",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
    },
    {
      "source": "article-Art16-Para3",
      "target": "article-Art8-Para2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art16-Para3 expressly subjects security testing for internet-exposed systems and applications to the environment-separation and production-testing requirements in article-Art8-Para2, point (b)(v) to (vii).",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art16-Para3__article-Art8-Para2__references",
      "source_canonical_ref": "celex:32024R1774/article-Art16-Para3",
      "target_canonical_ref": "celex:32024R1774/article-Art8-Para2"
    },
    {
      "source": "article-Art16-Para4",
      "target": "article-Art16-Para2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para4 expressly adds integration-phase security testing of software packages to the testing procedure established in article-Art16-Para2.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art16-Para4__article-Art16-Para2__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art16-Para4",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
    },
    {
      "source": "article-Art16-Para4",
      "target": "article-Art8-Para2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art16-Para4 expressly subjects software-package security testing to the environment-separation and production-testing requirements in article-Art8-Para2, point (b)(v) to (vii).",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art16-Para4__article-Art8-Para2__references",
      "source_canonical_ref": "celex:32024R1774/article-Art16-Para4",
      "target_canonical_ref": "celex:32024R1774/article-Art8-Para2"
    },
    {
      "source": "article-Art16-Para5",
      "target": "article-Art16-Para2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para5 expressly makes anonymisation, pseudonymisation or randomisation of production data and protection of non-production data part of the testing procedure established in article-Art16-Para2.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art16-Para5__article-Art16-Para2__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art16-Para5",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
    },
    {
      "source": "article-Art16-Para6",
      "target": "article-Art16-Para2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para6 expressly places its tightly controlled production-data testing exception within the acquisition, development and maintenance procedure established in article-Art16-Para2.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art16-Para6__article-Art16-Para2__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art16-Para6",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
    },
    {
      "source": "article-Art16-Para6",
      "target": "article-Art16-Para5",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "article-Art16-Para6 expressly derogates from article-Art16-Para5 by permitting production data for specific testing occasions only for limited periods, after approval and with reporting to the ICT risk-management function.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art16-Para6__article-Art16-Para5__qualifies",
      "source_canonical_ref": "celex:32024R1774/article-Art16-Para6",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para5"
    },
    {
      "source": "article-Art16-Para7",
      "target": "article-Art16-Para2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para7 expressly adds controls protecting source-code integrity, including code developed by ICT third-party providers, to the procedure established in article-Art16-Para2.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art16-Para7__article-Art16-Para2__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art16-Para7",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
    },
    {
      "source": "article-Art16-Para8",
      "target": "article-Art16-Para2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para8 expressly makes pre-deployment analysis and testing of proprietary, third-party and open-source software part of the procedure established in article-Art16-Para2.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art16-Para8__article-Art16-Para2__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art16-Para8",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
    },
    {
      "source": "article-Art16-Para8",
      "target": "article-Art16-Para3",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art16-Para8 expressly requires proprietary, third-party and open-source software to be analysed and tested according to the static and dynamic source-code review regime in article-Art16-Para3.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art16-Para8__article-Art16-Para3__references",
      "source_canonical_ref": "celex:32024R1774/article-Art16-Para8",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para3"
    },
    {
      "source": "article-Art16-Para9",
      "target": "article-Art16-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para9 expressly extends the acquisition, development and maintenance policy duty in article-Art16-Para1 to ICT systems developed or managed by users outside the ICT function, subject to a risk-based approach.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art16-Para9__article-Art16-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para1"
    },
    {
      "source": "article-Art16-Para9",
      "target": "article-Art16-Para2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para9 expressly extends the pre-use and post-maintenance testing and approval procedure in article-Art16-Para2 to ICT systems developed or managed outside the ICT function.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art16-Para9__article-Art16-Para2__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
    },
    {
      "source": "article-Art16-Para9",
      "target": "article-Art16-Para3",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para9 expressly extends the source-code review, vulnerability analysis and remediation regime in article-Art16-Para3 to user-developed or user-managed ICT systems.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art16-Para9__article-Art16-Para3__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para3"
    },
    {
      "source": "article-Art16-Para9",
      "target": "article-Art16-Para4",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para9 expressly extends the integration-phase software-package security testing required by article-Art16-Para4 to ICT systems developed or managed outside the ICT function.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art16-Para9__article-Art16-Para4__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para4"
    },
    {
      "source": "article-Art16-Para9",
      "target": "article-Art16-Para5",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para9 expressly extends the non-production data safeguards in article-Art16-Para5 to ICT systems developed or managed by users outside the ICT function.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art16-Para9__article-Art16-Para5__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para5"
    },
    {
      "source": "article-Art16-Para9",
      "target": "article-Art16-Para6",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para9 expressly extends the limited and approved production-data testing exception in article-Art16-Para6 to ICT systems developed or managed outside the ICT function.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art16-Para9__article-Art16-Para6__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para6"
    },
    {
      "source": "article-Art16-Para9",
      "target": "article-Art16-Para7",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para9 expressly extends the source-code integrity controls in article-Art16-Para7 to ICT systems developed or managed by users outside the ICT function.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art16-Para9__article-Art16-Para7__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para7"
    },
    {
      "source": "article-Art16-Para9",
      "target": "article-Art16-Para8",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art16-Para9 expressly extends the pre-deployment proprietary, third-party and open-source analysis required by article-Art16-Para8 to systems developed or managed outside the ICT function.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art16-Para9__article-Art16-Para8__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art16-Para9",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para8"
    },
    {
      "source": "article-Art18-Para2",
      "target": "article-Art18-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art18-Para2 expressly enumerates the access, environmental, asset-protection and clear-desk controls that the physical and environmental security policy established in article-Art18-Para1 must contain.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art18-Para2__article-Art18-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art18-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art18-Para1"
    },
    {
      "source": "article-Art18-Para2",
      "target": "article-Art21-Para1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art18-Para2 expressly imports the physical access-management controls in article-Art21-Para1, point (g), into the physical and environmental security policy.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art18-Para2__article-Art21-Para1__references",
      "source_canonical_ref": "celex:32024R1774/article-Art18-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art21-Para1"
    },
    {
      "source": "article-Art2-Para2",
      "target": "article-Art2-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art2-Para2 expressly applies its governance and content requirements to the ICT security policies established under article-Art2-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art2-Para2__article-Art2-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art2-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art2-Para1"
    },
    {
      "source": "article-Art20-Para1",
      "target": "article-Art21-Para1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art20-Para1 expressly makes unique identification and authentication the prerequisite for assigning user access rights under article-Art21-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art20-Para1__article-Art21-Para1__references",
      "source_canonical_ref": "celex:32024R1774/article-Art20-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art21-Para1"
    },
    {
      "source": "article-Art20-Para2",
      "target": "article-Art20-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art20-Para2 expressly specifies the unique-account and identity-lifecycle contents of the identity-management policies and procedures established in article-Art20-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art20-Para2__article-Art20-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art20-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art20-Para1"
    },
    {
      "source": "article-Art20-Para2",
      "target": "article-Art21-Para1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art20-Para2 expressly references article-Art21-Para1 through a without-prejudice clause that preserves the exceptional generic and shared-account regime in point (c) while imposing the one-identity-to-one-account rule.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art20-Para2__article-Art21-Para1__references",
      "source_canonical_ref": "celex:32024R1774/article-Art20-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art21-Para1"
    },
    {
      "source": "article-Art22-Para1",
      "target": "article-Art23-Para2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art22-Para1 expressly requires its incident-policy mechanisms to enable prompt anomalous-activity detection in accordance with Article 23; article-Art23-Para2 is the narrow paragraph that defines that prompt-detection mechanism and its capabilities.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art22-Para1__article-Art23-Para2__references",
      "source_canonical_ref": "celex:32024R1774/article-Art22-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art23-Para2"
    },
    {
      "source": "article-Art23-Para2",
      "target": "article-Art12-Para2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art23-Para2 expressly includes logs collected under Article 12 among its detection inputs, and article-Art12-Para2 is the narrow target specifying the events, retention, protection, and handling requirements for those logs.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art23-Para2__article-Art12-Para2__references",
      "source_canonical_ref": "celex:32024R1774/article-Art23-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art12-Para2"
    },
    {
      "source": "article-Art23-Para6",
      "target": "article-Art23-Para5",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "article-Art23-Para6 expressly operates for the purposes of article-Art23-Para5 and qualifies its four trigger criteria by adding the criticality of the affected services as a required consideration.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art23-Para6__article-Art23-Para5__qualifies",
      "source_canonical_ref": "celex:32024R1774/article-Art23-Para6",
      "target_canonical_ref": "celex:32024R1774/article-Art23-Para5"
    },
    {
      "source": "article-Art24-Para1",
      "target": "article-Art25-Para1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art24-Para1 expressly places testing and review within Article 25; article-Art25-Para1 is the narrow anchor that subjects ICT business continuity plan testing to the BIA and ICT risk assessment.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art24-Para1__article-Art25-Para1__references",
      "source_canonical_ref": "celex:32024R1774/article-Art24-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art25-Para1"
    },
    {
      "source": "article-Art24-Para1",
      "target": "article-Art26-Para1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art24-Para1 expressly places development, testing, and review of ICT response and recovery plans under Article 26, and article-Art26-Para1 is the narrow anchor defining those plans' required content and recovery objectives.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art24-Para1__article-Art26-Para1__references",
      "source_canonical_ref": "celex:32024R1774/article-Art24-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art26-Para1"
    },
    {
      "source": "article-Art24-Para1",
      "target": "article-Art26-Para2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art24-Para1 expressly requires business-continuity alignment to potential failure scenarios including those in article-Art26-Para2, the narrow paragraph containing the mandatory response-and-recovery scenario set.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art24-Para1__article-Art26-Para2__references",
      "source_canonical_ref": "celex:32024R1774/article-Art24-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art26-Para2"
    },
    {
      "source": "article-Art24-Para2",
      "target": "article-Art24-Para1",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "article-Art24-Para2 expressly adds central-counterparty-specific recovery times, interdependencies, and secondary-site arrangements to the general ICT business continuity policy requirements in article-Art24-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art24-Para2__article-Art24-Para1__qualifies",
      "source_canonical_ref": "celex:32024R1774/article-Art24-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art24-Para1"
    },
    {
      "source": "article-Art24-Para3",
      "target": "article-Art24-Para1",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "article-Art24-Para3 expressly supplements article-Art24-Para1 for central securities depositories by adding infrastructure interdependencies and a two-hour recovery-time objective.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art24-Para3__article-Art24-Para1__qualifies",
      "source_canonical_ref": "celex:32024R1774/article-Art24-Para3",
      "target_canonical_ref": "celex:32024R1774/article-Art24-Para1"
    },
    {
      "source": "article-Art24-Para4",
      "target": "article-Art24-Para1",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "article-Art24-Para4 expressly supplements article-Art24-Para1 for trading venues by adding a near-two-hour resumption target and a near-zero maximum data-loss requirement.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art24-Para4__article-Art24-Para1__qualifies",
      "source_canonical_ref": "celex:32024R1774/article-Art24-Para4",
      "target_canonical_ref": "celex:32024R1774/article-Art24-Para1"
    },
    {
      "source": "article-Art25-Para1",
      "target": "article-Art3-Para1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art25-Para1 expressly requires continuity-plan testing to take account of the ICT risk assessment in article-Art3-Para1, point (b), which defines the assessment procedure and methodology.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art25-Para1__article-Art3-Para1__references",
      "source_canonical_ref": "celex:32024R1774/article-Art25-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art3-Para1"
    },
    {
      "source": "article-Art25-Para2",
      "target": "article-Art25-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art25-Para2 repeatedly identifies its subject as the testing of ICT business continuity plans referred to in article-Art25-Para1, so its scenario, switchover, and response requirements depend on that testing obligation.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art25-Para2__article-Art25-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art25-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art25-Para1"
    },
    {
      "source": "article-Art25-Para2",
      "target": "article-Art26-Para2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art25-Para2 expressly requires testing staff, systems, and services against scenarios taken into account under article-Art26-Para2, the paragraph listing response-and-recovery scenarios.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art25-Para2__article-Art26-Para2__references",
      "source_canonical_ref": "celex:32024R1774/article-Art25-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art26-Para2"
    },
    {
      "source": "article-Art25-Para3",
      "target": "article-Art25-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art25-Para3 expressly identifies the plans whose testing must involve clearing members, external providers, and relevant infrastructure institutions as the plans referred to in article-Art25-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art25-Para3__article-Art25-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art25-Para3",
      "target_canonical_ref": "celex:32024R1774/article-Art25-Para1"
    },
    {
      "source": "article-Art25-Para3",
      "target": "article-Art25-Para2",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "article-Art25-Para3 expressly adds central-counterparty participant requirements to the general continuity-plan testing requirements in article-Art25-Para2.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art25-Para3__article-Art25-Para2__qualifies",
      "source_canonical_ref": "celex:32024R1774/article-Art25-Para3",
      "target_canonical_ref": "celex:32024R1774/article-Art25-Para2"
    },
    {
      "source": "article-Art25-Para4",
      "target": "article-Art25-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art25-Para4 expressly identifies the continuity plans whose testing must involve users, utilities, service providers, depositories, and market infrastructures as the plans referred to in article-Art25-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art25-Para4__article-Art25-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art25-Para4",
      "target_canonical_ref": "celex:32024R1774/article-Art25-Para1"
    },
    {
      "source": "article-Art25-Para4",
      "target": "article-Art25-Para2",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "article-Art25-Para4 expressly adds central-securities-depository participant requirements to the general continuity-plan testing requirements in article-Art25-Para2.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art25-Para4__article-Art25-Para2__qualifies",
      "source_canonical_ref": "celex:32024R1774/article-Art25-Para4",
      "target_canonical_ref": "celex:32024R1774/article-Art25-Para2"
    },
    {
      "source": "article-Art25-Para5",
      "target": "article-Art25-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art25-Para5 makes documentation, analysis, remediation, and management-body reporting conditional on results of the testing defined in article-Art25-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art25-Para5__article-Art25-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art25-Para5",
      "target_canonical_ref": "celex:32024R1774/article-Art25-Para1"
    },
    {
      "source": "article-Art26-Para2",
      "target": "article-Art26-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art26-Para2 expressly applies its mandatory disruption scenarios to the ICT response and recovery plans referred to in article-Art26-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art26-Para2__article-Art26-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art26-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art26-Para1"
    },
    {
      "source": "article-Art26-Para3",
      "target": "article-Art26-Para1",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "article-Art26-Para3 qualifies the plans defined in article-Art26-Para1 by requiring alternative options where primary recovery measures may be infeasible in the short term because of cost, risk, logistics, or unforeseen circumstances.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art26-Para3__article-Art26-Para1__qualifies",
      "source_canonical_ref": "celex:32024R1774/article-Art26-Para3",
      "target_canonical_ref": "celex:32024R1774/article-Art26-Para1"
    },
    {
      "source": "article-Art26-Para4",
      "target": "article-Art26-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art26-Para4 expressly makes third-party-provider continuity measures part of the ICT response and recovery plans referred to in article-Art26-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art26-Para4__article-Art26-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art26-Para4",
      "target_canonical_ref": "celex:32024R1774/article-Art26-Para1"
    },
    {
      "source": "article-Art27-Para2",
      "target": "article-Art27-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art27-Para2 defines the mandatory information for the report referred to in article-Art27-Para1 and therefore depends on that paragraph's report and electronic-format obligation.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art27-Para2__article-Art27-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art27-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art27-Para1"
    },
    {
      "source": "article-Art28-Para2",
      "target": "article-Art28-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art28-Para2 expressly applies its management-body duties to the financial entities identified in article-Art28-Para1 and to the simplified framework established there.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art28-Para2__article-Art28-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art28-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art28-Para1"
    },
    {
      "source": "article-Art28-Para2",
      "target": "article-Art30-Para1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art28-Para2 expressly requires management-body approval and review of the information-asset classification in article-Art30-Para1, which is the narrow paragraph imposing identification and classification duties.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art28-Para2__article-Art30-Para1__references",
      "source_canonical_ref": "celex:32024R1774/article-Art28-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
    },
    {
      "source": "article-Art28-Para3",
      "target": "article-Art28-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art28-Para3 expressly applies its outsourcing option and retained-responsibility rule to the financial entities referred to in article-Art28-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art28-Para3__article-Art28-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art28-Para3",
      "target_canonical_ref": "celex:32024R1774/article-Art28-Para1"
    },
    {
      "source": "article-Art28-Para4",
      "target": "article-Art28-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art28-Para4 expressly applies segregation and independence requirements for control and internal-audit functions to the financial entities referred to in article-Art28-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art28-Para4__article-Art28-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art28-Para4",
      "target_canonical_ref": "celex:32024R1774/article-Art28-Para1"
    },
    {
      "source": "article-Art28-Para5",
      "target": "article-Art28-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art28-Para5 expressly subjects the simplified ICT risk management framework of the financial entities identified in article-Art28-Para1 to independent, risk-commensurate internal audit.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art28-Para5__article-Art28-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art28-Para5",
      "target_canonical_ref": "celex:32024R1774/article-Art28-Para1"
    },
    {
      "source": "article-Art28-Para6",
      "target": "article-Art28-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art28-Para6 expressly assigns remediation of critical audit findings to the financial entities referred to in article-Art28-Para1, whose simplified governance framework supplies the rule's scope.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art28-Para6__article-Art28-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art28-Para6",
      "target_canonical_ref": "celex:32024R1774/article-Art28-Para1"
    },
    {
      "source": "article-Art28-Para6",
      "target": "article-Art28-Para5",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art28-Para6 expressly bases timely verification and remediation of critical findings on the audit required by article-Art28-Para5.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art28-Para6__article-Art28-Para5__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art28-Para6",
      "target_canonical_ref": "celex:32024R1774/article-Art28-Para5"
    },
    {
      "source": "article-Art29-Para2",
      "target": "article-Art29-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art29-Para1 because its ICT security measures must be established from the information security policy defined in paragraph 1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art29-Para2__article-Art29-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art29-Para1"
    },
    {
      "source": "article-Art29-Para2",
      "target": "article-Art30-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art30-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches that paragraph’s identification, classification and documentation of critical functions, supporting information and ICT assets, and their interdependencies.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art29-Para2__article-Art30-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
    },
    {
      "source": "article-Art29-Para2",
      "target": "article-Art30-Para2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art30-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches that paragraph’s identification of critical or important functions supported by ICT third-party service providers.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art29-Para2__article-Art30-Para2__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art30-Para2"
    },
    {
      "source": "article-Art29-Para2",
      "target": "article-Art31-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art31-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches that paragraph’s risk-tolerance, risk-assessment, mitigation, effectiveness-monitoring and change-, test- and incident-driven assessment measures.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art29-Para2__article-Art31-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art31-Para1"
    },
    {
      "source": "article-Art29-Para2",
      "target": "article-Art31-Para2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art31-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the periodic documented ICT risk assessment calibrated to the entity’s ICT risk profile.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art29-Para2__article-Art31-Para2__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art31-Para2"
    },
    {
      "source": "article-Art29-Para2",
      "target": "article-Art31-Para3",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art31-Para3 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches continuous monitoring of relevant threats and vulnerabilities and regular review of risk scenarios affecting critical or important functions.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art29-Para2__article-Art31-Para3__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art31-Para3"
    },
    {
      "source": "article-Art29-Para2",
      "target": "article-Art31-Para4",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art31-Para4 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the alert thresholds and criteria that trigger and initiate ICT-related incident response processes.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art29-Para2__article-Art31-Para4__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art31-Para4"
    },
    {
      "source": "article-Art29-Para2",
      "target": "article-Art32-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art32-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches threat- and classification-based physical security measures for ICT assets and accessible information assets.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art29-Para2__article-Art32-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art32-Para1"
    },
    {
      "source": "article-Art29-Para2",
      "target": "article-Art32-Para2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art32-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches protection of premises and applicable data centres against unauthorised access, attacks, accidents and environmental hazards.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art29-Para2__article-Art32-Para2__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art32-Para2"
    },
    {
      "source": "article-Art29-Para2",
      "target": "article-Art32-Para3",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art32-Para3 because its express incorporation of all ICT security requirements in Articles 30 to 38 reaches the proportionality constraint linking environmental protection to premises importance and the criticality of operations or ICT systems located there.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art29-Para2__article-Art32-Para3__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art32-Para3"
    },
    {
      "source": "article-Art29-Para2",
      "target": "article-Art33-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art33-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the logical and physical access-control procedure, including least-privilege, accountability, account-management, authentication and review controls.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art29-Para2__article-Art33-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art33-Para1"
    },
    {
      "source": "article-Art29-Para2",
      "target": "article-Art34-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art34-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches ICT-operations controls for asset lifecycle, capacity, vulnerabilities and patches, logging, anomalous activity, cyber threats and information leakage.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art29-Para2__article-Art34-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art34-Para1"
    },
    {
      "source": "article-Art29-Para2",
      "target": "article-Art35-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art35-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches network and data safeguards covering protection in use, transit and at rest, secure transfer, deletion and disposal, and teleworking and endpoint-device risks.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art29-Para2__article-Art35-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art35-Para1"
    },
    {
      "source": "article-Art29-Para2",
      "target": "article-Art36-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art36-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the testing plan that validates their effectiveness and considers identified threats and vulnerabilities.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art29-Para2__article-Art36-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art36-Para1"
    },
    {
      "source": "article-Art29-Para2",
      "target": "article-Art36-Para2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art36-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches review, assessment and testing of those measures with regard to the overall ICT-asset risk profile.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art29-Para2__article-Art36-Para2__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art36-Para2"
    },
    {
      "source": "article-Art29-Para2",
      "target": "article-Art36-Para3",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art36-Para3 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches monitoring and evaluation of security-test results and prompt updating of measures for systems supporting critical or important functions.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art29-Para2__article-Art36-Para3__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art36-Para3"
    },
    {
      "source": "article-Art29-Para2",
      "target": "article-Art37-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art37-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the risk-based procedure and security controls for ICT-system acquisition, development, maintenance, pre-use testing and production changes.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art29-Para2__article-Art37-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art37-Para1"
    },
    {
      "source": "article-Art29-Para2",
      "target": "article-Art38-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art38-Para1 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the documented ICT project-management procedure, assigned implementation roles and coverage of every project stage from initiation to closure.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art29-Para2__article-Art38-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art38-Para1"
    },
    {
      "source": "article-Art29-Para2",
      "target": "article-Art38-Para2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art29-Para2 depends on article-Art38-Para2 because its express incorporation of all ICT security measures in Articles 30 to 38 reaches the controlled ICT change-management procedure covering recording, testing, assessment, approval, implementation and verification of changes.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art29-Para2__article-Art38-Para2__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art29-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art38-Para2"
    },
    {
      "source": "article-Art30-Para2",
      "target": "article-Art30-Para1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art30-Para2 references article-Art30-Para1 to inherit the paragraph-1 entity scope before adding identification of critical or important functions supported by ICT third-party service providers.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art30-Para2__article-Art30-Para1__references",
      "source_canonical_ref": "celex:32024R1774/article-Art30-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
    },
    {
      "source": "article-Art31-Para2",
      "target": "article-Art31-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art31-Para2 depends on article-Art31-Para1 because the periodic documented assessment in paragraph 2 is the ICT risk assessment established as part of the paragraph-1 simplified risk framework.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art31-Para2__article-Art31-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art31-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art31-Para1"
    },
    {
      "source": "article-Art31-Para3",
      "target": "article-Art31-Para1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art31-Para3 references article-Art31-Para1 to carry its financial-entity scope into continuous threat and vulnerability monitoring for critical functions and supporting assets.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art31-Para3__article-Art31-Para1__references",
      "source_canonical_ref": "celex:32024R1774/article-Art31-Para3",
      "target_canonical_ref": "celex:32024R1774/article-Art31-Para1"
    },
    {
      "source": "article-Art31-Para4",
      "target": "article-Art31-Para1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art31-Para4 references article-Art31-Para1 to apply alert-threshold and incident-response-trigger duties to the financial entities defined in paragraph 1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art31-Para4__article-Art31-Para1__references",
      "source_canonical_ref": "celex:32024R1774/article-Art31-Para4",
      "target_canonical_ref": "celex:32024R1774/article-Art31-Para1"
    },
    {
      "source": "article-Art32-Para1",
      "target": "article-Art30-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art32-Para1 depends on article-Art30-Para1 because physical security measures must be designed in accordance with the information-asset and ICT-asset classification established there.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art32-Para1__article-Art30-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art32-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
    },
    {
      "source": "article-Art32-Para2",
      "target": "article-Art32-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art32-Para2 depends on article-Art32-Para1 because it specifies the premises, data centres, threats and hazards against which the paragraph-1 physical security measures must protect.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art32-Para2__article-Art32-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art32-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art32-Para1"
    },
    {
      "source": "article-Art32-Para3",
      "target": "article-Art32-Para2",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "article-Art32-Para3 qualifies article-Art32-Para2 by making its environmental-threat protection proportionate to premises importance and the criticality of operations or ICT systems located there.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art32-Para3__article-Art32-Para2__qualifies",
      "source_canonical_ref": "celex:32024R1774/article-Art32-Para3",
      "target_canonical_ref": "celex:32024R1774/article-Art32-Para2"
    },
    {
      "source": "article-Art33-Para1",
      "target": "article-Art30-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art33-Para1 depends on article-Art30-Para1 because authentication strength under the access-control procedure must be commensurate with the asset classification established in that paragraph.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art33-Para1__article-Art30-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art33-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
    },
    {
      "source": "article-Art33-Para1",
      "target": "article-Art34-Para1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art33-Para1 references article-Art34-Para1 because privileged, emergency and administrator access assigned under Article 33 must be logged under the Article 34 first-paragraph point-(f) logging control.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art33-Para1__article-Art34-Para1__references",
      "source_canonical_ref": "celex:32024R1774/article-Art33-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art34-Para1"
    },
    {
      "source": "article-Art34-Para1",
      "target": "article-Art30-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art34-Para1 depends on article-Art30-Para1 because the required vulnerability scanning and assessments are calibrated to the asset classification defined in Article 30(1).",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art34-Para1__article-Art30-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art34-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
    },
    {
      "source": "article-Art35-Para1",
      "target": "article-Art30-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art35-Para1 depends on article-Art30-Para1 because its data, system and network safeguards must be selected while taking the Article 30(1) asset classification into account.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art35-Para1__article-Art30-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art35-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art30-Para1"
    },
    {
      "source": "article-Art36-Para1",
      "target": "article-Art31-Para3",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art36-Para1 depends on article-Art31-Para3 because its testing plan must consider the threats and vulnerabilities continuously identified under the simplified ICT risk management framework.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art36-Para1__article-Art31-Para3__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art31-Para3"
    },
    {
      "source": "article-Art36-Para1",
      "target": "article-Art33-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art36-Para1 depends on article-Art33-Para1 because the security testing plan expressly validates the effectiveness of the access-control measures required by that paragraph.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art36-Para1__article-Art33-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art33-Para1"
    },
    {
      "source": "article-Art36-Para1",
      "target": "article-Art34-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art36-Para1 depends on article-Art34-Para1 because the security testing plan expressly validates the effectiveness of the ICT-operations security measures required by that paragraph.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art36-Para1__article-Art34-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art34-Para1"
    },
    {
      "source": "article-Art36-Para1",
      "target": "article-Art35-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art36-Para1 depends on article-Art35-Para1 because the security testing plan expressly validates the effectiveness of the data, system and network safeguards required by that paragraph.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art36-Para1__article-Art35-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art35-Para1"
    },
    {
      "source": "article-Art36-Para1",
      "target": "article-Art37-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art36-Para1 depends on article-Art37-Para1 because the security testing plan expressly validates the effectiveness of the acquisition, development and maintenance controls required by that paragraph.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art36-Para1__article-Art37-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art37-Para1"
    },
    {
      "source": "article-Art36-Para1",
      "target": "article-Art38-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art36-Para1 depends on article-Art38-Para1 because the security testing plan expressly validates the effectiveness of the ICT project-management procedure required by that paragraph.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art36-Para1__article-Art38-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art38-Para1"
    },
    {
      "source": "article-Art36-Para1",
      "target": "article-Art38-Para2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art36-Para1 depends on article-Art38-Para2 because the security testing plan expressly validates the effectiveness of the ICT change-management procedure required by that paragraph.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art36-Para1__article-Art38-Para2__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art36-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art38-Para2"
    },
    {
      "source": "article-Art36-Para2",
      "target": "article-Art36-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art36-Para2 depends on article-Art36-Para1 because its review, assessment and testing of ICT security measures operationalise the testing plan and entity scope established in paragraph 1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art36-Para2__article-Art36-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art36-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art36-Para1"
    },
    {
      "source": "article-Art36-Para3",
      "target": "article-Art36-Para1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art36-Para3 references article-Art36-Para1 to inherit the financial-entity scope and testing-plan context for monitoring and evaluating security-test results.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art36-Para3__article-Art36-Para1__references",
      "source_canonical_ref": "celex:32024R1774/article-Art36-Para3",
      "target_canonical_ref": "celex:32024R1774/article-Art36-Para1"
    },
    {
      "source": "article-Art36-Para3",
      "target": "article-Art36-Para2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art36-Para3 depends on article-Art36-Para2 because the results that paragraph 3 requires entities to evaluate arise from the review, assessment and testing mandated in paragraph 2.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art36-Para3__article-Art36-Para2__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art36-Para3",
      "target_canonical_ref": "celex:32024R1774/article-Art36-Para2"
    },
    {
      "source": "article-Art38-Para2",
      "target": "article-Art38-Para1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art38-Para2 references article-Art38-Para1 to inherit its financial-entity scope before imposing the separate controlled ICT change-management procedure.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art38-Para2__article-Art38-Para1__references",
      "source_canonical_ref": "celex:32024R1774/article-Art38-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art38-Para1"
    },
    {
      "source": "article-Art39-Para2",
      "target": "article-Art39-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art39-Para2 depends on article-Art39-Para1 because it prescribes the approval, resources, recovery, backup and communication content of the business continuity plans developed under paragraph 1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art39-Para2__article-Art39-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art39-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art39-Para1"
    },
    {
      "source": "article-Art4-Para2",
      "target": "article-Art4-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art4-Para2 defines the mandatory contents of the ICT asset-management policy that article-Art4-Para1 requires financial entities to establish.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art4-Para2__article-Art4-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art4-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art4-Para1"
    },
    {
      "source": "article-Art40-Para1",
      "target": "article-Art39-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art40-Para1 depends on article-Art39-Para1 because the annual or major-change test covers the business continuity plans and severe-disruption scenarios established in Article 39(1).",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art40-Para1__article-Art39-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art40-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art39-Para1"
    },
    {
      "source": "article-Art40-Para1",
      "target": "article-Art39-Para2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art40-Para1 depends on article-Art39-Para2 because its express requirement to test the Article 39 business continuity plans at least annually for backup and restore procedures reaches the paragraph that specifies backup procedures, restoration and recovery measures, recovery levels and timeframes.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art40-Para1__article-Art39-Para2__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art40-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art39-Para2"
    },
    {
      "source": "article-Art40-Para2",
      "target": "article-Art40-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art40-Para2 depends on article-Art40-Para1 because it defines what the paragraph-1 testing must demonstrate about business viability, operational re-establishment and plan deficiencies.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art40-Para2__article-Art40-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art40-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art40-Para1"
    },
    {
      "source": "article-Art40-Para3",
      "target": "article-Art40-Para1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art40-Para3 references article-Art40-Para1 to inherit the financial-entity scope and the business-continuity-plan testing whose results must be documented.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art40-Para3__article-Art40-Para1__references",
      "source_canonical_ref": "celex:32024R1774/article-Art40-Para3",
      "target_canonical_ref": "celex:32024R1774/article-Art40-Para1"
    },
    {
      "source": "article-Art40-Para3",
      "target": "article-Art40-Para2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art40-Para3 depends on article-Art40-Para2 because the deficiencies to be analysed, addressed and reported are those the paragraph-2 test is required to identify.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art40-Para3__article-Art40-Para2__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art40-Para3",
      "target_canonical_ref": "celex:32024R1774/article-Art40-Para2"
    },
    {
      "source": "article-Art41-Para2",
      "target": "article-Art41-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art41-Para2 depends on article-Art41-Para1 because it specifies the mandatory content of the searchable electronic simplified-framework review report introduced in paragraph 1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art41-Para2__article-Art41-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art41-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art41-Para1"
    },
    {
      "source": "article-Art5-Para2",
      "target": "article-Art5-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art5-Para2 supplies the criticality-assessment criteria for the ICT asset-management procedure created by article-Art5-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art5-Para2__article-Art5-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art5-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art5-Para1"
    },
    {
      "source": "article-Art6-Para2",
      "target": "article-Art6-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art6-Para2 prescribes the design and rules of the encryption and cryptographic-controls policy mandated by article-Art6-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art6-Para2__article-Art6-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art6-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art6-Para1"
    },
    {
      "source": "article-Art6-Para2",
      "target": "article-Art7-Para1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art6-Para2 refers cryptographic-key management to Article 7, and article-Art7-Para1 is the narrow paragraph specifying whole-lifecycle key management.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art6-Para2__article-Art7-Para1__references",
      "source_canonical_ref": "celex:32024R1774/article-Art6-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art7-Para1"
    },
    {
      "source": "article-Art6-Para2",
      "target": "article-Art7-Para2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art6-Para2's express Article 7 reference includes protection of cryptographic keys, which article-Art7-Para2 specifically regulates throughout the key lifecycle.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art6-Para2__article-Art7-Para2__references",
      "source_canonical_ref": "celex:32024R1774/article-Art6-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art7-Para2"
    },
    {
      "source": "article-Art6-Para3",
      "target": "article-Art6-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art6-Para3 adds technique-selection and mitigation criteria to the cryptographic-controls policy established by article-Art6-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art6-Para3__article-Art6-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art6-Para3",
      "target_canonical_ref": "celex:32024R1774/article-Art6-Para1"
    },
    {
      "source": "article-Art6-Para4",
      "target": "article-Art10-Para2",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art6-Para4 expressly invokes article-Art10-Para2 point (a) when requiring awareness-driven updates that keep cryptographic technology resilient to cyber threats.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art6-Para4__article-Art10-Para2__references",
      "source_canonical_ref": "celex:32024R1774/article-Art6-Para4",
      "target_canonical_ref": "celex:32024R1774/article-Art10-Para2"
    },
    {
      "source": "article-Art6-Para4",
      "target": "article-Art6-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art6-Para4 requires technology-update provisions within the encryption and cryptographic-controls policy mandated by article-Art6-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art6-Para4__article-Art6-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art6-Para4",
      "target_canonical_ref": "celex:32024R1774/article-Art6-Para1"
    },
    {
      "source": "article-Art6-Para5",
      "target": "article-Art6-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art6-Para5 places recording and explanation duties inside the cryptographic-controls policy first required by article-Art6-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art6-Para5__article-Art6-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art6-Para5",
      "target_canonical_ref": "celex:32024R1774/article-Art6-Para1"
    },
    {
      "source": "article-Art6-Para5",
      "target": "article-Art6-Para3",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art6-Para5 expressly requires records for mitigation and monitoring measures adopted under article-Art6-Para3 when leading practices or reliable techniques cannot be followed.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art6-Para5__article-Art6-Para3__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art6-Para5",
      "target_canonical_ref": "celex:32024R1774/article-Art6-Para3"
    },
    {
      "source": "article-Art6-Para5",
      "target": "article-Art6-Para4",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art6-Para5 expressly requires a reasoned record of the mitigation and monitoring measures adopted under article-Art6-Para4 when cryptographic technology cannot be updated.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art6-Para5__article-Art6-Para4__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art6-Para5",
      "target_canonical_ref": "celex:32024R1774/article-Art6-Para4"
    },
    {
      "source": "article-Art7-Para1",
      "target": "article-Art6-Para2",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art7-Para1 expressly makes its whole-lifecycle key requirements part of the cryptographic-key management policy specified in article-Art6-Para2 point (d).",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art7-Para1__article-Art6-Para2__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art7-Para1",
      "target_canonical_ref": "celex:32024R1774/article-Art6-Para2"
    },
    {
      "source": "article-Art8-Para2",
      "target": "article-Art13-Para1",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art8-Para2 expressly applies the segregation requirement in article-Art13-Para1 point (a) to all components of separated production and non-production environments.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art8-Para2__article-Art13-Para1__references",
      "source_canonical_ref": "celex:32024R1774/article-Art8-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art13-Para1"
    },
    {
      "source": "article-Art8-Para2",
      "target": "article-Art16-Para6",
      "relation": "references",
      "confidence": "high",
      "reasoning": "article-Art8-Para2 expressly uses article-Art16-Para6 as the approval and limited-duration standard for testing in production environments.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art8-Para2__article-Art16-Para6__references",
      "source_canonical_ref": "celex:32024R1774/article-Art8-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para6"
    },
    {
      "source": "article-Art8-Para2",
      "target": "article-Art8-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art8-Para2 prescribes the required operational, monitoring and error-handling contents of the ICT-operations policies created by article-Art8-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art8-Para2__article-Art8-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art8-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art8-Para1"
    },
    {
      "source": "article-Art9-Para2",
      "target": "article-Art9-Para1",
      "relation": "depends_on",
      "confidence": "high",
      "reasoning": "article-Art9-Para2 adds system-specific proportional measures to the capacity and performance management procedures required by article-Art9-Para1.",
      "source_type": "article_paragraph",
      "target_type": "article_paragraph",
      "edge_id": "article-Art9-Para2__article-Art9-Para1__depends_on",
      "source_canonical_ref": "celex:32024R1774/article-Art9-Para2",
      "target_canonical_ref": "celex:32024R1774/article-Art9-Para1"
    },
    {
      "source": "recital-10",
      "target": "article-Art8-Para2",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-10 provides guidance for article-Art8-Para2 by explaining the security purpose of separating production from development, testing and other non-production environments and the exceptional justification and approval required for testing in production.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-10__article-Art8-Para2__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-10",
      "target_canonical_ref": "celex:32024R1774/article-Art8-Para2"
    },
    {
      "source": "recital-11",
      "target": "article-Art10-Para2",
      "relation": "concretizes",
      "confidence": "high",
      "reasoning": "recital-11 concretizes article-Art10-Para2 by requiring reliable vulnerability information, automated monitoring, remediation, and verification that ICT third-party service providers promptly investigate and address vulnerabilities in supplied services.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-11__article-Art10-Para2__concretizes",
      "source_canonical_ref": "celex:32024R1774/recital-11",
      "target_canonical_ref": "celex:32024R1774/article-Art10-Para2"
    },
    {
      "source": "recital-12",
      "target": "article-Art10-Para4",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-12 provides guidance for article-Art10-Para4 by explaining that patches should be tested and deployed in a controlled environment so that identified vulnerabilities are remedied without creating operational disruption.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-12__article-Art10-Para4__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-12",
      "target_canonical_ref": "celex:32024R1774/article-Art10-Para4"
    },
    {
      "source": "recital-12",
      "target": "recital-11",
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-12 builds on recital-11 by presenting controlled patch testing and deployment as the remediation step for the vulnerabilities that recital-11 requires financial entities and their ICT providers to identify and address.",
      "source_type": "recital",
      "target_type": "recital",
      "edge_id": "recital-12__recital-11__builds_on",
      "source_canonical_ref": "celex:32024R1774/recital-12",
      "target_canonical_ref": "celex:32024R1774/recital-11"
    },
    {
      "source": "recital-13",
      "target": "article-Art10-Para2",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-13 provides guidance for the responsible-disclosure procedure in article-Art10-Para2 by identifying severity, stakeholder impact, and the readiness of a fix or mitigation as factors for communicating ICT vulnerabilities.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-13__article-Art10-Para2__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-13",
      "target_canonical_ref": "celex:32024R1774/article-Art10-Para2"
    },
    {
      "source": "recital-14",
      "target": "article-Art20-Para1",
      "relation": "concretizes",
      "confidence": "high",
      "reasoning": "recital-14 concretizes article-Art20-Para1 by explaining that unique identification must cover both individuals and systems so that user access rights can be assigned without exposing the entity to unauthorised access and untraceable activity.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-14__article-Art20-Para1__concretizes",
      "source_canonical_ref": "celex:32024R1774/recital-14",
      "target_canonical_ref": "celex:32024R1774/article-Art20-Para1"
    },
    {
      "source": "recital-14",
      "target": "article-Art21-Para1",
      "relation": "restricts",
      "confidence": "high",
      "reasoning": "recital-14 restricts article-Art21-Para1 by clarifying that generic or shared accounts are exceptional and may be used only under specified circumstances while preserving accountability for every action performed through them.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-14__article-Art21-Para1__restricts",
      "source_canonical_ref": "celex:32024R1774/recital-14",
      "target_canonical_ref": "celex:32024R1774/article-Art21-Para1"
    },
    {
      "source": "recital-15",
      "target": "article-Art15-Para2",
      "relation": "concretizes",
      "confidence": "high",
      "reasoning": "recital-15 concretizes article-Art15-Para2 by identifying acquisition, maintenance, development and change of ICT systems as project-management subject matter regardless of the methodology selected by the financial entity.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-15__article-Art15-Para2__concretizes",
      "source_canonical_ref": "celex:32024R1774/recital-15",
      "target_canonical_ref": "celex:32024R1774/article-Art15-Para2"
    },
    {
      "source": "recital-15",
      "target": "article-Art15-Para3",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-15 provides guidance for article-Art15-Para3 by requiring project testing methods suited to the entity, applied on a risk basis, while preserving a secure, reliable and resilient ICT environment.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-15__article-Art15-Para3__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-15",
      "target_canonical_ref": "celex:32024R1774/article-Art15-Para3"
    },
    {
      "source": "recital-15",
      "target": "article-Art15-Para4",
      "relation": "concretizes",
      "confidence": "high",
      "reasoning": "recital-15 concretizes article-Art15-Para4 by explaining that staff from business areas or roles affected by an ICT project must supply the information and expertise needed for secure implementation.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-15__article-Art15-Para4__concretizes",
      "source_canonical_ref": "celex:32024R1774/recital-15",
      "target_canonical_ref": "celex:32024R1774/article-Art15-Para4"
    },
    {
      "source": "recital-15",
      "target": "article-Art15-Para5",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-15 provides guidance for article-Art15-Para5 by linking management-body reporting to projects affecting critical or important functions and by tying report frequency and detail to each project’s importance and size.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-15__article-Art15-Para5__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-15",
      "target_canonical_ref": "celex:32024R1774/article-Art15-Para5"
    },
    {
      "source": "recital-16",
      "target": "article-Art16-Para3",
      "relation": "concretizes",
      "confidence": "high",
      "reasoning": "recital-16 concretizes article-Art16-Para3 by requiring source-code review through both static and dynamic testing to reveal vulnerabilities and security gaps and to assess software integrity before operational use.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-16__article-Art16-Para3__concretizes",
      "source_canonical_ref": "celex:32024R1774/recital-16",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para3"
    },
    {
      "source": "recital-16",
      "target": "article-Art16-Para4",
      "relation": "concretizes",
      "confidence": "high",
      "reasoning": "recital-16 concretizes article-Art16-Para4 by explaining that acquired or developed software packages must undergo ICT security testing so that they can be integrated securely into the existing ICT environment.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-16__article-Art16-Para4__concretizes",
      "source_canonical_ref": "celex:32024R1774/recital-16",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para4"
    },
    {
      "source": "recital-16",
      "target": "article-Art16-Para8",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-16 provides guidance for article-Art16-Para8 by specifying that review should cover acquired software, including proprietary software and, where feasible, source code supplied by ICT third-party service providers.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-16__article-Art16-Para8__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-16",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para8"
    },
    {
      "source": "recital-17",
      "target": "article-Art17-Para1",
      "relation": "concretizes",
      "confidence": "high",
      "reasoning": "recital-17 concretizes article-Art17-Para1 by explaining why change-security verification, separation of approval from request and implementation, assigned roles, controlled testing, quality assurance, and fall-back responsibilities are required to contain confidentiality, integrity, availability, and disruption risks.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-17__article-Art17-Para1__concretizes",
      "source_canonical_ref": "celex:32024R1774/recital-17",
      "target_canonical_ref": "celex:32024R1774/article-Art17-Para1"
    },
    {
      "source": "recital-17",
      "target": "recital-15",
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-17 builds on recital-15 because recital-15 places ICT changes within project management and testing, while recital-17 develops that change strand into dedicated approval-separation, transition, quality, and fall-back controls.",
      "source_type": "recital",
      "target_type": "recital",
      "edge_id": "recital-17__recital-15__builds_on",
      "source_canonical_ref": "celex:32024R1774/recital-17",
      "target_canonical_ref": "celex:32024R1774/recital-15"
    },
    {
      "source": "recital-18",
      "target": "article-Art22-Para1",
      "relation": "concretizes",
      "confidence": "high",
      "reasoning": "recital-18 concretizes article-Art22-Para1 by identifying the incident-policy functions implemented there: an end-to-end management process, internal and external coordination contacts, and detailed analysis of significant or recurring incidents and patterns.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-18__article-Art22-Para1__concretizes",
      "source_canonical_ref": "celex:32024R1774/recital-18",
      "target_canonical_ref": "celex:32024R1774/article-Art22-Para1"
    },
    {
      "source": "recital-19",
      "target": "article-Art23-Para1",
      "relation": "concretizes",
      "confidence": "high",
      "reasoning": "recital-19 concretizes article-Art23-Para1 by tying that paragraph's clear-role requirement specifically to responsibility for collecting, monitoring, and analysing information used to detect anomalous activities early and effectively.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-19__article-Art23-Para1__concretizes",
      "source_canonical_ref": "celex:32024R1774/recital-19",
      "target_canonical_ref": "celex:32024R1774/article-Art23-Para1"
    },
    {
      "source": "recital-19",
      "target": "article-Art23-Para2",
      "relation": "concretizes",
      "confidence": "high",
      "reasoning": "recital-19 concretizes article-Art23-Para2 by explaining that its detection mechanism must combine logs with reports from internal functions, external information, and incident notices from ICT third-party providers rather than relying on logs alone.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-19__article-Art23-Para2__concretizes",
      "source_canonical_ref": "celex:32024R1774/recital-19",
      "target_canonical_ref": "celex:32024R1774/article-Art23-Para2"
    },
    {
      "source": "recital-19",
      "target": "recital-18",
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-19 builds on recital-18 by developing the detection phase of recital-18's incident-management process into concrete internal, log, external, and ICT-provider information sources with assigned responsibilities.",
      "source_type": "recital",
      "target_type": "recital",
      "edge_id": "recital-19__recital-18__builds_on",
      "source_canonical_ref": "celex:32024R1774/recital-19",
      "target_canonical_ref": "celex:32024R1774/recital-18"
    },
    {
      "source": "recital-19",
      "target": "recital-30",
      "relation": "provides_context_for",
      "confidence": "high",
      "reasoning": "recital-19 provides context for recital-30 because its incident-detection data collection is the concrete setting in which recital-30 reiterates full data-protection application and uses data minimisation for incident detection as its example.",
      "source_type": "recital",
      "target_type": "recital",
      "edge_id": "recital-19__recital-30__provides_context_for",
      "source_canonical_ref": "celex:32024R1774/recital-19",
      "target_canonical_ref": "celex:32024R1774/recital-30"
    },
    {
      "source": "recital-1",
      "target": "article-Art1-Para1",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-1 explains the proportionality rationale for article-Art1-Para1 by tying ICT requirements to entity size, structure, complexity and corresponding ICT risk.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-1__article-Art1-Para1__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-1",
      "target_canonical_ref": "celex:32024R1774/article-Art1-Para1"
    },
    {
      "source": "recital-20",
      "target": "article-Art22-Para1",
      "relation": "concretizes",
      "confidence": "high",
      "reasoning": "recital-20 concretizes the evidence-retention duty in article-Art22-Para1 by explaining that its period must balance effective incident detection against regulatory burden while reflecting data criticality and Union-law retention requirements.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-20__article-Art22-Para1__concretizes",
      "source_canonical_ref": "celex:32024R1774/recital-20",
      "target_canonical_ref": "celex:32024R1774/article-Art22-Para1"
    },
    {
      "source": "recital-20",
      "target": "recital-18",
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-20 builds on recital-18 by adding evidence retention and a calibrated retention period to the incident-policy and incident-management process introduced in recital-18.",
      "source_type": "recital",
      "target_type": "recital",
      "edge_id": "recital-20__recital-18__builds_on",
      "source_canonical_ref": "celex:32024R1774/recital-20",
      "target_canonical_ref": "celex:32024R1774/recital-18"
    },
    {
      "source": "recital-21",
      "target": "article-Art23-Para5",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-21 provides guidance for article-Art23-Para5 by clarifying that every listed trigger criterion must be considered, but that the list is non-exhaustive and the listed circumstances need not occur simultaneously.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-21__article-Art23-Para5__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-21",
      "target_canonical_ref": "celex:32024R1774/article-Art23-Para5"
    },
    {
      "source": "recital-21",
      "target": "article-Art23-Para6",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-21 provides guidance for article-Art23-Para6 by explaining that the criticality assessment concerns the importance of the affected ICT services when deciding whether to trigger incident detection and response.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-21__article-Art23-Para6__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-21",
      "target_canonical_ref": "celex:32024R1774/article-Art23-Para6"
    },
    {
      "source": "recital-21",
      "target": "recital-18",
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-21 builds on recital-18 by specifying how trigger criteria are to operate within the detection and response phases of the incident-management process established in recital-18.",
      "source_type": "recital",
      "target_type": "recital",
      "edge_id": "recital-21__recital-18__builds_on",
      "source_canonical_ref": "celex:32024R1774/recital-21",
      "target_canonical_ref": "celex:32024R1774/recital-18"
    },
    {
      "source": "recital-22",
      "target": "article-Art24-Para1",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-22 provides guidance for article-Art24-Para1 by requiring the ICT business continuity policy assembled under that paragraph to integrate incident management, communication, change management, and ICT third-party-provider risk considerations.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-22__article-Art24-Para1__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-22",
      "target_canonical_ref": "celex:32024R1774/article-Art24-Para1"
    },
    {
      "source": "recital-22",
      "target": "recital-17",
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-22 builds on recital-17 by expressly making the ICT change-management process developed in recital-17 an input to the design of the ICT business continuity policy.",
      "source_type": "recital",
      "target_type": "recital",
      "edge_id": "recital-22__recital-17__builds_on",
      "source_canonical_ref": "celex:32024R1774/recital-22",
      "target_canonical_ref": "celex:32024R1774/recital-17"
    },
    {
      "source": "recital-22",
      "target": "recital-18",
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-22 builds on recital-18 by expressly incorporating ICT-related incident management and its communication dimension into the ICT business continuity policy.",
      "source_type": "recital",
      "target_type": "recital",
      "edge_id": "recital-22__recital-18__builds_on",
      "source_canonical_ref": "celex:32024R1774/recital-22",
      "target_canonical_ref": "celex:32024R1774/recital-18"
    },
    {
      "source": "recital-23",
      "target": "article-Art25-Para2",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-23 provides guidance for article-Art25-Para2 by explaining the purpose of severe-but-plausible scenario testing and of switchover tests: verify redundant capacity, backups, and facilities over a sufficient period and restore normal operation to the recovery objectives.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-23__article-Art25-Para2__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-23",
      "target_canonical_ref": "celex:32024R1774/article-Art25-Para2"
    },
    {
      "source": "recital-23",
      "target": "article-Art26-Para2",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-23 provides guidance for article-Art26-Para2 by directing entities to assess the relevance and plausibility of the response-and-recovery scenarios listed there and to consider whether alternative scenarios are needed.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-23__article-Art26-Para2__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-23",
      "target_canonical_ref": "celex:32024R1774/article-Art26-Para2"
    },
    {
      "source": "recital-23",
      "target": "recital-22",
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-23 builds on recital-22 by moving from the components to be integrated into an ICT business continuity policy to the scenarios used to implement response and recovery plans and test continuity plans.",
      "source_type": "recital",
      "target_type": "recital",
      "edge_id": "recital-23__recital-22__builds_on",
      "source_canonical_ref": "celex:32024R1774/recital-23",
      "target_canonical_ref": "celex:32024R1774/recital-22"
    },
    {
      "source": "recital-24",
      "target": "article-Art16-Para2",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-24 explains why article-Art16-Para2 adds sector-specific ICT-system testing participation for central counterparties and central securities depositories: the RTS builds project-management controls on the operational-risk rules already applicable to those infrastructures.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-24__article-Art16-Para2__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-24",
      "target_canonical_ref": "celex:32024R1774/article-Art16-Para2"
    },
    {
      "source": "recital-24",
      "target": "article-Art17-Para2",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-24 supplies the sectoral rationale for article-Art17-Para2, whose stringent post-change testing duties specifically address central counterparties and central securities depositories under the ICT change-management requirements.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-24__article-Art17-Para2__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-24",
      "target_canonical_ref": "celex:32024R1774/article-Art17-Para2"
    },
    {
      "source": "recital-24",
      "target": "article-Art24-Para2",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-24 explains the legislative basis for the central-counterparty-specific continuity requirements in article-Art24-Para2 by stating that the RTS builds on operational-risk rules already applicable to central counterparties.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-24__article-Art24-Para2__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-24",
      "target_canonical_ref": "celex:32024R1774/article-Art24-Para2"
    },
    {
      "source": "recital-24",
      "target": "article-Art24-Para3",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-24 explains the legislative basis for the central-securities-depository-specific continuity requirements in article-Art24-Para3 by linking the RTS to pre-existing operational-risk rules for those depositories.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-24__article-Art24-Para3__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-24",
      "target_canonical_ref": "celex:32024R1774/article-Art24-Para3"
    },
    {
      "source": "recital-24",
      "target": "article-Art24-Para4",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-24 explains why article-Art24-Para4 preserves trading-venue-specific recovery and data-loss requirements within the RTS business-continuity framework.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-24__article-Art24-Para4__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-24",
      "target_canonical_ref": "celex:32024R1774/article-Art24-Para4"
    },
    {
      "source": "recital-24",
      "target": "article-Art25-Para3",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-24 provides the sectoral context for article-Art25-Para3, which supplements general continuity-plan testing with participation duties tailored to central counterparties.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-24__article-Art25-Para3__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-24",
      "target_canonical_ref": "celex:32024R1774/article-Art25-Para3"
    },
    {
      "source": "recital-24",
      "target": "article-Art25-Para4",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-24 provides the sectoral context for article-Art25-Para4, which supplements continuity-plan testing with participants and infrastructures relevant specifically to central securities depositories.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-24__article-Art25-Para4__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-24",
      "target_canonical_ref": "celex:32024R1774/article-Art25-Para4"
    },
    {
      "source": "recital-25",
      "target": "article-Art27-Para1",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-25 explains the processing and transmission rationale for article-Art27-Para1 requiring the DORA Article 6(5) ICT-risk-framework review report to be submitted in a searchable electronic format.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-25__article-Art27-Para1__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-25",
      "target_canonical_ref": "celex:32024R1774/article-Art27-Para1"
    },
    {
      "source": "recital-26",
      "target": "article-Art1-Para1",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-26 guides application of article-Art1-Para1 by explaining that scale, risk, size and complexity justify limiting the simplified ICT risk management framework to the minimum controls needed to protect data and services.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-26__article-Art1-Para1__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-26",
      "target_canonical_ref": "celex:32024R1774/article-Art1-Para1"
    },
    {
      "source": "recital-26",
      "target": "article-Art28-Para1",
      "relation": "concretizes",
      "confidence": "high",
      "reasoning": "recital-26 concretizes article-Art28-Para1 by identifying an internal governance and control framework as the organisational basis for effective and sound ICT risk management by simplified-framework entities.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-26__article-Art28-Para1__concretizes",
      "source_canonical_ref": "celex:32024R1774/recital-26",
      "target_canonical_ref": "celex:32024R1774/article-Art28-Para1"
    },
    {
      "source": "recital-26",
      "target": "article-Art28-Para2",
      "relation": "concretizes",
      "confidence": "high",
      "reasoning": "recital-26 concretizes the clear-responsibility element of article-Art28-Para2 by requiring governance arrangements with unambiguous responsibilities for the simplified ICT risk management framework.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-26__article-Art28-Para2__concretizes",
      "source_canonical_ref": "celex:32024R1774/recital-26",
      "target_canonical_ref": "celex:32024R1774/article-Art28-Para2"
    },
    {
      "source": "recital-26",
      "target": "article-Art29-Para1",
      "relation": "concretizes",
      "confidence": "high",
      "reasoning": "recital-26 directly concretizes article-Art29-Para1: simplified-framework entities use one information security policy containing high-level rules that protect confidentiality, integrity, availability and authenticity.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-26__article-Art29-Para1__concretizes",
      "source_canonical_ref": "celex:32024R1774/recital-26",
      "target_canonical_ref": "celex:32024R1774/article-Art29-Para1"
    },
    {
      "source": "recital-26",
      "target": "recital-2",
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-26 builds_on recital-2 by turning recital-2’s flexibility and essential-policy premise into the simplified-framework rule that entities maintain one high-level information security policy proportionate to scale and risk.",
      "source_type": "recital",
      "target_type": "recital",
      "edge_id": "recital-26__recital-2__builds_on",
      "source_canonical_ref": "celex:32024R1774/recital-26",
      "target_canonical_ref": "celex:32024R1774/recital-2"
    },
    {
      "source": "recital-29",
      "target": "recital-28",
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-29 builds_on recital-28: recital-28 identifies the ESAs’ draft regulatory technical standards, while recital-29 records the Joint Committee consultation, cost-benefit analysis and stakeholder advice for that same draft.",
      "source_type": "recital",
      "target_type": "recital",
      "edge_id": "recital-29__recital-28__builds_on",
      "source_canonical_ref": "celex:32024R1774/recital-29",
      "target_canonical_ref": "celex:32024R1774/recital-28"
    },
    {
      "source": "recital-2",
      "target": "article-Art10-Para1",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-2 expressly lists vulnerability management among the technical implementation procedures that article-Art10-Para1 requires financial entities to establish.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-2__article-Art10-Para1__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-2",
      "target_canonical_ref": "celex:32024R1774/article-Art10-Para1"
    },
    {
      "source": "recital-2",
      "target": "article-Art10-Para3",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-2 separately names patch management as a necessary technical procedure, directly explaining the obligation in article-Art10-Para3.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-2__article-Art10-Para3__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-2",
      "target_canonical_ref": "celex:32024R1774/article-Art10-Para3"
    },
    {
      "source": "recital-2",
      "target": "article-Art11-Para1",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-2 identifies data and system security as a technical implementation area, which is the precise procedure created by article-Art11-Para1.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-2__article-Art11-Para1__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-2",
      "target_canonical_ref": "celex:32024R1774/article-Art11-Para1"
    },
    {
      "source": "recital-2",
      "target": "article-Art12-Para1",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-2 expressly includes logging among necessary technical procedures, supplying the policy rationale for article-Art12-Para1's logging obligation.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-2__article-Art12-Para1__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-2",
      "target_canonical_ref": "celex:32024R1774/article-Art12-Para1"
    },
    {
      "source": "recital-2",
      "target": "article-Art2-Para2",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-2 guides application of article-Art2-Para2 by allowing existing documentation to satisfy documentation duties and by explaining why only essential policy elements require dedicated documentation.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-2__article-Art2-Para2__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-2",
      "target_canonical_ref": "celex:32024R1774/article-Art2-Para2"
    },
    {
      "source": "recital-2",
      "target": "article-Art9-Para1",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-2 expressly identifies capacity and performance management as a technical procedure domain, providing the rationale for the procedure mandated by article-Art9-Para1.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-2__article-Art9-Para1__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-2",
      "target_canonical_ref": "celex:32024R1774/article-Art9-Para1"
    },
    {
      "source": "recital-2",
      "target": "recital-1",
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-2 expressly proceeds 'for the same reason' from recital-1's proportionality rationale and develops that rationale into flexibility and documentation reuse.",
      "source_type": "recital",
      "target_type": "recital",
      "edge_id": "recital-2__recital-1__builds_on",
      "source_canonical_ref": "celex:32024R1774/recital-2",
      "target_canonical_ref": "celex:32024R1774/recital-1"
    },
    {
      "source": "recital-30",
      "target": "article-Art23-Para2",
      "relation": "restricts",
      "confidence": "high",
      "reasoning": "recital-30 restricts the collection and analysis required by article-Art23-Para2: where incident-detection information is personal data, the Union data-protection regime and data-minimisation principle continue to apply.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-30__article-Art23-Para2__restricts",
      "source_canonical_ref": "celex:32024R1774/recital-30",
      "target_canonical_ref": "celex:32024R1774/article-Art23-Para2"
    },
    {
      "source": "recital-30",
      "target": "article-Art34-Para1",
      "relation": "restricts",
      "confidence": "high",
      "reasoning": "recital-30 restricts the anomalous-activity monitoring and security-information measures in article-Art34-Para1 by requiring any personal-data processing for incident detection to comply fully with Union data-protection law and data minimisation.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-30__article-Art34-Para1__restricts",
      "source_canonical_ref": "celex:32024R1774/recital-30",
      "target_canonical_ref": "celex:32024R1774/article-Art34-Para1"
    },
    {
      "source": "recital-3",
      "target": "article-Art2-Para2",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-3 explains why article-Art2-Para2 requires maintained ICT-security roles and responsibilities and consequences for staff non-compliance.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-3__article-Art2-Para2__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-3",
      "target_canonical_ref": "celex:32024R1774/article-Art2-Para2"
    },
    {
      "source": "recital-4",
      "target": "article-Art2-Para2",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-4 supplies the conflict-of-interest rationale for the segregation-of-duties arrangements mandated in article-Art2-Para2.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-4__article-Art2-Para2__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-4",
      "target_canonical_ref": "celex:32024R1774/article-Art2-Para2"
    },
    {
      "source": "recital-4",
      "target": "recital-3",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "recital-4 qualifies recital-3's general assignment of ICT roles by requiring segregation of duties where needed to avoid conflicts of interest.",
      "source_type": "recital",
      "target_type": "recital",
      "edge_id": "recital-4__recital-3__qualifies",
      "source_canonical_ref": "celex:32024R1774/recital-4",
      "target_canonical_ref": "celex:32024R1774/recital-3"
    },
    {
      "source": "recital-5",
      "target": "article-Art2-Para2",
      "relation": "restricts",
      "confidence": "high",
      "reasoning": "recital-5 limits article-Art2-Para2's non-compliance provision by confirming that a dedicated provision is unnecessary when another policy or procedure already contains it.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-5__article-Art2-Para2__restricts",
      "source_canonical_ref": "celex:32024R1774/recital-5",
      "target_canonical_ref": "celex:32024R1774/article-Art2-Para2"
    },
    {
      "source": "recital-5",
      "target": "recital-3",
      "relation": "qualifies",
      "confidence": "high",
      "reasoning": "recital-5 qualifies recital-3's requirement for non-compliance consequences by creating an exception when another policy or procedure already states them.",
      "source_type": "recital",
      "target_type": "recital",
      "edge_id": "recital-5__recital-3__qualifies",
      "source_canonical_ref": "celex:32024R1774/recital-5",
      "target_canonical_ref": "celex:32024R1774/recital-3"
    },
    {
      "source": "recital-6",
      "target": "article-Art2-Para2",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-6 explains that evolving ICT risk requires leading practices and applicable standards, guiding the corresponding standards and material-change criteria in article-Art2-Para2.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-6__article-Art2-Para2__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-6",
      "target_canonical_ref": "celex:32024R1774/article-Art2-Para2"
    },
    {
      "source": "recital-6",
      "target": "recital-2",
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-6 builds on recital-2's leading-practice and standards principle by explaining its continuing importance in an evolving ICT-risk landscape.",
      "source_type": "recital",
      "target_type": "recital",
      "edge_id": "recital-6__recital-2__builds_on",
      "source_canonical_ref": "celex:32024R1774/recital-6",
      "target_canonical_ref": "celex:32024R1774/recital-2"
    },
    {
      "source": "recital-7",
      "target": "article-Art2-Para1",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-7 links operational, asset and capacity controls to network security, intrusion safeguards and data protection, explaining the common outcomes required by article-Art2-Para1.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-7__article-Art2-Para1__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-7",
      "target_canonical_ref": "celex:32024R1774/article-Art2-Para1"
    },
    {
      "source": "recital-7",
      "target": "article-Art4-Para1",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-7 expressly identifies development and implementation of an ICT asset-management policy as necessary for digital operational resilience, explaining the obligation in article-Art4-Para1.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-7__article-Art4-Para1__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-7",
      "target_canonical_ref": "celex:32024R1774/article-Art4-Para1"
    },
    {
      "source": "recital-7",
      "target": "article-Art4-Para2",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-7 explains lifecycle monitoring as the purpose of ICT asset management, directly guiding the lifecycle-management content of article-Art4-Para2.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-7__article-Art4-Para2__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-7",
      "target_canonical_ref": "celex:32024R1774/article-Art4-Para2"
    },
    {
      "source": "recital-7",
      "target": "article-Art8-Para1",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-7 describes effective and smooth day-to-day ICT operation as the objective of the operational policies and procedures required by article-Art8-Para1.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-7__article-Art8-Para1__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-7",
      "target_canonical_ref": "celex:32024R1774/article-Art8-Para1"
    },
    {
      "source": "recital-7",
      "target": "article-Art9-Para1",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-7 explains that capacity and performance management should optimise ICT operations and meet business and security objectives, guiding article-Art9-Para1.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-7__article-Art9-Para1__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-7",
      "target_canonical_ref": "celex:32024R1774/article-Art9-Para1"
    },
    {
      "source": "recital-7",
      "target": "recital-2",
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-7 builds on recital-2's identification of technical procedure domains by explaining the operational purposes of asset, capacity and ICT-operations controls.",
      "source_type": "recital",
      "target_type": "recital",
      "edge_id": "recital-7__recital-2__builds_on",
      "source_canonical_ref": "celex:32024R1774/recital-7",
      "target_canonical_ref": "celex:32024R1774/recital-2"
    },
    {
      "source": "recital-8",
      "target": "article-Art4-Para2",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-8 explains the legacy-system risk purpose of recording and monitoring support end-dates, directly guiding the support-date records in article-Art4-Para2.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-8__article-Art4-Para2__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-8",
      "target_canonical_ref": "celex:32024R1774/article-Art4-Para2"
    },
    {
      "source": "recital-8",
      "target": "article-Art5-Para2",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-8 prioritises business-critical assets by the impact of confidentiality, integrity and availability loss, guiding the criticality assessment criteria in article-Art5-Para2.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-8__article-Art5-Para2__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-8",
      "target_canonical_ref": "celex:32024R1774/article-Art5-Para2"
    },
    {
      "source": "recital-8",
      "target": "article-Art8-Para2",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-8 identifies support expiry monitoring as a means to manage legacy-system risk, providing application guidance for the legacy-system control required by article-Art8-Para2.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-8__article-Art8-Para2__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-8",
      "target_canonical_ref": "celex:32024R1774/article-Art8-Para2"
    },
    {
      "source": "recital-8",
      "target": "recital-7",
      "relation": "builds_on",
      "confidence": "high",
      "reasoning": "recital-8 builds on recital-7's lifecycle-based asset-management rationale by addressing the specific legacy-system risk created when third-party support expires.",
      "source_type": "recital",
      "target_type": "recital",
      "edge_id": "recital-8__recital-7__builds_on",
      "source_canonical_ref": "celex:32024R1774/recital-8",
      "target_canonical_ref": "celex:32024R1774/recital-7"
    },
    {
      "source": "recital-9",
      "target": "article-Art6-Para2",
      "relation": "concretizes",
      "confidence": "high",
      "reasoning": "recital-9 concretizes article-Art6-Para2 by linking the encryption policy to approved data classification and ICT risk assessment, distinguishing data at rest, in transit and in use, and explaining the equivalent safeguards required when in-use encryption is infeasible.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-9__article-Art6-Para2__concretizes",
      "source_canonical_ref": "celex:32024R1774/recital-9",
      "target_canonical_ref": "celex:32024R1774/article-Art6-Para2"
    },
    {
      "source": "recital-9",
      "target": "article-Art6-Para3",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-9 provides guidance for article-Art6-Para3 by explaining why cryptographic techniques must track leading practices and standards and why a flexible combination of risk mitigation and monitoring is needed when the most reliable techniques cannot be used.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-9__article-Art6-Para3__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-9",
      "target_canonical_ref": "celex:32024R1774/article-Art6-Para3"
    },
    {
      "source": "recital-9",
      "target": "article-Art6-Para4",
      "relation": "provides_guidance_for",
      "confidence": "high",
      "reasoning": "recital-9 provides guidance for article-Art6-Para4 by identifying rapid cryptanalysis developments, including quantum-related threats, as the reason to update cryptographic technology or adopt compensating mitigation and monitoring measures.",
      "source_type": "recital",
      "target_type": "article_paragraph",
      "edge_id": "recital-9__article-Art6-Para4__provides_guidance_for",
      "source_canonical_ref": "celex:32024R1774/recital-9",
      "target_canonical_ref": "celex:32024R1774/article-Art6-Para4"
    }
  ],
  "metadata": {
    "document": "COMMISSION DELEGATED REGULATION (EU) 2024/1774 of 13 March 2024 supplementing Regulation (EU) 2022/2554 of the European Parliament and of the Council with regard to regulatory technical standards specifying ICT risk management tools, methods, processes, and policies and the simplified ICT risk management framework (Text with EEA relevance)",
    "document_short": "DORA ICT Risk Management RTS",
    "celex": "32024R1774",
    "source_eli": "http://data.europa.eu/eli/reg_del/2024/1774/oj",
    "official_source_url": "https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202401774",
    "document_content_attribution_ids": [],
    "source_attributions": {
      "schema": "eu-legal-to-json/source-attribution@1.0",
      "records": [
        {
          "id": "src-lexapi-case-law-research-32024r1774",
          "provider": "LexAPI",
          "provider_url": "https://lex-api.com/",
          "provider_terms_url": "https://lex-api.com/terms",
          "provider_source_url": null,
          "retrieval_method": "lex_search + lex_cited_by",
          "retrieved_at": "2026-08-05T21:21:51Z",
          "content_origin": {
            "name": "EUR-Lex",
            "identifier_type": "CELEX",
            "identifier": "32024R1774",
            "url": "http://data.europa.eu/eli/reg_del/2024/1774/oj",
            "attribution_text": "Source: EUR-Lex, © European Union."
          },
          "official_verification_url": "http://data.europa.eu/eli/reg_del/2024/1774/oj",
          "verification_status": "target_act_verified_no_case_item_retained",
          "attribution_text": "LexAPI supplied bounded query and citation-count metadata for CELEX 32024R1774; the target act is identified through EUR-Lex, © European Union. No judgment content or case identity was retained.",
          "content_refs": [
            {
              "kind": "case_law_research",
              "id": "case-law-research-32024r1774"
            }
          ],
          "attributed_fields": [
            "query_audit",
            "scope"
          ],
          "rights_notice": "LexAPI was used for bounded discovery metadata only. This artifact does not relicense LexAPI parsing, structuring, enrichment, citation-graph data, semantic scores or raw API responses; official EUR-Lex material remains subject to its own reuse terms.",
          "provider_license": null,
          "provider_specific_material": "none",
          "permission_reference": null,
          "publication_status": "attribution_complete"
        },
        {
          "id": "src-oldp-case-law-research-32024r1774",
          "provider": "Open Legal Data",
          "provider_url": "https://de.openlegaldata.io/",
          "provider_source_url": "https://de.openlegaldata.io/api/cases/search/",
          "retrieval_method": "Open Legal Data paginated case search (two query formulations, page 1 each)",
          "retrieved_at": "2026-08-05T21:21:51Z",
          "content_origin": {
            "name": "Open Legal Data search index; no decision retained",
            "identifier_type": "query_set",
            "identifier": "oldp-32024r1774",
            "url": "https://de.openlegaldata.io/api/cases/search/",
            "attribution_text": "Source: Open Legal Data database metadata, licensed under Open Database License (ODbL) v1.0; no decision text retained."
          },
          "official_verification_url": null,
          "verification_status": "not_applicable_no_case_item_retained",
          "attribution_text": "Search-result count metadata only; no German decision text or case record was retained in the artifact.",
          "content_refs": [
            {
              "kind": "case_law_research",
              "id": "case-law-research-32024r1774"
            }
          ],
          "attributed_fields": [
            "query_audit",
            "scope"
          ],
          "rights_notice": "Open Legal Data database metadata is attributed under the Open Database License (ODbL) v1.0. No decision text was copied or relicensed, and no official court source was required because no case item was retained.",
          "provider_license": {
            "name": "Open Database License (ODbL) v1.0",
            "url": "https://opendatacommons.org/licenses/odbl/1.0/"
          },
          "provider_specific_material": "none",
          "permission_reference": null,
          "publication_status": "attribution_complete"
        }
      ],
      "document_content_attribution_ids": [],
      "license_scope_statement": "The repository licence covers only original selection, structure and analysis. It does not relicense third-party source material or provider-specific enrichment."
    },
    "legal_status": "in force since 15 July 2024",
    "total_recitals": 30,
    "total_article_paragraphs": 111,
    "total_recommendation_points": 0,
    "total_annex_points": 0,
    "akn4eu_root_element": "act",
    "akn4eu_document_name": "REG_DELEG",
    "akn4eu_document_type_uri": "http://publications.europa.eu/resource/authority/resource-type/REG_DELEG",
    "akn4eu_frbrprescriptive": true,
    "akn4eu_legal_status": "in force since 15 July 2024",
    "akn4eu_long_title": {
      "doc_type": "COMMISSION DELEGATED REGULATION",
      "doc_number": "(EU) 2024/1774",
      "doc_date": "2024-03-13",
      "doc_purpose": "specifying ICT risk management tools, methods, processes and policies and the simplified ICT risk management framework under Regulation (EU) 2022/2554"
    },
    "akn4eu_eea_relevance": true,
    "akn4eu_frbr_language": "en",
    "akn4eu_authentic_language": null,
    "akn4eu_preamble": {
      "akn4eu_acting_entity": {
        "text": "THE EUROPEAN COMMISSION,",
        "akn4eu_acting_entity_refers_to": null
      },
      "akn4eu_citations": [
        {
          "akn4eu_citation_role": "legalBasis",
          "akn4eu_refers_to": "~legalBasis",
          "text": "Having regard to the Treaty on the Functioning of the European Union,",
          "akn4eu_target_uri": null
        },
        {
          "akn4eu_citation_role": "legalBasis",
          "akn4eu_refers_to": "~legalBasis",
          "text": "Having regard to Regulation (EU) 2022/2554 of the European Parliament and of the Council of 14 December 2022 on digital operational resilience for the financial sector and amending Regulations (EC) No 1060/2009, (EU) No 648/2012, (EU) No 600/2014, (EU) No 909/2014 and (EU) 2016/1011 ( 1 ) , and in particular Article 15, fourth subparagraph, and Article 16(3), fourth subparagraph, thereof,",
          "akn4eu_target_uri": "http://data.europa.eu/eli/reg/2022/2554/oj"
        }
      ],
      "akn4eu_enacting_formula": {
        "text": "HAS ADOPTED THIS REGULATION:",
        "akn4eu_name": "enactingFormula"
      },
      "ordering_check": "pass"
    },
    "akn4eu_hierarchy": [
      {
        "id": "title-i",
        "type": "title",
        "num": "TITLE I",
        "heading": "GENERAL PRINCIPLE",
        "parent": null,
        "parent_id": null
      },
      {
        "id": "title-ii",
        "type": "title",
        "num": "TITLE II",
        "heading": "FURTHER HARMONISATION OF ICT RISK MANAGEMENT TOOLS, METHODS, PROCESSES, AND POLICIES IN ACCORDANCE WITH ARTICLE 15 OF REGULATION (EU) 2022/2554",
        "parent": null,
        "parent_id": null
      },
      {
        "id": "title-ii-chapter-i",
        "type": "chapter",
        "num": "CHAPTER I",
        "heading": "ICT Security policies, procedures, protocols, and tools",
        "parent": "TITLE II",
        "parent_id": "title-ii"
      },
      {
        "id": "title-ii-chapter-i-section-1",
        "type": "section",
        "num": "Section 1",
        "heading": null,
        "parent": "CHAPTER I",
        "parent_id": "title-ii-chapter-i"
      },
      {
        "id": "title-ii-chapter-i-section-2",
        "type": "section",
        "num": "Section 2",
        "heading": null,
        "parent": "CHAPTER I",
        "parent_id": "title-ii-chapter-i"
      },
      {
        "id": "title-ii-chapter-i-section-3",
        "type": "section",
        "num": "Section 3",
        "heading": "ICT asset management",
        "parent": "CHAPTER I",
        "parent_id": "title-ii-chapter-i"
      },
      {
        "id": "title-ii-chapter-i-section-4",
        "type": "section",
        "num": "Section 4",
        "heading": "Encryption and cryptography",
        "parent": "CHAPTER I",
        "parent_id": "title-ii-chapter-i"
      },
      {
        "id": "title-ii-chapter-i-section-5",
        "type": "section",
        "num": "Section 5",
        "heading": "ICT operations security",
        "parent": "CHAPTER I",
        "parent_id": "title-ii-chapter-i"
      },
      {
        "id": "title-ii-chapter-i-section-6",
        "type": "section",
        "num": "Section 6",
        "heading": "Network security",
        "parent": "CHAPTER I",
        "parent_id": "title-ii-chapter-i"
      },
      {
        "id": "title-ii-chapter-i-section-7",
        "type": "section",
        "num": "Section 7",
        "heading": "ICT project and change management",
        "parent": "CHAPTER I",
        "parent_id": "title-ii-chapter-i"
      },
      {
        "id": "title-ii-chapter-i-section-8",
        "type": "section",
        "num": "Section 8",
        "heading": null,
        "parent": "CHAPTER I",
        "parent_id": "title-ii-chapter-i"
      },
      {
        "id": "title-ii-chapter-ii",
        "type": "chapter",
        "num": "CHAPTER II",
        "heading": "Human resources policy and access control",
        "parent": "TITLE II",
        "parent_id": "title-ii"
      },
      {
        "id": "title-ii-chapter-iii",
        "type": "chapter",
        "num": "CHAPTER III",
        "heading": "ICT-related incident detection and response",
        "parent": "TITLE II",
        "parent_id": "title-ii"
      },
      {
        "id": "title-ii-chapter-iv",
        "type": "chapter",
        "num": "CHAPTER IV",
        "heading": "ICT business continuity management",
        "parent": "TITLE II",
        "parent_id": "title-ii"
      },
      {
        "id": "title-ii-chapter-v",
        "type": "chapter",
        "num": "CHAPTER V",
        "heading": "Report on the ICT risk management framework review",
        "parent": "TITLE II",
        "parent_id": "title-ii"
      },
      {
        "id": "title-iii",
        "type": "title",
        "num": "TITLE III",
        "heading": "SIMPLIFIED ICT RISK MANAGEMENT FRAMEWORK FOR FINANCIAL ENTITIES REFERRED TO IN ARTICLE 16(1) OF REGULATION (EU) 2022/2554",
        "parent": null,
        "parent_id": null
      },
      {
        "id": "title-iii-chapter-i",
        "type": "chapter",
        "num": "CHAPTER I",
        "heading": "Simplified ICT risk management framework",
        "parent": "TITLE III",
        "parent_id": "title-iii"
      },
      {
        "id": "title-iii-chapter-ii",
        "type": "chapter",
        "num": "CHAPTER II",
        "heading": "Further elements of systems, protocols, and tools to minimise the impact of ICT risk",
        "parent": "TITLE III",
        "parent_id": "title-iii"
      },
      {
        "id": "title-iii-chapter-iii",
        "type": "chapter",
        "num": "CHAPTER III",
        "heading": "ICT business continuity management",
        "parent": "TITLE III",
        "parent_id": "title-iii"
      },
      {
        "id": "title-iii-chapter-iv",
        "type": "chapter",
        "num": "CHAPTER IV",
        "heading": "Report on the review of the simplified ICT risk management framework",
        "parent": "TITLE III",
        "parent_id": "title-iii"
      },
      {
        "id": "title-iv",
        "type": "title",
        "num": "TITLE IV",
        "heading": "FINAL PROVISIONS",
        "parent": null,
        "parent_id": null
      }
    ],
    "akn4eu_hierarchy_edges": [
      {
        "from": "title-ii-chapter-i",
        "to": "title-ii",
        "relation": "part_of",
        "reasoning": "CHAPTER I is structurally contained in TITLE II in the official act."
      },
      {
        "from": "title-ii-chapter-i-section-1",
        "to": "title-ii-chapter-i",
        "relation": "part_of",
        "reasoning": "Section 1 is structurally contained in CHAPTER I in the official act."
      },
      {
        "from": "title-ii-chapter-i-section-2",
        "to": "title-ii-chapter-i",
        "relation": "part_of",
        "reasoning": "Section 2 is structurally contained in CHAPTER I in the official act."
      },
      {
        "from": "title-ii-chapter-i-section-3",
        "to": "title-ii-chapter-i",
        "relation": "part_of",
        "reasoning": "Section 3 is structurally contained in CHAPTER I in the official act."
      },
      {
        "from": "title-ii-chapter-i-section-4",
        "to": "title-ii-chapter-i",
        "relation": "part_of",
        "reasoning": "Section 4 is structurally contained in CHAPTER I in the official act."
      },
      {
        "from": "title-ii-chapter-i-section-5",
        "to": "title-ii-chapter-i",
        "relation": "part_of",
        "reasoning": "Section 5 is structurally contained in CHAPTER I in the official act."
      },
      {
        "from": "title-ii-chapter-i-section-6",
        "to": "title-ii-chapter-i",
        "relation": "part_of",
        "reasoning": "Section 6 is structurally contained in CHAPTER I in the official act."
      },
      {
        "from": "title-ii-chapter-i-section-7",
        "to": "title-ii-chapter-i",
        "relation": "part_of",
        "reasoning": "Section 7 is structurally contained in CHAPTER I in the official act."
      },
      {
        "from": "title-ii-chapter-i-section-8",
        "to": "title-ii-chapter-i",
        "relation": "part_of",
        "reasoning": "Section 8 is structurally contained in CHAPTER I in the official act."
      },
      {
        "from": "title-ii-chapter-ii",
        "to": "title-ii",
        "relation": "part_of",
        "reasoning": "CHAPTER II is structurally contained in TITLE II in the official act."
      },
      {
        "from": "title-ii-chapter-iii",
        "to": "title-ii",
        "relation": "part_of",
        "reasoning": "CHAPTER III is structurally contained in TITLE II in the official act."
      },
      {
        "from": "title-ii-chapter-iv",
        "to": "title-ii",
        "relation": "part_of",
        "reasoning": "CHAPTER IV is structurally contained in TITLE II in the official act."
      },
      {
        "from": "title-ii-chapter-v",
        "to": "title-ii",
        "relation": "part_of",
        "reasoning": "CHAPTER V is structurally contained in TITLE II in the official act."
      },
      {
        "from": "title-iii-chapter-i",
        "to": "title-iii",
        "relation": "part_of",
        "reasoning": "CHAPTER I is structurally contained in TITLE III in the official act."
      },
      {
        "from": "title-iii-chapter-ii",
        "to": "title-iii",
        "relation": "part_of",
        "reasoning": "CHAPTER II is structurally contained in TITLE III in the official act."
      },
      {
        "from": "title-iii-chapter-iii",
        "to": "title-iii",
        "relation": "part_of",
        "reasoning": "CHAPTER III is structurally contained in TITLE III in the official act."
      },
      {
        "from": "title-iii-chapter-iv",
        "to": "title-iii",
        "relation": "part_of",
        "reasoning": "CHAPTER IV is structurally contained in TITLE III in the official act."
      }
    ],
    "akn4eu_annex": null,
    "akn4eu_filename_xml": "REG_DELEG-2024-1774-en.xml",
    "akn4eu_filename_leg": "REG_DELEG-2024-1774-en.leg",
    "akn4eu_conflicts": [],
    "relation_counts": {
      "recital_to_article": 59,
      "recital_to_annex": 0,
      "recital_to_recital": 17,
      "article_to_article": 132,
      "annex_hierarchy": 0,
      "annex_to_article": 0,
      "case_law_to_block": 0,
      "akn4eu_hierarchy_edge": 17
    },
    "consistency_check": {
      "run": true,
      "edge_symmetry": "pass",
      "method": "node relations will be regenerated from one canonical edge list",
      "orphan_outbound": 0,
      "orphan_inbound": 0,
      "referential_integrity": "pass",
      "status": "pass"
    },
    "case_law_research": {
      "id": "case-law-research-32024r1774",
      "status": "bounded_search_complete",
      "searched_at": "2026-08-05T21:21:51Z",
      "cutoff_date": "2026-08-05",
      "sources": [
        "lexapi",
        "open_legal_data"
      ],
      "query_audit": [
        {
          "id": "controls-lexapi-exact-judgment",
          "provider": "LexAPI",
          "method": "lex_search",
          "query": "\"Regulation (EU) 2024/1774\"",
          "filters": {
            "documentType": "judgment",
            "language": "en",
            "textScope": "title-text"
          },
          "pagination": {
            "max_pages": 3,
            "pages_fetched": 1,
            "total_pages": 0
          },
          "result_count": 0,
          "material_case_count": 0,
          "status": "zero_result_within_recorded_scope"
        },
        {
          "id": "controls-lexapi-doctrinal-judgment",
          "provider": "LexAPI",
          "method": "lex_search",
          "query": "ICT risk management tools methods processes policies DORA",
          "filters": {
            "documentType": "judgment",
            "language": "en",
            "textScope": "title-text"
          },
          "pagination": {
            "max_pages": 3,
            "pages_fetched": 1,
            "total_pages": 0
          },
          "result_count": 0,
          "material_case_count": 0,
          "status": "zero_result_within_recorded_scope"
        },
        {
          "id": "controls-lexapi-cited-by",
          "provider": "LexAPI",
          "method": "lex_cited_by",
          "query": "cited-by CELEX 32024R1774",
          "filters": {
            "limit": 100,
            "offset": 0
          },
          "pagination": {
            "total": 0,
            "returned": 0,
            "total_citations": 0,
            "unique_documents": 0,
            "returned_documents": 0,
            "complete": true
          },
          "result_count": 0,
          "material_case_count": 0,
          "status": "zero_result_within_recorded_scope"
        },
        {
          "id": "controls-oldp-exact",
          "provider": "Open Legal Data",
          "method": "GET /api/cases/search/",
          "query": "\"Regulation (EU) 2024/1774\"",
          "filters": {
            "page": 1,
            "page_size": 10
          },
          "pagination": {
            "count": 0,
            "next": null,
            "complete": true
          },
          "result_count": 0,
          "material_case_count": 0,
          "status": "zero_result_within_recorded_scope"
        },
        {
          "id": "controls-oldp-doctrinal",
          "provider": "Open Legal Data",
          "method": "GET /api/cases/search/",
          "query": "ICT risk management tools methods processes policies DORA",
          "filters": {
            "page": 1,
            "page_size": 10
          },
          "pagination": {
            "count": 0,
            "next": null,
            "complete": true
          },
          "result_count": 0,
          "material_case_count": 0,
          "status": "zero_result_within_recorded_scope"
        }
      ],
      "scope": {
        "lexapi": {
          "max_pages_requested": 3,
          "pages_fetched_per_search": 1,
          "cited_by_limit": 100,
          "cited_by_offset": 0,
          "cited_by_total": 0,
          "pagination_complete": true
        },
        "open_legal_data": {
          "pages_fetched_per_query": 1,
          "page_size": 10,
          "next": null,
          "pagination_complete": true
        }
      },
      "candidate_count": 0,
      "verified_case_count": 0,
      "emitted_edge_count": 0,
      "exclusions": [],
      "unresolved_targets": [],
      "excluded_or_pending_candidates": [],
      "non_exhaustive": true,
      "limitations": [
        "The bounded search is a documented retrieval exercise, not a negative claim that no relevant decision exists.",
        "LexAPI exact citation and lexical judgment searches and Open Legal Data exact/doctrinal query variants were checked only within the recorded pages and offsets.",
        "Zero results describe the recorded provider responses at the stated retrieval time and scope; they do not establish absence of relevant case law outside those bounds."
      ]
    },
    "intentional_absences": [
      {
        "source_id": "article-Art1-Para1",
        "edge_family": "article_to_article",
        "reason": "Its broad references to Titles II and III do not identify a defensible target article paragraph.",
        "partition": 1
      },
      {
        "source_id": "article-Art10-Para1",
        "edge_family": "article_to_article",
        "reason": "Its only citation is Article 9(2) of external Regulation (EU) 2022/2554.",
        "partition": 1
      },
      {
        "source_id": "article-Art10-Para3",
        "edge_family": "article_to_article",
        "reason": "Its only numbered citation is Article 9(2) of Regulation (EU) 2022/2554, not an internal RTS provision.",
        "partition": 1
      },
      {
        "source_id": "article-Art11-Para1",
        "edge_family": "article_to_article",
        "reason": "article-Art11-Para1 cites only Article 9(2) of external Regulation (EU) 2022/2554 and contains no internal RTS paragraph dependency.",
        "partition": 2
      },
      {
        "source_id": "article-Art12-Para1",
        "edge_family": "article_to_article",
        "reason": "article-Art12-Para1 is the self-contained duty to establish logging procedures, protocols, and tools and contains no internal article or paragraph reference.",
        "partition": 2
      },
      {
        "source_id": "article-Art14-Para1",
        "edge_family": "article_to_article",
        "reason": "article-Art14-Para1 establishes the information-in-transit control duty without citing or legally depending on another internal RTS paragraph.",
        "partition": 2
      },
      {
        "source_id": "article-Art15-Para1",
        "edge_family": "article_to_article",
        "reason": "article-Art15-Para1 is the self-contained duty to establish an ICT project-management policy and has no internal outgoing paragraph dependency.",
        "partition": 2
      },
      {
        "source_id": "article-Art16-Para1",
        "edge_family": "article_to_article",
        "reason": "article-Art16-Para1 cites only Article 2 of external Regulation (EU) No 1025/2012 and has no high-confidence internal RTS target.",
        "partition": 2
      },
      {
        "source_id": "article-Art17-Para1",
        "edge_family": "article_to_article",
        "reason": "article-Art17-Para1 cites Article 9(4)(e) of external Regulation (EU) 2022/2554; its mention of patches does not create an internal Article 10 dependency.",
        "partition": 2
      },
      {
        "source_id": "article-Art17-Para2",
        "edge_family": "article_to_article",
        "reason": "article-Art17-Para2 states entity-specific stressed-testing requirements; references to the first subparagraph remain inside this single paragraph node.",
        "partition": 2
      },
      {
        "source_id": "article-Art18-Para1",
        "edge_family": "article_to_article",
        "reason": "article-Art18-Para1 refers only to the classification under Article 8(1) of external Regulation (EU) 2022/2554 and has no internal RTS dependency.",
        "partition": 2
      },
      {
        "source_id": "article-Art19-Para1",
        "edge_family": "article_to_article",
        "reason": "article-Art19-Para1 cites only external Directive (EU) 2019/1937 and contains no high-confidence internal RTS paragraph dependency.",
        "partition": 2
      },
      {
        "source_id": "article-Art2-Para1",
        "edge_family": "article_to_article",
        "reason": "Article 9(2) is expressly a provision of Regulation (EU) 2022/2554, not internal article-Art9-Para1 or article-Art9-Para2.",
        "partition": 1
      },
      {
        "source_id": "article-Art21-Para1",
        "edge_family": "article_to_article",
        "reason": "article-Art21-Para1 refers to Article 8(1) of external Regulation (EU) 2022/2554; its remaining access-control rules are self-contained in this node.",
        "partition": 2
      },
      {
        "source_id": "article-Art23-Para1",
        "edge_family": "article_to_article",
        "reason": "article-Art23-Para1 is a self-contained assignment of detection and response roles and contains no same-act cross-reference or legally necessary paragraph dependency.",
        "partition": 3
      },
      {
        "source_id": "article-Art23-Para3",
        "edge_family": "article_to_article",
        "reason": "article-Art23-Para3 independently protects anomalous-activity recordings against tampering and unauthorised access without citing or legally depending on another same-act paragraph.",
        "partition": 3
      },
      {
        "source_id": "article-Art23-Para4",
        "edge_family": "article_to_article",
        "reason": "article-Art23-Para4 independently specifies the date, time, and type fields to log for each anomaly and contains no same-act cross-reference or indispensable paragraph dependency.",
        "partition": 3
      },
      {
        "source_id": "article-Art23-Para5",
        "edge_family": "article_to_article",
        "reason": "article-Art23-Para5 cites only Article 10(2) of external Regulation (EU) 2022/2554 and otherwise states a self-contained trigger list, so no internal article edge is emitted.",
        "partition": 3
      },
      {
        "source_id": "article-Art26-Para1",
        "edge_family": "article_to_article",
        "reason": "article-Art26-Para1 cites only Article 11(3) of external Regulation (EU) 2022/2554 and otherwise defines the response-and-recovery plan requirements without an internal dependency.",
        "partition": 3
      },
      {
        "source_id": "article-Art27-Para1",
        "edge_family": "article_to_article",
        "reason": "article-Art27-Para1 cites only Article 6(5) of external Regulation (EU) 2022/2554 and independently imposes the searchable-format requirement.",
        "partition": 3
      },
      {
        "source_id": "article-Art28-Para1",
        "edge_family": "article_to_article",
        "reason": "article-Art28-Para1 cites only Article 16(1) of external Regulation (EU) 2022/2554 and otherwise independently establishes the simplified governance framework.",
        "partition": 3
      },
      {
        "source_id": "article-Art29-Para1",
        "edge_family": "article_to_article",
        "reason": "Its only Article 16(1) citation expressly names Regulation (EU) 2022/2554 and therefore remains external rather than resolving to internal article-Art16-Para1.",
        "partition": 4
      },
      {
        "source_id": "article-Art3-Para1",
        "edge_family": "article_to_article",
        "reason": "Article 6(8) is expressly from Regulation (EU) 2022/2554, while references to points within this same graph node do not warrant self-edges.",
        "partition": 1
      },
      {
        "source_id": "article-Art30-Para1",
        "edge_family": "article_to_article",
        "reason": "Article 16(1)(a) and the later phrase 'paragraph 1 of that Article' both refer to external Regulation (EU) 2022/2554, not to an internal RTS node.",
        "partition": 4
      },
      {
        "source_id": "article-Art31-Para1",
        "edge_family": "article_to_article",
        "reason": "The sole numbered citation is external DORA Article 16(1), and the paragraph otherwise establishes its own simplified ICT risk-management requirements.",
        "partition": 4
      },
      {
        "source_id": "article-Art37-Para1",
        "edge_family": "article_to_article",
        "reason": "Its only numbered citation is external DORA Article 16(1); the acquisition, development and maintenance procedure is otherwise self-contained.",
        "partition": 4
      },
      {
        "source_id": "article-Art38-Para1",
        "edge_family": "article_to_article",
        "reason": "Its only numbered citation is external DORA Article 16(1); the ICT project-management procedure is otherwise self-contained.",
        "partition": 4
      },
      {
        "source_id": "article-Art39-Para1",
        "edge_family": "article_to_article",
        "reason": "Its only numbered citation is external DORA Article 16(1); the business-continuity-plan and scenario requirement contains no internal RTS citation or necessary paragraph dependency.",
        "partition": 4
      },
      {
        "source_id": "article-Art4-Para1",
        "edge_family": "article_to_article",
        "reason": "Its only numbered reference is Article 9(2) of external Regulation (EU) 2022/2554.",
        "partition": 1
      },
      {
        "source_id": "article-Art41-Para1",
        "edge_family": "article_to_article",
        "reason": "Article 16(1) of Regulation (EU) 2022/2554 and 'paragraph 2 of that Article' are both external DORA references; neither resolves to internal article-Art16-Para1 or article-Art41-Para2.",
        "partition": 4
      },
      {
        "source_id": "article-Art42-Para1",
        "edge_family": "article_to_article",
        "reason": "The entry-into-force clause is self-contained and contains no internal cross-reference or legally necessary dependency.",
        "partition": 4
      },
      {
        "source_id": "article-Art5-Para1",
        "edge_family": "article_to_article",
        "reason": "It is a standalone duty to establish an ICT asset-management procedure and contains no internal paragraph citation.",
        "partition": 1
      },
      {
        "source_id": "article-Art6-Para1",
        "edge_family": "article_to_article",
        "reason": "Its only citation is Article 9(2) of Regulation (EU) 2022/2554, which is not an internal RTS target.",
        "partition": 1
      },
      {
        "source_id": "article-Art7-Para2",
        "edge_family": "article_to_article",
        "reason": "It states standalone key-protection controls without an explicit internal citation or indispensable narrower target.",
        "partition": 1
      },
      {
        "source_id": "article-Art7-Para3",
        "edge_family": "article_to_article",
        "reason": "It independently requires replacement methods for lost, compromised, or damaged keys and contains no internal cross-reference.",
        "partition": 1
      },
      {
        "source_id": "article-Art7-Para4",
        "edge_family": "article_to_article",
        "reason": "It independently requires a certificate and certificate-device register and contains no internal cross-reference.",
        "partition": 1
      },
      {
        "source_id": "article-Art7-Para5",
        "edge_family": "article_to_article",
        "reason": "It is a standalone certificate-renewal duty with no explicit or legally necessary article-paragraph target.",
        "partition": 1
      },
      {
        "source_id": "article-Art8-Para1",
        "edge_family": "article_to_article",
        "reason": "Article 9(2) is expressly from Regulation (EU) 2022/2554 and therefore is not internal article-Art9-Para1 or article-Art9-Para2.",
        "partition": 1
      },
      {
        "source_id": "article-Art9-Para1",
        "edge_family": "article_to_article",
        "reason": "Its Article 9(2) citation is expressly to Regulation (EU) 2022/2554 and cannot create an RTS self-edge.",
        "partition": 1
      },
      {
        "source_id": "recital-1",
        "edge_family": "recital_to_recital",
        "reason": "This is the opening proportionality recital and has no defensible outbound dependency on another recital.",
        "partition": 1
      },
      {
        "source_id": "recital-10",
        "edge_family": "recital_to_recital",
        "reason": "recital-10 independently explains production-environment separation and the narrow testing exception; neighbouring operational recitals do not create a directed high-confidence dependency.",
        "partition": 2
      },
      {
        "source_id": "recital-11",
        "edge_family": "recital_to_recital",
        "reason": "recital-11 independently states the vulnerability-management rationale and ICT-provider monitoring duty; no other recital is a necessary premise for it.",
        "partition": 2
      },
      {
        "source_id": "recital-13",
        "edge_family": "recital_to_recital",
        "reason": "recital-13 independently explains responsible vulnerability disclosure; its shared vulnerability topic with recital-11 is insufficient for a directed high-confidence relation.",
        "partition": 2
      },
      {
        "source_id": "recital-14",
        "edge_family": "recital_to_recital",
        "reason": "recital-14 independently explains unique identity, exceptional shared accounts, and accountability; no other recital materially qualifies or grounds those statements.",
        "partition": 2
      },
      {
        "source_id": "recital-15",
        "edge_family": "recital_to_recital",
        "reason": "recital-15 independently explains ICT project governance, testing, business expertise, and reporting; adjacency to software-development recitals is not a legal dependency.",
        "partition": 2
      },
      {
        "source_id": "recital-16",
        "edge_family": "recital_to_recital",
        "reason": "recital-16 independently explains secure software integration, security testing, and source-code review; topical continuity with recital-15 does not establish a directed recital relation.",
        "partition": 2
      },
      {
        "source_id": "recital-18",
        "edge_family": "recital_to_recital",
        "reason": "recital-18 introduces the incident-policy baseline; later recitals 19 to 22 build on it, but recital-18 itself neither depends on nor qualifies another recital strongly enough for a directed high-confidence edge.",
        "partition": 3
      },
      {
        "source_id": "recital-24",
        "edge_family": "recital_to_recital",
        "reason": "The recital grounds its sector-specific overlay in three external sectoral regulations and does not express a sufficiently strong outgoing dependency on another recital; nearby general continuity recitals are only thematic candidates.",
        "partition": 4
      },
      {
        "source_id": "recital-25",
        "edge_family": "recital_to_recital",
        "reason": "The searchable-format rationale is self-contained and neither develops nor qualifies another recital with high confidence.",
        "partition": 4
      },
      {
        "source_id": "recital-27",
        "edge_family": "recital_to_article",
        "reason": "The recital explains why the ordinary and simplified DORA mandates were packaged in one RTS; it does not supply a narrow substantive rule for any internal article paragraph.",
        "partition": 4
      },
      {
        "source_id": "recital-27",
        "edge_family": "recital_to_recital",
        "reason": "Its legislative-packaging and simultaneous-applicability rationale is self-contained and has no high-confidence outgoing relation to another recital.",
        "partition": 4
      },
      {
        "source_id": "recital-28",
        "edge_family": "recital_to_article",
        "reason": "The recital records submission of the draft RTS and consultation with ENISA, not a substantive requirement implemented by an article paragraph.",
        "partition": 4
      },
      {
        "source_id": "recital-28",
        "edge_family": "recital_to_recital",
        "reason": "The recital independently identifies the draft's institutional provenance; the later procedural steps are correctly expressed by recital-29's outgoing edge back to it.",
        "partition": 4
      },
      {
        "source_id": "recital-29",
        "edge_family": "recital_to_article",
        "reason": "All numbered Article 54 and Article 37 citations are to external ESA regulations, and the remaining text is procedural history rather than an internal RTS control.",
        "partition": 4
      },
      {
        "source_id": "recital-3",
        "edge_family": "recital_to_recital",
        "reason": "It states the baseline roles and non-compliance principle; later recitals qualify it, but it has no strong outbound recital dependency.",
        "partition": 1
      },
      {
        "source_id": "recital-30",
        "edge_family": "recital_to_recital",
        "reason": "The existing recital-19 to recital-30 context edge already expresses the one-way setting for the data-protection example; adding a reciprocal relation from recital-30 would duplicate that semantic link.",
        "partition": 4
      },
      {
        "source_id": "recital-9",
        "edge_family": "recital_to_recital",
        "reason": "recital-9 independently explains encryption, cryptanalysis, and compensating cryptographic controls; no other recital supplies a necessary premise or express qualification.",
        "partition": 2
      }
    ],
    "source_provenance": {
      "authority": "EUR-Lex / Official Journal of the European Union",
      "alignment_date": "2026-08-05",
      "source_files": [
        {
          "filename": "html"
        },
        {
          "filename": "md"
        },
        {
          "filename": "pdf"
        }
      ],
      "verbatim_method": "canonical EUR-Lex HTML parsed with source-region and cell-boundary preservation"
    },
    "run_audit": {
      "skill": "eu-legal-to-json@3.5.1",
      "active_config_path": "/opt/data/config.yaml",
      "max_concurrent_children": 8,
      "child_timeout_seconds": 1800,
      "stages": [
        {
          "stage": "initial_mapping",
          "status": "pass",
          "edge_count": 207,
          "intentional_absence_count": 57,
          "partition_count": 4,
          "global_wave_size": 8
        },
        {
          "stage": "qa_round1",
          "status": "pass",
          "edge_count": 208,
          "intentional_absence_count": 57,
          "partition_count": 4,
          "global_wave_size": 8,
          "delta_counts": {
            "remove": 23,
            "update": 18,
            "add": 24
          }
        },
        {
          "stage": "qa_round2",
          "status": "pass",
          "edge_count": 208,
          "intentional_absence_count": 57,
          "partition_count": 4,
          "global_wave_size": 8,
          "delta_counts": {
            "remove": 0,
            "update": 0,
            "add": 0
          }
        },
        {
          "stage": "source_fidelity_reqa",
          "status": "pass",
          "report": "dora-controls_source_reqa.json",
          "report_sha256": "7349beabb4c90225974131aea7b8dc5ad322bf02a788d038f4dd3df9da338c4c",
          "source_graph_sha256": null
        },
        {
          "stage": "case_law_enrichment",
          "status": "pass",
          "sources_queried": [
            "lexapi",
            "open_legal_data"
          ],
          "verified_case_count": 0,
          "emitted_edge_count": 0
        },
        {
          "stage": "pre_delivery_gates",
          "status": "pass",
          "checks": [
            "akn4eu_metadata",
            "annex_absence_coherent",
            "article_type_uri",
            "attribution_records_complete",
            "attribution_schema",
            "canonical_projection_symmetry",
            "case_law_both_sources",
            "case_law_counts",
            "consistency_status",
            "edge_identity",
            "edge_ids_unique",
            "high_confidence_only",
            "intentional_absences_present",
            "metadata_node_counts",
            "nested_source_structure",
            "no_ag_opinion_as_case_node",
            "no_reasoning_template_over_30pct",
            "nonempty_node_text",
            "official_title_and_conclusions",
            "paragraph_kind_no_mixing",
            "reasoning_unique",
            "relation_arrays",
            "relation_counts_derived",
            "relation_vocabulary",
            "source_structure_immutable",
            "source_text_immutable",
            "top_level_arrays",
            "top_relation_arrays",
            "unique_node_ids"
          ]
        }
      ],
      "waves": [
        {
          "stage": "source_fidelity_qa",
          "useful_remaining_tasks": 2,
          "batch_size": 2,
          "formula": "min(8, 2) = 2",
          "smaller_wave_reason": "Only two independent source acts existed; no dummy or duplicate tasks were created.",
          "delegation_id": "deleg_e886b236",
          "status": "fail",
          "result": "One worker completed with two structural blocking findings; one worker timed out after writing a fail report. The single permitted repair cycle was entered."
        },
        {
          "stage": "source_fidelity_reqa",
          "useful_remaining_tasks": 2,
          "batch_size": 2,
          "formula": "min(8, 2) = 2",
          "smaller_wave_reason": "Exactly two repaired source graphs required independent re-QA; no dummy or duplicate tasks were created.",
          "delegation_id": "deleg_aca42772",
          "status": "pass",
          "result": "Both repaired source graphs passed independent child re-QA with no blocking failures: DORA 15/15 checks, DORA Controls 21/21 checks. Source-graph input hashes matched the bound contexts.",
          "dora_report_sha256": "d5459a9b4992129bcc4858d1ad6dbccbe06fcf87e64dcd5dfa48b7dbff98668b",
          "dora_controls_report_sha256": "7349beabb4c90225974131aea7b8dc5ad322bf02a788d038f4dd3df9da338c4c"
        },
        {
          "stage": "initial_semantic_mapping",
          "useful_remaining_tasks": 8,
          "batch_size": 8,
          "formula": "min(8, 8) = 8",
          "smaller_wave_reason": null,
          "delegation_id": "deleg_b962e561",
          "status": "pass",
          "result": "All eight mapping partitions passed their local contracts. Global merge passed after one schema-alias integration retry and one target-specific reasoning repair affecting 95 DORA edges without changing edge identity; the independent QA waves review the repaired post-merge graph.",
          "dora_edge_count": 648,
          "dora_controls_edge_count": 207
        },
        {
          "stage": "qa_round1",
          "useful_remaining_tasks": 8,
          "batch_size": 8,
          "formula": "min(8, 8) = 8",
          "smaller_wave_reason": null,
          "delegation_id": "deleg_bbc705a4",
          "reviewer_rotation": "new independent agents; context order p2,p3,p4,p1 for each act",
          "status": "pass",
          "result": "All eight QA1 literal deltas passed local validation and were applied to immutable baselines. DORA: 648 to 676 edges (remove 11, update 27, add 39); DORA Controls: 207 to 208 edges (remove 23, update 18, add 24). One target-specific reasoning repair to 19 DORA update records was applied after the global template gate and is subject to QA2.",
          "dora_output_sha256": "965f3c583ab9e1a727a123fd38a78ec5b246b978cc04e2d2881f8b27a4452b70",
          "dora_controls_output_sha256": "0434cbddba782bcc190b31cdbb7a022d174e4f0599dfbf0af8009c57d69030ce"
        },
        {
          "stage": "qa_round2",
          "useful_remaining_tasks": 8,
          "batch_size": 8,
          "formula": "min(8, 8) = 8",
          "smaller_wave_reason": null,
          "delegation_id": "deleg_36625790",
          "reviewer_rotation": "new independent agents; context order p3,p4,p1,p2 for each act",
          "status": "pass",
          "result": "All eight QA2 deltas passed local and global validation. DORA: 676 to 724 edges (remove 3, update 0, add 51); DORA Controls: null delta, 208 edges retained. All coverage records and intentional absences were regenerated from the post-delta state.",
          "dora_output_sha256": "f46b48d402b58bad009e6a14b2a96e483f656029e50e08ee83adf7d14e0195a2",
          "dora_controls_output_sha256": "f9bbded7457c8a777c026f9efd79f5519aee89d14ca2d1a9ba1c09b253b5bd47"
        },
        {
          "stage": "case_law_enrichment",
          "useful_remaining_tasks": 2,
          "batch_size": 2,
          "formula": "min(8, 2) = 2",
          "smaller_wave_reason": "Exactly two final act graphs require bounded LexAPI and Open Legal Data case-law enrichment.",
          "delegation_id": "deleg_7444aef7",
          "status": "pass",
          "result": "Both bounded-search enrichments passed independent source QA after minor attribution/pinpoint corrections. DORA: 24 cited-by documents reviewed, no material judgment; AG Opinion 62023CC0256 excluded with official type, ECLI and footnote pinpoints. DORA Controls: zero bounded search and cited-by results. Both acts retain zero case-law nodes and judicial edges.",
          "dora_qa_sha256": "ae6473f6f581f804d5161b7120eb3dd35404b893ef65b9a8c04255fc002cc395",
          "dora_controls_qa_sha256": "25191c83ad5cf2ff8a2419b89724ed149569479e274d53c84b40a584ca494364"
        }
      ]
    },
    "source_structure_enrichment": {
      "status": "pass",
      "method": "independent stdlib DOM ancestry over canonical EUR-Lex HTML",
      "subunit_events": 404,
      "nested_subunit_events": 133,
      "logical_article_paragraphs": 111,
      "multi_direct_source_paragraph_groups": 22,
      "fields": [
        "akn4eu_sub_units.depth",
        "akn4eu_sub_units.parent_marker",
        "akn4eu_sub_units.path",
        "akn4eu_source_paragraphs"
      ]
    },
    "official_long_title": "COMMISSION DELEGATED REGULATION (EU) 2024/1774 of 13 March 2024 supplementing Regulation (EU) 2022/2554 of the European Parliament and of the Council with regard to regulatory technical standards specifying ICT risk management tools, methods, processes, and policies and the simplified ICT risk management framework (Text with EEA relevance)",
    "akn4eu_conclusions": [
      {
        "sequence": 1,
        "akn4eu_role": "binding_formula",
        "text": "This Regulation shall be binding in its entirety and directly applicable in all Member States.",
        "source_line_start": 7036,
        "source_line_end": 7036
      },
      {
        "sequence": 2,
        "akn4eu_role": "place_date",
        "text": "Done at Brussels, 13 March 2024.",
        "source_line_start": 7037,
        "source_line_end": 7037
      },
      {
        "sequence": 3,
        "akn4eu_role": "signature",
        "text": "For the Commission",
        "source_line_start": 7039,
        "source_line_end": 7041
      },
      {
        "sequence": 4,
        "akn4eu_role": "signature",
        "text": "The President",
        "source_line_start": 7042,
        "source_line_end": 7044
      },
      {
        "sequence": 5,
        "akn4eu_role": "signature",
        "text": "Ursula VON DER LEYEN",
        "source_line_start": 7045,
        "source_line_end": 7046
      }
    ],
    "akn4eu_annex_absence": {
      "status": "intentional",
      "reason": "The canonical EUR-Lex body contains no structural annex after the final article.",
      "canonical_annex_regions": 0
    }
  },
  "schema": "akn4eu/legal-mapping@1.0.0",
  "contract_profile": "legacy_syntax_only",
  "migration": {
    "mode": "syntax_only",
    "source_path": "2024-03-13_EU_Commission_DORA_Delegated_Regulation_2024-1774_recital_article_case_law_mapping.md",
    "source_schema": null,
    "semantic_enrichment_performed": false,
    "preservation": {
      "pass": true,
      "node_count_before": 141,
      "node_count_after": 141,
      "node_occurrence_count_before": 141,
      "node_occurrence_count_after": 141,
      "duplicate_node_occurrences_before": 0,
      "duplicate_node_occurrences_after": 0,
      "edge_count_before": 208,
      "edge_count_after": 208,
      "nodes_added": 0,
      "nodes_removed": 0,
      "edges_added": 0,
      "edges_removed": 0,
      "relations_reclassified": 0,
      "endpoints_changed": 0,
      "semantic_fields_authored": 0,
      "verbatim_and_existing_fields_preserved": true
    },
    "integrity": {
      "preserved_semantics_sha256": "1bb0fa344c2fa5199e0ff2e979a58e1ddcc60ad78238d72a207ac1a5a6db8a26",
      "migrated_payload_sha256": "6d6f6308bc77812564d36df9738c6c051618379ae8f0c834df3f0c1b92f21850",
      "source_artifact_sha256": "76c5924ff41832b1eb2c0a404bff98e5c8317996473e2fc791f22d686af5d792",
      "markdown_wrapper_sha256": "0aaf90f60d92055c65f0cfdb27fb8048ceef493ce7b1baa533e76cd2dd0950e8"
    }
  }
}
```
