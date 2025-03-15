java cCOMP3340 Applied Deep Learning The University of Hong Kong
Assignment 1
Feb 2025
Question 1 - XOR Approximation
We consider the problem of designing a feedforward neural network to approximate the XOR
function. Specifically, for any input points (x1, x2), x1, x2 ∈ {0, 1}, the output of the network
should be approximately equal to x1 ⊕ x2. Suppose the network has two input neurons, one
hidden layer with two neurons, and an output layer with one neuron, as shown in Figure 1.
The activation function for all neurons is the Sigmoid function defined as σ(z) = 1+
1
e−z .
(a) Please provide the specific values for the parameters in your designed network. Demon strate how your network approximates the XOR function (Table 1) by performing forward
propagation on the given inputs (x1, x2), x1, x2 ∈ {0, 1}.
(b) If we need the neural network to approximate the XNOR function (Table 1), how should
we modify the output neuron without altering the neurons in the hidden layer?
x1 x2 x1 ⊕ x2 x1  x2
0 0 0 1
0 1 1 0
1 0 1 0
1 1 0 1
Table 1: XOR and XNOR Value Table
 !
 "
 #
Figure 1: Network structure and the notation of pa代 写COMP3340、Python/Java
代做程序编程语言rameters
COMP3340 Applied Deep Learning The University of Hong Kong
Question 2 - Backpropagation
We consider the problem of the forward pass and backpropagation in a neural network whose
structure is shown in Figure 1. The network parameters is initialized as w1 = 1, w2 = −2,
w3 = 2, w4 = −1, w5 = 1, w6 = 1, b1 = b2 = b3 = 0. The activation function for all neurons
is the Sigmoid function defined as σ(z) = 1+
1
e−z .
(a) Suppose the input sample is (1, 2) and the ground truth label is 0.1. Please compute
the output y of the network.
(b) Suppose we use the Mean Squared Error (MSE) loss. Please compute the loss value for
the sample (1, 2) and its gradient with respect to the network parameters using chain rules.
The final answer should be limited to 3 significant figures.
(c) Suppose we use stochastic gradient descent (SGD) with a learning rate of α = 0.1.
Please specify the parameters of the network after one step of gradient descent, using the
gradient computed in (b). Please also specify the prediction value and the corresponding loss
of the new network on the same input (1, 2).

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
