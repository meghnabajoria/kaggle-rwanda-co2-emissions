# Emission Analysis and Prediction

This repository contains code for analyzing and predicting emission data. Here's a brief summary of the steps:

- **Data Preparation**: 
  - Data is downloaded from a Kaggle competition.
  - Basic data exploration to understand the dataset's structure.
  - A time series plot is generated to visualize emissions over time.
- **Geographical Analysis**:
  - Geographical plots are used to understand emissions based on latitude and longitude.
  - A folium map is generated for visual representation.
- **Data Transformation**:
  - Irrelevant columns are dropped.
  - Emission data for the year 2020 is corrected.
  - New features, including season and cyclical time representations, are generated.
- **Modeling**:
  - A Random Forest Regressor is trained on the data.
  - Model performance is evaluated using cross-validation.
- **Prediction & Submission**:
  - Predictions are made on the test set.
  - A submission file is created for the Kaggle competition.

For a detailed look, please refer to the Jupyter notebook.
