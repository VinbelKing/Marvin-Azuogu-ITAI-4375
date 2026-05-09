# Assignment 5 — Evaluating Prognostic Models

**Course:** ITAI 4375 — AI in Healthcare  
**Institution:** Houston City College  
**Instructor:** Dr. Doreen Rosenstrauch

## Overview

Critical evaluation of a multimodal machine learning model designed to predict 5-year mortality following Percutaneous Coronary Intervention (PCI). The study integrates imaging, clinical notes, and structured data using state-of-the-art ML architectures.

## Study Details

- **Clinical Task:** Predict 5-year all-cause mortality after PCI (cardiac stent procedure)
- **Dataset:** 10,353 patients
- **Model Architecture:** Multimodal fusion combining:
  - **CLIP** — for medical imaging analysis (coronary angiography)
  - **BioBERT** — for clinical notes / unstructured text processing
  - **LightGBM** — for structured tabular clinical data
  - **SHAP** — for model explainability (SHapley Additive exPlanations)

## Performance

| Metric | Value |
|--------|-------|
| AUC-ROC | 0.814 |

## Strengths

- Leverages complementary data modalities for richer patient representation
- SHAP values provide clinician-interpretable feature importance
- Large patient cohort improves generalizability
- Addresses a clinically meaningful long-term outcome

## Weaknesses

- Multimodal complexity increases computational cost and deployment barriers
- Missing modality handling not fully addressed
- Single-institution data may limit external validity
- Long follow-up period introduces confounding variables

## Concepts Covered

- Prognostic model design and evaluation
- Multimodal machine learning (imaging + text + tabular fusion)
- AUC-ROC interpretation for binary classification
- SHAP explainability for clinical AI
- Strengths and limitations critique of published ML studies
