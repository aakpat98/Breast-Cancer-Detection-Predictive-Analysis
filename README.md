# 🩺 Breast Cancer ML Classification

## 📌 Project Overview
This project explores **breast cancer classification** using the **Wisconsin Diagnostic Breast Cancer (WDBC) dataset**. We implemented **Decision Trees, K-Nearest Neighbors (KNN), Logistic Regression, and Support Vector Machines (SVM)** to determine the best-performing model.  

To ensure **robust model selection**, we applied **Nested Stratified K-Fold Cross-Validation** with **GridSearchCV** for hyperparameter tuning. The models were evaluated using **AUC-ROC, precision, recall, F1-score, and Matthews Correlation Coefficient (MCC)**, prioritizing **high recall for early cancer detection**.

---

## 📂 Repository Contents
- **README.md** - Project details and usage instructions  
- **Breast_Cancer_Analysis.ipynb** - Jupyter Notebook with full ML pipeline  
- **Breast_Cancer_Analysis.pdf** - PDF version of the analysis  
- **wdbc.data** - Contains the raw dataset (WDBC)  

---

## 📊 Models & Evaluation

### ✅ **Machine Learning Models Used**
- **Decision Tree** 🌲  
- **K-Nearest Neighbors (KNN)** 🤝  
- **Logistic Regression** 📉  
- **Support Vector Machine (SVM)** 🛠 *(Best Performing Model)*  

### 🎯 **Key Findings**
- **SVM achieved the highest recall (97.2%) & AUC = 0.99**  
- **Nested cross-validation improved model generalization**  
- **Feature scaling was crucial for KNN & SVM performance**  
