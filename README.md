# ❤️ Heart Disease Prediction — EDA & ML

<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**An end-to-end ML pipeline to predict heart disease from clinical data.**

*Data cleaning · EDA · Logistic Regression · ROC-AUC Evaluation*

[![Open in Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/code/abmusawir/heart-disease-prediction-eda-ml)

</div>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Tech Stack](#-tech-stack)
- [Pipeline](#-pipeline)
- [Model Evaluation](#-model-evaluation)
- [Getting Started](#-getting-started)
- [Author](#-author)

---

## 🧠 Overview

Heart disease is one of the leading causes of mortality worldwide. Early and accurate prediction from clinical indicators can save lives. This project builds a complete **end-to-end ML pipeline** — from raw messy clinical data all the way to a trained and evaluated **Logistic Regression classifier**.

**What this project covers:**
- Cleaning real-world clinical data with missing values (`'?'` entries)
- Exploratory Data Analysis with visualizations and correlation heatmap
- Training a Logistic Regression model with proper feature scaling
- Evaluating with confusion matrix, classification report, and ROC-AUC score

---

## 🛠 Tech Stack

| Category | Tools |
|---|---|
| **Language** | Python 3.x |
| **Data Handling** | pandas, numpy |
| **Visualization** | matplotlib, seaborn |
| **ML** | scikit-learn (LogisticRegression, StandardScaler, metrics) |
| **Environment** | Kaggle Notebooks / Jupyter |

---

## ⚙️ Pipeline

```
Raw Clinical Dataset
        │
        ▼
┌──────────────────────────────┐
│       Data Cleaning          │
│  • Replace '?' → NaN         │
│  • Type conversion           │
│  • Median imputation         │
└──────────────────────────────┘
        │
        ▼
┌──────────────────────────────┐
│  Exploratory Data Analysis   │
│  • Feature distributions     │
│  • Class balance check       │
│  • Correlation heatmap       │
└──────────────────────────────┘
        │
        ▼
┌──────────────────────────────┐
│  Preprocessing & Splitting   │
│  • StandardScaler            │
│  • 80% Train / 20% Test      │
└──────────────────────────────┘
        │
        ▼
┌──────────────────────────────┐
│   Logistic Regression Model  │
│   Binary Classification      │
│   Heart Disease: Yes / No    │
└──────────────────────────────┘
        │
        ▼
  Confusion Matrix · Classification Report · ROC-AUC
```

---

## 📈 Model Evaluation

| Metric | Score |
|---|---|
| **Accuracy** | ~XX% |
| **Precision** | ~XX% |
| **Recall** | ~XX% |
| **F1-Score** | ~XX% |
| **ROC-AUC** | ~X.XX |

> 📝 *Update this table with your actual results after running the notebook.*

---

## 🚀 Getting Started

### Option 1 — Run on Kaggle *(Recommended)*

[![Open in Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://www.kaggle.com/code/abmusawir/heart-disease-prediction-eda-ml)

No setup needed — open and run all cells directly.

---

### Option 2 — Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/Musawir456/heart-disease-prediction.git
cd heart-disease-prediction

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch the notebook
jupyter notebook
```

**requirements.txt**
```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

## 👨‍💻 Author

<div align="center">

**Abdul Musawir**
*Data Science & ML Engineer*
📍 Lahore, Pakistan
🎓 Superior University, Lahore

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdul-musawir-a9713a20b/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Musawir456)
[![Kaggle](https://img.shields.io/badge/Kaggle-Profile-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/abmusawir)

</div>

---

<div align="center">

⭐ **If this project helped you, please give it a star!** ⭐

*Made with ❤️ by Abdul Musawir — Lahore, Pakistan*

</div>
