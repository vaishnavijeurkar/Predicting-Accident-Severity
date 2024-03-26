# Predicting Road Traffic Accident Severity

### Overview
The FARS dataset comprises statistics of US road traffic accidents, with over 100,000 examples and 30 features. This project aims to predict the severity of accidents by classifying them into one of seven predefined labels using machine learning techniques.

### Business Understanding
The project aims to improve road safety by leveraging machine learning to predict and classify accident severity. This assists stakeholders such as transportation authorities and emergency services in resource allocation and preventive measures, thereby reducing human and economic costs associated with accidents.

### Approach
1. **Data Preprocessing:** 
   - 80-20 train-test split.
   - MinMax scaling for numerical features.
   - One-Hot encoding for categorical features.
   - Addressing class imbalance using SMOTE.

2. **Model Implementation:**
   - Logistic Regression with LDA.
   - Support Vector Machine (SVM) with PCA.
   - Random Forest.
   - Decision Tree.

3. **Evaluation:**
   - K-fold cross-validation.
   - Hyperparameter tuning for Random Forest and Decision Tree models.
   - SVM with PCA achieved a validation set accuracy of 79.18%.

### Outcome
The SVM model demonstrates competitive accuracy levels in predicting accident severity. The project showcases a systematic approach from data preprocessing to model implementation, resulting in a well-performing machine learning model.
