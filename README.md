# AI-SE-Week7_AI_ETHICS_Assignment

## Overview

This repository contains my completed Week 7 AI Ethics assignment for the AI and Society course. The focus is on identifying and addressing algorithmic bias in AI systems, analyzing GDPR’s impact on AI, exploring fairness in facial recognition and hiring algorithms, and proposing ethical policies for AI use in healthcare.

## Contents

### 1. `AIFairness360.ipynb`

A Jupyter Notebook analyzing fairness in a real-world AI application using the COMPAS dataset.

- **Objective**: Evaluate racial bias in recidivism risk predictions.
- **Key Findings**:
  - Statistical Parity Difference: `-0.1287`
  - Disparate Impact: `0.8099`
  - False Positive Rate Disparities between groups.
- **Remediation Steps**:
  - Reweighing training data
  - Adversarial debiasing
  - Post-processing calibration

> Tools used: AIF360 (IBM), Python, fairness metrics

### 2. `BONUS.pdf`

A policy guideline document titled **"Ethical AI Use in Healthcare"**, providing a framework for ensuring AI applications in medicine are trustworthy, fair, and patient-centric.

- **Main Principles**:
  - Patient Consent Protocols
  - Bias Mitigation Strategies
  - Transparency Requirements
- **Suggested Actions**:
  - Use explainable models
  - Conduct regular bias audits
  - Involve clinicians and regulators

> Intended for use by healthcare providers, developers, and policymakers.

### 3. `Week7_AI_Ethics_Assignment.txt` *(content provided via ChatGPT)*

A complete written submission addressing all assignment prompts, including:

- Definitions of **algorithmic bias**
- Difference between **transparency** and **explainability**
- Impact of **GDPR**
- Case studies: **Amazon's hiring tool**, **Facial recognition in policing**
- Fairness metrics: **Statistical Parity**, **Equal Opportunity**, **Predictive Parity**
- Personal ethical reflection and bonus policy guidelines

> This serves as the main report tying together the practical, theoretical, and ethical aspects of the week’s work.

---

## Tools & Libraries Used

- Python
- Jupyter Notebook
- IBM AI Fairness 360 Toolkit (AIF360)
- PDF Authoring Tools (for BONUS guideline)

## Author

**Klaas Matlou**  
Student at Power Learn Project  
Week 7 – AI & Society Ethics Module

## Submission Notes

This assignment is submitted as part of the AI Ethics module, focusing on fairness, transparency, responsible AI, and compliance with legal frameworks like GDPR.

---