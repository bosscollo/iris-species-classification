# Iris Species Classification 

This project trains and evaluates 3 machine learning models to classify Iris flower species:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest Classifier

## Dataset
- Source: [sklearn.datasets.load_iris](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)
- Features: Sepal length, sepal width, petal length, petal width
- Classes: Setosa, Versicolor, Virginica

## Models & Evaluation
Each model is trained and evaluated with:
- Accuracy
- Precision / Recall / F1-Score
- Confusion Matrix
- ROC AUC Score
- Cross-validation

## How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
