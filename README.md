# Iris Flower Classification

This project trains and evaluates machine learning classification models to identify the species of an iris flower based on its physical measurements.

## Objective

Classify iris flowers into one of three species:

- Setosa
- Versicolor
- Virginica

The model uses four input features:

- Sepal length
- Sepal width
- Petal length
- Petal width

## Tech Stack

- Python
- pandas
- scikit-learn
- matplotlib
- seaborn
- Jupyter Notebook

## Dataset

The project uses the built-in Iris dataset from scikit-learn:

```python
from sklearn.datasets import load_iris
```

No external dataset download is required.

## Project Files

- `iris_flower_classification.ipynb` — main Jupyter Notebook with EDA, visualisations, model training, and evaluation
- `requirements.txt` — Python dependencies required to run the notebook
- `README.md` — project overview and usage instructions

## Features Covered

- Load the Iris dataset
- Perform Exploratory Data Analysis
- Check shape, data types, null values, and descriptive statistics
- Visualise feature relationships using pairplot
- Create box plots for each feature
- Discuss most discriminative features
- Split data into training and testing sets
- Train multiple classifiers
- Evaluate models using:
  - Accuracy score
  - Confusion matrix
  - Classification report
- Identify the best-performing model

## Models Used

- Logistic Regression
- K-Nearest Neighbours
- Decision Tree
- Random Forest

## Setup Instructions

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## How to Run

Start Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
iris_flower_classification.ipynb
```

Run all cells from top to bottom.

## Expected Output

The notebook outputs:

- Dataset summary and statistics
- Pairplot and box plot visualisations
- Model accuracy comparison
- Confusion matrices
- Classification reports
- Best model recommendation with justification

## Feature Selection Summary

Petal length and petal width are usually the most discriminative features in the Iris dataset. Setosa is clearly separated from the other species, while Versicolor and Virginica have some overlap but are still well classified using petal measurements.

## References

- scikit-learn Iris dataset documentation: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_iris.html
- scikit-learn supervised learning guide: https://scikit-learn.org/stable/supervised_learning.html
- seaborn pairplot documentation: https://seaborn.pydata.org/generated/seaborn.pairplot.html
