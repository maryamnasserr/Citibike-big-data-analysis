# Citi Bike Big Data Analysis

## Overview

This repository contains a Big Data Analytics project that analyzes the Citi Bike dataset using Apache Spark and Python. The project demonstrates large-scale data processing, feature engineering, exploratory data analysis, SQL-based analytics, machine learning, and interactive dashboard visualization.

The objective is to uncover user behavior patterns, identify operational insights, and build predictive models using distributed data processing techniques.

---

## Dataset

The project uses the Citi Bike trip dataset, which contains information about bike trips, including:

- Trip start and end times
- Start and end stations
- Rider demographics
- Bike identifiers
- User type
- Geographic coordinates
- Trip duration

---

## Project Objectives

The project aims to:

- Process large datasets using Apache Spark.
- Clean and preprocess raw trip data.
- Engineer new analytical features.
- Perform business-oriented analysis using Spark SQL.
- Build machine learning models using Spark ML.
- Develop an interactive dashboard for visualization.

---

## Technologies Used

- Python
- Apache Spark
- PySpark
- Spark SQL
- Spark ML
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Project Workflow

The notebook follows the following workflow:

1. Data Loading
2. Data Cleaning
3. Missing Value Handling
4. Duplicate Detection
5. Feature Engineering
6. Exploratory Data Analysis
7. Business Intelligence Queries
8. Machine Learning
9. Interactive Dashboard Development

---

## Feature Engineering

Several new features were created to improve analysis, including:

- Rider Age
- Trip Duration
- Trip Distance
- Trip Speed
- Period of Day
- Start Month
- Season
- Day Type
- Noise Detection Flag
- Age Group

---

## Business Analysis

The project investigates several business questions, including:

- Round-trip behavior by user type
- Most popular start stations
- Peak commuting hours
- Trip duration by age group
- Seasonal riding patterns
- Bike utilization for maintenance planning
- User destination preferences
- Most common station pairs
- Gender-based riding behavior
- Weekday versus weekend usage

---

## Machine Learning

Three machine learning models were developed using Spark ML:

- Logistic Regression
- Decision Tree
- Random Forest

The models were trained to predict rider gender using engineered trip features.

### Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 67.7% |
| Decision Tree | 74.1% |
| Random Forest | 74.1% |

Random Forest and Decision Tree achieved the highest prediction accuracy.

---

## Dashboard

An interactive dashboard was developed using ipywidgets and Matplotlib to visualize:

- Hourly demand
- Seasonal usage
- User type distribution
- Station popularity
- Station pair analysis
- Age group behavior
- Gender analysis
- Bike utilization
- Trip duration
- Weekend versus weekday behavior

---

## Key Findings

Some important insights from the analysis include:

- Bike demand peaks during morning and evening commuting hours.
- Subscribers primarily use bikes for commuting, while customers use them more for recreational trips.
- Summer records the highest bike usage, while winter has the lowest.
- Certain stations consistently experience the highest traffic and require greater operational capacity.
- A small number of bikes account for a significant share of total usage and should be prioritized for maintenance.
- Rider age is the strongest predictor in the machine learning models.

---

## Repository Contents

```
├── CitiBike_Big_Data_Analysis.ipynb
└── README.md
```

---

## Learning Outcomes

This project strengthened practical skills in:

- Distributed data processing
- Apache Spark
- Spark SQL
- Spark ML
- Feature engineering
- Business intelligence
- Machine learning
- Interactive dashboard development
- Data visualization

---

## Author

**Maryam Nasser**

Business Informatics Student

German International University (GIU)
