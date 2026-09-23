
# Raisin Classification using LDA and QDA

## Overview

This project applies **Linear Discriminant Analysis (LDA)** and **Quadratic Discriminant Analysis (QDA)** to classify raisin varieties using their morphological features.

The dataset contains measurements of raisin grains belonging to two classes:

* **Kecimen**
* **Besni**

The project includes data preprocessing, exploratory data analysis, dimensionality reduction, classification, model evaluation, and comparison of LDA and QDA.

## Dataset

The **Raisin Dataset** contains:

* 900 samples
* 7 morphological features
* 2 classes: Kecimen and Besni

The features describe physical and geometric properties of raisin grains.

Dataset source:

**UCI Machine Learning Repository – Raisin Dataset**

https://archive.ics.uci.edu/dataset/850/raisin

## Methods

The project follows these steps:

1. Load and inspect the dataset
2. Perform exploratory data analysis
3. Visualize feature distributions
4. Preprocess and standardize the data
5. Split the data into training and testing sets
6. Apply Principal Component Analysis (PCA)
7. Train an LDA classifier
8. Train a QDA classifier
9. Evaluate classification performance
10. Compare model performance using multiple evaluation metrics

## Models

### Linear Discriminant Analysis (LDA)

LDA assumes a common covariance structure between classes and finds a linear decision boundary for classification.

### Quadratic Discriminant Analysis (QDA)

QDA allows each class to have its own covariance matrix and therefore produces quadratic decision boundaries.

## Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC
* Confusion Matrix
* Log Loss
* Balanced Accuracy
* Cohen's Kappa
* Matthews Correlation Coefficient

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* SciPy
* Scikit-learn
* Jupyter Notebook

## Project Structure

```text
Raisin-LDA-QDA/
│
├── README.md
├── requirements.txt
│
├── notebooks/
│   └── LDA_QDA_Raisin_Code.ipynb
│
├── data/
│   └── Raisin_Dataset.xlsx
│
├── figures/
│   └── project_visualizations
│
└── results/
    └── model_results
```

## How to Run

Clone the repository and install the required Python packages:

```bash
pip install -r requirements.txt
```

Open the notebook:

```text
notebooks/LDA_QDA_Raisin_Code.ipynb
```

Make sure the dataset is available in:

```text
data/Raisin_Dataset.xlsx
```

Then run the notebook cells sequentially.

## Author

Lavudiya Hasini

