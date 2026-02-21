# Day 11: Inside the Neural Node
If a Neural Network is a "brain," a Node is a single brain cell. Its entire job is to take in information, weigh its importance, and decide whether to pass that information along.

## Definition of a Neural Node
A neural node, also called a perceptron, is the basic unit of a neural network.
It is a mathematical function that mimics the way a biological brain cell processes a signal.
Its main purpose is to take in data, calculate its significance, and produce an output.

## The Three Steps of Operation
* Input and Weighting: The node receives various inputs. Each input is multiplied by a weight, which defines how much influence that specific piece of data has on the outcome.
* Summation and Bias: The node adds all the weighted inputs together. It then adds a bias value, which helps the model shift the decision threshold up or down to make it more flexible.
* Activation: The final sum is passed through an activation function. This function acts as a gatekeeper to decide if the signal is strong enough to be passed on to the next layer.

## Classifications of Activation Functions
* ReLU: This stands for Rectified Linear Unit. It is the most common function used in modern AI. It turns all negative values into zero and keeps positive values as they are.
* Sigmoid: This squashes the output into a range between 0 and 1. It is mostly used for predicting probabilities, like the likelihood of an image being a cat.
* Tanh: This function maps the input to a range between -1 and 1. It is useful for data that has negative values and needs to be centered around zero.

### Analogy for Understanding
* Inputs: Imagine factors like the weather, the cost of a ticket, and your energy level.
* Weights: These represent your personal preferences, such as caring more about the cost than the weather.
* Bias: This is your general mood, which might make you more or less likely to go out regardless of the other factors.
* Activation: This is the final internal decision that results in either staying home or going out.

### Biological Comparisons
* Dendrites: These correspond to the input signals the node receives.
* Cell Body: This corresponds to the summation and activation math happening inside the node.
* Axon: This corresponds to the final output signal being sent to the next node.
