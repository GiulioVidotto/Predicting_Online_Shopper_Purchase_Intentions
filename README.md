# Predicting Online Shopper Purchase Intentions
This project aims to build a machine learning classification model to predict whether or not an online shopper will make a purchase. The dataset used for this project is the **Online Shoppers Purchasing Intention** dataset from the UCI Machine Learning Repository, which includes various features related to online shopper behavior.

## Project Overview

The project is divided into three main steps:
1. **Data Exploration and Preprocessing**:  
   The dataset is first analyzed to identify any correlations between features and the target variable (whether the shopper made a purchase or not). Special attention is given to handling missing data in the `Exit Rate` feature by building a regression model to predict its values.

2. **Classification Model**:  
   After recovering missing values in `Exit Rate`, a classification model is built to predict whether an online shopper will make a purchase based on browsing behavior and other features. Several algorithms are compared to find the best-performing model.

3. **Clustering Models**:  
   The project also explores clustering-based algorithms to classify shoppers' purchase intentions, and compares the performance of these models with the best classification model.

## Dataset Features

The dataset contains over 12,000 samples and includes both categorical and continuous variables, such as:
- Administrative Pages Visited
- Product Pages Visited
- Bounce Rate
- Exit Rate (with missing data to be predicted)
- Special Day (e.g., Mother's Day, Valentine's Day)
- Visitor Type (new or returning)
- Operating System, Browser, Region, and more.

## Methodology

1. **Regression for Missing Data**:  
   A regression model is trained to predict the missing `Exit Rate` values using the remaining features in the dataset.

2. **Classification**:  
   A classification model is built to predict the likelihood of a purchase based on user behavior. The performance of various classification algorithms is evaluated.

3. **Clustering**:  
   Clustering algorithms are used to analyze patterns in shopper behavior, and their performance is compared to the classification models.

## Tools and Libraries Used
- **Python**: Jupyter Notebooks
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## How to Run the Code
1. Clone the repository.
2. Move inside the cloned repository.
3. Open the `Predicting_Online_Shopper_Purchase_Intentions.ipynb` file in Jupyter Notebook.
4. Run all cells to execute the analysis and model building.
5. Ensure all necessary libraries are installed (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`).
