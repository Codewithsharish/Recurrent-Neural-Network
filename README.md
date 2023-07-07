# Recurrent-Neural-Network
**Adding custom attention layer**

The “attention mechanism” is integrated with deep learning networks to improve their performance. Adding an attention component to the network has shown significant improvement in tasks such as machine translation, image recognition, text summarization, and similar applications.

This code shows how to add a custom attention layer to a network built using a recurrent neural network. I will illustrate an end-to-end application of time series forecasting using a very simple dataset. The code is designed for anyone looking for a basic understanding of how to add user-defined layers to a deep learning network and use this simple example to build more complex applications.

This code is divided into three parts; they are:
1. Preparing a simple dataset for time series forecasting
2. How to use a network built via SimpleRNN for time series forecasting
3. Adding a custom attention layer to the SimpleRNN network

**The Dataset**
The focus of this is to gain a basic understanding of how to build a custom attention layer to a deep learning network. For this purpose, let’s use a very simple example of a Fibonacci sequence, where one number is constructed from the previous two numbers. The first 10 numbers of the sequence are shown below:

0, 1, 1, 2, 3, 5, 8, 13, 21, 34, …

When given the previous ‘t’ numbers, can you get a machine to accurately reconstruct the next number? This would mean discarding all the previous inputs except the last two and performing the correct operation on the last two numbers.

For this code, you’ll construct the training examples from t time steps and use the value at t+1 as the target.

THANKS FOR THE MACHINE LEARNING MASTERY FOR OVERALL TUTORIAL. 




