# Machine Learning Hackathon – Predicting Bicycle Traffic 

This repository contains my project from the **Hackathon of the Machine Learning course**.  
The goal was to **predict daily bicycle traffic counts** using weather data, holiday information, and seasonal effects.  
The project was organized as a Kaggle competition, where teams submitted predictions and were ranked by **Mean Absolute Error (MAE)**.

---

## Project Overview
- **Task:** Regression – Predict the number of bicycles passing a counting station per day.  
- **Data:**  
  - Daily bike counts (2012–2024)  
  - Weather variables (temperature, precipitation, sunshine, wind, …)  
  - Calendar features (weekdays, months, holidays, school holidays)  
- **Goal:** Achieve a lower MAE than the linear regression baseline (MAE = 620.3).  

---

## Methods & Models
- Data preprocessing and feature engineering (handling seasonality, weather features, holidays).  
- Tried multiple machine learning models, including:  
  - Linear Regression (baseline)  
  - Tree-based methods (Random Forest, Gradient Boosting, CatBoost)  
  - Neural network baseline (EfficientNetB0 for time series representation in the extended part).  
- Hyperparameter tuning for improved performance.  

---

## Results
- Successfully achieved MAE below the benchmark (Linear Regression).  
- Best submission placed competitively on the Kaggle leaderboard.  
- Demonstrated teamwork, model comparison, and reproducible ML pipeline design.  

---

## Repository Structure
.
├── hyperparamaniacs.ipynb   # Jupyter notebook with code & results
├── README.md                # Project description
├── requirements.txt         # Dependencies
└── .gitignore               # Ignore unnecessary files

## How to Run
1. Clone the repository:
   ```bash
   git clone https://gitlab.com/Eliftpskl/ml-hackathon-bicycle-traffic.git
   cd ml-hackathon-bicycle-traffic
2. Install dependencies:

  pip install -r requirements.txt

3. Open the notebook:

  jupyter notebook hyperparamaniacs.ipynb

   
