# Principal Component Analysis (PCA) on Digits Dataset

This project demonstrates the implementation of Principal Component Analysis (PCA) for dimensionality reduction using Python.

## Project Overview
High-dimensional datasets often contain many features that may be redundant or highly correlated. PCA helps reduce the number of features while preserving the most important information in the data.

In this project, PCA is applied to the **Digits dataset** to analyze how much variance each principal component explains.

## Dataset
The dataset used in this project is the Digits dataset from Scikit-Learn.

- Contains images of handwritten digits (0–9)
- Each image is represented by **64 features (8×8 pixels)**

## Steps Performed
1. Imported required Python libraries
2. Loaded the digits dataset
3. Converted the dataset into a DataFrame
4. Separated features (X) and target labels (y)
5. Standardized the dataset
6. Applied PCA
7. Calculated explained variance for each component
8. Visualized individual and cumulative explained variance

## Key Result
The explained variance plot shows that a smaller number of principal components can capture most of the dataset’s information, reducing dimensionality while preserving variance.

## Visualization
The project includes a visualization showing:
- Individual explained variance
- Cumulative explained variance across principal components

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Project File
`PCA-Principle Component Analysis.ipynb`

## Learning Outcome
This project helped in understanding how PCA works for dimensionality reduction and how it can simplify complex datasets while retaining important patterns.

## Author
Ronit Mathur  
Data Science & AI Learner
