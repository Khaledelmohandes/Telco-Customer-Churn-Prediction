\# 📞 Telco Customer Churn Prediction



\## 📌 Project Overview



Customer churn is one of the most important problems in the telecom industry.



The goal of this project is to build a Machine Learning model that predicts whether a customer is likely to leave the company or stay.



The project includes data preprocessing, exploratory data analysis, model training, evaluation, optimization, and deployment using Streamlit.



\---



\## 🎯 Project Objectives



\- Analyze customer behavior and factors affecting churn.

\- Build classification models to predict customer churn.

\- Compare different machine learning algorithms.

\- Optimize the best-performing model.

\- Deploy the final model as an interactive web application.



\---



\## 📊 Dataset



\*\*Dataset:\*\* Telco Customer Churn Dataset



The dataset contains information about telecom customers including:



\- Customer demographics

\- Account information

\- Services subscribed

\- Monthly charges

\- Contract information

\- Payment methods

\- Churn status





\### Features:



\- gender

\- SeniorCitizen

\- Partner

\- Dependents

\- tenure

\- PhoneService

\- MultipleLines

\- InternetService

\- OnlineSecurity

\- OnlineBackup

\- DeviceProtection

\- TechSupport

\- StreamingTV

\- StreamingMovies

\- Contract

\- PaperlessBilling

\- PaymentMethod

\- MonthlyCharges

\- TotalCharges





\---



\# 🛠️ Technologies Used



\## Programming Language



\- Python





\## Libraries



\- Pandas

\- NumPy

\- Matplotlib

\- Seaborn

\- Scikit-learn

\- Joblib

\- Streamlit





\---



\# 🔍 Machine Learning Workflow



\## 1. Data Understanding



\- Dataset exploration

\- Checking missing values

\- Understanding feature distributions





\## 2. Data Preprocessing



Performed:



\- Handling missing values

\- Encoding categorical features using OneHotEncoder

\- Scaling numerical features using StandardScaler





\## 3. Models Implemented



The following classification algorithms were tested:



\- Logistic Regression

\- KNN

\- Decision Tree

\- Random Forest

\- Support Vector Machine (SVM)





\---



\# 📈 Model Evaluation



Because the dataset is imbalanced, evaluation focused on:



\- F1 Score

\- Recall

\- Confusion Matrix

\- Classification Report





\## Model Comparison



| Model | F1 Score | Recall |

|---|---|---|

| Logistic Regression | 0.60 | 0.55 |

| SVM | 0.56 | 0.48 |

| Random Forest | 0.55 | 0.49 |

| KNN | 0.54 | 0.53 |

| Decision Tree | 0.49 | 0.49 |





\---



\# 🚀 Model Optimization



Hyperparameter tuning was performed using:



\- GridSearchCV

\- Cross Validation





Final Model:



\*\*Logistic Regression\*\*





Best Parameters:C = 0.1

Penalty = l2

Class Weight = balanced



\##########################################







Final F1 Score: **0.627**

**##########################################**





**---**



**# 🔎 Feature Importance Analysis**



**## Features Increasing Churn Risk:**



**- Fiber optic internet service**

**- High Total Charges**

**- Electronic check payment method**

**- Paperless Billing**

**- High Monthly Charges**





**## Features Reducing Churn Risk:**



**- Two year contract**

**- Long tenure**

**- One year contract**

**- Online Security**

**- Tech Support**





**---**



**# 🌐 Deployment**



**The final model was deployed using:**



**\*\*Streamlit\*\***



**The application allows users to:**



**- Enter customer information**

**- Predict churn status**

**- Display churn probability**





**---**



**# 📂 Project Structure**

**Telco-Churn-Project**



**│**

**├── app.py**

**├── telco\_churn\_model.pkl**

**├── requirements.txt**

**├── Telco\_Churn\_Project.ipynb**

**└── README.md**

**#######################################**





**---**



**# 👨‍💻 Author**



**Khaled Youssef  Elmohandes**



**Machine Learning Project**





