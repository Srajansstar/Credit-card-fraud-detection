# Credit-card-fraud-detection

# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using various machine learning algorithms. The goal is to identify the most accurate and effective model for predicting fraudulent activity in a dataset.

## Project Overview

Credit card fraud is a significant problem, and detecting fraudulent transactions can help mitigate financial losses and enhance security. In this project, we apply several machine learning algorithms to classify transactions as fraudulent or non-fraudulent. We evaluate the models based on their accuracy, precision, recall, and other performance metrics to select the best model.

## Algorithms Used

The following algorithms were applied and evaluated:

1. **Decision Tree Classifier**
2. **Random Forest Classifier**
3. **Gaussian Naive Bayes (NB)**
4. **K-Nearest Neighbors (KNN)**
5. **Logistic Regression**

## Dataset

The dataset used for this project is the credit card fraud detection dataset, containing information on various transactions labeled as fraudulent or non-fraudulent. It includes features like transaction amount, transaction time, and anonymized principal components.

## Project Workflow

1. **Data Preprocessing**: 
   - Cleaning and preparing the dataset for modeling.
   - Handling missing values, if any.
   - Normalizing and scaling features as needed.

2. **Exploratory Data Analysis (EDA)**:
   - Visualizing data distributions and identifying correlations.
   - Analyzing the distribution of fraudulent vs. non-fraudulent transactions.

3. **Model Implementation**:
   - Training multiple models using the algorithms listed above.
   - Evaluating each model based on metrics such as accuracy, precision, recall, and F1-score.
   - Comparing models to determine the most effective one.

4. **Model Evaluation and Selection**:
   - Selecting the best-performing model based on evaluation metrics.

## Results

After evaluating all models, KNN was the most accurate with determining Fraud Transaction but was very slow in classifying. So for practical use Logistic Regression can be deployed as it was found to be Pretty accurate and faster than any other models.

## Conclusion

This project demonstrates how various machine learning models can be applied and compared for credit card fraud detection. It highlights the importance of model evaluation metrics and the process of selecting and tuning the best model for real-world applications.


