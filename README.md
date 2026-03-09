# Online-Payment-Fraud-detection-Analysis
Exploratory Data Analysis of online payment transactions to identify fraud patterns using Python.
# Online Payment Fraud Detection Analysis

## Project Overview

Online payment systems have become an essential part of modern financial transactions. However, with the rapid growth of digital payments, the risk of fraudulent transactions has also increased significantly.

This project focuses on analyzing online transaction data to identify patterns associated with fraudulent activities. Using Python and exploratory data analysis (EDA), the project investigates transaction behavior, fraud distribution, and key indicators that can help detect fraudulent transactions.

The goal of this analysis is to understand fraud patterns and derive insights that can assist financial institutions in improving fraud detection systems.

---

## Dataset

The dataset used in this project was obtained from Kaggle and contains historical transaction data used for fraud detection.

Key features in the dataset include:

* **step** – Represents time unit (1 step = 1 hour)
* **type** – Type of transaction (CASH_IN, CASH_OUT, TRANSFER, PAYMENT, DEBIT)
* **amount** – Transaction amount
* **nameOrig** – Customer initiating the transaction
* **oldbalanceOrg** – Balance before transaction
* **newbalanceOrig** – Balance after transaction
* **nameDest** – Recipient account
* **oldbalanceDest** – Recipient balance before transaction
* **newbalanceDest** – Recipient balance after transaction
* **isFraud** – Indicates fraudulent transaction (1 = Fraud, 0 = Legitimate)

---

## Tools and Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Google Colab**

---

## Project Workflow

The project follows a structured data analysis workflow:

1. Data Loading and Inspection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Fraud Pattern Identification
5. Data Visualization
6. Insight Generation

---

## Key Analysis Performed

The project investigates multiple aspects of transaction data, including:

* Fraud rate in the dataset
* Transaction amount distribution
* Fraud occurrence by transaction type
* Account balance behavior during fraud
* Time-based fraud trends
* Correlation between transaction amount and fraud likelihood
* Destination account analysis
* Outlier detection in financial transactions

---

## Key Insights

* Fraud transactions represent **approximately 0.11% of all transactions**, making fraud a rare but critical event.
* Fraud is concentrated in **CASH_OUT** and **TRANSFER** transaction types.
* Fraudulent transactions tend to involve **higher transaction amounts**.
* Fraudulent activity often results in **sudden depletion of origin account balances**.
* Fraud tends to occur during **specific time intervals rather than uniformly**.
* A relatively **small number of destination accounts are repeatedly involved in fraud**, suggesting possible organized activity.

---

## Fraud Prevention Recommendations

Based on the analysis, several preventive measures can be considered:

* Implement stricter verification for **CASH_OUT and TRANSFER transactions**
* Introduce **alerts for unusually large transactions**
* Monitor **high-risk destination accounts**
* Apply **real-time anomaly detection during peak fraud intervals**

---

## Project Files

| File                            | Description                               |
| ------------------------------- | ----------------------------------------- |
| `project_on_online_fraud.ipynb` | Colab Notebook containing full analysis |
| `project_on_online_fraud.py`    | Python script version of the analysis     |
| `Online_fraud_project.pdf`      | Detailed project report                   |
| `README.md`                     | Project documentation                     |

---

## Future Improvements

Future work can extend this project by implementing machine learning models such as:

* Logistic Regression
* Random Forest
* XGBoost
* Neural Networks

These models can help build an automated fraud detection system capable of predicting fraudulent transactions in real time.

---

## Author

**Abhishek Rawat**

Aspiring Data Analyst with an interest in data analytics, machine learning, and financial data analysis.

---

## Acknowledgements

* Kaggle for providing the dataset
* Open-source Python libraries used in this project
* Learning resources that supported this analysis
