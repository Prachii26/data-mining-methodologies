# 🧠 Data Mining Methodologies – CRISP-DM, KDD & SEMMA

This repository demonstrates three complete data-mining workflows, each implemented on a Kaggle dataset.  
Every project follows its respective methodology end-to-end — from data understanding to modeling, evaluation, and deployment.

## 🔗 Medium Article link- https://medium.com/@prachigupta2610/a-comparative-analysis-of-semma-kdd-and-crisp-dm-frameworks-through-applied-data-mining-projects-a54d5d664ebd
---

## 📂 Folder Structure

```
data-mining-methodologies/
│
├── crispdm-obesity/         # CRISP-DM methodology
│   ├── data/                # obesity dataset
│   ├── models/              # Trained Random Forest model (.pkl)
│   └── notebook/            # Google Colab notebook
│
├── kdd-coffee-quality/      # KDD methodology
│   ├── data/                # Coffee quality dataset 
│   ├── model/               # Saved K-Means model
│   └── notebook/            # Colab notebook
│
├── semma-sleep-health/      # SEMMA methodology
│   ├── data/                # Sleep health dataset
│   ├── model/               # Random Forest + scaler files
│   └── notebook/            # Colab notebook
│
└── README.md                # This file
```

---

## 🔍 Project Overviews

### 🩺 CRISP-DM – Obesity Level Estimation
- **Dataset:** *Estimation of Obesity Levels based on Eating Habits and Physical Condition*  
- **Goal:** Predict obesity category from lifestyle attributes.  
- **Best Model:** Random Forest (Accuracy ≈ 96%, Macro-F1 ≈ 0.96).  
- **Key Insights:** Weight, height, and vegetable consumption (FCVC) are most predictive.

---

### ☕ KDD – Coffee Quality Clustering
- **Dataset:** *Coffee Quality Database (CQI Arabica)*  
- **Goal:** Identify flavor and quality clusters from sensory evaluation scores.  
- **Technique:** K-Means (k = 4) + PCA visualization.  
- **Findings:** Two major clusters represent standard and premium flavor profiles; smaller clusters contain outliers.

---

### 💤 SEMMA – Sleep Health & Lifestyle
- **Dataset:** *Sleep Health and Lifestyle Dataset*  
- **Goal:** Predict sleep disorders (Insomnia, Apnea, None).  
- **Best Model:** Random Forest (Accuracy ≈ 92%, F1 ≈ 0.89).  
- **Top Features:** Blood Pressure, BMI Category, Sleep Duration.

---

## ⚙️ Tech Stack
- **Languages:** Python 3, Jupyter/Colab  
- **Libraries:** pandas, numpy, scikit-learn, seaborn, matplotlib, joblib  
- **Tools:** Google Colab, GitHub  

---

## 🧩 How to Run
1. Open any notebook in Google Colab.  
2. Upload the corresponding dataset (from Kaggle links in each folder).  
3. Run cells sequentially to reproduce results.  
4. Saved models can be reloaded for quick inference.

---

## 🧾 Notes
Prepared for **Data Mining coursework** to demonstrate practical application of  
**CRISP-DM**, **KDD**, and **SEMMA** methodologies using small, interpretable datasets.
