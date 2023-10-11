# CouponExercise
Project for Berkeley certificate AI/ML
# Will a Customer Accept the Coupon?

## Context

This project aims to explore the factors that influence whether a driver will accept a coupon delivered to their cell phone while driving. Several variables such as the type of establishment (restaurant, bar, coffee house, etc.), weather conditions, and time of day are considered.

## Overview

The goal is to leverage data visualization and probability distributions to differentiate between customers who accept coupons and those who don't.

## Data Source

Data is sourced from the UCI Machine Learning repository and collected via an Amazon Mechanical Turk survey. The survey includes a variety of driving scenarios and asks the participant whether they would accept a coupon under those conditions.

## Data Description

### User Attributes
- Gender: male, female
- Age: various ranges
- Marital Status: single, married, etc.
- (Include all other attributes...)

### Contextual Attributes
- Driving destination: home, work, etc.
- Location: geographical data included
- Weather: sunny, rainy, etc.
- (Include all other attributes...)

### Coupon Attributes
- Time before expiration: 2 hours, one day

## Deliverables

A brief report highlighting statistical summaries and visualizations. Code will be included for reproducibility.

## Tools Used
- Python for data manipulation and statistical analysis
- MatPlotLib for data visualization
- Random Forest, Recursive Feature Elimination and Gradient boosting to gauge feature importance
- K-means to segment the user base into clusters
- Silhouette score and Davies-Boudin index to evaluate clusters

## Summary of Findings

### Key Insights
1. **Acceptance Rates**: Acceptance rates for bar coupons vary based on frequency of bar visits and other lifestyle factors.
2. **Significant Variables**: Variables like 'passanger', 'destination', and 'time' significantly influence coupon usage.
3. **Model Complexity**: Different machine learning models yielded varying feature importances, highlighting the complexity of factors influencing coupon usage.

### Methods
- **Data Cleaning**: Handled missing values and outliers.
- **Descriptive Statistics**: Utilized for initial insights.
- **Machine Learning**: Employed Random Forest and Gradient Boosting models for predictive analytics.
- **Clustering**: Utilized K-means for user segmentation.
- **Evaluation Metrics**: Metrics like accuracy, precision, recall, and F1-score used for model evaluation.

### Implications
1. **Marketing Optimization**: Marketing strategies can be optimized by targeting frequent bar-goers and considering the 'passanger' variable.
2. **Model Accuracy**: The model accuracy ranges from 59.6% to 58.3%, indicating room for improvement.
3. **Feature Importance**: The variability in feature importance across models suggests the need for ensemble methods or more sophisticated models for accurate prediction.

## Contributors

- Annika Peacock (https://github.com/AnnikaPeacockAI)

