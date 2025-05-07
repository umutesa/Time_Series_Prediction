# USD-ZAR Prediction Model Using Deep Learning Models
<small> by Umutesa Munyurangabo </small>

A USD/ZAR prediction model is designed to forecast the exchange rate between the US Dollar (USD) and the South African Rand (ZAR) using deep learning models. The focus is comparing the following deep neural network models: Artficial Neural Network (ANNs) , Recurrent Neural Networks (RNNs), Long Short-Term Memory (LSTM) networks, and Gated Recurrent Units (GRUs). This project will systematically evaluate the performance of these algorithms, carefully analyzing their capabilities, strengths, and weaknesses in the context of financial time series forecasting. This involves assessing their ability to capture temporal dependencies, manage long-term relationships in sequential data, and handle the inherent complexities of exchange rate prediction, such as volatility and non-linear patterns. Using historical exchange data retrieved from Yahoo Finance, we evaluate various neural network architectures designed to model temporal dependencies in financial time series. The goal is to provide accurate short- and long-term forecasts to support decision-making in trading, risk management, and economic analysis

### About the Dataset

The Yahoo Finance dataset contains historical stock market data collected over several years. It is particularly valuable for conducting trend analysis, exploring correlation relationships, and building predictive models. For our analysis, we focus specifically on the closing price.
##### **Attributes**:
- **Date**: The date when the stock market data was recorded.
- **Open**: The opening price of the stock on that particular date.
- **High**: The highest price the stock reached during the trading day.
- **Low**: The lowest price the stock dropped to during the trading day.
- **Close**: The closing price of the stock on the same date.

**License**:
This dataset is sourced from Yahoo Finance and is intended for analytical purposes. Please refer to Yahoo Finance's terms of use for detailed information regarding data usage and licensing.

### Training, Testing and Validation
We divided the dataset into two portions: 80% was allocated for training the model, while the remaining 20% was set aside for testing purposes. The training data is used to teach the model, allowing it to learn patterns and relationships in the data. The testing data, on the other hand, serves to evaluate the model's performance by assessing its accuracy and effectiveness in making predictions on unseen data. This approach ensures that the model generalizes well and avoids overfitting, providing a reliable measure of its predictive capabilities.

## Objectives

- Forecast the USD/ZAR exchange rate using past values and time-lagged features.
- Compare and evaluate model performance across ANN, RNN, LSTM, and GRU architectures.

1. **Artificial Neural Networks (ANNs)**: ANNs are neural networks inspired by the human brain that consist of layers of interconnected nodes (neurons) designed to process data in a feed forward manner and identify patterns. ANNs adjust their weights during training through backpropagation and gradient descent to minimize errors, enabling accurate predictions on new data.
  - Feed-forward multilayer perceptron (MLP)
  - Input layer flattened from time windows
  - ReLU activations, dropout regularization 

3. **Recurrent Neural Networks (RNNs)** : RNNs are a type of neural network designed to work with sequential data, such as time series. Unlike traditional feedforward networks, RNNs use loops to pass information from one step of the sequence to the next. This feature allows them to maintain a form of memory.
  - Simple RNN layers capturing sequential order
  - Prone to vanishing gradient in long sequences

5. **Long Short-Term Memory (LSTM) Networks** : LSTMs are a special type of RNN designed to overcome the limitations of standard RNNs. They incorporate memory cells and gating mechanisms (input, forget, and output gates) that allow them to selectively retain or discard information over longer periods. This makes them highly effective for modeling long-term dependencies in time series data.
  - Advanced recurrent unit with forget, input, and output gates
  - Preserves long-term dependencies through cell states


7. **Gated Recurrent Units (GRUs)** : GRUs are a simplified version of LSTMs that use fewer parameters while maintaining a similar level of performance. They combine the input and forget gates into a single update gate and eliminate the output gate altogether. This simplification often makes GRUs computationally more efficient than LSTMs.
  - Efficient alternative to LSTM
  - Merges memory and gating into a simpler structure


