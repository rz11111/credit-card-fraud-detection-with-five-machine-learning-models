# Credit Card Fraud Detection with Five Machine Learning Models
This repository encompasses a variety of business analytic projects including Python, Power BI, and Keynote.

## 1. Overview
This project focuses on credit card fraud detection, employing five distinct machine learning models implemented with under- and over-sampling techniques in **Python**. Visualisations of the datasets are created using **Power BI**, while model performance evaluations are summarised using **Keynote**. By leveraging these tools, our primary objective is to effectively identify fraudulent credit card transactions and determine which machine learning models and resampling techniques yield the best performance.

## 2. Major Tools
- Python
- Jupyter Notebook
- Power BI Desktop
- Apple Keynote

## 3. About Dataset
**Data Source:** Machine Learning Group - ULB, Andrea. (2017). Credit Card Fraud Detection, Version 3. Available at: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud.

**Data Content**: The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where there were 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.173% of all transactions.It contains only numerical input variables which are the result of a PCA transformation. Due to confidentiality issues, there are not provided the original features and more background information about the data. 

## 4. Machine Learning Analysis
This **machine learning analysis** encompasses both data exploration and credit card fraud detection using various machine learning models, including Random Forest, Logistic Regression, K-Nearest Neighbors, Support Vector Machine, and neural networks using TensorFlow. These models are implemented with Random Under-sampling and Synthetic Minority Over-sampling Technique (SMOTE). Below is the table of contents of the Jupyter Notebook. (View details in [repository](https://github.com/rz11111/credit-card-fraud-detection-with-five-machine-learning-models/blob/main/Python%20-%20Machine%20Learning%20Analysis/credit-card-fraud-detection.ipynb))

1. About Dataset
2. Import Libraries
3. Read Dataset
   - Check Columns and Rows
   - Check the Dataset
   - Check Missing Data
4. Data Exploration
   - Class
   - Amount and Time
   - Feature Correlation
5. Feature Scaling
6. Predictive Models (Without Under-/Over-sampling)
   - Train Test Split
   - Random Forest
   - Logistic Regression
   - K-Nearest Neighbors
   - Support Vector Machine
   - Neural Networks Using TensorFlow
   - Performance Comparison
7. Predictive Models (With Random Under-sampling)
   - Resampling
   - Random Forest
   - Logistic Regression
   - K-Nearest Neighbors
   - Support Vector Machine
   - Neural Networks Using TensorFlow
   - Performance Comparison
8. Predictive Models (With SMOTE - Synthetic Minority Over-sampling Technique)
   - Random Forest
   - Logistic Regression
   - K-Nearest Neighbors
   - Support Vector Machine
   - Neural Networks Using TensorFlow
   - Performance Comparison
9. Summary

## 5. Data Visualisation 
This data visualisation was created by loading, cleansing, and preprocessing the dataset in **Power BI Desktop**, showcasing the dataset's key characteristics. (View in [repository](https://github.com/rz11111/credit-card-fraud-detection-with-five-machine-learning-models/blob/main/Power%20BI%20-%20Data%20Visualisation/powerbi-dashboard.pdf))

![powerbi-dashboard.png](https://github.com/rz11111/credit-card-fraud-detection-with-five-machine-learning-models/blob/main/Power%20BI%20-%20Data%20Visualisation/powerbi-dashboard.png)

## 6. Model Performance Evaluation 
The following pages provide a glimpse into the summary of the performance of the five machine learning models before and after implementing resampling techniques, as created in **Keynote**. (View the complete version in [repository](https://github.com/rz11111/credit-card-fraud-detection-with-five-machine-learning-models/blob/main/Keynote%20-%20Model%20Performance%20Evaluation/model-performance-evaluation.pdf))

![model-performance-evaluation-image-02.png](https://github.com/rz11111/credit-card-fraud-detection-with-five-machine-learning-models/blob/main/Keynote%20-%20Model%20Performance%20Evaluation/Images/model-performance-evaluation-image-02.png)

![model-performance-evaluation-image-04.png](https://github.com/rz11111/credit-card-fraud-detection-with-five-machine-learning-models/blob/main/Keynote%20-%20Model%20Performance%20Evaluation/Images/model-performance-evaluation-image-04.png)

![model-performance-evaluation-image-06.png](https://github.com/rz11111/credit-card-fraud-detection-with-five-machine-learning-models/blob/main/Keynote%20-%20Model%20Performance%20Evaluation/Images/model-performance-evaluation-image-06.png)

![model-performance-evaluation-image-11.png](https://github.com/rz11111/credit-card-fraud-detection-with-five-machine-learning-models/blob/main/Keynote%20-%20Model%20Performance%20Evaluation/Images/model-performance-evaluation-image-11.png)

![model-performance-evaluation-image-12.png](https://github.com/rz11111/credit-card-fraud-detection-with-five-machine-learning-models/blob/main/Keynote%20-%20Model%20Performance%20Evaluation/Images/model-performance-evaluation-image-12.png)






