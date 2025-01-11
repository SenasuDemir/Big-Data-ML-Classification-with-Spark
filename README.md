# 📉 Customer Churn Prediction with Apache Spark 🔮

## 📜 Introduction

In this project, the goal is to predict customer churn using machine learning models implemented in **Apache Spark**. Customer churn prediction is crucial for businesses to identify at-risk customers and take proactive measures to retain them. The dataset used contains various features related to customer demographics and behaviors, with the target variable being **Churn** (indicating whether a customer has churned).

The project is structured as follows:
- **Requirements**: Details the tools, libraries, and environment setup required to execute the project.
- **Import Data**: Covers the process of loading and preparing the dataset in Spark.
- **EDA (Exploratory Data Analysis)**: Analyzes the dataset to understand feature distributions, identify patterns, and address missing or inconsistent data.
- **Modelling**: Implements and trains two machine learning models:
    - **Logistic Regression**: A linear model well-suited for binary classification tasks.
    - **GBTClassifier**: An ensemble-based model that captures non-linear relationships in the data.
- **Result**: Compares the performance of the models based on their accuracy and effectiveness in predicting churn.
- **Conclusion**: Summarizes the findings and identifies the model best suited for churn prediction.

## 📊 Results

Two models were trained and evaluated for the purpose of predicting customer churn:

### 1. **Logistic Regression**
- **Accuracy**: 92.33%
- The Logistic Regression model achieved strong performance, effectively separating customers likely to churn from those who are not. This model is highly efficient for binary classification tasks and provides accurate predictions.

### 2. **Gradient-Boosted Tree Classifier (GBTClassifier)**
- **Accuracy**: 84.31%
- The GBTClassifier, while more robust to non-linear patterns, underperformed in this specific context. Although it captures complex relationships in the data, it did not outperform Logistic Regression for this dataset.

## 🏆 Conclusion

- The **Logistic Regression** model outperformed the **Gradient-Boosted Tree Classifier** in terms of accuracy.
- Therefore, the **Logistic Regression** model is recommended for predicting customer churn in this dataset, as it provides the highest accuracy and is a more reliable choice for identifying at-risk customers.
