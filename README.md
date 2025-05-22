# Student Dropout Prediction using Machine Learning

This project explores the use of supervised machine learning algorithms to predict whether a student will graduate or drop out based on academic, demographic, and financial features.

## Dataset

The dataset used is **"Predict Students Dropout and Academic Success"** from the UCI Machine Learning Repository.

- Dataset link (https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+successs)

It includes 37 features (36 predictors and 1 target variable) for over 4,400 students enrolled in Portuguese higher education institutions.

## Models Implemented

- Decision Tree  
- Random Forest  
- XGBoost  
- Support Vector Machine (RBF Kernel)  
- Logistic Regression  
- Neural Network

## Preprocessing Steps

- Missing value check  
- Outlier removal (IQR method)  
- Correlation analysis and redundant feature removal  
- SMOTE for class imbalance handling  
- Feature scaling (StandardScaler)

## Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC  
- Cross-validation score  
- Training time and model size

## Findings

XGBoost delivered the best overall performance in terms of accuracy, recall, and generalization. Logistic Regression offered strong interpretability, while Random Forest performed well but showed signs of overfitting.

## Future Work

- Explore unsupervised and semi-supervised learning approaches  
- Apply advanced encoding techniques  
- Tune hyperparameters to further improve model performance  
- Investigate cost-sensitive alternatives to SMOTE

---

**Author**: Koshaliya Shanmugathasan  
**Course**: UFCFMJ-15-M | Machine Learning & Predictive Analytics  
