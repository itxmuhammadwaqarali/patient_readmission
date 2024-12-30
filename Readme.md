# Patient Readmission Prediction

This project involves predicting patient readmissions within 30 days using a dataset of hospital records. The goal is to build and evaluate machine learning models to identify high-risk patients and provide actionable insights.

## Project Overview

### Objective
To train and evaluate machine learning models to predict patient readmissions using hospital readmissions data.

### Key Steps
1. Data Preprocessing: Handle missing values, normalize numerical features, and encode categorical features.
2. Exploratory Data Analysis (EDA): Analyze and visualize data to understand distributions and relationships.
3. Model Training: Train Logistic Regression, Random Forest, and XGBoost models.
4. Model Evaluation: Evaluate models using ROC-AUC, confusion matrix, and classification reports.
5. Hyperparameter Tuning: Optimize Random Forest hyperparameters using GridSearchCV.
6. Insights: Summarize findings and provide insights based on the results.

## Dataset
The dataset used for this project contains hospital readmission records with features such as:
- Patient demographics (e.g., age)
- Medical information (e.g., glucose levels, A1C test results)
- Admission details (e.g., time in hospital, number of lab procedures)

### Data Source
The dataset was loaded from a Google Drive directory for analysis in Google Colab.

## Methods and Tools
- **Preprocessing**: OneHotEncoder, StandardScaler, ColumnTransformer.
- **Modeling**: Logistic Regression, Random Forest, XGBoost.
- **Evaluation Metrics**: ROC-AUC, confusion matrix, classification report.
- **Hyperparameter Tuning**: GridSearchCV.
- **Visualization**: Matplotlib, Seaborn.

## Implementation

### Data Preprocessing
- Mapped the `readmitted` column to binary values (`yes` -> 1, `no` -> 0).
- Split the data into training and testing sets (80%-20%).
- Applied normalization for numerical features and one-hot encoding for categorical features.

### Models Trained
1. **Logistic Regression**
   - Achieved ROC-AUC of `0.59%`.
2. **Random Forest**
   - Baseline ROC-AUC of `0.57%`.

### Best Performing Model
- The best Random Forest model after hyperparameter tuning achieved the highest performance.

### Visualizations
- **ROC Curve**: Generated to evaluate the performance of the best Random Forest model.
- **Confusion Matrix**: Visualized for the best model to analyze predictions.


## Conclusion
This project demonstrates the effective use of machine learning to predict patient readmissions, highlighting the importance of feature engineering, model selection, and hyperparameter tuning in achieving high predictive performance.

## Acknowledgments
- Dataset Source: Hospital Readmissions Data.
- Libraries: Scikit-learn, XGBoost, Matplotlib, Seaborn.

## Contact
For queries, reach out to Muhammad Waqar Ali at [itxmewaqar@gmail.com](mailto:itxmewaqar@gmail.com).
