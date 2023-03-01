# Prastuti-Workshop-1-Assignment

## Iris Dataset Description

The Iris dataset is a classic example of a supervised learning problem. It consists of 150 observations of iris flowers, each with measurements for four features (sepal length, sepal width, petal length, and petal width) and a corresponding label indicating the iris species (setosa, versicolor, or virginica). The dataset is widely used in machine learning and data mining for classification and clustering tasks.

The Iris dataset is included in many machine learning libraries, such as scikit-learn in Python, and can also be downloaded from various online sources.

## Assignment

Here's an assignment you can give to your workshop participants based on the Iris dataset:

 - Download the Iris dataset and load it into your machine learning environment.
 - Split the dataset into training and testing sets.
 - Train a linear regression model to predict the sepal width based on the other features.
 - Train a logistic regression model to classify the iris species based on the four features.
 - Train an artificial neural network (ANN) with one hidden layer to classify the iris species.
 - Write a brief report summarizing your findings and conclusions from the analysis of the Iris dataset.
 - Note: You can use any programming language and machine learning library of your choice to complete this assignment.

The iris dataset has been provided in this github 


## What is Google Colab?

Google Colab is a cloud-based platform for developing and running machine learning models using the Python programming language. It provides a free environment with access to powerful computing resources, including GPUs and TPUs, which are useful for training large models quickly. Google Colab also allows users to share their notebooks with others, making it a useful tool for collaboration.

You need to do your assignment in google colab

## How to use Google Colab for the machine learning assignment?

To use Google Colab for the machine learning assignment, follow these steps:

 - Go to the Google Colab website: https://colab.research.google.com/
 - Click on "New Notebook" to create a new notebook.
 - Choose a runtime type (e.g., Python 3, GPU, TPU) and click on "Create".
 - Import the necessary libraries (e.g., numpy, pandas, scikit-learn) using the "import" statement.
 - Load the Iris dataset into the notebook using the appropriate method (e.g., pandas.read_csv).
 - Split the dataset into training and testing sets using the appropriate method (e.g., train_test_split from scikit-learn).
 - Train the machine learning models (e.g., linear regression, logistic regression, ANN) on the training data using the appropriate methods from scikit-learn or other libraries.
 - Evaluate the performance of the models on the testing data using the appropriate metrics (e.g., accuracy, F1 score, mean squared error).
 - Write a brief report summarizing your findings and conclusions from the analysis of the Iris dataset.

This Iris dataset that you have to work on is given here only as iris.csv

## What is pandas?

Pandas is a popular Python library for data manipulation and analysis. It provides data structures for efficiently storing and processing large datasets, as well as a wide range of functions for data cleaning, aggregation, and visualization.

## How to use pandas to load the Iris dataset?

To load the Iris dataset into a pandas DataFrame, follow these steps:

Import the pandas library using the "import" statement:

```python
import pandas as pd
```

Load the Iris dataset from the CSV file (iris.csv) using the "read_csv" function:

```python
iris_df = pd.read_csv("iris.csv")
```

Optionally, you can view the first few rows of the dataset using the "head" function:

```python

print(iris_df.head())
```

This will display the first 5 rows of the dataset, including the column headers.

## How to manipulate the Iris dataset using pandas?

Once the Iris dataset is loaded into a pandas DataFrame, you can use a variety of functions to manipulate and analyze the data. Here are a few examples:

Select specific columns:
```python
# select the sepal length and petal width columns
sepal_petal_df = iris_df[['sepal_length', 'petal_width']]
```

Filter rows based on a condition:

```python
# filter the rows where the species is setosa
setosa_df = iris_df[iris_df['species'] == 'setosa']
```

Group the data by a column and compute summary statistics:

```python
# group the data by species and compute the mean values for each column
species_mean_df = iris_df.groupby('species').mean()
```

Visualize the data using pandas plotting functions:

```python
# create a scatter plot of sepal length vs. sepal width
iris_df.plot(kind='scatter', x='sepal_length', y='sepal_width')
```

Note: These are just a few examples of the many functions available in pandas. For more information, see the pandas documentation at https://pandas.pydata.org/docs/.




