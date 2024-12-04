# PySpark with Google Colab: Analyzing City Temperature Data

## Overview

This repository demonstrates how to use PySpark in Google Colab to perform data analysis and machine learning tasks on a dataset of city temperatures. The workflow includes data loading, preprocessing, exploratory analysis, feature engineering, and predictive modeling.

---

## Features

- **Data Loading**: Load a CSV dataset from Google Drive using PySpark.
- **Data Cleaning**: Filter rows based on conditions, drop unnecessary columns, and handle categorical data using StringIndexer.
- **Exploratory Analysis**:
  - Display row counts and filtered subsets.
  - Plot histograms for numerical distributions.
  - Generate correlation heatmaps.
- **Feature Engineering**:
  - Normalize numerical features using MinMaxScaler.
  - Assemble features for ML models.
- **Machine Learning**:
  - Train a Linear Regression model to predict average temperature.
  - Evaluate the model using RMSE and R² metrics.
  - Visualize predictions versus actual values.

---

## Prerequisites

- **Google Colab**: Ensure you have access to Google Colab.
- **PySpark**: Install PySpark (`!pip install pyspark`).
- **Libraries**: Install additional libraries such as `matplotlib`, `seaborn`, and `sklearn`.

---

## Quick Start

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
