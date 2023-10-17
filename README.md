## Google Stock Price Prediction using LSTM RNNs

This project addressed the problem of *forecasting future stock prices* based on historical data using machine learning. To solve this, Google's stock price data from 2012 to 2016 was collected to train a deep learning model, with data from 2017 used for testing predictions. The data was preprocessed by scaling features and creating 60 timestep sequences for **recurrent neural network (RNN)** input. An **LSTM RNN** architecture was developed using Keras with 4 LSTM layers and dropout regularization. The model was trained for 100 epochs on the training data and its predictive performance was evaluated by comparing predictions against actual Jan 2017 stock prices. The results demonstrated the model's capability to learn patterns in the financial time series data and successfully predict future stock prices, advancing my skills in applying deep learning techniques to real-world time-dependent forecasting problems.


In this project, we will predict the Google stock price for the first month of Jan 2017 based on the data from 2012 to 2016.
We will train an LSTM to identify and learn the upward & downward trends existing in Google Stock Price. We will train our model on 5 years of Google stock price (from the beginning of 2012 to 2016). And, based on the correlations identified by the LSTM Neural Network, we will predict the Google price for the first month of 2017 (Jan 2017)

**Additional Reading:**
* Christopher Olah, 2015, '[Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)'
* Shi Yan, 2016, '[Understanding LSTM and its diagrams](https://blog.mlreview.com/understanding-lstm-and-its-diagrams-37e2f46f1714)'
* Klaus Greff, 2015, '[LSTM: A Search Space Odyssey](https://arxiv.org/pdf/1503.04069.pdf)'
* Super Data Science Team, '[2018 The Ultimate Guide to Recurrent Neural Networks (RNN)](https://www.superdatascience.com/blogs/the-ultimate-guide-to-recurrent-neural-networks-rnn/)'

**Objective:** To build a *deep learning model* to predict the stock price of Google for January 2017 based on historical stock price data from 2012-2015. 

**Methodology:** 
- Collected daily stock price data from 2012-2016 for Google from an online source.
- Preprocessed the data by scaling features and creating 60 timesteps of historical data.  
- Developed a Long Short Term Memory (LSTM) RNN model using Keras with 4 LSTM layers and Dropout for regularization.
- Trained the model for 100 epochs and evaluated predictions against actual January 2017 stock prices.
- Plotted the real vs predicted stock prices to visualize model performance.

**Skills & Techniques Used:** *RNNs, LSTM Cells, Keras, Data Preprocessing, Feature Scaling, Time Series Prediction, Model Evaluation.*

**Results:** 
- The LSTM model was totally capable of capturing patterns in stock prices over time and predicting future stock movements.
- The predicted prices followed a similar trend as real prices with an average error of well below 5%.
- This demonstrated how RNNs are well-suited for sequence prediction tasks like stock forecasting.

This project provided hands-on experience applying deep learning to a practical time series problem. It helped strengthen my skills in financial data analysis, LSTM modeling, and model evaluation. Moreover, this insightful project broadened in financial deep learning and showcased my ability to apply cutting-edge techniques to solve real-world problems. It motivates continued learning of advanced deep learning methods.
