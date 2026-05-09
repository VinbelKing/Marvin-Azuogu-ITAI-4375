# Assignment 4 — Evaluating Results From a Diagnostic Study

**Course:** ITAI 4375 — AI in Healthcare  
**Institution:** Houston City College  
**Instructor:** Dr. Doreen Rosenstrauch

## Overview

Critical evaluation of the TriOx liquid biopsy blood test developed by researchers at Oxford. Analysis covers diagnostic performance metrics including sensitivity, specificity, and the clinical implications of false positive and false negative results.

## Study: TriOx Liquid Biopsy

- **Developer:** University of Oxford
- **Test Type:** Liquid biopsy (blood-based cancer detection)
- **Technology:** TAPS (Tumor-informed Analysis of cell-free DNA from Plasma) combined with machine learning
- **Cancers Detected:** 6 cancer types

## Diagnostic Performance

| Metric | Value |
|--------|-------|
| Sensitivity | 94.9% |
| Specificity | 88.8% |

## Key Analysis

- **False Positives:** Patients without cancer incorrectly flagged as positive — leads to unnecessary follow-up testing, patient anxiety, and healthcare costs
- **False Negatives:** Patients with cancer missed by the test — delayed diagnosis, disease progression, worse outcomes
- **Clinical Tradeoff:** High sensitivity prioritized to minimize missed cancers; specificity tradeoff acceptable given consequences of delayed cancer diagnosis

## Concepts Covered

- Diagnostic test evaluation framework (sensitivity, specificity, PPV, NPV)
- Liquid biopsy and cell-free DNA (cfDNA) technology
- Machine learning applied to cancer biomarker detection
- Clinical decision-making under diagnostic uncertainty
- Implications of false positives vs. false negatives in oncology screening
