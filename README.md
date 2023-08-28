## Summary
| Code          |     Name                       | Published Article|    PowerBi Dashboard
| ------------- | -------------                  | -------------    |    -----------------
| LP2           | Telcom Customer Churn Prediction |  [Article]()               |[PowerBI]()




# <center>Telcom Customer Churning Prediction Project</center>
[Author: MUGISHA Robert]

## **Introduction**

In the rapidly evolving telecommunications industry, customer retention has become a vital challenge for service providers. Retaining existing customers is more cost-effective than acquiring new ones, making churn prediction a crucial aspect of business strategy. The "Telcom Customer Churning Prediction" project addresses this challenge by developing a machine learning model to predict customer churn, enabling companies to take proactive measures to retain valuable customers.


## **Project Overview**
#### **Objective**

The main objective of this project is to create an accurate and efficient churn prediction model that can identify customers likely to churn. By identifying potential churners in advance, telecom companies can implement personalized retention strategies, reduce churn rates, and enhance overall customer satisfaction.


## **Approach**

This project employs machine learning techniques to predict customer churn using popular libraries such as NumPy, pandas, matplotlib, seaborn, and scikit-learn. The project focuses on evaluating the performance of various algorithms, including Logistic Regression, Decision Trees, Random Forest, and Support Vector Machines (SVM).


- **Gender:** Indicates whether the customer is male or female.
- **Partner:** Reflects whether the customer has a partner (Yes, No).
- **SeniorCitizen:** Identifies if the customer is a senior citizen.
- **Dependents:** Indicates if the customer has dependents (Yes, No).
- **Tenure:** Represents the number of months the customer has been with the company.
- **Phone Service:** Indicates if the customer has a phone service (Yes, No).
- **InternetService:** Specifies the customer's internet service provider (DSL, Fiber Optic, No).
- **Contract:** Represents the contract term of the customer (Month-to-Month, One year, Two years).
- **MonthlyCharges:** Reflects the amount charged to the customer monthly.
- **TotalCharges:** Represents the total amount charged to the customer.
- **Churn:** Indicates whether the customer churned or not (Yes or No).

### **Installation:**

1. **Activate Your Virtual Environment:**
- If you're using a virtual environment, activate it in your terminal or command prompt. This ensures that you're capturing the packages installed in the correct environment.

2. **Navigate to Your Project Directory:**
- Use the cd command to navigate to the directory where your project is located.

3. **Run the Command:**
- Use the pip freeze command followed by > to redirect the output to a requirements.txt file. Specify the file name you want to create or overwrite, like this: **pip freeze > requirements.txt**

4. **Review the File:**
- Open the requirements.txt file in a text editor to verify that the package names and versions have been captured correctly.

## **Methodology**

The project follows a structured approach:

- **Data Preparation:** Cleaning and preprocessing the data, handling missing values, and converting categorical variables into numerical form.
- **Exploratory Data Analysis (EDA):** Analyzing data distributions, correlations, and visualizations to gain insights into customer behavior patterns.
- **Feature Selection:** Identifying relevant features that have a significant impact on churn prediction.
- **Model Selection and Evaluation:** Implementing multiple machine learning algorithms and evaluating their performance using metrics like ROC AUC, accuracy, precision, and recall.
- **Hyperparameter Tuning:** Fine-tuning the selected models to optimize their performance using techniques like RandomizedSearchCV.
- **Model Comparison:** Comparing the performance of different models to identify the best-performing one.
- **Interpretation:** Interpreting the model's insights, such as feature importance, to understand the factors influencing churn.

## **Conclusion**

The "Telcom Customer Churning Prediction" project showcases how machine learning can help telecom companies predict and prevent customer churn effectively. By leveraging data analysis and predictive modeling, companies can implement targeted retention strategies, improve customer satisfaction, and make informed business decisions. This project highlights the significance of data-driven approaches in addressing real-world challenges in the telecommunications industry.

## ****
