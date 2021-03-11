# neural_net_simulink
Neural Neural Network Blackbox Visualization and Modeling using Simulink


nn_sample.mat contains the input (ts), weights, and biases for the neural network to work.


Step 1: On the MATLAB command window type in,

>>>load nn_sample.mat

Make sure that you are on the path where the .mat file is located.

Step 2: Double click on the nn_blackbox.slx project.

Step 3: Set the Simulation end time to 1s.

Step 4: Run the simulation.

Step 5: Observe the output on the scope.

This simple neural network used predetermined weights and biases. I will update the model to make it self-learning. For now, this just aims to visualize what happens inside the "blackbox" of a neural network.

About the model:

The model consists of dosage inputs from 0 to 1. The idea is to determine whether a particular value of dosage is effective or not (binary classification). The model has one hidden layer and two hidden neurons. A rectified linear unit (ReLU) activation function is used. The weights and biases manipulates the shape of the activation function to fit the data.

The inputs, weights, and biases are parameterized.
