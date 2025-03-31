# 📈 Time Series Models: A Comparative Analysis of Time Series Transformer and LSTM

This project presents a comparative analysis of stock price prediction using two time series models:

- 🧠 **Time Series Transformer** from Hugging Face  
- 🔁 **Long Short-Term Memory (LSTM)** network as a baseline

Both models were trained to forecast future stock prices based on historical time series data.

## 🧪 Objective

The goal was to evaluate and compare the performance of the two models in predicting key financial indicators, namely:

- High price  
- Low price  
- Close price  
- Trading volume

## 📊 Evaluation Metric

Model performance was assessed using the **Symmetric Mean Absolute Percentage Error (sMAPE)**, which is particularly effective for measuring forecasting accuracy in time series data.

## 🏆 Results

The results show that the **Time Series Transformer consistently outperforms the LSTM baseline** across all four financial indicators. This demonstrates the transformer's superior ability to capture complex temporal dependencies in financial time series data.

## 🛠️ Tools & Libraries

- Python  
- PyTorch  
- Hugging Face Transformers  
- NumPy, Pandas  
- scikit-learn  

