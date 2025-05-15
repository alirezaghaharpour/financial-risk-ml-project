# Financial Risk Prediction using Machine Learning and HPC

This repository contains my MSc project from Brunel University London, where I implemented a machine learning pipeline for predicting financial risk levels. The project combined classification algorithms with parallel computing tools to enhance performance.

---

## 🧠 Project Overview

The objective is to classify individuals into **Low**, **Medium**, or **High** risk levels based on demographic, financial, and behavioural data. The original dataset contains 15,000 records and was obtained from [Kaggle](https://www.kaggle.com/datasets).

---

## 🗃️ Folder Structure

- `ML_R/` → Supervised learning in **R**, including SVM and XGBoost models.
- `HPC_Python/` → Distributed hyperparameter tuning using **Ray** and preprocessing with **Dask**.
- `.gitignore` → Clean repository for data science use cases.

---

## ⚙️ Technologies Used

- **Languages**: R, Python
- **ML Tools**: SVM, XGBoost, SMOTE, caret, ROC, F1, Kappa
- **Parallelization**: Ray (tune), Dask
- **Platform**: Google Colab
- **Data Source**: Kaggle (not uploaded here)

---

## 🔍 Key Highlights

- Applied **class balancing** with SMOTE (1-step and 2-step strategies)
- Performed **binary vs multiclass** comparison
- Used **ROC curves**, **F1-score**, **Kappa**, and **AUC** for evaluation
- Achieved **76.7% accuracy** and **AUC > 0.9** for High-risk class (SVM)
- Tuned SVM parameters (C, gamma) using **Ray Tune** with **ASHAScheduler**

---

## 📈 Results Snapshot

| Model | Accuracy | Kappa | High Risk AUC |
|-------|----------|--------|----------------|
| SVM (2SMOTE) | 76.7% | 0.65 | 0.91 |
| XGBoost (2SMOTE) | 67.2% | 0.51 | 0.912 |

---

## 🚫 Data Disclaimer

The dataset used is publicly available on Kaggle but not uploaded to this repository due to licensing.  
You can access it from [this Kaggle link](https://www.kaggle.com/datasets) and follow the same preprocessing steps.

---

## 📬 Contact

Feel free to connect or reach out via LinkedIn:  
[linkedin.com/in/alireza-ghaharpour](https://www.linkedin.com/in/alireza-ghaharpour)
