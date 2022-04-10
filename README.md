# Predicting-Bike-Sharing-Patterns

### Hint: 
This project was realized as part of the Udacity Nanodegree program "Deep Learning".

### Introduction
The aim of this project was to build a neural network from scratch to carry out a prediction problem on a real dataset. By building a neural network from the ground up, you'll have a much better understanding of gradient descent, backpropagation, and other concepts that are important to

### Database
The data comes from the UCI Machine Learning Database.

### Instructions
The following packages are required: numpy, matplotlib, pandas and jupyter notebook.

Predicting_bike_sharing_data.ipynb needs to be edited as well as my_answers.py python file, whose components are imported into the notebook at various places.


### The result will met the following criteria:

- The activation function should be a sigmoid
- The number of epochs should be between 50 and 15000
- The number of hidden nodes should be 5 and 100
- There should be exactly one output node
- The learning_rate should be between 0.05 and 5
- As already mentioned in the test-cases in Your_first_neural_network.ipynb, for the given NeuralNetwork(3, 2, 1, 0.5), the forward pass implementation, backpropagation   implementation, and update_weights implementation should be correct. Expected updated weights are:
- Hidden to output = [[0.37275328], [-0.03172939]]
- Input to hidden=[[0.10562014, -0.20185996], [0.39775194, 0.50074398], [-0.29887597, 0.19962801]]
- The run method should have an expected input as 0.09998924
- Produces good results when running the network on full data. Requirements are:
- Training loss should be less than 0.09
- Validation loss should be less than 0.18
