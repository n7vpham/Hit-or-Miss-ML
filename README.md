# Hit or Miss: Game Edition

A machine learning project for predicting the commercial success of video games based on features like platform, genre, and review scores. This project compares logistic regression and neural network models to classify whether a game will sell over one million units globally.

## 📊 Problem Statement

The video game industry is increasingly competitive, with only a small portion of titles achieving high sales. This project explores the use of data-driven models to predict whether a newly released game is likely to be a commercial hit, helping developers and publishers make more informed decisions.

## 🧠 Models Implemented

- **Logistic Regression** (Scikit-learn)
  - Balanced class weights
  - Learning curve analysis
- **Neural Network** (TensorFlow & Keras)
  - 3 hidden layers: 128 → 64 → 32 neurons (ReLU)
  - Sigmoid output activation
  - Manual class weighting and early stopping
  - Threshold tuning for improved recall

## 🧾 Dataset

- Source: [Kaggle – Video Game Sales with Ratings](https://www.kaggle.com/datasets/rush4ratio/video-game-sales-with-ratings)
- Records: 16,719 games
- Features: platform, genre, rating, critic/user scores, sales regions, release year

## 📄 Final Report

The full project write-up includes:
- Motivation and industry background
- Data preparation steps
- Visual and statistical analysis
- Confusion matrices and model performance
- Learning curves and overfitting discussion

📥 [Download the Final Report (PDF)](./Hit-or-Miss-ML-Final-Report.pdf)

## 🚀 Technologies Used

- Python
- Scikit-learn
- TensorFlow & Keras
- Jupyter Notebook
- Pandas, NumPy, Matplotlib
