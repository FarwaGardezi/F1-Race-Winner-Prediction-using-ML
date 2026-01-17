🏎️ F1 Race Winner Prediction (Python, Machine Learning)

A predictive model built using Random Forest to forecast Formula 1 race winners based on historical race, qualifying, and driver data.

✨ Features

Preprocessed and merged multiple datasets: drivers, races, results, qualifying

Performed data cleaning, feature engineering, and handled missing values

Created a target variable for race winners (1 = winner, 0 = others)

Built a Random Forest model with hyperparameter tuning

Evaluated performance using accuracy, F1-score, and ROC-AUC

Visualized top drivers, circuits, and race trends

Plotted feature importances to identify key factors influencing race outcomes

Includes interactive prediction function: predict win probability for any driver, year, grid/qualifying position, and race round

🛠 Concepts & Tools

Python Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Machine Learning: Random Forest, Feature Engineering, Model Evaluation

Data Visualization: Bar plots, line plots, scatter plots with trend line

🚀 How to Use

Load datasets (drivers, races, results, qualifying).

Run the preprocessing and feature engineering script.

Train the Random Forest model.

Use the predict_driver_win_for_year() function to predict win probability for a given driver and race scenario.

📌 Purpose

This project demonstrates end-to-end data science workflow: cleaning, merging, modeling, evaluation, visualization, and interactive prediction — applied to a real-world sports analytics problem.
