Early and accurate detection of breast cancer is crucial in the healthcare sector. This repository provides the program used to compare various machine learning (ML) classifiers and data pre-processing techniques applied to the Wisconsin Diagnostic Breast Cancer (WDBC) dataset for the task of binary classification to distinguish between malignant and benign tumors. 
Seven models are trained and evaluated: Logistic Regression, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), Random Forest, XGBoost, a Multilayer Perceptron (MLP), and a Stacked Ensemble classifier. 
To address class imbalance, the Synthetic Minority Oversampling Technique (SMOTE) was applied, and standard scaling was used to normalize feature distributions.
Performance was assessed using accuracy, precision, recall, F1-score, and AUC metrics. The results showed strong performance across all classifiers, with accuracies all above 95%. 
The Stacked Ensemble classifier achieved the best overall performance, with a test accuracy of 99.12%, F1-score of 98.80%, and AUC of 99.67%, outperforming all other models.

### Stacked ensemble classifier confusion matrix
<div align = "center">
<img width="500" alt="CPU Block Diagram" src="https://github.com/user-attachments/assets/5aa273f9-ad2c-4b95-8ba9-56a96081ecaa">
</div>

### Stacked ensemble classifier and MLP ROC curves
<div align = "center">
<img width="500" alt="CPU Block Diagram" src="https://github.com/user-attachments/assets/832157c2-e0a3-4859-8ebf-e8994aebc6d7">
</div>
