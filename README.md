# Classification with Logistic Regression
This notebook uses the Breast Cancer Wisconsin dataset to build a binary classifier that predicts whether a tumor is malignant (1) or benign (0).

### Summary:
- Imported and cleaned the dataset
- Encoded target (`diagnosis`) and standardized all features
- Trained a logistic regression model using Scikit-learn
- Evaluated model using:
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-Score)
  - ROC-AUC Score and ROC Curve

### Results:
- Accuracy: 96% (default threshold), 97% (threshold = 0.4)
- ROC-AUC Score: 1.00
- Adjusting the classification threshold improved recall and overall F1-score
- Explained how logistic regression uses the sigmoid function to output probabilities

This project demonstrates how logistic regression can be effectively used for binary medical classification with strong performance.
