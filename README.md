# YouTube Ad View Prediction

This project predicts YouTube ad views based on video features using machine learning and deep learning models like Linear Regression, Support Vector Regressor, Decision Tree, Random Forest, and an Artificial Neural Network (ANN). 

## Project Overview

Our goal is to estimate `adview` counts for YouTube videos by analyzing features like `views`, `likes`, `dislikes`, `comments`, `category`, `duration`, and `published` date. This project helps understand how these features contribute to ad engagement and offers predictions that could assist content creators and marketers.

## Data

The dataset includes the following columns: `vidid` (video ID), `views`, `likes`, `dislikes`, `comments`, `published` date, `duration`, `category`, and `adview` (target variable). Data cleaning involved removing outliers, handling erroneous entries, and encoding categorical features.

## Methodology

1. **Data Preprocessing**: Categorical features (`category`, `duration`, `vidid`, `published`) were encoded, and `duration` was converted to seconds. Features were then normalized using MinMaxScaler.
  
2. **Model Training**: We trained and evaluated five models, testing their effectiveness in predicting ad views. Evaluation metrics included Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

3. **Results**: Model performance is compared to determine the most accurate predictions.

## Future Work

Future improvements include hyperparameter tuning, additional feature engineering (e.g., keywords in video titles), and the use of ensemble methods for better prediction accuracy.

## Installation

Clone the repository and install dependencies:
```bash
git clone https://github.com/yourusername/youtube-adview-prediction.git
cd youtube-adview-prediction
pip install -r requirements.txt
```

---

This README provides a concise overview of the project, including the data, methodology, and future directions.
