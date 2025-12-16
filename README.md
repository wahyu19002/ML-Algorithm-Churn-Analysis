## Project Overview
Dalam industri telekomunikasi, mempertahankan pelanggan (*customer retention*) jauh lebih hemat biaya dibandingkan mengakuisisi pelanggan baru. Proyek ini bertujuan untuk membangun model Machine Learning yang dapat memprediksi apakah seorang pelanggan akan berhenti berlangganan (*churn*) atau tidak berdasarkan data historis mereka.

## Dataset
Dataset yang digunakan berasal dari [Kaggle: Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn?resource=download)

**Jumlah Data:** 7043 baris (pelanggan).
**Fitur Utama:**
    - **Demografi:** Gender, Senior Citizen, Partner, Dependents.
    - **Services:** Phone Service, Internet Service, Streaming TV, dll.
    - **Account Info:** Contract, Payment Method, Monthly Charges, Total Charges.
    - **Target:** **Churn** (Yes/No).

## Model
Melatih beberapa algoritma Machine Learning untuk perbandingan performa:
  - Logistic Regression
  - Random Forest Classifier
  - Support Vector Machine (SVM)
  - XGBoost

# Model Evaluation
Menggunakan metrik Accuracy, Precision, Recall, dan F1-Score.

# Perbandingan Performa
- Logistic Regression Test F1-Score data uji: 0.7776311169827481
- Logistic Regression Training F1-Score data train: 0.7611836244396653
- Random Forest Test F1-Score data uji: 0.8334504783053709
- Random Forest Training F1-Score data train: 0.8850556635999225
- SVM Test F1-Score: 0.7797774225694617
- SVM Training F1-Score: 0.772974540678008
- XGB Test F1-Score: 0.8204638160736651
- XGB Training F1-Score: 0.9012126779391547

# Performa setelah Hyperparameter Tuning pada XGBoost 
- Train F1 XGB: 0.8625
- Test F1 XGB: 0.8323
