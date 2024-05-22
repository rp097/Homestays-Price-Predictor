# Homestays Price Prediction

Welcome to the Homestays Price Prediction project! This repository contains a comprehensive analysis and a robust predictive model to estimate the `log_price` of homestay listings. The project leverages various data processing, analysis, and machine learning techniques to provide insights and accurate predictions.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Steps and Tasks](#steps-and-tasks)
  - [1. Feature Engineering](#1-feature-engineering)
  - [2. Exploratory Data Analysis (EDA)](#2-exploratory-data-analysis-eda)
  - [3. Geospatial Analysis](#3-geospatial-analysis)
  - [4. Sentiment Analysis on Textual Data](#4-sentiment-analysis-on-textual-data)
  - [5. Amenities Analysis](#5-amenities-analysis)
  - [6. Categorical Data Encoding](#6-categorical-data-encoding)
  - [7. Model Development and Training](#7-model-development-and-training)
  - [8. Model Optimization and Validation](#8-model-optimization-and-validation)
  - [9. Feature Importance and Model Insights](#9-feature-importance-and-model-insights)
  - [10. Predictive Performance Assessment](#10-predictive-performance-assessment)
- [Final Deliverables](#final-deliverables)
- [Installation and Usage](#installation-and-usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The primary objective of this project is to build a predictive model to estimate the `log_price` of homestay listings based on various features such as characteristics, amenities, and host information. The project involves data cleaning, feature engineering, exploratory data analysis, model development, and evaluation.

## Dataset

The dataset used in this project is provided in the `Homestays_Data.csv` file, which is extracted from the `Homestays_Data.zip`. It contains multiple columns and over 70,000 rows of homestay listing data.

## Steps and Tasks

### 1. Feature Engineering

- **Host_Tenure**: Calculated the number of years from `host_since` to the current date to measure host experience.
- **Amenities_Count**: Counted the items listed in the `amenities` array to quantify property offerings.
- **Days_Since_Last_Review**: Calculated the days between `last_review` and today to assess listing activity and relevance.

### 2. Exploratory Data Analysis (EDA)

- Analyzed the correlation between `log_price` and various categorical and numerical features.
- Used visualizations such as correlation matrices, histograms, and scatter plots to explore relationships.

### 3. Geospatial Analysis

- Plotted listings on a map using `latitude` and `longitude` data to assess price distribution.
- Examined the influence of neighborhoods and proximity to city centers on pricing.

### 4. Sentiment Analysis on Textual Data

- Applied sentiment analysis to the `description` texts to extract sentiment scores.
- Incorporated sentiment scores into the predictive model as a feature.

### 5. Amenities Analysis

- Parsed and analyzed the `amenities` provided in the listings.
- Identified which amenities are most associated with higher or lower prices using statistical tests.

### 6. Categorical Data Encoding

- Applied one-hot encoding to variables like `room_type`, `city`, and `property_type` for machine learning analysis.

### 7. Model Development and Training

- Designed and trained predictive models starting with linear regression.
- Explored more complex models such as RandomForest and GradientBoosting.

### 8. Model Optimization and Validation

- Used grid search to experiment with different hyperparameters settings.
- Validated model choices through k-fold cross-validation to ensure generalization.

### 9. Feature Importance and Model Insights

- Analyzed the trained models to identify significant features impacting `log_price`.
- Utilized feature importance scores and SHAP values for in-depth understanding.

### 10. Predictive Performance Assessment

- Evaluated model performance using RMSE and R-squared metrics.
- Provided a detailed analysis of residuals to check for model biases or misfit.

## Final Deliverables

- **Comprehensive Jupyter Notebook**: Contains all codes, analytical steps, visualizations, and detailed commentary.
- **PDF Export of the Notebook**: For easy viewing and sharing.

## Installation and Usage

To run the project locally, clone the repository and then open the jupyter notebook:

   ```bash
   git clone https://github.com/yourusername/Homestays_Price_Prediction.git


