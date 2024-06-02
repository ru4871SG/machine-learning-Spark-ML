# Machine Learning with Spark ML

This repository contains different Jupyter notebooks that demonstrate how to use Spark ML for Machine Learning tasks.

## Notebooks

1. [Linear Regression](linear_regression_spark_ml.ipynb): This notebook demonstrates how to use Spark ML's Linear Regression to predict house sale prices. It uses the `housing.csv` dataset.

2. [Logistic Regression](logistic_regression_spark_ml.ipynb): This notebook shows how to use Spark ML's Logistic Regression for classification tasks. It uses the `drybeans.csv` dataset.

3. [Clustering](clustering_spark_ml.ipynb): This notebook illustrates how to use Spark ML's K-means clustering model. The dataset used in this notebook is `seeds.csv`.

4. [Linear Regression to Predict Sales](linear_regression_predict_sales_spark_ml.ipynb): This notebook utilizes Spark ML's Linear Regression to make sales predictions for the year 2023 and 2024, using a data source that contains different search terms for the year 2020, 2021, and 2022. The dataset used in this notebook is `searchterms.csv`. Additionally, this notebook showcases how to persist a model for future use.

## Datasets

The datasets used in these notebooks are located in the `sources/` directory:

- `drybeans.csv`
- `housing.csv`
- `seeds.csv`
- `searchterms.csv`

## Requirements

To run these notebooks, you need to install `PySpark`, `findspark`, `Jupyter`, `mlxtend`, and `scikit-learn`.