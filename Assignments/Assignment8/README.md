# Assignment 8 — Critiquing an NLP Study in Healthcare

**Course:** ITAI 4375 — AI in Healthcare  
**Institution:** Houston City College  
**Instructor:** Dr. Doreen Rosenstrauch

## Overview

Critical analysis of a study applying Natural Language Processing (NLP) — specifically BERT-based models — to Electronic Health Records (EHRs). Evaluates benefits, limitations, and whether the benefits outweigh the risks for clinical deployment.

## Study Focus

- **Technology:** BERT (Bidirectional Encoder Representations from Transformers) applied to clinical text in EHRs
- **Application:** Extraction of clinically relevant information from unstructured clinical notes for diagnosis support and early detection

## Benefits

- **Efficiency:** Automates extraction of insights from vast volumes of unstructured clinical documentation
- **Early Detection:** NLP models can identify patterns in notes predictive of conditions before formal diagnosis
- **Scalability:** One trained model can process records across large patient populations
- **Reduced Clinician Burden:** Surfaces relevant history without manual chart review

## Limitations

- **Privacy Gaps:** Training on EHR data raises HIPAA compliance concerns; de-identification is imperfect
- **Generalizability:** Models trained on one institution's note style may underperform at others with different documentation practices
- **Bias in Training Data:** Historical documentation disparities may encode racial, gender, or socioeconomic biases
- **Interpretability:** BERT's black-box nature makes clinical validation difficult

## Conclusion

Benefits outweigh risks when robust safeguards are in place: rigorous de-identification, diverse training datasets, regular bias auditing, and clinician oversight. NLP should augment, not replace, clinical judgment.

## Concepts Covered

- BERT and transformer-based NLP architecture
- Clinical NLP applications in EHR systems
- HIPAA and patient data privacy in AI
- Bias in clinical NLP models
- Framework for critiquing AI/ML studies in healthcare
