
# 📈 Stock Market Prediction using LSTM (AAPL)

This project focuses on predicting the **closing stock prices of Apple Inc. (AAPL)** using **LSTM (Long Short-Term Memory)**, a type of recurrent neural network specialized for time series data.

---

## 🔍 Project Overview

- ✅ **Dataset**: `aapl.us.txt` from Kaggle (contains historical stock data)
- ✅ **Target**: Predict **future closing prices**
- ✅ **Model**: Deep Learning using **LSTM**
- ✅ **Tools**: Python, pandas, seaborn, matplotlib, TensorFlow/Keras

---

## 📊 What Was Done

1. **Data Loading & Cleaning**  
   Loaded and parsed the text dataset, checked for nulls, and visualized key patterns.

2. **Exploratory Data Analysis (EDA)**  
   - Visualized trends in Close, High, and Low prices  
   - Correlation heatmaps and line plots for pattern discovery

3. **Data Preprocessing**  
   - Normalized the data using `MinMaxScaler`  
   - Created sequences of past 60 days to predict the next day  
   - Split data into train and test sets

4. **Model Building with LSTM**  
   - Used stacked LSTM layers with dropout to prevent overfitting  
   - Trained the model using historical close prices  
   - Visualized training/validation loss

5. **Evaluation**  
   - Compared real vs predicted prices  
   - Calculated regression metrics

---

## 🧪 Final Results

| Metric                     | Value   |
|---------------------------|---------|
| Mean Squared Error (MSE)  | 33.7630 |
| Root Mean Squared Error   | 5.8106  |
| R² Score                  | 0.9653  |

✅ The model achieved **high accuracy**, with an R² score of **96.53%**, meaning it explains most of the variability in stock price trends.

---

## 📁 How to Use

1. Upload the `aapl.us.txt` file to your Kaggle notebook or local project  
2. Run the notebook / script  
3. Modify sequence length or LSTM layers to experiment further


---

