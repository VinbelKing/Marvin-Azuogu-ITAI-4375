# Assignment 12 — Evaluating Federated Learning Case Studies in Healthcare

**Course:** ITAI 4375 — AI in Healthcare  
**Institution:** Houston City College  
**Instructor:** Dr. Doreen Rosenstrauch  
**Date:** April 27, 2026

## Overview

Evaluation of two landmark federated learning case studies that demonstrate privacy-preserving AI model training across healthcare institutions. Covers methodology, findings, comparative analysis, benefits, challenges, and future impact.

## What Is Federated Learning?

Federated learning enables multiple institutions to collaboratively train AI models without centralizing raw patient data. Each institution trains locally; only model parameters are shared across the network. This preserves HIPAA compliance while enabling robust, generalizable models from diverse patient populations.

## Case Study 1: Privacy-First Health Research (Sadilek et al., 2021)

- **Published in:** NPJ Digital Medicine
- **Goal:** Prove federated learning + differential privacy can achieve accuracy comparable to centralized models without prohibitive computational cost
- **Data:** Multi-site clinical and epidemiological records, patient demographics, medical histories, real-time health signals
- **Key Finding:** First study to apply modern federated learning with differential privacy to clinical/epidemiological research — privacy and accuracy are not mutually exclusive

## Case Study 2: COVID-19 Mortality Prediction (Vaid et al., 2021)

- **Published in:** JMIR Medical Informatics
- **Goal:** Predict 7-day mortality in hospitalized COVID-19 patients without sharing raw EHR data
- **Data:** 4,029 patients across 5 hospitals, Mount Sinai Health System, NYC
- **Models:** Logistic regression (LASSO) and multilayer perceptron (MLP) neural networks
- **Key Finding:** Federated MLP outperformed local models at 4 of 5 hospitals and matched pooled (centralized) model performance; COVID-19 mortality risk factors identified across institutions (pneumonia, diabetes, cancer history)

## Comparison

| Dimension | Sadilek et al. | Vaid et al. |
|-----------|----------------|-------------|
| Focus | General methodology | Specific clinical task |
| Data scope | Diverse health studies | EHR data, single health system |
| Privacy method | Differential privacy | Federated aggregation |
| Contribution | Foundational proof-of-concept | Applied clinical utility |

## Challenges and Limitations

- **Data heterogeneity:** Different coding systems and documentation practices across institutions
- **Privacy leakage risk:** Model parameter updates can still leak information; differential privacy adds overhead
- **Infrastructure requirements:** Robust governance, technical expertise, and inter-site protocols needed
- **Regulatory uncertainty:** Guidelines for federated model validation and accountability still developing

## Future Impact

- Accelerate medical discoveries via larger, diverse patient populations
- Democratize AI research participation for smaller institutions
- Resolve the privacy paradox: use data for research while protecting individual privacy
- Enable rapid pandemic response without data-sharing agreement delays

## Concepts Covered

- Federated learning architecture and aggregation protocols
- Differential privacy in healthcare AI
- LASSO and MLP neural network model comparison
- Multi-institutional EHR research design
- Privacy-preserving machine learning frameworks
- Healthcare AI governance and regulatory considerations
