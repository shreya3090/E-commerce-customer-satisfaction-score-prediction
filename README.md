# 🛍️ E-Commerce Customer Satisfaction Score Prediction

A Machine Learning project focused on predicting **customer satisfaction scores in an e-commerce environment** using customer, order, product, and service-related information.

The project explores customer behavior and transaction data, performs data preprocessing and exploratory analysis, and builds a predictive machine learning model to estimate customer satisfaction.

---

## 📌 Project Overview

Customer satisfaction is an important indicator of an e-commerce platform's performance. Factors such as order value, delivery experience, product quality, customer interactions, and purchasing behavior can influence how customers rate their experience.

This project uses machine learning to analyze these factors and predict the **customer satisfaction score**.

The project covers the complete data science workflow:

```text
Data Collection
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Feature Engineering
      ↓
Data Preprocessing
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Customer Satisfaction Prediction
```

---

## 🎯 Objectives

* Predict customer satisfaction scores using machine learning.
* Identify important factors affecting customer satisfaction.
* Perform exploratory data analysis on e-commerce data.
* Prepare and transform raw data for machine learning.
* Build and evaluate a predictive model.
* Generate satisfaction-score predictions for new customer/order data.

---

## 📊 Problem Statement

The objective is to develop a machine learning model that can learn patterns from historical e-commerce data and predict the satisfaction score associated with a customer experience.

The prediction can help an e-commerce platform understand customer experience and identify areas where improvements may be required.

---

## 🔍 Key Areas of Analysis

The project analyzes different aspects of e-commerce customer experience, including:

* Customer information
* Order-related information
* Product-related information
* Purchase behavior
* Delivery experience
* Customer reviews
* Satisfaction ratings
* Transaction-related factors

These variables are processed and analyzed to identify patterns associated with customer satisfaction.

---

## 🧠 Machine Learning Approach

The project follows a structured machine learning pipeline.

### 1. Data Preprocessing

The raw dataset is prepared for modeling through steps such as:

* Handling missing values
* Removing unnecessary data
* Cleaning inconsistent records
* Encoding categorical variables
* Scaling numerical features where required
* Preparing the target variable

### 2. Exploratory Data Analysis

EDA is performed to understand the dataset and discover relationships between different variables and customer satisfaction.

Visualizations can be used to analyze:

* Distribution of satisfaction scores
* Customer/order characteristics
* Relationships between numerical variables
* Categorical feature distributions
* Correlations between features

### 3. Feature Engineering

Relevant features are transformed into a format suitable for machine learning algorithms.

### 4. Model Training

Machine learning techniques are applied to learn the relationship between customer/order attributes and the satisfaction score.

### 5. Model Evaluation

The trained model can be evaluated using appropriate regression metrics such as:

* **MAE — Mean Absolute Error**
* **MSE — Mean Squared Error**
* **RMSE — Root Mean Squared Error**
* **R² Score**

> Exact model metrics should be added after running the final notebook so that no performance values are incorrectly reported.

---

## 🛠️ Technologies Used

| Technology       | Purpose                         |
| ---------------- | ------------------------------- |
| Python           | Programming language            |
| Pandas           | Data manipulation               |
| NumPy            | Numerical computation           |
| Matplotlib       | Data visualization              |
| Seaborn          | Exploratory data analysis       |
| Scikit-learn     | Machine learning                |
| Jupyter Notebook | Development and experimentation |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/shreya3090/E-commerce-customer-satisfaction-score-prediction.git
cd E-commerce-customer-satisfaction-score-prediction
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
E-commerce customer satisfaction score prediction (1).ipynb
```

Run the notebook cells sequentially to reproduce the analysis and model-training workflow.

---

## 📈 Model Evaluation

The model performance can be evaluated using standard regression metrics.

### MAE

Measures the average absolute difference between the actual and predicted satisfaction scores.

### MSE

Measures the average squared prediction error and gives greater weight to larger errors.

### RMSE

Represents the typical prediction error in the same unit as the target variable.

### R² Score

Measures how much of the variation in customer satisfaction can be explained by the model.

---

## 💡 Business Applications

A customer satisfaction prediction system can help e-commerce businesses with:

* 📊 Customer experience analysis
* 🚚 Delivery and service improvement
* ⭐ Understanding factors affecting customer ratings
* 🔎 Identifying potentially dissatisfied customers
* 📈 Improving customer retention strategies
* 🎯 Data-driven customer experience decisions

---

## 🔮 Future Improvements

The project can be extended by:

* Building an interactive Streamlit prediction application
* Comparing multiple machine learning algorithms
* Applying hyperparameter optimization
* Adding NLP-based analysis of customer reviews
* Performing sentiment analysis on review text
* Using advanced ensemble models
* Adding model explainability using SHAP
* Deploying the trained model through an API
* Implementing automated model retraining

---

## 📁 Repository Structure

```text
E-commerce-customer-satisfaction-score-prediction/
│
├── E-commerce customer satisfaction score prediction (1).ipynb
│
└── README.md
```

---

## 👩‍💻 Author

**Shreya Sachan**

B.Tech CSE – Cyber Security

GitHub:
https://github.com/shreya3090

---

## ⭐ Project

If you found this project useful, consider giving the repository a ⭐.
