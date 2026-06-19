# TRUST-AST: Reference Framework and Replication Package

This repository contains the replication package for the systematic literature review and conceptual framework reported in:
> M. N. Fazil and N. Pombo *Trust-Centered Architecture for Agentic Testing*, submitted to the **Journal of Systems and Software (JSS)**.

It provides all artefacts required to inspect and reproduce the study selection, coding, and synthesis reported in the manuscript.

## Repository Contents

* **TRUST_AST_PRISMA_Dataset.csv**
  The complete systematic screening log covering all 211 literature records evaluated during the study selection. It documents duplicate elimination flags, title/abstract screening decisions, full-text eligibility status, and explicit, documented exclusion reasons for each filtered-out study.

* **Thematic analysis sheets.xlsx**
  The master data extraction and synthesis spreadsheet containing the structured evaluation of the 36 included primary studies. It tracks the raw taxonomy classifications including testing lifecycle phases, agentic coordination modalities, explainability (XAI), human oversight, and technical safety guardrails.

* For the exact Boolean search strings, multi-database query construction steps, and digital library indexing protocols, please refer directly to **Section 2.1** of the main manuscript.

## How to Use This Package

* **To inspect the study selection process:** Open `TRUST_AST_PRISMA_Dataset.csv` and filter by the screening decision columns to reproduce the step-by-step PRISMA flow attrition counts reported in Section 2.3 of the paper.
* **To inspect the thematic synthesis:** Open `Thematic analysis sheets.xlsx` to trace how each primary study was categorized and mapped to construct the core dimensions of the TRUST-AST framework discussed in Section 3.

## Contact

For any questions regarding this replication package or the data extraction schema, please contact:
* Muhammad Noman Fazil — m.noman.fazil@ubi.pt
