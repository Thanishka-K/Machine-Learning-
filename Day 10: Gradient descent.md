# Day 10: How Neural Networks Learn (Gradient Descent)

## The Concept
If a Neural Network is the "body," Gradient Descent is the "brain" figuring out how to improve.
It is an optimization algorithm used to minimize the Loss Function (the error).
Think of it as being at the top of a foggy mountain (high error) and needing to find the bottom of the valley (zero error) by feeling the slope under your feet.

## The Process
* Forward Propagation: The model makes a guess.
* Calculate Loss: The model compares its guess to the actual answer to see how wrong it was.
* Backpropagation: The model goes backward from the output to the input, calculating how much each "neuron" contributed to the error.
* Update Weights: It tweaks the weights slightly to make a better guess next time.

## Key Terminology
Learning Rate: How big of a step the model takes down the mountain.
* Too big: You might jump over the valley.
* Too small: It will take forever to reach the bottom.
* Epoch: One full pass of the entire training dataset through the neural network.
* Batch Size: The number of training examples used in one iteration to update the weights.

## Real-World Scenario: Learning to Play Darts
Imagine you are blindfolded and throwing darts at a board:
* Trial 1: You throw. Your friend says, "You hit 2 feet too high and to the left." (Loss Calculation)
Adjustment: You adjust your arm power and angle slightly. (Backpropagation & Weight Update)
* Trial 2: You throw again. You're closer.
* Result: After 100 throws (Epochs), you are hitting the bullseye consistently even without the blindfold.

Math Simplified
* The core update rule for a weight (W) is:
W_new = W_old - (Learning Rate * Gradient)
