# IrisData-ML

This repository contains an exploratory and predictive modeling analysis using the classic Iris dataset. Through data preprocessing, visualization, feature selection, model evaluation, and statistical testing, this project compares the performance of multiple supervised learning algorithms.

## Project Structure

- `iris.data` — Original dataset (without headers)
- `IrisData.ipynb` — Full notebook: preprocessing, visualization, modeling, evaluation
- `README.md` — This file

## Project Steps

### 1. Data Loading and Cleaning
- Dataset loaded without column headers
- Columns renamed for clarity
- Null values and duplicates removed
- Categorical class labels mapped to numeric values

### 2. Exploratory Data Analysis
- Visualizations: histograms, boxplots, scatterplots, pie chart
- Insights into class distribution, feature spread, and outliers

### 3. Feature Selection
- Correlation matrix computed among numeric features
- Features with absolute correlation above 0.9 removed to reduce redundancy

### 4. Predictive Modeling
- Algorithms used: K-Nearest Neighbors, Decision Tree, Random Forest
- K-Fold Cross-Validation applied for robust evaluation
- Hyperparameter tuning via `ParameterGrid`
- Metrics recorded: F1-score, Accuracy, Precision, Recall

### 5. Statistical Comparison
- Wilcoxon signed-rank test used to compare algorithm performance
- p-values interpreted to determine statistically significant differences

## Technologies Used

- Python 3
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- scipy.stats

## Conclusion

The pipeline successfully identified the top-performing model based on average F1-score. Statistical testing confirmed whether its advantage over others was significant. Results showed that [insert best-performing model] consistently outperformed competing classifiers.

## Author

Developed by [@beatrizmbrm](https://github.com/beatrizmbrm) as a practical machine learning study on classification techniques.
