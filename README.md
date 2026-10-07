# Supplier Risk Prediction using Machine Learning

## 📌 Project Overview

Supplier performance plays a critical role in maintaining product quality and ensuring an efficient supply chain. This project develops a machine learning model to predict supplier risk using operational, financial, and quality-related attributes.

The objective is to identify high-risk suppliers at an early stage, enabling organizations to take proactive measures to reduce supply chain disruptions and improve supplier performance.

---

## 🎯 Objectives

- Perform data cleaning and preprocessing.
- Conduct exploratory data analysis (EDA) to understand supplier characteristics.
- Build a Logistic Regression model to classify supplier risk.
- Evaluate model performance using standard classification metrics.
- Identify the key factors influencing supplier risk through coefficient analysis.

---

## 📂 Dataset

The dataset contains information related to supplier quality, operational performance, and financial indicators.

### Features include:

- Region
- Distance from facility
- Financial Score
- Years Active
- Lead Time
- On-time Delivery
- Delay Days
- Lot Size
- Price Variance
- Defect Rate
- Communication Score
- Inspection Skip

**Target Variable**

- `supplier_risk`
  - 0 → Low Risk
  - 1 → High Risk

---

## 🔍 Exploratory Data Analysis

The following analyses were performed:

- Supplier Risk Distribution
- Defect Rate vs Supplier Risk
- Delay Days vs Supplier Risk
- Correlation Heatmap

### Key Insights

- Higher defect rates are associated with increased supplier risk.
- Suppliers with longer delivery delays are more likely to be classified as high risk.
- Communication quality and operational metrics contribute significantly to supplier performance.
- Several numerical variables exhibit meaningful relationships with supplier risk.

---

## ⚙️ Data Preprocessing

The preprocessing pipeline included:

- Handling missing values
- Removing irrelevant features
- One-hot encoding categorical variables
- Feature scaling using StandardScaler
- Train-test split (80:20)

---

## 🤖 Machine Learning Model

**Algorithm Used**

- Logistic Regression

### Model Evaluation

The model was evaluated using:

- Confusion Matrix
- Accuracy
- Precision
- Recall
- F1-Score

### Performance

| Metric | Value |
|--------|-------|
| Precision | 0.59 |
| Recall | 1.00 |
| F1 Score | 0.74 |

---

## 📈 Key Findings

Coefficient analysis indicated that supplier risk is primarily influenced by:

- Defect Rate
- Delivery Delays
- Communication Score
- Financial Score
- Lead Time

These variables provide valuable insights for supplier evaluation and proactive risk management.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📁 Project Structure

```text
Supplier-Risk-Prediction/
│
├── data/
│   └── supplier_quality.csv
│
├── notebooks/
│   └── Supplier_Risk_Prediction.ipynb
│
├── images/
│   ├── correlation_heatmap.png
│   ├── defect_rate_vs_risk.png
│   ├── delay_days_vs_risk.png
│   └── confusion_matrix.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 Future Improvements

- Evaluate ensemble models such as Random Forest and XGBoost.
- Address class imbalance using advanced sampling techniques.
- Deploy the trained model as a web application.
- Develop an interactive dashboard for supplier risk monitoring.

---

## 👩‍💻 Author

**Nidhi Kumari**

M.S. in Quality Management Science  
Indian Statistical Institute, Bengaluru

**Areas of Interest**

- Machine Learning
- Data Analytics
- Statistics
- Operations Research
