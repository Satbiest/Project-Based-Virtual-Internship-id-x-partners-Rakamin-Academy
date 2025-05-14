# Project-Based-Virtual-Internship-id-x-partners-Rakamin-Academy
Credit Risk Prediction — ID/X Partners Virtual Internship Project
This project was developed as part of the Data Scientist Project-Based Virtual Internship at ID/X Partners. The primary objective is to construct a machine learning model to predict credit risk, supporting financial institutions in identifying high-risk loan applicants. The model aims to enhance decision-making processes and reduce financial losses by accurately forecasting potential defaults.

📌 Project Summary
The Credit Risk Prediction initiative focuses on improving the reliability of risk evaluation within the multi-finance sector, where it is critical to assess a borrower's ability to meet debt obligations. Using historical loan records, the project predicts the likelihood of default based on variables such as loan amount, interest rate, loan duration, credit history, and other financial indicators.

⚙️ Tools & Technologies
Programming Language: Python

Libraries:

Pandas (data manipulation)

NumPy (numerical processing)

Matplotlib & Seaborn (data visualization)

Scikit-Learn (machine learning framework)

XGBoost, Random Forest, Logistic Regression (classification models)

📂 Dataset Overview
The dataset contains over 466,000 entries and 75 features, encompassing:

Loan amount and terms (e.g., 36 or 60 months)

Interest rates

Employment duration

Credit history

Financial and demographic details

Several features had missing values, which were addressed through thorough data cleaning and imputation steps.

🔧 Project Workflow
1. Data Cleaning
Addressed missing values

Standardized formats for columns like term, emp_length, and date fields

Ensured overall data consistency

2. Exploratory Data Analysis (EDA)
Examined the distribution of the target variable

Analyzed numerical feature patterns and outliers

Evaluated feature correlations

Investigated categorical variable distributions

3. Data Preprocessing
Dropped irrelevant columns

Imputed missing values

Converted date features to datetime format

Encoded categorical variables

Prepared the dataset for model training

4. Modeling
Multiple machine learning models were trained and tested, including:

Logistic Regression

Random Forest

XGBoost

AdaBoost

K-Nearest Neighbors (KNN)

LightGBM

Gradient Boosting

Decision Tree

5. Model Evaluation
Performance was assessed using metrics like F1-score

XGBoost outperformed others, achieving the lowest false positives and false negatives.

