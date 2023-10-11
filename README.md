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

### Tools Used
- Python for data manipulation and statistical analysis
- MatPlotLib for data visualization
- Random Forest, Recursive Feature Elimination and Gradient boosting to gauge feature importance
- K-means to segment the user base into clusters
- Silhouette score and Davies-Boudin index to evaluate clusters

## How to Run the Project

1. Clone the repository.
2. Navigate to the project directory.
3. Run `python analysis.py` to generate the report.

## Contributors

- Annika Peacock (https://github.com/AnnikaPeacockAI)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
