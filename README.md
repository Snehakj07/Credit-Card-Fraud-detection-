# Credit-Card FraudDetection
Developed a machine learning model to detect fraudulent credit card transactions. Preprocessed imbalanced data, selected key features, identified outliers and used mutilple algorithms to explore which model better fits. Achieved high accuracy and AUC-ROC, minimizing false positives to ensure secure and reliable fraud detection.
# Data Source
The dataset used for Credit-Card Fraud detection is available on Kaggle. You can find the dataset and additional information: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

# Data Preprocessing
The dataset underwent the following preprocessing steps:

Handling Imbalanced Data: Techniques such as oversampling (SMOTE) or undersampling were applied to address class imbalance.

Normalization: Features were scaled to ensure uniformity and improved algorithm performance.

Data Splitting: The dataset was divided into training and testing sets to evaluate the model effectively.

# Outlier Detection
Outliers were detected and handled to reduce noise in the dataset, improving model robustness.

# Modeling
Multiple machine learning algorithms were explored to identify the most suitable model for fraud detection:

Logistic Regression

Decision Trees

Random Forest

Hyperparameter tuning was performed to optimize each model.

# Evaluation Metrics
To ensure reliable fraud detection, the following metrics were used: 

Accuracy: Overall correctness of the model.	

AUC-ROC: Measures the trade-off between true positive and false positive rates.

Precision: Proportion of true fraud cases among predicted frauds.

Recall (Sensitivity): Proportion of actual fraud cases detected.

F1-Score: Balance between precision and recall.

# Results
The final model achieved:

High Accuracy: Effectively distinguished between fraudulent and non-fraudulent transactions.

AUC-ROC: Demonstrated robust performance across thresholds.

Minimized False Positives: Ensured legitimate transactions were not falsely flagged.

# Contributing

Contributions are welcome! If you have suggestions or find issues, feel free to open an issue or submit a pull request.
