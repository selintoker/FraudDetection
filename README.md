# FraudDetection

Leveraged advanced anomaly detection techniques, including Isolation Forest and Autoencoders, to accurately identify fraudulent transactions within a highly imbalanced credit card dataset. This project was developed as part of AI4ALL's Ignite program, which provides cutting-edge resources and mentorship in AI.

## Problem Statement <!--- do not change this line -->

Credit card fraud poses significant risks to financial institutions and customers, resulting in billions of dollars in losses annually. This project aims to enhance fraud detection by applying unsupervised machine learning techniques to accurately identify fraudulent transactions while minimizing false positives. The impact of this work is twofold: improving financial security and enhancing customer trust in online transactions.

## Key Results <!--- do not change this line -->

Autoencoder Model:
Precision (Fraud): 0.13
Recall (Fraud): 0.36
F1 Score (Fraud): 0.19
ROC AUC: 0.64
Accuracy: 0.89
Isolation Forest Model:
Precision (Fraud): 0.25
Recall (Fraud): 0.25
F1 Score (Fraud): 0.25
ROC AUC: 0.61
Accuracy: 0.95
While the Isolation Forest model achieved a higher overall accuracy and precision for non-fraudulent transactions, the Autoencoder model performed better in identifying fraud (higher recall) despite its lower precision. These results highlight the trade-off between precision and recall, which is crucial for evaluating fraud detection models.

## Methodologies <!--- do not change this line -->

Applied the following methodologies to achieve project goals:

Data Preprocessing
Feature Scaling: Applied standard scaling to normalize features and ensure consistency in data.
Principal Component Analysis (PCA): Used PCA for dimensionality reduction to handle the dataset's high dimensionality.
Model Selection
Isolation Forest: An unsupervised anomaly detection technique that isolates anomalies by partitioning the dataset recursively.
Autoencoder Neural Networks: A type of neural network designed to learn efficient data representations, useful for anomaly detection when trained in an unsupervised manner.
Model Evaluation
The models were evaluated using the following metrics:

Precision, Recall, F1 Score, and Accuracy to assess performance on both fraud and non-fraud transactions.
ROC AUC to understand the trade-off between the true positive rate (sensitivity) and false positive rate (1 - specificity).
Area Under the Precision-Recall Curve (AUPRC): Given the highly imbalanced nature of the dataset, AUPRC was used as a more reliable performance metric.


## Data Sources <!--- do not change this line -->

Kaggle Datasets: [Link to Kaggle Dataset 1](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud), [Link to Kaggle Dataset 2](https://www.kaggle.com/c/ieee-fraud-detection/)

## Technologies Used <!--- do not change this line -->

- Python
- NumPy
- pandas
- scikit-learn
- TensorFlow
- Matplotlib
- Jupyter Notebooks
- VS Code
- GitHub


## Authors <!--- do not change this line -->

This project was completed in collaboration with:
- Selin Toker
- Sebastian Nares
- Virinchi Vanjarapu
- Tatenda Joseph
- Amrit Shakya
