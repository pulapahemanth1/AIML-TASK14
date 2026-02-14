📌 Overview
This project focuses on comparing multiple machine learning classification models on a single dataset and selecting the best-performing model based on evaluation metrics. The task demonstrates how industry ML teams choose optimal algorithms by evaluating model performance and generalization.
📊 Dataset
Breast Cancer Dataset (from scikit-learn)
Binary classification problem
Target: Malignant vs Benign tumors
Numerical features only
Well-suited for model comparison
🛠 Tools & Libraries Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Joblib
⚙️ Workflow
Loaded the Breast Cancer dataset
Performed train-test split with the same split for all models
Applied feature scaling using StandardScaler
Trained multiple ML models
Evaluated each model using standard classification metrics
Created a comparison table
Plotted a bar chart for performance comparison
Selected the best model based on F1-score
Saved the best model for future use
🤖 Models Compared
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Support Vector Machine (SVM)
📈 Evaluation Metrics
Each model was evaluated using:
Accuracy
Precision
Recall
F1-Score
