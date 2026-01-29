## Day 3: Decision Trees

Decision Trees are about logic, the other regressions were about mathematical formulas. This algorithm mimics how humans make decisions by asking a series of "Yes/No" questions.
It is one of the most intuitive algorithms because you can actually visualize the "tree" of choices the computer is making.

# How it Works
The model starts at a "Root Node" (the first question) and splits the data into branches based on a specific feature. 

It keeps splitting the data until it reaches a "Leaf Node," which provides the final prediction.

The algorithm chooses which question to ask first by looking for the feature that separates the data most cleanly. 

In technical terms, it tries to reduce "Entropy" (randomness/messiness) at every step.
