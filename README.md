# advtopics_ML3

Problem 1: Softmax Activation Function 
Explore the softmax activation function in the output layer.
Study the cross-entropy loss with one-hot encoded class label.
Demonstrate the correctness of the given derivative equation concerning the loss.

Problem 2 :Neural Network Training and Backpropagation
Review notebook on training a 2-layered neural network using sigmoid activations and backpropagation.
Modify notebook to train a 3-layered neural network with two hidden layers.
Implement a scaled sigmoid activation function.
Modify functions for forward propagation, cost calculation, and backpropagation to suit the new 3-layered structure.
Train the 3-layered neural network and compare its accuracy with the 2-layered neural network from the original notebook.

Problem 3: Weight Initialization, Dead Neurons, Leaky ReLU 
Study blogs on weight initialization and understand vanishing and exploding gradients.
Experiment with different weight initializations using the given 5-layer neural network model.
Investigate the dying ReLU phenomenon using a specific 1-dimensional function.
Analyze the effect of Leaky ReLU activation on preventing dying neurons.

Problem 4: Batch Normalization, Dropout, MNIST 
Learn about co-adaptation and internal covariance-shift from two provided papers.
Experiment with LeNet-5 for MNIST data using different normalization and dropout techniques.
Compare the performance of batch normalization, dropout, and their conjunction.
Train the network using a combination of batch normalization and dropout to assess their combined impact on performance.

Problem 5: Learning Rate, Batch Size, FashionMNIST 
Study the cyclical learning rate policy.
Modify code to implement the policy on FashionMNIST dataset using LeNet-5.
Explore the impact of various learning rates and batch sizes on the training process.
