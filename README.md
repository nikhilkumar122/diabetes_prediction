# Diabetes_prediction

Building machine learning models to accurately predict whether or not the patients in the dataset have diabetes.

## Diabetes Prediction Project

This project aims to predict the onset of diabetes in individuals using machine learning models. The dataset used contains information about several health metrics such as glucose levels, blood pressure, skin thickness, insulin levels, BMI, age, and diabetes pedigree function, along with the target variable indicating whether the individual developed diabetes or not.

### Data Preprocessing:

Investigated the dataset for missing values and unusual zero values in features.
Filled missing values with median values.
Visualized the distribution of features using histograms and violin plots.

### Feature Scaling:

Standardized the features to have a mean of 0 and a standard deviation of 1 to ensure all features contribute equally to the model.

### Handling Class Imbalance:

Used SMOTE (Synthetic Minority Over-sampling Technique) to balance the target variable, as the dataset had an imbalance in the number of diabetes cases.

### Modeling:

Trained several classification models, including Logistic Regression, Support Vector Machine, K-Nearest Neighbors, Decision Tree, Random Forest, and XGBoost.
Utilized GridSearchCV for hyperparameter tuning to improve model performance.

### Model Evaluation:

Evaluated the models using F1 score, which is suitable for imbalanced classification tasks.
Compared the performance of each model to determine the best performing model.

### Stacking Models:

Stacked the best performing models, XGBoost and Random Forest, to improve prediction accuracy.

### Conclusion:
The stacked model showed improved performance compared to individual models, achieving a higher F1 score for diabetes prediction.

### Next Steps:
Further analysis could include feature selection to identify the most important features for prediction and fine-tuning the stacked model for better performance.
