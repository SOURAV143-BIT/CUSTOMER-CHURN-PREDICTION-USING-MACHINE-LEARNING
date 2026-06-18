Customer Churn Analysis and Prediction

📌 Project Overview

Customer churn is a critical challenge in the telecom industry, directly impacting revenue and customer lifetime value. This project focuses on analyzing customer behavior and predicting churn using data-driven techniques and machine learning models.

The project leverages the Telecom Customer Churn dataset to uncover key patterns and build predictive models that help identify customers at risk of leaving.

---

🎯 Objectives

- Analyze customer demographics and service usage patterns.
- Perform exploratory data analysis (EDA) to identify churn drivers.
- Visualize trends influencing customer retention.
- Build and evaluate machine learning models for churn prediction.
- Compare model performance and identify the most effective approach.

---

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

📂 Dataset Information

The dataset includes key customer attributes such as:

- Gender
- Senior Citizen Status
- Tenure
- Monthly Charges
- Contract Type
- Payment Method
- Internet Service
- Churn Status

Target Variable:
Churn (Yes / No)

---

📊 Data Manipulation & EDA

- Filtered high-risk customer segments (e.g., senior citizens with electronic payments).
- Analyzed customer tenure and spending behavior.
- Identified churn-prone groups such as:
  - Short tenure customers
  - Month-to-month contract users
  - High monthly charge customers
- Created random samples and performed categorical distribution analysis.

---

📈 Data Visualization Insights

- Internet Service Distribution: Fiber users showed higher churn tendency.
- Tenure Analysis: Customers with low tenure had significantly higher churn rates.
- Monthly Charges vs Tenure: High-paying new customers were more likely to churn.
- Contract Type Analysis: Long-term contracts (2-year) had the lowest churn rates.

---

🤖 Machine Learning Models

🔹 Linear Regression

- Predicted Monthly Charges using Tenure.
- Evaluated using RMSE.
- Showed moderate correlation between tenure and charges.

---

🔹 Logistic Regression

Simple Model:

- Input: Monthly Charges
- Output: Churn
- Achieved moderate accuracy, indicating pricing impacts churn.

Multiple Model:

- Inputs: Tenure + Monthly Charges
- Improved prediction performance compared to single-variable model.

---

🔹 Decision Tree Classifier

- Captured non-linear relationships in churn behavior.
- Provided interpretable decision rules.
- Performance improved over logistic regression for classification.

---

🔹 Random Forest Classifier ⭐

- Best performing model.
- Higher accuracy and better generalization.
- Reduced overfitting compared to decision tree.

---

📌 Results & Key Findings

- Customers with short tenure and high monthly charges are more likely to churn.
- Contract type is a major factor — long-term contracts reduce churn significantly.
- Random Forest model achieved the highest accuracy, making it the most reliable for prediction.
- Ensemble methods outperformed basic regression models in classification tasks.

---

🚀 Future Improvements

- Feature Engineering (customer behavior scoring)
- Hyperparameter tuning (GridSearchCV)
- Cross-validation for robust evaluation
- Advanced models like XGBoost & LightGBM
- Dashboard development using Power BI / Tableau
- Customer retention recommendation system

---

📷 Project Workflow

1. Data Collection
2. Data Cleaning
3. Data Manipulation
4. Exploratory Data Analysis
5. Data Visualization
6. Model Building
7. Model Evaluation
8. Churn Prediction

---

👨‍💻 Author

Sourabh 
BCA STUDENT |  Aspiring Data Scientist | 
