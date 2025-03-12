# Ice Cream Sales Prediction Based on Day's Temperature using Machine Learning

This project involves predicting ice cream sales based on the temperature of the day using Machine Learning. It was developed as part of a challenge to enhance Machine Learning skills.

## Project Overview

The goal of this project is to develop a predictive model that can estimate the number of ice cream sales based on the temperature. This can help optimize production, reduce waste, and maximize profits for ice cream vendors.

### Key Steps:

1. **Data Collection**: Gathered historical data of ice cream sales and the temperature of each day.
2. **Data Preprocessing**: Cleaned and preprocessed the data to make it suitable for training.
3. **Model Development**: Built a regression model to predict sales based on temperature.
4. **Model Training**: Trained the model using historical data and evaluated its performance.
5. **MLflow Integration**: Used MLflow to manage and track the model's parameters and performance.
6. **Real-Time Predictions**: Implemented the model for real-time sales prediction.

## Files

- `inputs/`: Contains input data for training and testing the model.
- `model.py`: Script that contains the model training process.
- `train_model.py`: Script that trains and tests the model.
- `predict_sales.py`: Script for making predictions based on input temperature.
- `README.md`: This file.
  
## Insights & Learnings

- The temperature has a strong correlation with ice cream sales.
- Proper feature engineering and model tuning are essential for accurate predictions.
- MLflow provides an easy way to track and manage model training and performance.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ice-cream-sales-prediction.git
   cd ice-cream-sales-prediction

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt

3. Run the model training script:
    ```bash
    python train_model.py

4. To make predictions:
    ```bash
    python predict_sales.py --temperature <TEMPERATURE_VALUE>
