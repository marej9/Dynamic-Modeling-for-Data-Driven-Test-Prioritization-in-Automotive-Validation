# Dynamic-Modeling-for-Data-Driven-Test-Prioritization-in-Automotive-Validation
Master's Thesis at BMW and ITR 

## Overview
This project presents a data-driven approach to modeling and optimizing the validation process in automotive software systems.  
The goal is to prioritize test cases based on their estimated risk, enabling more efficient allocation of limited testing resources.

The work is based on my Master's thesis at the Technical University of Munich in collaboration with an industrial partner.

---

## Objective
Modern automotive systems generate large volumes of validation data, but these are rarely used systematically.  
This project aims to:

- Model the validation process as a **probabilistic dynamic system**
- Estimate **defect occurrence** and **severity**
- Combine both into an **expected risk score**
- Enable **risk-based test prioritization**

---

## Methodology

### Data Processing
- Analysis of historical test and defect data
- Feature engineering for tabular validation datasets
- Construction of training and evaluation datasets

### Modeling Approach
The validation process is decomposed into:

- **Defect Occurrence Model** (classification)
- **Severity Estimation Model** (regression / ranking)
- **Risk Aggregation** → Expected risk score

### Machine Learning Models
- Random Forest (baseline)
- Prior-based probabilistic models
- Transformer-based tabular models (e.g. PFN)
- Hybrid model combining specialized components

---

## Results

- Tree-based models perform strongly for defect prediction  
- Transformer-based models improve severity estimation  
- Hybrid approaches achieve the best overall performance  

The results show that **data-driven prioritization significantly improves early detection of critical defects**.

---

## Key Takeaways

- Validation processes can be effectively modeled as **probabilistic systems**
- Separating occurrence and severity improves interpretability
- Hybrid ML approaches outperform single-model solutions
- Data-driven prioritization enables **more efficient testing under constraints**

---

## Tech Stack
- Python
- Scikit-learn
- PyTorch
- Tabular ML (PFN / Transformers)
- Data processing & analysis tools

---

## Context
- Master's Thesis, TUM (2026)
- Chair of Information-Oriented Control
- Industry collaboration: BMW AG

---

## Related Work
For a more general study on modeling dynamical systems:
👉 [Modeling Dynamic Systems Repository](https://github.com/marej9/Modeling_Dynamic_Systems)

---

## 👤 Author
Aleksandar Marjanovic
