# Deep Learning And NeuralNetworkAssignments
EC239 Deep Learning and Neural Networks Assignments 

Completed using numpy and Jupyter notebooks


1. knn_svm_softmax

Implemented K-Nearest Neighbors , Softmax and Support Vector machine classifiers

KNN prediction using L2 distance and then a faster technique using vectorization. Performed cross validation to get the best hyperparameters for KNN.

SVM and Softmax- Training, Loss and Gradient calculation, Stochastic gradient descent, Validation to tune hyperparamters.


2. Twolayer_fullconnectedNetworks

2 Layer Neural Network - Forward Pass, Backward Pass, Training, Classification of CIFAR dataset, Stochastic Gradient Descent, Optimization

Fully Connect Neural Network - Modular layers, Linear Layers, Affine Forward Pass, Affine Backward pass, ReLU forward Pass, ReLu Backward Pass, Softmax and SVM losses

3. Optimizers_and_Batch_Normalization

Optimizations for Fully Connected Network: SGD+momentum, SGD+ Nesterov momentum, RMSProp, Adaptive moments(Adam) and their comparisons

Batch Normalization: Batchnorm Forward Pass, Batchnorm Backward Pass, Training FC net using batch normalization, Initialization , Dropout implementation, Dropout foward pass, Dropout Backward Pass, FC-net with Dropout that is more than 60% accurate on testing of CIFAR classification.

4. Convolutional Neural Networks

Implement CNN layers,Forward Pass, Backward Pass, Max pool forward and backward passes, fast implementations of CNN ( provided by CS231 Stanford), Spatial Batch normalization ( forward and backward passes )

Final part consists of implementating a 3-layer CNN that does more than 65% validation accuracy o CIFAR-10
