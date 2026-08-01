# Predictive Analytics: Human Cognitive Performance Analysis

## Overview

This project investigates how lifestyle factors influence human cognitive performance using statistical analysis and machine learning techniques. The study examines relationships between sleep duration, stress level, exercise frequency, screen time, caffeine intake, demographic characteristics, reaction time, and memory performance to identify significant predictors of cognitive score.

The project was developed as part of a university Predictive Analytics coursework and demonstrates the complete data analytics workflow, from data preprocessing and exploratory analysis to statistical modelling, clustering, predictive modelling, and model evaluation.

---

## Objectives

The project addresses three main objectives:

1. Analyse the relationships between lifestyle factors and cognitive performance.
2. Investigate the relationship between sleep duration and cognitive performance across different demographic groups.
3. Develop and evaluate predictive models for estimating cognitive performance.

---

## Dataset

The dataset contains approximately **80,000 observations** with variables describing participants' demographics, lifestyle habits, sleep behaviour, and cognitive assessment results.

### Main Variables

* Age
* Gender
* Sleep Duration
* Stress Level
* Exercise Frequency
* Daily Screen Time
* Diet Type
* Caffeine Intake
* Reaction Time
* Memory Test Score
* Cognitive Score

---

## Project Workflow

### 1. Data Understanding

* Dataset inspection
* Missing value checking
* Descriptive statistics
* Distribution of categorical variables

### 2. Data Preprocessing

* Removed unnecessary variables
* Encoded categorical features
* Generated boxplots for outlier inspection
* Performed exploratory data analysis (EDA)
* Generated statistical summaries and feature distributions

### 3. Statistical Analysis

The project includes multiple statistical techniques:

* Multiple Linear Regression
* ANOVA
* Tukey HSD Post-hoc Test
* Correlation Analysis
* Interaction Effect Analysis

---

### 4. Cluster Analysis

Lifestyle profiles were explored using:

* K-Means Clustering
* Gaussian Mixture Models (GMM)
* Elbow Method
* Silhouette Score Evaluation

---

### 5. Predictive Analytics

Three machine learning models were evaluated:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

Model performance was compared using:

* R² Score
* RMSE
* MAE

Additional analyses include:

* Feature selection
* Data partitioning
* Residual analysis
* Error distribution analysis
* Feature importance
* Prediction correlation analysis

---

## Technologies Used

* Python
* pandas
* NumPy
* Matplotlib
* Seaborn
* scikit-learn
* Statsmodels
* SciPy
* PyGAM

---

## Key Analyses Performed

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Statistical hypothesis testing
* Multiple regression modelling
* Correlation analysis
* Lifestyle clustering
* Sleep pattern analysis
* Predictive modelling
* Model comparison
* Feature importance analysis
* Residual diagnostics

---

## Results

The project demonstrates an end-to-end predictive analytics workflow for analysing cognitive performance. Multiple statistical methods and machine learning algorithms were applied to understand lifestyle influences and develop predictive models. Model performance was evaluated using standard regression metrics, while clustering techniques identified groups with similar lifestyle characteristics.

---

## Future Improvements

Possible extensions include:

* Hyperparameter tuning
* Cross-validation
* Additional ensemble learning algorithms
* Explainable AI techniques (e.g., SHAP or LIME)
* Deep learning approaches
* Time-series or longitudinal analysis if temporal data becomes available

