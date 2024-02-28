# Numerical Optimization Algorithms

This repository contains implementations of various numerical optimization algorithms commonly used in machine learning and optimization problems.

## Optimization Algorithms Implemented

1. **Batch Gradient Descent**: A classic optimization algorithm that computes the gradient of the loss function w.r.t. all training examples to update model parameters.
   
2. **Stochastic Gradient Descent (SGD)**: An optimization algorithm that computes the gradient of the loss function w.r.t. a single training example at each iteration to update model parameters.

3. **Mini-Batch Gradient Descent**: A variation of SGD that computes the gradient using a small subset (mini-batch) of training examples to update model parameters.

4. **Momentum-based Gradient Descent**: An optimization algorithm that adds momentum to the gradient update to accelerate convergence and escape local minima.

5. **Nesterov Accelerated Gradient (NAG)**: A modification of momentum-based gradient descent that reduces the oscillations and overshooting by updating the parameters with a look-ahead gradient.

6. **Adagrad**: An adaptive learning rate optimization algorithm that adapts the learning rate for each parameter based on the historical gradients.

7. **RMSProp**: Another adaptive learning rate optimization algorithm that uses a moving average of squared gradients to adjust the learning rate.

8. **ADAM (Adaptive Moment Estimation)**: A popular optimization algorithm that combines the benefits of both momentum-based methods and adaptive learning rate methods.

9. **Second Order Optimization**: Optimization algorithms that utilize second-order information such as Hessian matrix for more accurate updates. Examples include Newton's Method and Quasi-Newton methods like BFGS and L-BFGS.

## How to Use

Each optimization algorithm is implemented as a separate module. You can find the implementation and usage instructions in the respective directories.

## Usage

To use any of the optimization algorithms, simply import the corresponding module and call the optimization function with appropriate parameters.


