# llm_ontology

## Overview

This repository provides supplementary materials accompanying the research paper:

**Transforming Unstructured Textual Feedback into Intervention-Ready Decision Knowledge through Scalable LLM-based Ontology-Guided Risk Operationalization**

The study presents a scalable decision-support framework that transforms large volumes of unstructured textual feedback into a quantified organizational problem space. The proposed methodology combines ontology-guided aspect-based sentiment analysis, embedding-assisted subaspect discovery, calibrated LLM-based severity estimation, and risk operationalization to identify and prioritize intervention opportunities.

The framework reconstructs organizational problem structures from textual evaluations and converts them into intervention-ready decision knowledge through a transparent and reproducible analytical workflow.

---

## Highlights of the manuscript

- Converts large-scale unstructured textual feedback into quantified, intervention-ready decision artifacts
- Proposes a scalable ontology-guided LLM-supported ABSA pipeline with full traceability
- Operationalizes Ishikawa-style root cause representation for organizational risk management
- Combines aspect polarity, frequency, severity and exposure into a structured risk priority index
- Demonstrates domain-agnostic applicability beyond the higher education case study

---

## Main steps of the algoritm

- Ontology-guided decomposition of complex textual feedback into atomic opinion units.
- Hierarchical reconstruction of organizational problem spaces through subaspect discovery and taxonomy consolidation.
- LLM-based calibrated expert assessment for severity estimation.
- Risk and impact operationalization supporting intervention prioritization.
- Scalable and reproducible architecture applicable beyond higher education.

---

## Repository Contents

### Prompts

This repository includes the three principal prompt templates used in the analytical framework.

#### 1. Ontology-Guided LLM-Based ABSA

This prompt performs multiple tasks simultaneously on raw textual feedback:

- decomposition of complex feedback into atomic opinion units,
- assignment of each opinion unit to a predefined ontology aspect,
- sentiment polarity classification,
- sentiment score estimation.

The prompt serves as the entry point of the analytical pipeline by transforming unstructured, multi-topic textual feedback into structured and traceable opinion-level data.

#### 2. Subaspect Discovery and Taxonomy Consolidation

After embedding-based semantic grouping, this prompt supports the discovery of latent subproblems within each ontology aspect.

The prompt is used in two consecutive stages:

- **Discovery:** identification and naming of candidate subaspects from semantically similar opinion groups,
- **Consolidation:** merging overlapping or conceptually equivalent subaspects into a coherent taxonomy.

The resulting taxonomy extends the ontology with data-driven, domain-specific problem categories.

#### 3. Calibrated LLM Expert for Severity Estimation

This prompt implements a calibrated expert assessment procedure for estimating the severity of identified problem categories.

The prompt provides:

- representative opinion examples,
- severity scale definitions,
- evaluation criteria,
- institutional and organizational consequence descriptions.

Using multi-shot prompting, the LLM acts as a calibrated expert evaluator and assigns severity scores together with explanatory rationales. These severity estimates are subsequently used in the risk operationalization stage of the framework.

### Supplementary Tables

#### Complete Risk and Impact Assessment Table

This repository contains the complete aspect–subaspect assessment table used in the study. The table extends the condensed ranking presented in Table 5 of the paper by providing results for all identified problem categories.

For each aspect–subaspect combination, the dataset includes:

- `Number_of_opinions` – number of associated atomic opinion units,
- `Courses_affected` – number of affected entities,
- `W_as` – normalized prevalence score,
- `H_as` – exposure indicator, number of affected users,
- `S_as_sentiment` – sentiment-based severity estimate,
- `S_as_LLM` – calibrated LLM expert severity estimate,
- `rationale_short` – condensed expert rationale,
- `S_as` – combined severity score,
- `R_as` – risk score,
- `I_as` – impact score,
- `L_as` – recommended intervention level.

The table provides the complete quantified problem space reconstructed by the framework and serves as the basis for intervention prioritization and decision-support applications.

---

## Related Publication

**Citation**

*Citation information will be added after publication.*

**Paper**

*DOI and publisher link will be added after publication.*

---

## How to Cite

Please cite the associated publication:

```text
Citation will be added after publication.
```

If using materials from this repository independently, please also cite this repository:

```text
Repository citation will be added after publication.
```

---

## License

License information will be added after publication.

---

## Contact

Contact information will be added after peer-review.
