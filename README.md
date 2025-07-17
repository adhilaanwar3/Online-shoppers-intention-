🛍️ Online Shoppers Purchasing Intention Prediction

This project analyzes the Online Shoppers Purchasing Intention Dataset to understand user behavior and predict the likelihood of a purchase. It includes data preprocessing, exploratory data analysis (EDA), and multiple machine learning models to evaluate performance.

🔗 Open in Google Colab 
(https://colab.research.google.com/drive/14QazoBA6DGmDwHpzw0R5tO4RrNXNwq38?usp=sharing)

📂 Dataset
Source: UCI Machine Learning Repository
Name: Online Shoppers Purchasing Intention Dataset
Dataset Link (https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset)
Rows: ~12,330
Features: 18
Target: Revenue (Boolean - whether the session ended in a purchase)

📊 Features Include
Administrative, Product-related, and Informational pages (number and duration)
Bounce rates, exit rates
Page values, special day impact
Operating system, browser, region, traffic type
Visitor type, weekend flag, and month

🧪 Project Workflow

1. 📌 Data Preprocessing
Handled missing values and data types
Encoded categorical variables
Feature scaling (StandardScaler)
2. 📈 Exploratory Data Analysis (EDA)
Visualizations using Seaborn and Matplotlib
Distribution analysis of key features
Correlation heatmap
Purchase behavior by visitor type, region, and month
3. 🤖 Machine Learning Models
Logistic Regression
Decision Tree
Random Forest
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
XGBoost
Naive Bayes
4. ✅ Evaluation Metrics
Accuracy
Precision
Recall
F1 Score
Confusion Matrix
ROC-AUC Curve

🏆 Best Performing Model
✅ [Add best performing model here after running all evaluations]
Example: "Random Forest achieved the highest accuracy of 89% with balanced precision and recall."

🔧 Requirements
pip install pandas numpy matplotlib seaborn scikit-learn xgboost 

🚀 How to Run
Clone the repo
Open the provided Colab link
Or run the code locally using Jupyter Notebook

📌 Credits
