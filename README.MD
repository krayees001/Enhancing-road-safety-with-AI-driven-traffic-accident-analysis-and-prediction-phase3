
# AI Road Traffic Accident Severity Prediction

## Overview

This project uses machine learning models to predict the severity of road traffic accidents based on real-world data. The aim is to support traffic authorities and policymakers in reducing road accidents by identifying high-risk conditions and locations using predictive analytics.

## Features

- Data preprocessing (handling missing values, encoding categorical data)
- Exploratory Data Analysis (EDA) using Seaborn and Matplotlib
- Feature engineering (rush hour detection, environmental factors, etc.)
- Training ML models (Random Forest, XGBoost, Logistic Regression)
- Evaluation using classification report and confusion matrix
- Visualization of feature importance and accident hotspots
- Integration of Google Colab for easy simulation

## Dataset

- Source: UK Road Safety Open Data (CSV format)
- Records: ~100,000
- Key Features: Date, Time, Weather, Road Type, Vehicle Type, etc.
- Target Variable: `Accident_Severity` (Slight, Serious, Fatal)

## Technologies Used

- Python 3.8+
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn, XGBoost
- Google Colab

## Installation

1. Upload the CSV file in Google Colab.
2. Run the provided Python script.
3. Visualize the outputs and insights.

## Team Members

| Rayees      | Team Leader                                           |
| Dhushyandh  | UI/UX & Deployment Developer (Streamlit Interface)   |
| Jebaraj     | Documentation & Report Writer                         |
| Jamal       | Visualization & Evaluation Analyst                    |
| Logith      | Data Engineer & Pre-processing Specialist             |


## Output

- Classification Report
- Confusion Matrix
- Top 10 Important Features Bar Chart

## License

This project is for educational and research purposes only.
