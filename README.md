# UNICEF Direct Mail Donation Prediction (Data Analytics Project)

## Project Summary
This project applies data analysis and machine learning to optimize Direct Mail (DM) donation targeting for [UNICEF Australia](chatgpt://generic-entity?number=0).  
I built an end-to-end analytics pipeline from data cleaning and EDA to modeling, evaluation, and business strategy translation.

本项目以 UNICEF 直邮募捐优化为背景，完整展示了我从数据清洗、探索性分析、建模评估到业务策略转化的数据分析全流程能力。

---

## Business Problem
Traditional DM targeting relied mainly on experience, leading to:
- High mailing cost  
- Unstable conversion rate  
- No clear prioritization of donors  

---

## Analytics Objective
- Predict whether a donor will contribute within 3 months after receiving DM  
- Output individual donation probability scores  
- Segment donors into A/B/C value groups for targeted campaigns  

---

## Data & Feature Engineering
- Multi-source CRM data: donor profile, donation history, DM logs, payment methods  
- Extensive feature engineering: frequency, recency, monetary value, payment type, donation streak, response ratio  
- 23 raw fields expanded to 87 modeling features  

---

## Exploratory Data Analysis (Key Findings)
- High-frequency donors show 3–5x higher re-donation probability  
- Recurring debit users are ~6x more likely to donate again  
- Donation probability decreases significantly as the time since last donation increases  
- Non-emergency DM themes perform better in long-term engagement  

---

## Modeling & Evaluation
- Models compared: Logistic Regression, Random Forest, XGBoost, LightGBM, CatBoost  
- Final model: **XGBoost**  
- Evaluation metrics: **AUC, F1-score, Recall**  
- Performance validated using ROC curve, PR curve, and confusion matrix  

---

## Data-Driven Business Output
- Converted predicted probabilities into **A/B/C user segmentation**
- Directly mapped segmentation to different DM targeting strategies
- Estimated impact under fixed budget:
  - ~30% DM cost reduction  
  - 20%+ improvement in overall conversion rate  

---

## Tech Stack
- Python (pandas, numpy, matplotlib, scikit-learn, XGBoost)
- SQL
- Jupyter Notebook
- LaTeX / PDF Reporting

---

## Deliverables
- Full analytical report (PDF)
- Model evaluation visualizations
- User segmentation strategy

---

## Data Disclaimer
All original data has been anonymized. This repository is for analytical demonstration only.

---

## Contact
Rongzhen Yu  
Email: rongzhen.yu@outlook.com
