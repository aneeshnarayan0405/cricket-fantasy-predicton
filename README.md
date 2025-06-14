# Cricket Player Performance Prediction using Machine Learning

## 📁 Project Overview

This project predicts cricket player performance using historical match data and machine learning models like Random Forest and XGBoost. It aims to help selectors, analysts, and enthusiasts forecast player outcomes based on past performances.

---

## 📦 Dataset Description

- **ball.csv**: Bowling statistics per player per match (wickets, overs, runs conceded, economy, etc.)
- **bat.csv**: Batting statistics per player per match (runs, balls faced, strike rate, boundaries, etc.)
- **match.csv**: Match-level details (teams, match type, date, total runs, overs, run rate, etc.)

---

## 🧹 Data Processing Steps

1. Loaded CSV files for batting, bowling, and matches.
2. Cleaned and merged datasets to align player performances with match context.
3. Engineered features such as strike rate, economy rate, and player roles.
4. Filtered data to focus on relevant matches and players.

---

## 🧠 Model Details

- **Algorithms Used:** Random Forest Regressor, XGBoost Regressor
- **Features:** Runs, balls faced, strike rate, wickets, overs, economy rate, match conditions
- **Target Variable:** Player performance metrics (e.g., runs scored, wickets taken)

---

## 🛠️ Preprocessing and Training

- Handled missing values and encoded categorical variables.
- Split data into training and testing sets (e.g., 80/20 split).
- Trained models on training data and validated on the test set.
- Evaluated model performance using metrics like Mean Squared Error (MSE) and Mean Absolute Error (MAE).

---

## 📈 Model Performance

- Random Forest and XGBoost models showed strong predictive power.
- Example metric: Final Test MAE around 1.33 (varies by target and features).

---
