# US Chronic Disease Analysis

This project focuses on analyzing chronic disease data across the United States. It leverages data cleaning, visualization, and regression models to understand trends and predict future chronic disease prevalence.

The project also includes a webpage with model outputs for linear, random forest, and XGBoost regression models, providing interactive access to analysis results.

---

## Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Data Sources](#data-sources)
- [Project Structure](#project-structure)
- [Features](#features)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

---

## Overview
Chronic diseases such as diabetes, heart disease, and obesity significantly impact public health in the U.S. This project aims to provide insights through data analysis and predictive modeling.

---

## Technologies Used
- **Programming Languages:** Python (98.9%), CSS (1.1%)
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Plotly-Dash
- **Models:** Linear Regression, Random Forest, XGBoost
- **Web Deployment:** Azure App Service (or other hosting)

---

## Data Sources
- CDC Chronic Disease Indicators dataset
- Other relevant health data sources

---

## Project Structure
```text
us_chronic_disease_analysis/
│
├── .github/workflows/        # CI/CD workflows for deployment
├── assets/                   # Static files for the web application
├── README.md                 # Project documentation
├── XGB_model.pkl             # Trained XGBoost model
├── cleaning_module.py        # Data cleaning functions
├── linear_regression_model.pkl  # Trained Linear Regression model
├── main.py                   # Entry point for the application
├── regression.py             # Regression model implementation
├── requirements.txt          # Project dependencies
├── rf_model.pkl              # Trained Random Forest model
└── visualization_Module_2.py # Visualization utilities
```
## Features
**Data Cleaning:** Preprocessing and handling missing data.
**Exploratory Data Analysis:** Insights into chronic disease trends.
**Regression Models:** Predicting chronic disease rates using multiple models.
**Web Application:** Interactive page to display and compare model predictions.

## Results
The analysis and models have yielded valuable insights, with an R² score of up to 0.94 for predicting chronic disease trends. The interactive webpage showcases these predictions to help stakeholders make informed decisions.

## Contributing
Contributions are welcome! Submit a pull request or open an issue for feedback or bug reports.

## License
This project is licensed under the MIT License
