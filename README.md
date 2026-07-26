# Telecom Customer Churn Analysis and Prediction

An end-to-end **Data Analytics and Machine Learning** project that analyzes customer behavior using the IBM Telco Customer Churn dataset to identify the key factors influencing customer churn and build predictive models for customer retention.

---

## Project Overview

This project follows a complete data analytics workflow:

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning Model Development
- Model Evaluation
- Business Recommendations

---

## Dataset

- **Dataset:** IBM Telco Customer Churn Dataset
- **Records:** 7,043
- **Features:** 21
- **Target Variable:** Churn

The dataset is available in the `data/` directory.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Google Colab / Jupyter Notebook

---

## Machine Learning Models

The following classification models were implemented and compared:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

### Model Performance

| Model | Accuracy | ROC-AUC |
|--------|---------:|---------:|
| Logistic Regression | **80.38%** | **0.836** |
| Random Forest | 78.68% | 0.818 |
| XGBoost | 78.04% | 0.818 |
| Decision Tree | 77.83% | 0.820 |

**Best Model:** Logistic Regression

**5-Fold Cross Validation Accuracy:** **80.25%**

---

## Key Insights

- Month-to-Month contract customers had the highest churn rate.
- Customers with shorter tenure were more likely to leave.
- Higher monthly charges were associated with increased churn.
- Electronic Check users showed the highest churn among payment methods.
- Online Security, Online Backup, and Technical Support were associated with improved customer retention.

---

## Repository Structure

```
Telecom-Customer-Churn-Analysis/
│
├── data/
├── images/
├── notebook/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/Har1528/Telecom-Customer-Churn-Analysis.git
```

2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Open the notebook located in the `notebook/` folder and run all cells.

---

## Future Improvements

- Hyperparameter tuning
- Handling class imbalance using SMOTE
- Interactive Streamlit dashboard
- Model deployment as a web application
