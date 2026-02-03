# CNN Framework using NumPy.
This repository showcases the first iteration of a convolutional neural network framework built using NumPy (Built for educational purposes)

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
