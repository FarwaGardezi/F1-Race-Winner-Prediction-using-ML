🏎️ F1 Race Winner Prediction

(Python, Machine Learning, XGBoost, Gradio)

A machine learning project that predicts Formula 1 race winners using historical race, qualifying, and driver data.
The backend model is built with XGBoost, and the project includes an interactive gradient-based frontend using Gradio for real-time predictions.

✨ Features

Merged and preprocessed multiple datasets:

Drivers

Races

Results

Qualifying

Performed:

Data cleaning and handling of missing values

Feature engineering for race and driver performance

Target variable creation (Winner = 1, Non-winner = 0)

Built an XGBoost (XGBoostClassifier) model for winner prediction

Tuned model parameters for improved performance

Evaluated model using:

Accuracy

F1-Score

ROC-AUC

Visualized:

Top drivers and circuits

Race performance trends

Feature importance to identify key winning factors

🚀 Interactive Gradient Frontend:

User inputs driver, year, grid/qualifying position, and race round

Model returns win probability instantly via a clean UI

🛠 Concepts & Tools
🔹 Programming & Libraries

Python

pandas, numpy

matplotlib, seaborn

🔹 Machine Learning

XGBoost (Gradient Boosting)

Feature Engineering

Classification & Model Evaluation

🔹 Frontend & Deployment

Gradio (Gradient-based interactive UI)

Model inference via user input

🚀 How to Use

Load datasets:

drivers.csv

races.csv

results.csv

qualifying.csv

Run preprocessing and feature engineering scripts.

Train the XGBoost model.

Launch the Gradio interface.

Enter:

Driver

Season year

Grid / qualifying position

Race round

Get predicted win probability instantly.

📌 Purpose

This project demonstrates a complete end-to-end machine learning workflow:

Data cleaning & merging

Feature engineering

Model training with XGBoost

Performance evaluation

Visualization

User-friendly gradient frontend for real-world interaction

Applied to a sports analytics problem in Formula 1 racing.
