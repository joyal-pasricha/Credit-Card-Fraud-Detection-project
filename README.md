# Credit-Card-Fraud-Detection-project
🚀 Project Overview

The primary goal of this project was to design and evaluate machine learning models that can detect fraudulent transactions in a highly imbalanced dataset (fraud vs. non-fraud). The challenge was to achieve the best trade-off between precision and recall—minimizing false negatives (missed fraud) while keeping false positives (legitimate transactions flagged as fraud) low.

##🔄 Data Preprocessing

-Applied SMOTE (Synthetic Minority Oversampling Technique) to handle class imbalance and improve model generalization.

- Performed feature scaling, encoding, and data cleaning to ensure consistency across models.

- Split the dataset into training and testing sets for unbiased evaluation.

##🧠 Models Implemented

The following models were developed and compared:

- Logistic Regression – as a baseline linear model.

- Random Forest Classifier – ensemble of decision trees for robust classification.

- XGBoost Classifier – gradient boosting framework optimized for speed and accuracy.

- Neural Network – multi-layer perceptron to capture non-linear relationships.

## 📊 Key Findings

- Both Random Forest and XGBoost delivered the best performance, detecting over 80% of fraudulent transactions while maintaining a relatively low false positive rate.

- Even with imbalanced datasets, good prediction results were achievable; however, balancing with SMOTE improved recall for minority classes.

Trade-off remains critical:

- High recall → More fraud detected but risk of flagging legitimate users.

- High precision → Fewer false positives but risk of missing fraudulent cases.

- Final recommendation: The choice of model depends on business objectives (e.g., banks may prioritize high recall to minimize financial losses, while e-commerce platforms may prefer high precision to reduce customer friction).

## ✅ Conclusion

This project highlights that:

-  There is no universal “perfect” model for fraud detection.

- Businesses must align fraud detection strategy with organizational priorities (customer experience vs. risk tolerance).

- Ensemble methods (Random Forest, XGBoost) currently provide the most effective balance between fraud detection rate and false alarm reduction.
