# Bank Customer Churn Analysis

## Project Overview

This repository contains a comprehensive analysis and predictive modeling project focused on identifying factors contributing to customer attrition (churn) within a bank. The goal is to develop machine learning models, specifically Logistic Regression, to accurately forecast which customers are at high risk of churning, allowing the bank to proactively intervene.

---

## Repository Structure

The project workflow is organized into sequential Jupyter Notebooks:

| File | Description |
| :--- | :--- |
| `BankChurmers.csv` | The raw dataset containing customer details and their churn status. |
| `01_Data_Preprocessing.ipynb` | Steps for data cleaning, handling missing values, feature engineering, and preparing the data for model training. |
| `02_Linear_Regression_Insights.ipynb` | Initial exploratory data analysis (EDA) using Linear Regression to gain insights into data relationships and potential feature importance. |
| `03_Logistic_Regression_Model.ipynb` | The core machine learning notebook for building, training, evaluating, and tuning the final Logistic Regression model for churn prediction. |
| `sample-architecture.txt` | A high-level description or diagram of the architectural setup for deploying and serving the churn prediction model. |
| `docker-compose.yml` | Configuration file for setting up the project environment using Docker, ensuring portability and reproducibility. |

---

## Getting Started

### Prerequisites

To run the notebooks locally, you will need Python and the following libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
