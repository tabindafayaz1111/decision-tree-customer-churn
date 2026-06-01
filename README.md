# Decision Tree Customer Churn Prediction

## Project Overview

This project uses the Decision Tree Classification algorithm to predict whether a bank customer is likely to leave the bank (churn) based on customer information such as credit score, age, balance, geography, and account activity.

Customer churn prediction helps banks identify customers at risk of leaving and take proactive measures to improve customer retention.

---

## Dataset

Dataset: Bank Customer Churn Prediction

The dataset contains customer information including:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of Products
* Has Credit Card
* Is Active Member
* Estimated Salary

### Target Variable

* Exited = 0 → Customer Stayed
* Exited = 1 → Customer Left (Churned)

---

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Encoding Categorical Variables
6. Train-Test Split
7. Decision Tree Model Building
8. Hyperparameter Tuning
9. Model Evaluation
10. Feature Importance Analysis
11. Decision Tree Visualization
12. Business Insights

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Data Preprocessing

### Removed Unnecessary Columns

The following columns were removed because they do not contribute to customer churn prediction:

* RowNumber
* CustomerId
* Surname

### Encoding

* Gender encoded using Label Encoding
* Geography encoded using One-Hot Encoding

---

## Model Used

### Decision Tree Classifier

The Decision Tree algorithm was chosen because:

* Easy to interpret
* Handles both numerical and categorical data
* Provides feature importance
* Requires minimal preprocessing

---

## Model Evaluation Metrics

The model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1-Score
* Classification Report

---

## Feature Importance

Feature importance analysis was performed to identify the factors that most influence customer churn.

Examples of important features:

* Age
* Balance
* Number of Products
* Is Active Member
* Credit Score

---

## Business Insights

* Older customers showed a higher tendency to churn.
* Active members were less likely to leave the bank.
* Customers with certain balance ranges showed increased churn risk.
* Geography had a noticeable impact on customer retention.
* Decision Trees help identify key factors affecting customer behavior.

---

## Project Structure

decision-tree-customer-churn/

├── data/

│ └── Churn_Modelling.csv

├── notebooks/

│ └── decision_tree_customer_churn.ipynb

├── README.md

---

## Installation

Clone the repository:

Move into the project folder:

```bash
cd decision-tree-customer-churn
```

Install dependencies:

```bash
pip install Python
pip install Pandas
pip install NumPy
pip install Matplotlib
pip install Seaborn
pip install Scikit-Learn
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## Results

The Decision Tree model successfully classified customer churn behavior and provided interpretable decision rules for understanding customer retention patterns.

Model performance was evaluated using multiple classification metrics and optimized through hyperparameter tuning.

---

## Future Improvements

* Random Forest Classifier
* XGBoost Classifier
* Hyperparameter Optimization using GridSearchCV
* Streamlit Deployment
* Customer Churn Probability Prediction

---

## Author

Lone Tabinda

Machine Learning Enthusiast | Data Science Learner

---

## License

This project is intended for educational and portfolio purposes.
