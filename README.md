# Amex_CTR

American Express Click-Through Rate (CTR) Prediction Project

## Overview

This project implements machine learning models to predict Click-Through Rates (CTR) for American Express data. The analysis includes data exploration, preprocessing, feature engineering, and model comparison across multiple algorithms.

## Project Description

The `amex.py` script contains a complete machine learning pipeline for CTR prediction, including:

- **Data Loading & Exploration**: Load and analyze American Express dataset
- **Data Preprocessing**: Cleaning, feature scaling, and normalization
- **Feature Engineering**: Statistical analysis and data visualization
- **Model Development**: Implementation and comparison of multiple ML algorithms
- **Evaluation**: Comprehensive performance metrics and analysis

## Libraries Used

### Data Manipulation & Analysis
- `pandas` - Data manipulation and analysis
- `numpy` - Numerical computing

### Visualization
- `matplotlib` - Plotting library
- `seaborn` - Statistical data visualization

### Statistical Analysis
- `scipy` - Scientific computing

### Machine Learning Models
- `scikit-learn` - Multiple models including:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
- `xgboost` - Gradient Boosting implementation

### Optimization
- `optuna` - Hyperparameter optimization framework

## Models Implemented

1. **Logistic Regression** - Baseline linear model
2. **Decision Tree Classifier** - Tree-based classification
3. **Random Forest Classifier** - Ensemble method
4. **Support Vector Machine (SVM)** - Non-linear classification
5. **K-Nearest Neighbors (KNN)** - Instance-based learning
6. **XGBoost** - Gradient boosting with optimization

## Performance Metrics

Models are evaluated using:
- Confusion Matrix
- Classification Report
- Accuracy Score

## Installation

### Prerequisites
- Python 3.7+
- pip or conda

### Setup

1. Clone the repository:
```bash
git clone https://github.com/sahildhania04/AMEX_CTR.git
cd AMEX_CTR
```

2. Install required dependencies:
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn xgboost optuna
```

## Usage

Run the main script:
```bash
python amex.py
```

The script will:
1. Load the dataset from Google Drive (requires authentication)
2. Perform exploratory data analysis
3. Preprocess and scale features
4. Train multiple models
5. Generate performance comparisons and visualizations

## Dataset

The dataset is loaded from Google Drive. Ensure you have the appropriate permissions and have authorized Colab/your environment to access the data.

## Results

The project generates:
- Statistical summaries
- Visualizations of data distributions
- Model performance comparisons
- Classification reports for each model

## Notes

- The script was originally developed in Google Colab
- Some Colab-specific magic commands are present in the code
- Warnings are suppressed for cleaner output

## Author

Sahil Dhania

## Repository

[GitHub - AMEX_CTR](https://github.com/sahildhania04/AMEX_CTR)

## License

This project is available on GitHub for educational and research purposes.
