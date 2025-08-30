# Predictive Analytics for Cybersecurity  
**Paper:** Enhancing Cybersecurity through Predictive Analytics: Real-Time Threat Detection and Response  

[![Journal](https://img.shields.io/badge/IJACSA-Vol16%20No8%202025-blue)](https://thesai.org/Publications/ViewPaper?Volume=16&Issue=8&Code=IJACSA&SerialNo=4)  

---

## Overview
This repository contains datasets, SPSS project files, and supporting material for the paper:  

**Muhammad Danish,** *Enhancing Cybersecurity through Predictive Analytics: Real-Time Threat Detection and Response*, *International Journal of Advanced Computer Science and Applications (IJACSA)*, Vol. 16, No. 8, 2025.

The project demonstrates how predictive analytics — leveraging **statistical methods and machine learning** — can enhance **real-time cyber-attack detection and response** in Security Operations Centers (SOCs).  

### Key Contributions
- Evaluation of **2,000+ network-traffic records** with features such as attack type, anomaly scores, packet length, protocol usage, and geo-location patterns.  
- Comparison of predictive analytics against traditional **signature-based IDS** and reactive baselines.  
- Use of **logistic regression, correlation analysis, chi-square tests, regression modeling, and t-tests** to assess predictive power.  
- Evidence that **attack type and contextual features** significantly influence response actions, while simple header metrics are insufficient.  
- Framework for reducing **false positives**, improving scalability, and supporting proactive defense strategies.  

---

## Repository Structure
├── Data.xlsx # Dataset used for descriptive & inferential analysis

├── Input.sav # SPSS input file

├── Output.spv # SPSS output results

├── README.md # Documentation (this file)

└── arXiv_Predictive_Analytics.pdf # Preprint version of the paper

## Getting Started
### Requirements
- [IBM SPSS Statistics](https://www.ibm.com/spss) (for `.sav` and `.spv` files)  
- Python or R (optional, for re-implementing regression/correlation analysis)  
- Microsoft Excel / LibreOffice (for `.xlsx` dataset)

### Usage
1. Open `Data.xlsx` for descriptive statistics and preprocessing.  
2. Load `Input.sav` into **SPSS** to replicate the study’s analyses.  
3. Review `Output.spv` for complete regression, correlation, and significance test results.  
4. Refer to the published paper [Enhancing Cyber Security Through Predictive Analytics: Real-Time Threat Detection and Response](https://thesai.org/Publications/ViewPaper?Volume=16&Issue=8&Code=IJACSA&SerialNo=4) for methodology and interpretations.  

---

## Results Summary
- **Descriptive Analysis:** Port ranges, packet lengths, anomaly scores, and device/user info show strong heterogeneity — crucial for robust modeling.  
- **Correlation Analysis:** Limited direct correlations, confirming the need for multi-feature predictive models.  
- **Crosstabulation & Chi-square:** Protocol is not a discriminative feature for attack type.  
- **Regression Models:** Attack type significantly predicts response actions (p = 0.001), while packet length and anomaly scores are weaker predictors.  
- **t-Tests:** No significant difference in packet lengths between attack-signature groups, underscoring the need for richer contextual features.  

---

## Citation
If you use this repository, please cite:

```bibtex
@article{danish2025predictive,
  author    = {Muhammad Danish},
  title     = {Enhancing Cyber Security Through Predictive Analytics: Real-Time Threat Detection and Response},
  journal   = {International Journal of Advanced Computer Science and Applications (IJACSA)},
  volume    = {16},
  number    = {8},
  year      = {2025},
  doi       = {10.14569/IJACSA.2025.0160804}
}
