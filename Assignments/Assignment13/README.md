# Assignment 13 — Identifying Risks in AI Healthcare Case Studies

**Course:** ITAI 4375 — AI in Healthcare  
**Institution:** Houston City College  
**Instructor:** Dr. Doreen Rosenstrauch  
**Date:** May 4, 2026

## Overview

Identification and analysis of three major risks of AI deployment in healthcare, with a deep dive into algorithmic bias as the most critical risk. Concludes with a cost-benefit assessment of AI in healthcare.

## Three Major Risks of AI in Healthcare

### Risk 1: Data Privacy and Security Breaches

AI systems collect vast amounts of sensitive patient data (medical histories, genetic information, personal identifiers), making them prime cyberattack targets. Specific threat vectors include:

- **Membership inference attacks** — determine if a person was in the training data
- **Reconstruction attacks** — recreate original patient data from model outputs
- **Property inference attacks** — learn algorithmic properties to exploit the system
- **Shadow IT risk** — employees using unvetted tools (e.g., ChatGPT) with PHI

**Example impact:** A 100,000-patient breach leads to identity theft, insurance fraud, regulatory penalties, and irreparable institutional trust damage.

### Risk 2: Algorithmic Bias and Discrimination

AI models trained on biased or unrepresentative data amplify existing healthcare inequities. Bias is particularly dangerous because AI outputs appear objective, obscuring discriminatory patterns embedded during training.

**Example impact:** A diagnostic AI trained on one racial group's imaging data underperforms for minority patients, causing delayed diagnoses. An organ transplant AI trained on cost-proxy data prioritizes patients by ability to pay rather than clinical need.

### Risk 3: Lack of Transparency and Accountability

"Black box" AI systems cannot explain their recommendations, making it impossible for clinicians to validate outputs or for regulators to assign liability when harm occurs.

**Example impact:** A cardiologist acts on an unexplained AI recommendation for surgery; if the surgery causes harm, responsibility is unclear — is it the AI developer, the hospital, or the clinician?

## Deep Dive: Algorithmic Bias as the Most Critical Risk

Algorithmic bias is identified as the most important risk for three reasons:

1. **Structural harm:** Violates healthcare's core equity principle — equal quality care regardless of background
2. **Silent propagation:** Unlike data breaches, biased decisions persist undetected for years, affecting thousands of patients
3. **Systemic erosion:** Discriminated communities distrust and avoid AI-powered care, widening existing disparities

### Mitigation Strategies

- Collect diverse, representative training data across racial, ethnic, socioeconomic, and geographic groups
- Conduct regular bias audits and discrimination testing
- Build diverse development teams (clinicians, data scientists, ethicists, patient advocates)
- Maintain transparent documentation of training data and model design
- Require clinical validation of AI recommendations before action

## Conclusion: Benefits vs. Risks

Benefits outweigh risks **when appropriate safeguards are proactively implemented** — not reactively after harm. AI's potential to improve diagnostic accuracy, enable early detection, expand access to underserved areas, and reduce clinician burden is real and significant. However, governance frameworks, security measures, bias testing, and accountability structures must be in place before deployment.

## Concepts Covered

- Healthcare AI risk taxonomy (privacy, bias, transparency)
- Adversarial attacks on ML models in clinical settings
- Algorithmic fairness and health equity
- Explainability requirements for clinical AI
- AI governance and responsible deployment frameworks
