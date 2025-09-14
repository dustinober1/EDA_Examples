# Iris Dataset EDA

## Overview
The Iris dataset is a classic dataset in machine learning and statistics, containing measurements of iris flowers from three different species. This analysis explores the relationships between the different flower measurements and species.

## Dataset Information
- **Source**: UCI Machine Learning Repository / scikit-learn
- **Size**: 150 rows, 5 columns
- **Type**: Structured, multivariate dataset
- **License**: Public domain

## Key Questions
1. How do the flower measurements vary between species?
2. Which measurements are most distinctive for each species?
3. Are there clear patterns that separate the three species?

## Analysis Highlights
- **Data Quality**: Clean dataset with no missing values
- **Key Findings**: 
  - Setosa species is clearly separable from the other two
  - Petal measurements are more discriminative than sepal measurements
  - Versicolor and Virginica show some overlap in measurements
- **Visualizations**: Scatter plots, box plots, correlation heatmap, pair plots
- **Recommendations**: Petal length and width are the most important features for species classification

## Files in this Directory
- `iris_eda.ipynb` - Main analysis notebook
- `README.md` - This file

## How to Run
1. Ensure you have the main requirements installed: `pip install -r ../../requirements.txt`
2. Open the Jupyter notebook: `jupyter notebook iris_eda.ipynb`
3. Run all cells to reproduce the analysis

## Dependencies
No additional dependencies beyond the main repository requirements. The dataset is loaded directly from scikit-learn.

## Results Summary
The Iris dataset demonstrates clear patterns in flower measurements across species. Setosa flowers are distinctly smaller in petal measurements, while Versicolor and Virginica show gradual differences. This makes it an excellent dataset for demonstrating classification techniques and data visualization methods.