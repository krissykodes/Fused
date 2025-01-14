# Corn Yield Prediction  

This repository contains v0 of Kristin's corn yield prediction model, leveraging Solar Induced Fluorescence (SIF) measurements and Fused UDFs for geospatial data analysis.  

## Overview  
The model predicts corn yields using three SIF measurements and a walk-forward validation approach to ensure robust out-of-sample performance.  

## Steps  
1. **Baseline Model**: Create a national-level linear model as a benchmark.  
2. **Data Retrieval**: Use Fused UDF-Cornucopia for accessing and processing data.  
3. **Random Forest Model**: Implement county-level yield predictions.  
4. **Walk-Forward Validation**: Train/test splits by year for robust performance evaluation.  
5. **Holdout Testing**: Reserve a final dataset to measure out-of-sample accuracy.  

## Goals  
- Create a scalable, accurate crop yield prediction model that outperforms USDA June predictions.  
- Demonstrate predictive power for the years 2015–2020.  
- Lay the foundation for building a real-time predictive model to enable actionable insights for for commodity traders.  
