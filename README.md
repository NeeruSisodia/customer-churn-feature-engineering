# Customer Churn Prediction using Feature Engineering

## Project Overview

This project focuses on improving customer churn prediction through business-driven feature engineering. The objective is to transform raw customer data into meaningful features that improve the performance and interpretability of a machine learning model.

The project was completed using Python and Scikit-learn, with a Random Forest classifier used for churn prediction.
This repository presents an enhanced version of a customer churn prediction task completed as part of the **BCG Data Science Virtual Experience Program** on Forage.

---

## Business Problem

Customer churn is one of the biggest challenges for utility companies. Identifying customers who are likely to leave allows businesses to take proactive retention measures.

This project explores how carefully designed features based on business knowledge can improve churn prediction.

---

## Dataset

The dataset contains customer information including:

- Customer characteristics
- Electricity consumption
- Gas consumption
- Pricing information
- Contract information
- Customer churn label

The dataset used in this project was provided as part of the **BCG Data Science Virtual Experience Program** on Forage.

The dataset is not included in this repository due to redistribution considerations. Users interested in reproducing the analysis can access it through the Forage program.

---

## Feature Engineering

The project includes both original and business-driven engineered features.

### Original Features

- Price Difference (December vs January)
- Peak vs Off-Peak Price Difference

### Engineered Features

- Delivery Delay Risk
- Power Cut Impact Risk
- Contract Expiry Risk
- Energy-to-Gas Ratio

Each engineered feature was created using business assumptions and domain knowledge.

---

## Machine Learning Model

Random Forest Classifier

---

## Model Evaluation

The model was evaluated using:

- Accuracy
- ROC-AUC Score
- Classification Report
- Confusion Matrix
- ROC Curve
- Feature Importance

### Final Performance

- Accuracy: **90%**
- ROC-AUC Score: **0.92**

---

## Key Business Insights

- Profit margin was one of the strongest predictors of customer churn.
- Electricity consumption significantly influenced churn prediction.
- Among the engineered features, **Energy-to-Gas Ratio** provided the highest predictive value.
- Feature engineering improved the model by incorporating business knowledge into the prediction process.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Git
- GitHub

---


---

## Future Improvements

- Hyperparameter tuning
- SHAP Explainability
- XGBoost and LightGBM comparison
- Streamlit deployment
- Power BI dashboard

---

## Acknowledgements

This project is based on the **BCG Data Science Virtual Experience Program** on Forage.

The original task has been significantly enhanced as part of my personal learning portfolio by adding:

- Business-driven feature engineering
- Detailed feature explanations
- Confusion Matrix and ROC Curve
- Feature Importance analysis
- Business insights and conclusions
- Improved project documentation and GitHub structure

The enhancements were implemented independently to strengthen my practical skills in machine learning and customer churn prediction.

---

## Author

Neeru Neeru

Aspiring Data Analyst | Machine Learning | Python | SQL | Power BI

GitHub: https://github.com/NeeruSisodia
