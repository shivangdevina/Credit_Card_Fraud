# 💳 Credit Card Fraud Detection Analysis

**Credit Card Fraud Detection Analysis** is a **Python-based machine learning project** that aims to identify fraudulent credit card transactions using classification algorithms and robust techniques for handling highly imbalanced data.  

The project leverages a dataset from **Kaggle** (`mlg-ulb/creditcardfraud`) and demonstrates end-to-end workflows in a **Jupyter Notebook** environment.

---

## 🚀 Features

- **Data Exploration:** Analyze features such as `Time`, `Amount`, anonymized variables (`V1`–`V28`), and the `Class` label (0 = non-fraud, 1 = fraud).
- **Data Preprocessing:** Handle missing values, scale features, and apply dimensionality reduction (`PCA`, `t-SNE`, `TruncatedSVD`).
- **Imbalanced Data Handling:** Use **SMOTE** for oversampling and **NearMiss** for undersampling to balance classes.
- **Model Training:** Train classifiers such as Logistic Regression, SVC, KNN, Decision Tree, and Random Forest.
- **Evaluation:** Evaluate models using metrics like precision, recall, F1-score, ROC-AUC, and accuracy, with cross-validation (`KFold`, `StratifiedKFold`).
- **Visualization:** Visualize correlations, scatter plots, and dimensionality reduction results using **Matplotlib** and **Seaborn**.

---

## 🛠️ Tech Stack

### 🧩 Programming Language
- **Python 3.x**

### 🗃️ Libraries
- **Data Processing:** `pandas`, `numpy`
- **Machine Learning:** `scikit-learn`, `tensorflow`, `imbalanced-learn`
- **Visualization:** `matplotlib`, `seaborn`
- **Dimensionality Reduction:** `sklearn.decomposition.PCA`, `sklearn.manifold.TSNE`, `sklearn.decomposition.TruncatedSVD`
- **Model Evaluation:** `sklearn.metrics`, `imblearn.metrics`

### 📂 Dataset
- **Kaggle Dataset:** [mlg-ulb/creditcardfraud](https://www.kaggle.com/mlg-ulb/creditcardfraud)

---

## ✅ Prerequisites

- **Python 3.8+**
- **Jupyter Notebook** or **JupyterLab**
- **Kaggle account & API token** for dataset access
- Required Python packages (see `Requirements.txt`)

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone <repository-url>
cd credit-card-fraud-detection
