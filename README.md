In this project, I implemented an artificial neural network (ANN) using NumPy, with two hidden layers and ReLU activation functions. The output layer uses a softmax activation function. The model is trained using stochastic gradient descent (SGD) with momentum.

After implementing the NumPy ANN, I implemented the same architecture using TensorFlow. Then I conducted several experiments to compare the performance of the models under different optimization algorithms, network architectures, and regularization techniques.

In the first experiment, I changed the optimization algorithm from SGD with momentum to the Adam optimizer. In the second experiment, I added more hidden layers to the network, and decreased the number of hidden units. Since neural network tended to overfit I applied dropout regularization to the network.

Through the experiments, I found that the TensorFlow model with the Adam optimizer and dropout regularization outperformed the NumPy model and the other configurations of the TensorFlow model. Using Adam optimizer, adding more hidden layers and decreasing the number of hidden units improved performance.
