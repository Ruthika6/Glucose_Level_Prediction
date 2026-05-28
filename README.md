# Glucose_Level_Prediction
🩺 Glucose Level Prediction using Machine Learning

A Machine Learning project that predicts whether a person has Normal or High Glucose Levels using health indicators from the Framingham Dataset.
The project compares multiple ML models and visualizes performance using ROC curves, confusion matrices, feature importance, and statistical plots.

📌 Project Overview

This project focuses on:

Data preprocessing & cleaning
Exploratory Data Analysis (EDA)
Feature engineering
Training ML classification models
Evaluating models using metrics
Visualizing insights using plots

The target variable is:

Normal Glucose (<126 mg/dL)
High Glucose (≥126 mg/dL)
📂 Dataset

Dataset Used: Framingham Heart Study Dataset

Features include:

Age
BMI
Blood Pressure
Cholesterol
Smoking Habits
Diabetes
Heart Rate
Glucose Level
etc.
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
📊 Exploratory Data Analysis

The project includes:

✅ Correlation Heatmap
✅ Distribution Plots
✅ Boxplots
✅ Feature Importance Analysis

🤖 Machine Learning Models

The following models were trained and compared:

Model	Accuracy	ROC-AUC
Logistic Regression	~97%	0.943
Decision Tree	~97%	0.663
Random Forest	~97%	0.924
📈 Visualizations Included
🔹 Correlation Heatmap

Shows relationships between medical features.

🔹 Distribution Plots

Visualizes spread of:

Glucose
BMI
Blood Pressure
Age
Cholesterol
🔹 Confusion Matrices

Compares prediction performance of models.

🔹 ROC Curves

Evaluates classification capability using AUC scores.

🔹 Feature Importance

Displays most influential health indicators.

🔍 Key Findings
Diabetes is the most important feature for predicting high glucose levels.
Logistic Regression achieved the highest ROC-AUC score.
Random Forest also performed strongly with balanced predictions.
Decision Tree showed lower ROC performance despite high accuracy.
📁 Project Structure
├── framingham.csv
├── Glucose_Prediction_Summary.ipynb
├── confusion_matrices.png
├── correlation_heatmap.png
├── distributions.png
├── feature_importance.png
├── glucose_boxplot.png
├── model_comparison.png
├── roc_curves.png
└── README.md
🚀 How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/glucose-level-prediction.git
2️⃣ Install Dependencies
pip install pandas numpy matplotlib seaborn scikit-learn
3️⃣ Run Jupyter Notebook
jupyter notebook

Open:

Glucose_Prediction_Summary.ipynb
📌 Results
High classification accuracy achieved
Strong ROC-AUC performance
Effective feature importance interpretation
Useful healthcare prediction insights
📷 Output Screenshots

Add these images in your repository:

correlation_heatmap.png
roc_curves.png
confusion_matrices.png
feature_importance.png
🎯 Future Improvements
Hyperparameter tuning
Deep Learning implementation
Deployment using Flask/Streamlit
Real-time prediction system
Handling class imbalance with SMOTE
👩‍💻 Author

Ruthika Reddy

B.Tech CSE Student | AI/ML Enthusiast
