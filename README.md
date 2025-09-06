# Time Series Classification with Neural Networks on the Ford-A Dataset
## Overview
This project focuses on the classification of time series data from the FordA dataset. The primary goal is to predict whether a specific engine noise pattern indicates a fault. The implementation includes data exploration, preprocessing, and the application of three different neural network architectures: a Simple Recurrent Neural Network (SimpleRNN), a Long Short-Term Memory (LSTM) network, a 1D Convolutional Neural Network (Conv1D), and also combination of Conv1D and LSTM.
## Dataset
The Ford-A dataset consists of 500-length recordings of engine noise. 
- Source: You can find the dataset and more information at [UCR Time Series Classification Archive](https://www.timeseriesclassification.com/index.php).
- Data Integrity: The initial analysis phase includes a check for missing values to ensure the dataset is complete and ready for modeling. Visualizations of sample time series are also generated to understand the data's structure.
## Models Implemented
Three deep learning models were built and trained to compare their effectiveness on this classification task:
1. SimpleRNN
2. LSTM
3. Conv1D
4. Combination of Conv1D and LSTM
