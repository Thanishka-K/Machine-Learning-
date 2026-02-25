# Structural Organization of a Network
* Input Layer: This is the first layer of the network. It receives the raw data, such as pixels from an image or numbers from a spreadsheet. There is one node for every feature in your dataset.
* Hidden Layers: These are the layers between the input and output. This is where the actual learning happens. Deep learning gets its name from having many of these hidden layers stacked on top of each other.
* Output Layer: This is the final layer that gives the prediction. If you are classifying an image as a cat or a dog, this layer will usually have two nodes representing those two choices.

## How Data Flows (Forward Propagation)

* Signal Processing: Data enters the input layer and travels through the hidden layers. Each node performs the math you learned on Day 11 (weighting, bias, and activation).
* Pattern Recognition: The first hidden layers might look for simple patterns like lines or edges. The deeper layers combine those lines to recognize shapes like eyes or ears.
* Final Prediction: By the time the data reaches the output layer, the network has processed all the complex features to make a final guess.

## How the Network Learns (The Training Process)
* Loss Function: After the network makes a guess, it compares that guess to the real answer using a loss function. This measures how far off the prediction was.
* Backpropagation: This is the most critical part of learning. The network works backward from the error at the end to the beginning, identifying which weights and biases were responsible for the mistake.
* Gradient Descent: This is the optimization tool that slightly adjusts the weights and biases to reduce the error. The goal is to find the lowest point of the loss function, where the model is most accurate.
