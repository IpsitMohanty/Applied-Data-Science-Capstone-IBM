# SpaceX Data Analysis and Machine Learning

This repository contains Jupyter notebooks for analyzing SpaceX launch data, performing machine learning predictions, and visualizing data. The notebooks include various data analysis, SQL queries, and machine learning steps using SpaceX data.

## Notebooks

### 1. **SpaceX_Machine_Learning_Prediction_Part_5.jupyterlite.ipynb**
   - **Description**: This notebook focuses on building and training machine learning models using SpaceX launch data. It includes data preprocessing, feature engineering, and model evaluation for predicting launch success.
   - **Key Techniques**:
     - Data cleaning and preprocessing
     - Machine learning model training (e.g., logistic regression, decision trees)
     - Model evaluation and metrics

### 2. **jupyter-labs-eda-dataviz.ipynb.jupyterlite (1).ipynb**
   - **Description**: This notebook is dedicated to Exploratory Data Analysis (EDA) and data visualization using SpaceX data. It includes visualizations to explore patterns, trends, and distributions in the dataset.
   - **Key Techniques**:
     - Data visualization using libraries like Plotly and Matplotlib
     - Statistical analysis to understand data distribution and correlations

### 3. **jupyter-labs-eda-sql-coursera_sqllite (1).ipynb**
   - **Description**: This notebook demonstrates how to perform EDA on SpaceX data stored in a SQL database. It includes SQL queries to fetch, filter, and aggregate data for analysis.
   - **Key Techniques**:
     - SQL queries for data extraction and manipulation
     - Integration of SQL with Python for data analysis

### 4. **jupyter-labs-spacex-data-collection-api-v2 (2).ipynb**
   - **Description**: This notebook focuses on collecting SpaceX data from an API. It demonstrates how to make requests, fetch data, and store it in a format suitable for analysis.
   - **Key Techniques**:
     - Using APIs to fetch SpaceX data
     - Data cleaning and storage for analysis

### 5. **lab-jupyter-launch-site-location-v2 (1).ipynb**
   - **Description**: This notebook visualizes the geographical locations of SpaceX launch sites. It uses folium and other mapping tools to create interactive maps.
   - **Key Techniques**:
     - Data visualization on geographical maps using Folium
     - Analyzing launch site locations and their proximity to coastlines, rail lines, and other infrastructure

## Requirements

To run these notebooks locally, you'll need the following libraries installed:

- **pandas**
- **plotly**
- **dash**
- **folium**
- **matplotlib**
- **scikit-learn**
- **SQLAlchemy** (for SQL-based notebooks)
- **requests** (for API data collection)

You can install these dependencies by running the following command:

```bash
pip install pandas plotly dash folium matplotlib scikit-learn SQLAlchemy requests
