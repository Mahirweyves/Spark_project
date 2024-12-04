# Spark Session with PySpark in Google Colab

This repository demonstrates how to create a Spark session using PySpark in Google Colab and perform various data preprocessing, visualization, and machine learning tasks on a dataset. The example uses a CSV file containing city temperature data.

---

## Features

### Spark Session Setup
- Use PySpark to create a Spark session in Google Colab.
- Mount Google Drive to access data files.

### Data Loading and Filtering
- Load a CSV file from Google Drive into a Spark DataFrame.
- Filter rows based on specific conditions.

### Data Visualization
- Convert Spark DataFrames to Pandas DataFrames for visualization.
- Create histograms to visualize data distributions.
- Generate a heatmap to show the correlation matrix.

### Data Transformation
- Encode categorical variables using `StringIndexer`.
- Normalize features using `MinMaxScaler`.
- Reorganize columns and drop unnecessary ones.

### Statistical Analysis
- Compute correlation matrices for features.

### Linear Regression
- Train a Linear Regression model using Spark MLlib.
- Evaluate the model using RMSE and R-squared metrics.
- Visualize actual vs. predicted values.

---

## Prerequisites

To run this project, you will need:
- **Python 3.x**
- **Google Colab**
- **PySpark**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---

## Getting Started

### Install PySpark
```bash
!pip install pyspark
