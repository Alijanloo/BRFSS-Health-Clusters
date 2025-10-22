# BRFSS Health Clusters

Behavioral clustering and chronic disease analysis using BRFSS (Behavioral Risk Factor Surveillance System) data to identify high-risk population groups and understand the relationship between lifestyle patterns and chronic health conditions.

## 🎯 Project Overview

This project employs unsupervised machine learning techniques to cluster individuals based on their health-related behaviors and analyze the correlation between these behavioral clusters and chronic disease prevalence. Using the comprehensive BRFSS dataset, we identify distinct lifestyle patterns and their associated health risks.

### Key Objectives
- **Behavioral Clustering**: Group individuals with similar health behaviors using K-means and DBSCAN algorithms
- **Risk Stratification**: Identify high-risk population segments for targeted health interventions
- **Pattern Analysis**: Discover correlations between lifestyle factors and chronic disease outcomes
- **Public Health Insights**: Provide actionable insights for preventive healthcare strategies

## 📊 Dataset

**Source**: Behavioral Risk Factor Surveillance System (BRFSS) 2023
- **Size**: 433,323 respondents across the United States
- **Scope**: Nationally representative health survey data
- **Variables**: 50+ behavioral, demographic, and health outcome indicators

### Key Variable Categories
- **Behavioral Factors**: Smoking, alcohol use, physical activity, diet, BMI
- **Chronic Conditions**: Diabetes, hypertension, heart disease, stroke, asthma
- **Demographics**: Age, gender, race/ethnicity, education, income

## 🔬 Statistical Methods

- **Clustering Validation**: Silhouette analysis, within-cluster sum of squares
- **Association Testing**: Chi-square tests for categorical outcomes
- **Risk Quantification**: Odds ratios with 95% confidence intervals
- **Visualization**: PCA dimensionality reduction for cluster interpretation

### Key Insights
- Behavioral patterns strongly predict chronic disease risk
- High-risk cluster represents 1/3 of population requiring focused interventions
- Lifestyle factors cluster together, enabling holistic health approaches
