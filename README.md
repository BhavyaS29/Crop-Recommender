# Crop Recommendation System

## Overview
This repository hosts a dataset and codebase for building a crop recommendation system using machine learning techniques. The system aims to assist farmers in making informed decisions about crop selection based on various soil and environmental parameters. The dataset used in this project is augmented from existing data sources on rainfall, climate, and fertilizer information specific to regions in India.

## Dataset
The dataset includes the following fields:

- **N**: Ratio of Nitrogen content in soil
- **P**: Ratio of Phosphorous content in soil
- **K**: Ratio of Potassium content in soil
- **temperature**: Temperature in degree Celsius
- **humidity**: Relative humidity in %
- **ph**: pH value of the soil

These parameters are crucial indicators of soil fertility and environmental conditions that significantly influence crop growth and yield.

## Methodology
Based on the above input parameters, the crop recommendation system employs machine learning algorithms to predict the most suitable crops for a particular farm. The process involves:

1. **Data Preprocessing**: Cleaning and transforming the raw dataset to prepare it for model training.
   
2. **Feature Selection**: Identifying the most relevant features (parameters) contributing to crop suitability prediction.

3. **Model Training**: Developing and evaluating machine learning models such as Logistic Regression and Random Forest and Support Vector Machine predicting crop recommendations.

4. **Model Evaluation**: Assessing model performance using accuracy, precision, recall, and F1-score metrics to ensure reliable recommendations.

5. **Deployment**: Providing a mechanism for farmers to input their soil and environmental data, generating real-time crop recommendations based on the trained models.
