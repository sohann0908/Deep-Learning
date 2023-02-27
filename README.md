# Deep-Learning

# Implemented Boston housing price prediction problem by Linear regression using Deep Neural network. Used Boston House price predictiondataset.

1. Load the Boston Housing dataset using load_boston() function from sklearn.datasets module.
2. Preprocess the data by scaling the features using StandardScaler from sklearn.preprocessing module.
3. Split the preprocessed data into training and test sets using train_test_split() function from sklearn.model_selection module.
4. Define a sequential model using tf.keras.Sequential() function from TensorFlow's Keras API with two dense layers having 64 units in the first layer and 1 unit in the output layer. Use 'relu' activation function for the first layer and no activation function for the output layer.
5. Compile the model using compile() method with mean squared error ('mse') as the loss function and Adam optimizer with a learning rate of 0.001.
6. Train the model using fit() method with training data, number of epochs, batch size, and a validation split of 0.1 to monitor the performance of the model on a validation set during training.
7. Evaluate the model on the test set using evaluate() method and print the mean squared error.
