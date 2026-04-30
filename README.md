#  NTPC Time Series Forecasting

## Dataset  
**NTPC.csv – NTPC Limited (National Thermal Power Corporation Limited)**  

---

## Overview  
This dataset contains historical stock market data of NTPC, a company listed in the NIFTY-50 index. It is a **time-series dataset**, where each record represents daily stock trading information.

---

## Features  
The dataset includes the following attributes:  
- Prev Close  
- Open  
- High  
- Low  
- Last  
- Close  
- VWAP  
- Volume  
- Turnover  
- Trades  
- Deliverable Volume / % Deliverable  

---

## Objective  
The objective of this project is to perform **multi-output time-series forecasting** using deep learning models like LSTM/GRU to predict future stock values based on past data.

---

## Methodology  

### 1. Data Preprocessing  
- Handled missing values  
- Removed duplicate records  
- Checked and corrected data formats  

### 2. Data Preparation  
- Normalized the dataset  
- Created sequences using sliding window technique  
- Example:  
  - Input: Last 5 or 10 days data  
  - Output: Next 5 days prediction  

### 3. Model Implementation  
- Built LSTM/GRU model using PyTorch  
- Trained the model on historical data  

### 4. Evaluation  
- Evaluated performance using regression metrics  

---

## Evaluation Metrics  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  
- Mean Absolute Error (MAE)  

---

## Results  
The predicted values are compared with actual values using graphs to analyze model performance.

---

## Tools & Technologies  
- Python  
- PyTorch  
- Pandas  
- NumPy  
- Matplotlib  

---

## Conclusion  
This project demonstrates how deep learning models like LSTM/GRU can be applied to time-series data for predicting multiple stock attributes effectively.

---
