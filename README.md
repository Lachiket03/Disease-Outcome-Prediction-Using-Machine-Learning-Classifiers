# Disease-Outcome-Prediction-Using-Machine-Learning-Classifiers

📚 **Overview**

This project explores the predictive performance of various machine learning classifiers for disease outcome prediction using symptom profiles and patient demographic data. The study compares four classifiers—Logistic Regression, Decision Tree, Random Forest, and AdaBoost—to identify the most effective model for this healthcare application.

📂 **Dataset Information**

The dataset used is the "Disease_symptom_and_patient_profile_dataset", which includes:

Symptoms: Fever, Cough, Fatigue, Difficulty Breathing

Demographics: Age, Gender

Health Indicators: Blood Pressure, Cholesterol Level

Outcome Variable: Binary indicator (Positive/Negative) for disease presence

Note: The "Disease" column was removed during preprocessing as it wasn't required for the predictive modeling task.

🧹 **Data Preprocessing**

Removed Irrelevant Columns: Dropped the 'Disease' column.

Label Encoding: Applied label encoding to categorical variables.

Data Type Conversion: Converted the 'Age' column to integer type.

Duplicate Removal: Removed duplicate records to ensure data integrity.

Exploratory Data Analysis (EDA): Conducted using .info(), .describe(), and .columns, with visualizations for age distribution and gender frequency.

⚡ **Model Evaluation and Results**

🔍 Classifier Performance Comparison

| Classifier               | Accuracy Score | ROC AUC Score |
| ------------------------ | -------------- | ------------- |
| Logistic Regression      | 52.6%          | 0.62          |
| Decision Tree            | 59.2%          | 0.59          |
| Random Forest Classifier | 57.9%          | 0.70          |
| AdaBoost Classifier      | 50.0%          | 0.60          |

Key Insight: The Random Forest Classifier outperformed other models with the highest ROC AUC score of 0.70, indicating superior discriminative ability.

📝 Key Insights & Recommendations

Ensemble Methods: Random Forest demonstrated the best performance amon⚡ Model Evaluation and Results

🔍 **Classifier Performance Comparison**

| Classifier               | Accuracy Score | ROC AUC Score |
| ------------------------ | -------------- | ------------- |
| Logistic Regression      | 52.6%          | 0.62          |
| Decision Tree            | 59.2%          | 0.59          |
| Random Forest Classifier | 57.9%          | 0.70          |
| AdaBoost Classifier      | 50.0%          | 0.60          |
Key Insight: The Random Forest Classifier outperformed other models with the highest ROC AUC score of 0.70, indicating superior discriminative ability.



**Grid search tested classifiers.**

Feature Engineering: Incorporate domain-specific features for improved accuracy.

Model Tuning: Utilize hyperparameter optimization techniques such as Grid Search.

Advanced Ensembles: Explore Gradient Boosting and XGBoost for potential performance gains.

Interpretability: Focus on model explainability for practical healthcare applications.

🌟 **Let's Collaborate!**

If this project interests you, feel free to star ⭐ the repository and contribute to enhancing disease outcome prediction techniques!
