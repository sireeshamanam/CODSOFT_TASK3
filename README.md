# CODSOFT_TASK3
Customer Churn Prediction using Machine Learning
# Customer Churn Prediction

## Project Overview
This project uses Machine Learning to predict whether a customer is likely to leave a subscription-based telecommunications service.

## Dataset
The Telco Customer Churn dataset contains customer demographics, service information, contract details, and billing information.

Dataset: [Telco Customer Churn - Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## Project Workflow
1. Load and explore the customer dataset.
2. Visualize the distribution of customer churn.
3. Convert `TotalCharges` into numeric values and handle missing values.
4. Remove the customer ID column.
5. Encode categorical features into numerical values.
6. Split the data into training and testing sets.
7. Train Logistic Regression and Random Forest models.
8. Evaluate the models using accuracy, precision, recall, F1-score, and confusion matrices.
9. Save the final trained model.

## Model Comparison

| Metric | Logistic Regression | Random Forest |
|---|---:|---:|
| Accuracy | 72.78% | 78.89% |
| Precision | 49.26% | 63.23% |
| Recall | 79.68% | 49.20% |
| F1-score | 60.88% | 55.34% |

## Final Model
Logistic Regression was selected because it achieved higher recall and F1-score in this experiment. It detected a larger proportion of customers who churned, which can be useful when the goal is to identify customers who may need retention support.

## Conclusion
This project demonstrates how machine learning can help predict customer churn. Comparing two classification models showed that the choice of model depends on the business objective, especially the balance between detecting churners and avoiding false alarms.

## Internship
CodSoft Machine Learning Internship - Task 3
