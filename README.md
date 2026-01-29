Customer Churn Prediction
📖 Project Overview

Customer churn prediction helps businesses identify customers who are likely to stop using their services.
In this project, we build a Machine Learning model using Logistic Regression to predict customer churn based on customer usage and subscription details.

The dataset used is the Telco Customer Churn dataset.

🚀 Technologies Used

Python

Pandas & NumPy – Data handling

Matplotlib & Seaborn – Data visualization

Scikit-learn – Machine learning model and evaluation

📂 Dataset

Source: Telco Customer Churn Dataset

Target Variable: Churn

Yes → Customer churned

No → Customer retained

🔍 Project Workflow

Import required libraries

Load the dataset

Exploratory Data Analysis (EDA)

Data preprocessing

Remove unnecessary columns

Handle missing values

Convert categorical values

Feature encoding using One-Hot Encoding

Train-test split

Feature scaling using StandardScaler

Model training using Logistic Regression

Model evaluation

Prediction on sample data

Visualization of churn distribution

🧠 Machine Learning Model

Algorithm: Logistic Regression

Why Logistic Regression?

Simple and interpretable

Works well for binary classification problems

Efficient and fast to train

📊 Model Evaluation

Accuracy Score

Confusion Matrix

These metrics help understand how well the model predicts customer churn.

📈 Visualization

Churn distribution is visualized using a count plot

Helps understand class imbalance in the dataset

🧪 Sample Prediction

The model predicts whether a customer:

✅ Will churn

❌ Will not churn

based on input features after scaling.
