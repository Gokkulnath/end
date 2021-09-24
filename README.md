# Neural Network : Introduction

1. What is a neural network neuron?

Neuron in Neural network is the smallest computation element which is used to model/approximate a function. It does signal mixing followed by a non linearity in order to fit the dataset. It is modelled after taking inspiration from biological Neurons


2. What is the use of the learning rate?

Learning rate is used to control/regulate the step size taken during updating the weights from the gradient information. It is very much possible that gradient obtained can be of varying magnitudes and can die out as the model converges to the optimum. Thus learning rate is used to determine how fast we climb down the loss landscape during optimisation. 


3. How are weights initialized?

Weights are initialized by a random fashion .These values are usually obtained from a distribution (guassian, uniform between -1 to 1) usually closer to 0. This is done inorder to break symmtery within the network and encourage the network to learn and build decision boundary on diverse features.


4. What is "loss" in a neural network?

Loss is an optimisation objective  which is used to quantitative measure the optimality of the model i.e how good the model is or has the model reached optimum. Usually, Lower the loss better the model but lower loss need not translate to better metric. Though both metric and losses are correlated but not necessarily always.


5. What is the "chain rule" in gradient flow?

Chain rule of derivatives is applied to compute the intermediate gradient from the later layes. During backpropgation, we use this principle to compute the gradients  information by computing the derivatives wrt current node and multiply it with partial derivatives wrt weights in order to obtain gradients for each weight parameters.
