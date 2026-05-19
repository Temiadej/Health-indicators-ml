# Predicting Health Conditions with the CDC Health Indicators Dataset

A machine learning project comparing four classification models to predict 
diabetes using lifestyle and socioeconomic features from the BRFSS 2015 dataset.

## Overview
This project explores whether lifestyle factors, socioeconomic factors, 
or a combination of both better predict diabetes outcomes. Four models 
were compared using stratified cross-validation across multiple metrics.

## Dataset
CDC Behavioral Risk Factor Surveillance System (BRFSS) 2015 Health Indicators Dataset
- File: `diabetes_binary_health_indicators_BRFSS2015.csv` (included in this repo)
- Original source: [Kaggle - Diabetes Health Indicators Dataset](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)

## Models Compared
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)

## Key Findings
- Logistic regression outperformed random forest on recall and F1 score
- [Add 1-2 more specific findings with your numbers]

## Methodology
- Stratified k-fold cross-validation
- Multiple scoring metrics: accuracy, precision, recall, F1
- Feature subset comparison across lifestyle, socioeconomic, and combined groupings

## Project Documents
- [Research Proposal](docs/proposal.pdf)
- [Final Report](docs/report.pdf)
- [Presentation](docs/Project.pdf)

## Tech Stack
Python, pandas, scikit-learn, Jupyter Notebook

## Author
Temitayo Adejare — Information Science, University of Illinois Urbana-Champaign
