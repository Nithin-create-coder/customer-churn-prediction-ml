📊 Customer Churn Prediction using Machine Learning
📌 Project Overview
Customer churn refers to when customers stop using a company's product or service. Predicting churn is important because retaining existing customers is more cost-effective than acquiring new ones.
This project analyzes telecom customer data and builds machine learning models to predict whether a customer is likely to churn. The project includes data cleaning, exploratory data analysis, model training, hyperparameter tuning, model explainability, and visualization.

🎯 Project Objectives
Analyze customer behavior and service usage.
Identify factors influencing customer churn.
Build machine learning models to predict churn.
Compare multiple machine learning models.
Improve model performance using hyperparameter tuning.
Explain model predictions using SHAP.

📂 Dataset
Dataset used: Telco Customer Churn Dataset
The dataset contains information about telecom customers including:
Feature
Description
gender
Customer gender
SeniorCitizen
Whether the customer is a senior citizen
tenure
Number of months the customer stayed
MonthlyCharges
Monthly billing amount
TotalCharges
Total charges paid
Contract
Contract type
InternetService
Type of internet service
PaymentMethod
Payment method
Churn
Whether the customer left the service

Total records: 7043 customers

🛠 Technologies Used
Python
Pandas
NumPy
Plotly
Matplotlib
Seaborn
Scikit-learn
SHAP
Streamlit

📊 Exploratory Data Analysis (EDA)
Exploratory Data Analysis was performed to understand patterns in the dataset.
Visualizations included:
Customer churn distribution
Churn by contract type
Monthly charges vs churn
Customer tenure distribution
Internet service vs churn
Correlation heatmap
These analyses help identify relationships between customer behavior and churn probability.

🤖 Machine Learning Models
Three machine learning models were trained and compared:
1️⃣ Logistic Regression
2️⃣ Decision Tree
3️⃣ Random Forest
Each model was evaluated using:
Accuracy
Confusion Matrix
Classification Report
ROC Curve
Random Forest achieved the best performance.

⚙ Hyperparameter Tuning
Hyperparameter tuning was performed using GridSearchCV to improve model performance.
Parameters tuned:
Number of trees (n_estimators)
Maximum tree depth (max_depth)
Minimum samples split (min_samples_split)
This process identifies the optimal configuration for the model.

🔍 Model Explainability
SHAP (SHapley Additive Explanations) was used to explain how features influence model predictions.
Important features affecting churn:
Contract type
Monthly charges
Customer tenure
Internet service type
SHAP visualizations help understand how different factors impact churn predictions.

📊 Key Insights
Customers with month-to-month contracts churn more frequently.
Higher monthly charges increase churn probability.
Customers with longer tenure are more loyal.
Contract type and tenure strongly influence churn behavior.

🔄 Project Workflow
Data Collection
       │
       ▼
Data Cleaning
       │
       ▼
Exploratory Data Analysis
       │
       ▼
Feature Engineering
       │
       ▼
Model Training
       │
       ▼
Model Evaluation
       │
       ▼
Hyperparameter Tuning
       │
       ▼
Model Explainability
       │
       ▼
Customer Churn Prediction


🏗 System Architecture
Dataset
   │
   ▼
Data Processing (Pandas)
   │
   ▼
Exploratory Data Analysis
   │
   ▼
Feature Engineering
   │
   ▼
Machine Learning Model
(Random Forest / Logistic Regression)
   │
   ▼
Model Evaluation
   │
   ▼
Prediction Output
   │
   ▼
Business Insights


⚙ End-to-End Machine Learning Pipeline
1️⃣ Data Ingestion
2️⃣ Data Cleaning
3️⃣ Exploratory Data Analysis
4️⃣ Feature Engineering
5️⃣ Model Training
6️⃣ Model Evaluation
7️⃣ Hyperparameter Tuning
8️⃣ Model Explainability
9️⃣ Prediction

📸 Project Screenshots
Customer Churn Distribution
![Churn Distribution](images/churn_distribution.png)

Monthly Charges vs Churn
![Monthly Charges vs Churn](images/monthly_charges_vs_churn.png)

Model Comparison
![Model Comparison](images/model_comparison.png)


⚙ How to Run the Project Locally
1️⃣ Clone the Repository
git clone https://github.com/yourusername/customer-churn-prediction-machine-learning.git


2️⃣ Navigate to the Project Folder
cd customer-churn-prediction-machine-learning


3️⃣ Install Required Libraries
pip install -r requirements.txt


4️⃣ Run the Jupyter Notebook
jupyter notebook

Open:
churn_prediction.ipynb




📦 Installation Requirements
Create a file called requirements.txt
pandas
numpy
matplotlib
seaborn
plotly
scikit-learn
shap
streamlit


📁 Project Structure
customer-churn-prediction-machine-learning
│
├── churn_prediction.ipynb
├── app.py
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── requirements.txt
├── README.md
│
└── images
     ├── churn_distribution.png
     ├── monthly_charges_vs_churn.png
     └── model_comparison.png


📌 Conclusion
This project demonstrates how machine learning can be used to analyze customer behavior and predict churn. By identifying high-risk customers early, businesses can implement strategies to improve customer retention and reduce revenue loss.


