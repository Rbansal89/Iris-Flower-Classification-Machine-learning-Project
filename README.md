# Multiclass Classification of Iris Flower Species Porject
In this project, we have data on three types of iris flowers. we will build a Neural Network model which will classify the flower based on its data.
Modules used for the project are Keras,numpy,pandas, scikit learn.

#Training

The base Neural Network consist one hidden layer with 4 neurons and one ouput layer with 3 neurons, optimizer used is Adam, loss measurement is done with crossentropy.

Best result was given by the Neural network using softmax classifier in the output layer

#Testing

Testing of the trained model is done using kfold Cross validation with k equals to 10.

#Result
The best mean accuracy is 96.67
and standard deviation is 3.33
