# BACE1 Inhibition Prediction  

This repository contains Jupyter notebooks and datasets used for predicting **Beta-secretase 1 (BACE1)** inhibitory activity. BACE1 is a key therapeutic target in Alzheimer's disease research, and this project explores machine learning approaches for bioactivity prediction.  

---

## 📂 Repository Contents  

- **Notebooks**  
  - `Beta_secretase_1.ipynb` – Data loading, preprocessing, and exploratory analysis  
  - `Beta_secretase_1_part2.ipynb` – Feature generation and initial modeling  
  - `beta_secratase_part3 (1).ipynb` – Model training and evaluation (Random Forest, SVM, etc.)  
  - `beta_secratase_part4 (3).ipynb` – Advanced analysis and Structure–Activity Relationship (SAR) study  

- **Datasets**  
  - `bioactivity_dataBeta-secretase 1.csv` – Raw bioactivity data  
  - `bioactivity_preprocessed_data.csv` – Cleaned and preprocessed dataset  
  - `bs1_06_bioactivity_data_3class_pIC50_pubchem_fp.csv` – PubChem fingerprints with activity classes  

---

## ⚙️ Methods  

- **Data Source**: PubChem bioactivity data  
- **Descriptors**: Molecular fingerprints, physicochemical descriptors  
- **Models Used**:  
  - Random Forest Regression (RFR)  
  - Support Vector Regression (SVR)  
- **Evaluation Metrics**: R², MSE, RMSE, MAE  

---

## 📊 Results  

- Random Forest and SVM models were compared for predictive performance.  
- Top candidates were selected for **Structure–Activity Relationship (SAR) analysis**.  

---




