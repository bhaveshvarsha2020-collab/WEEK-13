# Loan Default Prediction System
Loan Risk Analysis and Loan Amount Prediction 
📌 Project Overview

This project analyzes loan data to identify risk categories, understand borrower behavior, and predict loan amounts using Machine Learning. The project performs data cleaning, exploratory data analysis (EDA), risk assessment, visualization, and predictive modeling using Python.

The goal is to gain insights into factors affecting loan repayment and loan approval amounts. 🎯 Objectives The main objective is to perform EDA, build a Linear Regression model, and create an interactive dashboard to understand patterns and support decision-making. This project aims to:

Data Collection • Load loan dataset from Kaggle • Understand dataset structure and features Data Cleaning & Preprocessing • Check missing values • Handle null values in income and employment • Convert categorical variables (term, home ownership, purpose) • Ensure correct data types Descriptive Statistics • Calculate: o Average loan amount o Average income o Interest rate distribution • Understand spread and variation Default Behavior Analysis • Compare: • Fully Paid vs Default loans • Identify high-risk borrower groups Group-Based Analysis • Income vs default • Employment length vs default • Loan purpose vs default • Home ownership vs default Relationship Analysis • Loan amount vs default • Interest rate vs default • Income vs loan amount • Identify strong influencing factors Data Visualization • Bar charts → Default distribution • Histograms → Income & loan distribution • Scatter plots → Relationships • Box plots → Outlier detection • Heatmaps → Correlation Risk Analysis • Classify borrowers into: • Low Risk • Medium Risk • High Risk • Identify potential defaulters Predictive Modeling (Linear Regression) • Define variables: • Independent variables: annual_inc, int_rate, term • Dependent variable: loan_amnt • Split data into training and testing sets • Build Linear Regression model • Train the model • Predict loan amount Model Evaluation • Calculate R² Score • Analyze residuals • Evaluate prediction accuracy Dashboard Creation • Create interactive dashboard using Plotly • Include visualizations: • Income vs Loan Amount • Loan distribution • Default comparison • Interest rate trends • Add interactive features: • Filters (loan term, purpose) • Dynamic charts Insights & Conclusion • Identify key default factors • Understand borrower financial behavior • Support better loan approval strategies #-Dataset Source: Kaggle Dataset Link:

https://www.kaggle.com/datasets/wordsforthewise/lending-club

Dataset Name: Lending Club Loan Data

⚙️ Project Workflow

Data Loading Embedded CSV dataset is loaded into a Pandas DataFrame. Data Cleaning Removed % symbol from interest rates. Converted interest rates to numeric values. Extracted numeric values from loan term and employment length. Handled missing values. Data Preprocessing Converted loan status into numerical values: Fully Paid → 0 Charged Off → 1 Encoded categorical features using Label Encoding. Exploratory Data Analysis (EDA) Generated:

Loan Status Distribution Annual Income Distribution Loan Amount Distribution Income vs Loan Amount Analysis Interest Rate vs Loan Status Correlation Heatmap 5. Risk Analysis

Loans were categorized as:

Interest Rate Risk Category < 10% Low Risk 10% - 18% Medium Risk ≥ 18% High Risk 6. Machine Learning Model

Implemented a Linear Regression Model using:

Input Features

Annual Income Interest Rate Loan Term

Target Variable

Loan Amount 7. Model Evaluation

Performance metrics:

R² Score Mean Absolute Error (MAE) 8. Interactive Visualizations

Created interactive dashboards using Plotly:

Loan Amount Distribution Income vs Loan Amount Interest Rate vs Loan Status Loan Purpose vs Risk Category 📈 Key Insights Higher interest rates are associated with higher loan default risk. Annual income influences the loan amount approved. Employment length can impact repayment behavior. Risk categorization helps identify potential defaulters. Data visualization provides clear insights into borrower trends. 🚀 How to Run the Project Clone the Repository git clone https://github.com/your-username/loan-risk-analysis.git cd loan-risk-analysis Install Required Libraries pip install pandas numpy matplotlib seaborn plotly scikit-learn Run the Program python loan_risk_analysis.py

Or open the notebook in Google Colab and run all cells.




<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/427e4738-b50a-4ab3-af09-bf091906a860" />
