# Short notes on machine learning 
ML is a way to get computers to learn from patterns in data rather than following a fixed set of instructions. Instead of a programmer writing every single "if-then" rule, the computer looks at examples and builds its own logic to predict outcomes.

## => The Three Main Types
Supervised Learning: This is like learning with a guide. You provide the computer with "labeled" data (input and the correct answer). For example, showing it 1,000 emails marked as "spam" or "not spam" until it can tell the difference itself.

Unsupervised Learning: Here, there are no labels. The computer is just given a pile of data and asked to find patterns or groups on its own. It’s useful for things like customer segmentation or finding anomalies in credit card transactions.

Reinforcement Learning: This is based on trial and error. An agent performs an action in an environment and gets a "reward" for good moves and a "penalty" for bad ones. It’s how AI learns to play games like Chess or Go.

## =>The Basic Workflow
Data Prep: You can't just throw raw data at a model. You have to clean it, handle missing values, and pick the most relevant "features" (the variables that actually matter).

The Training Phase: This is where the model "studies." It runs the data through an algorithm to minimize errors in its predictions.

Testing/Evaluation: You save some data that the model has never seen before to test it. If it performs well here, you know it has actually learned the concepts rather than just memorizing the training set.

## =>Key Concepts to Know
Algorithms: These are the specific math tools used, like Linear Regression (for numbers) or Decision Trees (for categories).

Overfitting: A common trap where a model learns the training data too well, including the noise/errors. It looks perfect on paper but fails in the real world because it can’t generalize.

Features & Targets: Features are your inputs (the data you have), and the Target is the output (the thing you’re trying to predict).

