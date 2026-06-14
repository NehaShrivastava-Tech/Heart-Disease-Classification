## 🫀 **Heart Disease Classification & Predictive Modeling**.

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Numpy](https://img.shields.io/badge/NumPy-1.21%2B-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-150458?logo=pandas&logoColor=white)](https://pandas.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.0%2B-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)

An end-to-end Machine Learning classification project designed to analyze patient clinical metrics and predict the probability of heart disease. Developed utilizing data preprocessing, target mapping, and supervised learning principles from the **Sheryians AI School Machine Learning Series**.

---

## 🔄 **Machine Learning Lifecycle Workflow**

<img width="2048" height="2048" alt="image" src="https://github.com/user-attachments/assets/2d20effb-65f0-4ffb-9658-a5b5cf003b46" />

---

## 📌 **Project Architecture**

┌──────────────┐      ┌──────────────────────────┐      ┌─────────────────────┐
│  Heart.csv   │ ───> │ Exploratory Data Analysis│ ───> │ Feature Engineering │
│   Dataset    │      │  (Nulls & Outlier Check) │      │ & Data Preparation  │
└──────────────┘      └──────────────────────────┘      └─────────────────────┘
│
▼
┌──────────────┐      ┌──────────────────────────┐      ┌─────────────────────┐
│ Final Binary │ <─── │     Model Evaluation     │ <─── │  Standard Scaling   │
│  Inference   │      │ (Accuracy, Matrix, ROC)  │      │  (Z-Score Normal)   │
└──────────────┘      └──────────────────────────┘      └─────────────────────┘


---

## 📊 **Pipeline Implementations**

### 1. Exploratory Data Analysis (EDA)
* Analyzed patient risk factors across metrics such as age, cholesterol, maximum heart rate, and chest pain indicators.
* Evaluated binary distribution boundaries to ensure data processing stability across classes.

### 2. Feature Preprocessing & Scaling
* Implemented feature transformation routines via Scikit-Learn's 'StandardScaler' to handle multi-unit variations, structuring all inputs to share an identical scaling profile:
    z = \frac{x - \mu}{\sigma}

  Clinical Data Inputs ──> [ Calculate Mean (μ) & StdDev (σ) ] ──> Normalized Metric Features

  ### 3. Classification Modeling
* Structured using robust model criteria to successfully predict binary boundaries ($0$ for healthy, $1$ for heart disease risk present).

---

## 📂 **Project Repository Structure**

```file
├── data/
│   └── Heart.csv             # Raw target data metrics
├── notebooks/
│   └── ml_project_2.ipynb    # Training, data profiling, and validation workspace
├── requirements.txt          # Python environments dependencies
└── README.md                 # Project Documentation


