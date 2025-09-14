# Prac2: Supervised Machine Learning

This repository contains a comprehensive Jupyter Notebook covering supervised machine learning techniques for classification and regression.

## Overview

This practical covers:

### Classification Algorithms:
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Naïve Bayes
- Logistic Regression

### Regression Algorithms:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## Datasets

The following datasets are included:

1. **Iris.csv** - Flower species classification (iris dataset)
2. **headbrain.csv** - Head size vs brain weight regression
3. **bank.csv** - Bank deposit prediction classification
4. **diabetes.csv** - Diabetic vs non-diabetic classification
5. **adult.csv** - Income factors classification
6. **50_Startups.csv** - Startup profit regression
7. **AirPassengers.csv** - Airline passengers time series regression

## Files Structure

```
Prac2/
├── Prac2_Supervised_ML_Complete.ipynb    # Main comprehensive notebook
├── datasets/                             # All datasets
│   ├── Iris.csv
│   ├── headbrain.csv
│   ├── bank.csv
│   ├── diabetes.csv
│   ├── adult.csv
│   ├── 50_Startups.csv
│   └── AirPassengers.csv
├── requirements.txt                      # Python dependencies
└── README.md                            # This file
```

## Installation & Setup

1. Clone the repository:
```bash
git clone <repository-url>
cd Prac2
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open `Prac2_Supervised_ML_Complete.ipynb`

## Notebook Contents

The notebook is organized into the following sections:

1. **Introduction & Setup** - Import libraries and setup
2. **Iris Classification** - Multi-class flower species classification
3. **Head-Brain Regression** - Simple linear regression example
4. **Bank Deposit Prediction** - Binary classification with categorical features
5. **Diabetes Classification** - Medical data binary classification
6. **Adult Income Classification** - Income prediction with mixed features
7. **Startup Profit Regression** - Multi-feature regression analysis
8. **Air Passengers Regression** - Time series regression
9. **Performance Summary** - Comprehensive model comparison

## Key Features

- **Complete Implementation**: All major supervised learning algorithms
- **Real-world Datasets**: Diverse datasets from different domains
- **Comprehensive Analysis**: Data exploration, visualization, and model evaluation
- **Performance Comparison**: Side-by-side model comparison with metrics
- **Educational Content**: Detailed explanations and insights

## Results Summary

The notebook demonstrates:
- How different algorithms perform on various types of data
- The importance of data preprocessing and feature scaling
- Model selection guidelines based on data characteristics
- Evaluation metrics for both classification and regression tasks

## Dependencies

- pandas >= 2.0.0
- numpy >= 1.21.0
- matplotlib >= 3.5.0
- seaborn >= 0.11.0
- scikit-learn >= 1.0.0
- jupyter >= 1.0.0

## Usage

Simply run all cells in the notebook to see the complete analysis. Each section can also be run independently for focused learning on specific algorithms or datasets.

The notebook includes:
- Data loading and exploration
- Feature preprocessing
- Model training and evaluation
- Visualization of results
- Performance comparisons
- Key insights and recommendations