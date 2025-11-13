Title: MNIST Digit Classification Neural Network

Name: Michael Tamirat

Framework: TensorFlow/Keras

Summary: This model is a three-layer feedforward neural network with an input layer (784 neurons from flattened 28x28 images) connected to a hidden layer (128 neurons) using ReLU activation; another hidden layer (64 neurons) using ReLU activation; and an output layer (10 neurons) using softmax activation. With a batch size of 32 and a 10% validation split, the network was trained using the Adam optimizer with categorical crossentropy loss across 532 epochs. Labels were one-hot encoded for the 10-digit classes, and input photos were preprocessed by flattening them into 784-dimensional vectors and standardizing pixel values to the range [0, 1].

Final Test Set Accuracy:
 Test Loss: 0.0813
 Test Accuracy: 0.9749
