# CNN Framework from scratch using NumPy.
This repository showcases a Convolutional Neural Network framework that I built without the use of any pre-existing machine learning framework.

# Why
Studying Mathematics at school, I was very drawn to Linear Algebra and its application so I started researching into it and after reading Human Compatible by Stuart Russell and seeing videos about Neural Nets on yt, I was drawn to machine learning and so I set out to challenge myself to build a framework which removes all abstraction and allows me to understand the tech at its core.

# What I implemented
Implemented convolutional layers, dense layers, optimisers and forward/backward propagation logic for each layer type

# What I learned
How modern ML works under the hood - gradient descent, parameter optimisation and through doing so, improved my ability to write module OOP code 

# Limitations
Purely educational and is NOT optimised for production 

## convolutional_layer.py
### ConvolutionLayer Class
#### Attributes:
- input_tensor_no int 
- output_tensor_no int
- kernel_size int
- learning_rate float

#### Methods:
- forward (forward propagation)
- backward (back propagation)
- update_params (optimisation aka gradient descent, mutator method)
- relu (Static)
- relu_derivative (Static)
- get_weights (accessor)
- get_biases (accessor)

## dense_layer.py
### DenseLayer Class
#### Attributes:
-   inputs_no int
-   neurons_no int
-   activation_function str
-   learning_rate float

#### Methods:
- forward
- Backward
- update_params
- relu
- relu_derivative
- softmax
- get_weights
- get_biases

## adam_optimiser.py
### AdamOptimiser Class
#### Attributes:
- learning_rate float
- beta_1 float
- beta_2 float
- epsilon float
- w_dims tuple(int)
- b_dims tuple(int)

#### Methods:
- get_update

example code will be added to the repository soon
