# USD-ZAR Prediction Model 
<small> by Umutesa Munyurangabo </small>

A USD/ZAR prediction model is designed to forecast the exchange rate between the US Dollar (USD) and the South African Rand (ZAR) using deep learning models. The focus is on comparing the following neural network models: Recurrent Neural Networks (RNNs), Long Short-Term Memory (LSTM) networks, and Gated Recurrent Units (GRUs). This project will systematically evaluate the performance of these algorithms, carefully analyzing their capabilities, strengths, and weaknesses in the context of financial time series forecasting. This involves assessing their ability to capture temporal dependencies, manage long-term relationships in sequential data, and handle the inherent complexities of exchange rate prediction, such as volatility and non-linear patterns.

1. **Recurrent Neural Networks (RNNs** : RNNs are a type of neural network designed to work with sequential data, such as time series. Unlike traditional feedforward networks, RNNs use loops to pass information from one step of the sequence to the next. This feature allows them to maintain a form of memory.

![RNN Network](rnn_orgi.jpg)

3. **Long Short-Term Memory (LSTM) Networks** : LSTMs are a special type of RNN designed to overcome the limitations of standard RNNs. They incorporate memory cells and gating mechanisms (input, forget, and output gates) that allow them to selectively retain or discard information over longer periods. This makes them highly effective for modeling long-term dependencies in time series data.

4. **Gated Recurrent Units (GRUs)** : GRUs are a simplified version of LSTMs that use fewer parameters while maintaining a similar level of performance. They combine the input and forget gates into a single update gate and eliminate the output gate altogether. This simplification often makes GRUs computationally more efficient than LSTMs.
