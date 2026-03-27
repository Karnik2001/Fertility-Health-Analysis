# 🧬 Fertility Health Analysis Using Machine Learning and Explainable Al
## 📌 Overview
This project focuses on analyzing fertility-related health data and building machine learning models to predict fertility outcomes. The goal is to identify patterns in biological and lifestyle variables and evaluate multiple classification algorithms to determine the most effective predictive model.

This project demonstrates skills in:
- Data preprocessing
- Classification modeling
- Model evaluation
- Comparative analysis of algorithms
  
## 📂 Dataset Description

The dataset contains medical and lifestyle attributes that influence fertility health. These include:
- Demographic features
- Physiological indicators
- Behavioral factors

⚠️ Note: Sensitive or identifying fields were excluded to ensure model integrity and privacy.

## ⚙️ Project Workflow
1. Data Preprocessing
- Handled missing values
- Encoded categorical variables
- Feature scaling (where required)
- Train-test split for model validation
  
2. Machine Learning Models Implemented

The following classification models were trained and evaluated:
- Logistic Regression
- Passive Aggressive Classifier
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
- MLP Classifier (Neural Network)
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Gaussian Naive Bayes
  
3. Model Evaluation

Models were evaluated using:
- Accuracy Score
- Comparative performance across models

📊 The best-performing model was selected based on overall predictive accuracy and generalization ability.

## 📈 Key Results
Multiple models were benchmarked to ensure robustness
Tree-based and ensemble models (e.g., Random Forest, Gradient Boosting) typically performed strongly
Neural networks (MLP) provided additional nonlinear modeling capability

🛠️ Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy

## 📌 Future Improvements
- Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
- Deploy model using Flask or Gradio
- Incorporate deep learning models
