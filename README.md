# Stock Price Prediction using LSTM

**Project Overview**

This project focuses on predicting stock prices using a Long Short-Term Memory (LSTM) neural network. The model is trained on past stock price data and uses sequential layers of LSTM units to capture temporal dependencies for better predictions.

**Data Collection and Preprocessing**

Data Collection: Day-wise historical stock prices of selected companies were gathered.

**Preprocessing Steps:**

1. Data discretization

2. Data transformation

3. Data cleaning

4. Data integration

5. Feature selection

**Model Architecture**

1. Input Layer: Sequential input layer

2. LSTM Layers: Three LSTM layers for learning temporal dependencies

3. Dense Layer: One dense layer with activation function

4. Output Layer: A final dense layer with a linear activation function

**Training Process**

1. The model is initialized using random weights and biases.

2. The training dataset is fed into the network.

3. Predictions are generated and compared with actual target values.

4. The error difference is calculated.

5. The Backpropagation algorithm is used to minimize the error by adjusting biases and weights iteratively.

**Implementation**

1. Implemented in Python using TensorFlow/Keras.

2. Data preprocessing handled using pandas and NumPy.

3. Visualization performed using Matplotlib and Seaborn.

**Expected Outcomes**

1. Accurate predictions of stock price trends based on historical data.

2. Ability to generalize well on unseen stock price patterns.

***Future Enhancements***

1. Incorporating additional financial indicators for better accuracy.

2. Using Attention mechanisms to improve model performance.

3. Deploying the model as an API or mobile application.

**Author**
***Gaurav Mandloi***
