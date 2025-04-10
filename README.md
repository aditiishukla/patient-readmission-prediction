Predicting Patient Readmission Risk Using Supervised Learning
This project focuses on developing a machine learning model to predict the likelihood of a hospital patient being readmitted, using structured clinical data. Accurate prediction of readmission risk is critical for improving patient care and reducing healthcare costs. The model is built using logistic regression, a widely used algorithm for binary classification tasks.

The dataset includes patient demographics, admission and discharge details, diagnosis information, and other relevant attributes. The preprocessing pipeline involves handling missing values, encoding categorical features, and applying feature scaling to prepare the data for modeling.

Logistic regression was selected for its interpretability and efficiency. The model is evaluated using accuracy, confusion matrix, precision, recall, F1-score, ROC-AUC, and precision-recall curves. Visualizations include a correlation heatmap, target distribution, and a feature influence plot based on model coefficients to enhance transparency and understanding of feature contributions.

This repository contains the complete Jupyter Notebook with all implementation steps, visualizations, and evaluation metrics. The trained model is also saved using joblib for future integration or deployment.

This project demonstrates the application of supervised learning in the healthcare domain and highlights the importance of explainability in predictive modeling. Potential extensions include addressing class imbalance, experimenting with ensemble methods, and deploying the model in a real-world setting.
