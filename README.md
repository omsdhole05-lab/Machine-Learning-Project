# Customer Churn Prediction – README

## 📌 Project Overview

This project focuses on predicting whether a customer will leave a bank (customer churn) using Machine Learning. The dataset contains customer demographic, financial, and account-related information. The objective is to build a classification model that helps banks identify customers who are likely to churn, allowing them to take proactive retention measures.

---

## 📂 Dataset Information

**Dataset Name:** `Churn_Modelling.csv`

**Total Records:** 10,000

**Total Features:** 14

### Features

| Feature         | Description                                            |
| --------------- | ------------------------------------------------------ |
| RowNumber       | Row index of the dataset                               |
| CustomerId      | Unique customer ID                                     |
| Surname         | Customer's surname                                     |
| CreditScore     | Customer's credit score                                |
| Geography       | Country of the customer                                |
| Gender          | Male/Female                                            |
| Age             | Customer's age                                         |
| Tenure          | Number of years with the bank                          |
| Balance         | Account balance                                        |
| NumOfProducts   | Number of bank products used                           |
| HasCrCard       | Whether customer has a credit card (0 = No, 1 = Yes)   |
| IsActiveMember  | Whether customer is an active member (0 = No, 1 = Yes) |
| EstimatedSalary | Estimated annual salary                                |
| Exited          | Target variable (1 = Churned, 0 = Stayed)              |

---

## 🎯 Problem Statement

Predict whether a customer will leave the bank based on their personal and financial information.

**Target Variable:** `Exited`

* **0** → Customer stays
* **1** → Customer leaves (Churn)

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📊 Project Workflow

1. Load the dataset
2. Explore the data (EDA)
3. Handle missing values (if any)
4. Encode categorical variables
5. Feature selection
6. Split data into training and testing sets
7. Train Machine Learning models
8. Evaluate model performance
9. Predict customer churn

---

## 🤖 Machine Learning Models

Possible models used:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* XGBoost (optional)

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC Score

---

## 📁 Project Structure

```text
Customer-Churn-Prediction/
│
├── Churn_Modelling.csv
├── Customer_Churn_Prediction.ipynb
├── requirements.txt
├── README.md
└── models/
```

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   [(https://github.com/omsdhole05-lab/Machine-Learning-Project)]
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `Customer_Churn_Prediction.ipynb` and execute all cells.

---

## 📌 Expected Outcome

The trained model predicts whether a customer is likely to churn, enabling the bank to identify at-risk customers and improve customer retention strategies.

---

## 📚 Future Improvements

* Hyperparameter tuning
* Feature engineering
* Class imbalance handling (SMOTE)
* Model deployment using Flask or Streamlit
* Real-time churn prediction API

---

## 👩‍💻 Author

**Om Dhole**

---


