# Tensorflow Stock Prediction

In this project, data is first gathered from yahoo finance using pandas DataReader. The simple returns were calculated based on the gathered data. Next, data was split into train and test sets. This will allow us to evaluate the model. Next parameters were set for 1 input, 1 output and 100 hidden layers. Next the model is created using an Recurrent Neural Network object and the inputs and outputs provided. A learning rate of .001 is used as well as an Adam optimizer which utilizes stochastic gradient descent. 1000 iterations was used and every 150 the loss is printed out. Finally, the comparison of the forecast and actual data is printed out.

## Authors

David Licerio


