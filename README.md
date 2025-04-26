📋 Project Overview
This project aims to predict the presence of cardiovascular disease (CVD) using various machine learning algorithms. Early prediction of CVD can assist healthcare providers in initiating preventive measures and treatments.
The goal is to evaluate and compare multiple algorithms to find the best-performing model.

📚 Dataset
Dataset includes patient data with various health attributes.

Features include parameters like age, gender, blood pressure, cholesterol levels, etc.

Target variable: presence (or absence) of cardiovascular disease.

⚙️ Technologies Used
Python

Scikit-learn

Pandas

Numpy

Matplotlib

Seaborn

🛠️ Machine Learning Models Applied
Support Vector Machine (SVM)

Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree Classifier

Random Forest Classifier

🔎 Data Preprocessing
Feature Scaling using StandardScaler for SVM, Logistic Regression, and KNN.

No scaling applied for Decision Tree and Random Forest (tree-based models).

📈 Evaluation Metrics
Accuracy

Confusion Matrix

Classification Report (Precision, Recall, F1-Score)

ROC Curve and AUC Score

📊 Results

Model	Accuracy (%)	ROC AUC Score
Support Vector Machine (SVM)	72.01%	—
Logistic Regression	71.78%	—
K-Nearest Neighbors (KNN)	67.68%	—
Decision Tree Classifier	71.87%	—
Random Forest Classifier	72.2%	0.77
Random Forest achieved the highest accuracy and ROC AUC score.

ROC Curve plotted for Random Forest to visualize performance.

📋 Conclusion
Random Forest Classifier was the best-performing model for predicting cardiovascular diseases.

The project highlights the significance of comparing multiple algorithms for effective model selection.

Future work can include hyperparameter tuning and more advanced ensemble techniques for better performance.



