# House Price Analysis and Prediction

## Overview

This project investigates the relationships between house prices and key predictors such as waterfront presence and living area size. Using exploratory data analysis (EDA), hypothesis testing, and regression modeling, the study provides insights to guide real estate business strategies. The dataset includes detailed information on houses, including price, size, and location features.

---

## Features

### **Exploratory Data Analysis**
- Data cleaning, including detection and removal of outliers and data type corrections.
- Visualization of house price distributions and comparison between waterfront and non-waterfront properties.
- Analysis of potential relationships between house prices and predictors.

### **Statistical Analysis**
- **Hypothesis Testing**: Student's t-test, Median test, and Mann-Whitney U test to assess the significance of differences in house prices for waterfront properties.
- **Correlation Analysis**: Examination of relationships between house prices and square meters of living area.

### **Regression Modeling**
- **Ordinary Least Squares (OLS)**: Simple linear regression to model house prices based on living area size.
- **Least Absolute Deviations (LAD)**: Robust regression method addressing outliers and heteroskedasticity.

### **Model Evaluation**
- Assessment of statistical assumptions for both OLS and LAD methods.
- Comparison of model robustness and insights derived from regression outputs.

---

## Key Results

- **Waterfront Properties**: Waterfront houses have significantly higher prices, supported by hypothesis testing results across multiple statistical methods.
- **Living Area Size**: A strong positive linear relationship exists between house prices and living area size, with a correlation coefficient of 0.7.
- **Modeling Insights**: LAD regression, which is robust to outliers, was identified as a more appropriate method than OLS for analyzing house price data.

---

## Repository Structure

