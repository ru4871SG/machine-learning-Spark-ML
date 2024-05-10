# Machine Learning with Spark ML

This repository contains different Jupyter notebooks that demonstrate how to use Spark ML for Machine Learning tasks.

## Notebooks

1. [Linear Regression](linear-regression-spark-ml.ipynb): This notebook demonstrates how to use Spark ML's Linear Regression to predict house prices. It uses the `housing.csv` dataset.

2. [Logistic Regression](logistic-regression-spark-ml.ipynb): This notebook shows how to use Spark ML's Logistic Regression for classification tasks. It uses the `seeds.csv` dataset.

3. [Clustering](clustering-spark-ml.ipynb): This notebook illustrates how to use Spark ML's K-means clustering model. The dataset used in this notebook is `drybeans.csv`.

## Datasets

The datasets used in these notebooks are located in the `sources/` directory:

- `housing.csv`
- `seeds.csv`
- `drybeans.csv`

## Requirements

To run these notebooks, you need to install `PySpark`, `findspark`, `Jupyter`, `mlxtend`, and `scikit-learn`.