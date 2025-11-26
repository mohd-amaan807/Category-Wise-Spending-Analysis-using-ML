# Indian Spending Across Categories

## Overview

This project analyzes how Indian consumers distribute their spending across major categories such as food, travel, healthcare, entertainment, utilities, and shopping. The aim is to uncover behavioral patterns, identify meaningful customer segments, and build models that help businesses understand and predict spending tendencies.

## Objectives

* Explore category-wise spending at individual and segment levels
* Understand demographic influences on spending behavior
* Build engineered features that highlight important patterns
* Perform segmentation to group consumers with similar habits
* Evaluate segment stability and generate actionable insights

## Dataset

The dataset includes consumer spending across multiple categories along with demographic information. Common fields:

* Age, gender, income, city type
* Monthly or aggregated category spending
* Time-related fields: month, quarter, festival periods

## Steps in the Project

### 1. Data Loading & Cleaning

* Load raw dataset and fix inconsistent formats
* Handle missing values and outliers
* Convert timestamps to usable features

### 2. Exploratory Data Analysis

* Category-wise heatmaps and distribution plots
* Monthly and seasonal spending trends
* Correlations between categories
* Income and demographic comparisons

### 3. Feature Engineering

* Spend ratios per category
* Essential vs luxury index
* Volatility in monthly spending
* Festival spending multiplier

### 4. Segmentation & Modeling

* K-Means, Hierarchical Clustering, or GMM
* Optionally train predictive models if labeled targets exist
* Save cluster assignments and summary profiles

### 5. Insights & Outputs

* Cluster-level behavior summaries
* Charts and SHAP-based explanations
* Final metrics saved in the outputs folder

## Project Structure

```
indian-spending-analysis/
├─ data/
├─ notebooks/
├─ src/
├─ models/
├─ outputs/
├─ README.md
├─ BLUEPRINT.md
└─ requirements.txt
```

## How to Run

1. Create a virtual environment and install dependencies:

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

2. Run the notebooks inside the `notebooks/` folder.
3. Processed data, charts, and model outputs will be saved automatically.

## Next Steps

* Add forecasting models for monthly category spend
* Build a Streamlit dashboard
* Enhance demographic segmentation

