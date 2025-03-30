Project Overview

This project implements a Support Vector Machine (SVM) classification model to predict customer responses to bank marketing campaigns. The dataset contains over 41,000 records with 20 features related to customer demographics, financial information, and campaign details.
Key Features

    Data Analysis: Performed comprehensive EDA to understand data distributions and relationships

    Data Cleaning: Handled duplicates and prepared data for modeling

    Feature Engineering:

        Standardized numerical features

        One-hot encoded categorical variables

        Applied PCA for dimensionality reduction

    Class Imbalance Handling: Used RandomOverSampler to address imbalanced target classes

    Model Development: Built and evaluated an SVM classifier with:

        90.5% accuracy

        86.5% precision

        95.8% recall

Technical Highlights

    Python with scikit-learn, pandas, numpy, and matplotlib/seaborn

    Comprehensive data visualization for EDA

    Pipeline-based preprocessing

    Cross-validation for optimal PCA components

    Detailed model evaluation metrics

Results

The SVM model demonstrates strong performance in predicting customer subscription to term deposits, with particularly high recall indicating effective identification of potential customers.
