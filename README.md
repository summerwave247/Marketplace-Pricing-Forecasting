# Marketplace Pricing Forecasting

A pricing analytics project built on marketplace transaction data to evaluate alternative forecasting approaches for trading card products.

## Project goal
This project studies how to improve marketplace price guidance by comparing baseline pricing logic with more tailored forecasting methods across products with different trading patterns.

## What this repo includes
- Data cleaning and preprocessing workflows
- Product- and SKU-level feature construction
- Diagnostic analysis of pricing errors
- Clustering of products with different market behavior
- XGBoost forecasting experiments
- ARIMA time-series forecasting experiments

## Repo structure
```text
notebooks/
  01_data_processing_clustering_xgboost.ipynb
  02_sku_features_arima.ipynb
data/
  README.md

## Methods used
-Feature engineering
-Error analysis
-Clustering
-XGBoost
-ARIMA
-Segment-level performance comparison

## Key business question
Which products need more tailored pricing logic, and when does a simple baseline break down?

## Notes
-Raw data is not included in this repository
-The notebooks were originally developed in Jupyter during an iterative project workflow
-This repo keeps the analysis in notebook form for readability and project transparency

## Future improvements
-Refactor repeated logic into scripts
-Add a cleaner evaluation pipeline
-Export a presentation-style summary notebook
