# 📊 Customer Churn Prediction Using Machine Learning

## 🚀 Project Overview

Customer churn prediction helps businesses identify customers who are likely to discontinue their services. In this project, various Machine Learning algorithms are implemented to predict customer churn using customer-related features such as tenure and monthly charges.

The project involves data preprocessing, exploratory data analysis (EDA), visualization, model building, and performance evaluation using multiple classification techniques.

---

## 🎯 Objectives

* Analyze customer churn behavior.
* Perform data cleaning and preprocessing.
* Visualize customer data using graphs and plots.
* Build predictive machine learning models.
* Compare the performance of different classification algorithms.

---

## 📂 Dataset Information

The dataset contains telecom customer information including:

* CustomerID
* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure
* Phone Service
* Internet Service
* Contract
* Payment Method
* Monthly Charges
* Total Charges
* Churn

### Target Variable

| Value | Meaning           |
| ----- | ----------------- |
| Yes   | Customer Churned  |
| No    | Customer Retained |

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 📈 Exploratory Data Analysis (EDA)

Several visualizations were created to understand customer behavior:

### Histogram

Used to analyze feature distributions.

### Box Plot

Used to identify outliers and compare customer groups.

### Churn Distribution Analysis

Understanding the balance between churned and retained customers.

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

* Handling missing values
* Data cleaning
* Feature selection
* Label encoding of categorical variables
* Train-Test Split

---

## 🤖 Machine Learning Models Implemented

### 1. Logistic Regression

Built a simple Logistic Regression model where:

* Dependent Variable: Churn
* Independent Variable: MonthlyCharges

#### Steps

* Dataset split into 65:35 ratio
* Model trained on training data
* Predictions generated on testing data
* Accuracy evaluated

---

### 2. Multiple Logistic Regression

Built a Multiple Logistic Regression model where:

* Dependent Variable: Churn
* Independent Variables:

  * Tenure
  * MonthlyCharges

#### Steps

* Dataset split into 80:20 ratio
* Model trained and tested
* Predictions evaluated

---

### 3. Decision Tree Classifier

Built a Decision Tree model where:

* Dependent Variable: Churn
* Independent Variable: Tenure

#### Steps

* Dataset split into 80:20 ratio
* Model training
* Prediction generation
* Accuracy calculation

---

### 4. Random Forest Classifier

Built a Random Forest model where:

* Dependent Variable: Churn
* Independent Variables:

  * Tenure
  * MonthlyCharges

#### Steps

* Dataset split into 70:30 ratio
* Forest model training
* Prediction generation
* Model evaluation

---

## 📊 Model Evaluation

The models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Metrics
* Prediction Results

---

## 🔍 Key Insights

* Monthly charges significantly impact churn probability.
* Customers with longer tenure are less likely to churn.
* Combining tenure and monthly charges improves prediction capability.
* Ensemble methods like Random Forest provide robust classification performance.

---

## 📁 Project Structure

```text
CUSTOMER-CHURN-PREDICTION-USING-MACHINE-LEARNING/
│
├── Customer_Churn_Prediction.ipynb
├── customer_churn.csv
├── README.md
└── requirements.txt
```

---

## ▶️ Installation

### Clone Repository

```bash
git clone https://github.com/SOURAV143-BIT/CUSTOMER-CHURN-PREDICTION-USING-MACHINE-LEARNING.git
```

### Navigate to Project Folder

```bash
cd CUSTOMER-CHURN-PREDICTION-USING-MACHINE-LEARNING
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

---

## 📷 Project Outputs

The notebook includes:

* Histograms
* Boxplots
* Customer Churn Analysis
* Logistic Regression Results
* Multiple Logistic Regression Results
* Decision Tree Results
* Random Forest Results
* Accuracy Comparisons

---


## 💡 Conclusion

This project demonstrates how Machine Learning algorithms can be used to predict customer churn effectively. By leveraging customer tenure and monthly charges, businesses can identify high-risk customers and take proactive retention measures to reduce customer loss.

---

## 👩‍💻 Author

**Sourabh**

Aspiring Data Scientist | Machine Learning Enthusiast

GitHub: https://github.com/SOURAV143-BIT
