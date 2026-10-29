Ice Cream Sales Predictor (TensorFlow / Keras)
An end-to-end Machine Learning model built with TensorFlow and Keras to predict daily ice cream sales based on ambient temperature using Single-Variable Linear Regression.
📌 Project Overview
This project demonstrates how a single-neuron neural network learns real-world physical relationships from numeric data. Given historical daily temperature records and corresponding sales figures, the model fits an optimal linear mapping (y = mx + c) to forecast revenue for target temperatures.
🛠️ Key Technical Details
Frameworks: TensorFlow, Keras, NumPy
Architecture: Sequential model with 1 Dense layer (units=1, input_shape=[1])
Optimization: Used the Adam optimizer (learning_rate=0.1) to resolve gradient explosion (NaN outputs) caused by standard SGD on unnormalized feature ranges.
Loss Function: Mean Squared Error (MSE)
🚀 How to Run
Open the .ipynb notebook directly in Google Colab via the badge above.
Run all code cells sequentially to train the model over 500 epochs.
Pass a target temperature (e.g., 35^\circ\text{C}) to model.predict() to evaluate the predicted sales output.
