# Air Quality Classification & Pollution Assessment

This project focuses on analyzing and classifying air quality levels based on environmental and pollution-related parameters. Using machine learning classification models, we aim to predict air quality categories and gain insights into contributing factors such as temperature, humidity, population density, and pollutant concentrations.

## 🧾 Project Overview

The project follows a structured machine learning workflow:

1. **Data Collection** - Air quality data with key environmental and pollution metrics.
2. **Exploratory Data Analysis (EDA)** - Visualizing distributions and pollutant relationships.
3. **Data Preprocessing** - Handling missing values, encoding categorical labels, and feature scaling.
4. **Model Training** - Applying multiple classification algorithms.
5. **Model Evaluation** - Comparing performance using metrics like accuracy and confusion matrix.

## 📊 Dataset Description

The dataset contains the following features:

`Temperature`                    
`Humidity`                       
`PM2.5`                          
`PM10`                           
`NO2`                            
`SO2`                            
`CO`                             
`Proximity_to_Industrial_Areas` 
`Population_Density`            
`Air Quality`                   

> Note: The target column `Air Quality` is a categorical label used for classification.

## 🔧 Technologies Used

This project uses the following tools and libraries:

- **Python 3.x**
- `pandas`, `numpy` - Data manipulation and analysis
- `matplotlib`, `seaborn` - Visualization
- `scikit-learn` - Classification models and preprocessing
- `xgboost` - Advanced gradient boosting

## ⚙️ Machine Learning Models

The following models are trained and evaluated:

- Logistic Regression
- Random Forest
- XGBoost Classifier

Each model is compared using:
- Accuracy Score
- Confusion Matrix
- Classification Report

## 📈 Insights

- Pollution levels (especially PM2.5, PM10, and NO2) strongly correlate with poor air quality.
- Population density and proximity to industrial areas also influence classification results.
- XGBoost and Random Forest tend to outperform simpler models in accuracy.
