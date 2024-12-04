Spark Session with PySpark in Google Colab

This repository demonstrates how to create a Spark session using PySpark in Google Colab and perform various data preprocessing, visualization, and machine learning tasks on a dataset. The example uses a CSV file containing city temperature data.

Features

Spark Session Setup:

Use PySpark to create a Spark session in Google Colab.

Mount Google Drive to access data files.

Data Loading and Filtering:

Load a CSV file from Google Drive into a Spark DataFrame.

Filter rows based on specific conditions.

Data Visualization:

Convert Spark DataFrames to Pandas DataFrames for visualization.

Create histograms to visualize data distributions.

Generate a heatmap to show the correlation matrix.

Data Transformation:

Encode categorical variables using StringIndexer.

Normalize features using MinMaxScaler.

Reorganize columns and drop unnecessary ones.

Statistical Analysis:

Compute correlation matrices for features.

Linear Regression:

Train a Linear Regression model using Spark MLlib.

Evaluate the model using RMSE and R-squared metrics.

Visualize actual vs. predicted values.

Prerequisites

Python 3.x

Google Colab

PySpark

Matplotlib

Seaborn

Scikit-learn

Getting Started

Install PySpark:

!pip install pyspark

Set Up Google Drive:
Mount your Google Drive to access the dataset:

from google.colab import drive
drive.mount('/content/drive')

Load Dataset:
Replace file_path with the path to your dataset in Google Drive:

file_path = "/content/drive/MyDrive/BigData/city_temperature.csv"
spark_df = spark.read.csv(file_path, header=True, inferSchema=True)

Run Data Preprocessing:

Filter data by year and temperature.

Encode categorical variables.

Normalize numerical features.

Visualize Data:

Use Matplotlib and Seaborn to create plots for insights.

Train and Evaluate Model:

Split data into training and testing sets.

Train a Linear Regression model.

Evaluate the model using RMSE and R-squared metrics.

Example Outputs

Histograms showing data distribution by year and average temperature.

Correlation heatmap for numerical features.

Scatter plot comparing actual vs. predicted average temperature values.

File Structure

spark_session_demo.py: Main script containing all the code.

city_temperature.csv: Sample dataset used for demonstration.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements

PySpark Documentation

Matplotlib Documentation

Seaborn Documentation

