# Assignment 9 — Designing Reinforcement Learning Scenarios in Healthcare

**Course:** ITAI 4375 — AI in Healthcare  
**Institution:** Houston City College  
**Instructor:** Dr. Doreen Rosenstrauch

## Overview

Design of a Reinforcement Learning (RL) system for automated insulin dosing in ICU patients with Type 1 Diabetes Mellitus (T1DM). Covers the full RL framework specification including state space, action space, and reward function design.

## Clinical Context

ICU patients with T1DM require precise, continuous insulin management. Glycemic dysregulation in the ICU increases mortality risk. An RL-based "artificial pancreas" system could optimize dosing dynamically in response to real-time patient data.

## RL Framework Design

### State Space
Patient physiological signals observable at each timestep:
- Current blood glucose level
- Rate of glucose change (trend)
- Recent insulin on board
- Meal/nutritional intake
- Vital signs (heart rate, blood pressure)

### Action Space
Discrete insulin dosing decisions:
- Increase basal rate
- Maintain current basal rate
- Decrease basal rate
- Administer correction bolus

### Reward Function
- **Positive reward:** Blood glucose within target range (80–180 mg/dL)
- **Negative reward (penalty):** Hypoglycemia (<70 mg/dL) — heavily penalized due to life-threatening risk
- **Negative reward:** Hyperglycemia (>180 mg/dL)

## Key Challenge: Safety During Learning

RL systems learn through trial and error, which is unacceptable when errors can cause patient harm. Mitigation strategy: require pre-deployment training exclusively on the **UVA/Padova metabolic simulator** — a validated in-silico patient model — before any human deployment.

## Concepts Covered

- Reinforcement learning fundamentals: state, action, reward, policy
- Clinical RL applications in closed-loop drug delivery
- Artificial pancreas systems
- Safety-constrained RL design
- UVA/Padova simulator for diabetes modeling
