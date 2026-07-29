# Telecom Customer Churn Prediction

<div>
  <p align="center">
    <img src="https://github.com/PrathuashaKB/telecom-customer-churn-prediction/blob/main/images/telecom_no_churn_logo.png" width="800">
  </p>
</div>

📉 *Predicting Customer Retention: Leveraging Machine Learning for Business Growth & Risk Mitigation*

**Telecom Customer Churn Prediction** is a **machine learning-based predictive analytics solution** designed to identify customers who are at high risk of discontinuing their subscription services.

Customer churn is a critical challenge for telecommunication companies, as retaining existing customers is often more cost-effective than acquiring new ones. By analyzing customer demographics, account information, service subscriptions, usage patterns, and customer support interactions, machine learning models can identify potential churn behaviour and help businesses take proactive retention measures.

This project was developed as an **Industry Client Project** during my **Data Science Research internship at Rubixe - AI Company**. The project follows an end-to-end Data Science workflow, beginning with data extraction from a **SQL database** and continuing through data preprocessing, exploratory data analysis, feature engineering, machine learning model development, model evaluation, and business insight generation.

The developed solution evaluates customer behaviour and account-level attributes to predict the likelihood of customer churn. The insights generated from the predictive models can support businesses in identifying high-risk customers and developing targeted customer retention strategies to reduce churn, improve customer satisfaction, and increase customer lifetime value.

![Python](https://img.shields.io/badge/Python-3.8-blue?style=flat\&logo=python\&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Database-orange?style=flat\&logo=mysql\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data--Analysis-black?style=flat\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical--Computing-purple?style=flat\&logo=numpy\&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine--Learning-blue?style=flat\&logo=scikit-learn\&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-Classifier-orange?style=flat\&logo=xgboost)
![Decision Tree](https://img.shields.io/badge/Decision--Tree-Classifier-brown?style=flat)
![Random Forest](https://img.shields.io/badge/Random--Forest-Classifier-green?style=flat)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical--Visualization-teal?style=flat)
![Business Analytics](https://img.shields.io/badge/Business--Analytics-Customer--Retention-success?style=flat)
![Predictive Analytics](https://img.shields.io/badge/Predictive--Analytics-Churn--Prediction-blue?style=flat)

> ✅ **Industry Client Project** at Rubixe - AI Company| Data Science Research Internship | Project Cycle Closed

[PROJECT NOTEBOOK](https://github.com/PrathuashaKB/telecom-customer-churn-prediction/blob/main/No_Churn_Telecom.ipynb), you can find the complete project implementation, data analysis, machine learning workflow, and model evaluation here.

#### *This project demonstrates the application of Machine Learning and Data Science techniques to predict customer churn and support data-driven customer retention strategies.*

## Features :

1. **Customer Churn Prediction** - Predicts the likelihood of customer churn using trained machine learning classification models.

2. **SQL-Based Data Acquisition** - Extracts and processes customer records from the `project_telecom` SQL database.

3. **Customer Behaviour Analysis** - Analyzes key customer usage and account metrics, including day, evening, night, and international call behaviour.

4. **Service & Account Analysis** - Evaluates service-related attributes such as international plans, voicemail plans, and customer support interactions.

5. **Data Preprocessing** - Handles missing values, categorical variables, feature encoding, and numerical feature scaling.

6. **Class Imbalance Handling** - Applies appropriate techniques to address class imbalance and improve predictive model performance.

7. **Machine Learning Model Comparison** - Trains and compares multiple classification algorithms, including Decision Tree, Random Forest, and XGBoost.

8. **Business-Oriented Insights** - Identifies important customer characteristics and behavioural patterns associated with churn to support proactive retention strategies.

9. **Model Performance** - The optimized XGBoost model achieved an accuracy of **93.83%** on the evaluated dataset.

## Methodology :

### 1. Data Acquisition :

* Queried and retrieved **4,617 customer records** from the `project_telecom` SQL database.
* Extracted customer account, service, demographic, and usage-related information.
* Prepared the retrieved data for further analysis and model development.

### 2. Data Preprocessing & Cleaning :

* Handled missing and inconsistent data.
* Encoded categorical variables such as `International_plan` and `VMail_Plan`.
* Applied numerical feature scaling where required.
* Prepared the dataset for machine learning model development.

### 3. Exploratory Data Analysis :

* Analyzed customer demographics and account characteristics.
* Examined customer usage patterns across different time periods.
* Investigated customer service interactions and their relationship with churn.
* Identified important patterns and potential drivers of customer churn.
* Visualized relationships between customer attributes and churn behaviour.

### 4. Feature Engineering :

* Transformed raw customer account and call usage attributes into predictive features.
* Selected relevant variables for churn prediction.
* Prepared the final feature set for machine learning model training.

### 5. Machine Learning Model Development :

Multiple classification algorithms were trained and compared to identify the most effective model for predicting customer churn.

* Decision Tree
* Random Forest
* XGBoost

### 6. Model Evaluation & Tuning :

The developed models were evaluated using multiple classification metrics to assess their predictive performance.

* Accuracy
* Precision
* Recall
* ROC-AUC
* Confusion Matrix

Model performance was compared to identify the best-performing algorithm. The optimized **XGBoost model achieved 93.83% accuracy** on the evaluated dataset.

### 7. Business Insights & Customer Retention :

The final model and feature analysis were used to derive actionable insights that can support customer retention strategies.

Key areas of analysis included:

* Customer service call behaviour
* International plan usage
* Customer usage patterns
* Account-level characteristics
* Factors contributing to increased churn risk

These insights can help businesses identify high-risk customers and develop targeted retention strategies to improve customer loyalty and reduce customer acquisition costs.

## System Design :

![No Churn System Design](https://github.com/PrathuashaKB/telecom-customer-churn-prediction/blob/main/images/no_churn_system_design.gif)

The system follows an end-to-end machine learning pipeline consisting of:

**SQL Database → Data Extraction → Data Preprocessing → Exploratory Data Analysis → Feature Engineering → Model Training → Model Evaluation → Churn Prediction → Business Insights**

## Project Outcome :

The project successfully demonstrated how **Machine Learning and predictive analytics** can be applied to customer churn prediction in the telecommunications domain.

The developed solution achieved **93.83% accuracy using an optimized XGBoost model** and provided insights into customer behaviour and account characteristics associated with churn.

The project highlights the potential of data-driven churn prediction systems to help businesses proactively identify at-risk customers, design targeted retention strategies, and make informed customer relationship management decisions.

#### Suggestions and project improvement are invited!

#### Prathuasha K B
