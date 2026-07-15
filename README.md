# bda-applications-2026-CH

# Bike Demand Forecasting Project

This repository contains the implementation and analysis for the bike-sharing demand forecasting project. The study explores the effectiveness of LightGBM-based models using spatiotemporal features and meteorological data.

## Project Contents
- `data/`: Contains the meteorological dataset (e.g., `vienna_weather.csv`).
- `notebooks/`: The main Jupyter Notebook containing data preprocessing, model training, and interpretability analysis.

## Workflow
The project follows these steps:
1. **Data Preprocessing**: Cleaning and feature engineering of historical bike usage and weather data.
2. **Modeling**: Training two LightGBM models—a spatiotemporal baseline and a weather-aware model.
3. **Evaluation**: Assessing convergence trajectories and feature importance using TreeSHAP to ensure model reliability.

## Key Findings
- Implementation and evaluation of two distinct LightGBM-based models.
- Analysis of feature complexity and its impact on model generalization.
- Insights into urban mobility patterns through interpretability tools.

## Requirements
To run the code, ensure the following libraries are installed:
```bash
pip install pandas numpy lightgbm matplotlib shap ipywidgets
