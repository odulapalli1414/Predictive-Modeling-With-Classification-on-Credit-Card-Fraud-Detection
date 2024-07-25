**Name:** Odulapalli Hitesh  
**Company:** CODETECH IT SOLUTIONS   
**ID:** CT08DS4579                                              
**Domain:** DATA SCIENCE   
**Duration:** JULY10th, 2024 to AUGUST 10th, 2024  
**Mentor:** Santhosh  

# Overview of the Project
## Project: Predictive Modeling With Classification on Credit Card Fraud Detection

This project focuses on detecting fraudulent transactions in a credit card dataset using various data processing, visualization, and machine learning techniques. Given the highly unbalanced nature of the dataset, specific techniques such as SMOTE for oversampling the minority class are utilized to improve model performance.

## Objective

- Detect fraudulent transactions in credit card data.
- Address the class imbalance problem in the dataset.
- Evaluate the performance of different machine learning algorithms.

## Key Activities

1. **Data Understanding and Preparation:**
   - Loaded and explored the dataset.
   - Checked for missing values and cleaned the data.
   - Analyzed the class distribution and visualized data features.
   - Applied SMOTE for oversampling the minority class to balance the dataset.

2. **Data Visualization:**
   - Created correlation heatmaps.
   - Visualized the distribution of transaction times and the class distribution using pie charts and density plots.

3. **Model Training and Evaluation:**
   - Trained multiple machine learning models including Logistic Regression, Naive Bayes, and Decision Tree Classifier.
   - Evaluated model performance using accuracy, precision, recall, F1-score, and Matthews correlation coefficient.
   - Visualized confusion matrices for each model.

4. **Hyperparameter Tuning:**
   - Used GridSearchCV to optimize hyperparameters for the Decision Tree Classifier.

## Technologies Used

**Programming Language:**
- Python

**Libraries:**
- **Data Processing:** pandas, numpy
- **Visualization:** matplotlib, seaborn, plotly
- **Machine Learning:** scikit-learn
- **Resampling:** imblearn (SMOTE)
- **Hyperparameter Tuning:** GridSearchCV

## Key Points

- **Dataset Characteristics:**
  - The dataset contains transactions made by European cardholders in September 2013.
  - It includes 284,807 transactions, with 492 identified as fraud (0.172% of the dataset).

- **Challenges:**
  - The primary challenge was the extreme imbalance in the dataset, with the majority of transactions being non-fraudulent.
  - This required applying techniques like SMOTE to create a balanced training set.

- **Machine Learning Models:**
  - Logistic Regression
  - Naive Bayes
  - Decision Tree Classifier

- **Evaluation Metrics:**
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Matthews Correlation Coefficient

- **Hyperparameter Tuning:**
  - GridSearchCV was used for fine-tuning the Decision Tree Classifier to achieve optimal performance.

## Conclusion

This project successfully demonstrates the application of machine learning techniques to detect fraudulent transactions in an imbalanced dataset. By leveraging data processing, visualization, resampling techniques, and rigorous evaluation, the models developed can help in identifying fraudulent activities with improved accuracy.

