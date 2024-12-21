# Feature Engineering and Predictive Modeling for Customer Churn at PowerCo

## Abstract  
This project focuses on advanced **feature engineering** and **predictive modeling** to address customer churn for **PowerCo**, a leading energy provider for SMEs. By leveraging engineered features and machine learning techniques, the goal is to uncover the underlying drivers of churn and improve the prediction accuracy of churn models.

## Key Objectives  
1. **Feature Engineering**:  
   - Enhance the dataset by creating new, meaningful features from existing data.  
   - Investigate price sensitivity metrics, including the difference between off-peak prices in December and January of the preceding year, to assess their impact on churn prediction.  
2. **Predictive Modeling**:  
   - Develop and train a classification model using the engineered dataset.  
   - Evaluate the model's performance with robust metrics such as accuracy, precision, and recall.  
3. **Model Insights**:  
   - Identify critical features driving churn predictions using feature importance analysis.  

## Feature Engineering Process  
1. **Data Refinement**:  
   - Removed redundant or irrelevant columns.  
   - Converted categorical variables into dummy variables and transformed skewed distributions for improved model compatibility.  
2. **Feature Creation**:  
   - Generated features like average and maximum price changes across time periods to capture pricing variance.  
   - Transformed date columns into usable numerical data (e.g., months) and converted boolean columns into binary flags.  
3. **Dataset Enrichment**:  
   - Combined datasets using shared keys to create a unified, enriched dataset ready for modeling.  

## Predictive Modeling Approach  
1. **Model Selection**:  
   - Implemented a **Random Forest Classifier** to predict customer churn, a binary classification problem.  
2. **Training and Testing**:  
   - Split data into training and testing sets to evaluate model performance on unseen data.  
3. **Performance Metrics**:  
   - Assessed the model using accuracy, precision, and recall to balance predictions between churned and non-churned customers.  

## Key Findings  
- **Feature Importance**: Features like **net margin** and **12-month consumption** emerged as critical predictors of churn.  
- **Challenges**: Current features inadequately capture the nuances of churn, suggesting a need for further feature refinement.  
- **Model Performance**: While accurate at predicting non-churn cases, the model requires improvement in identifying customers likely to churn.  




