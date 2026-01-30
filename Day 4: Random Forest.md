## Day 4: Random Forest

A more powerful evolution of a Decision Tree is a the Random Forest. If a Decision Tree is a single expert, a Random Forest is a committee of experts.
This is an "Ensemble Learning" method, meaning it combines multiple models to get a more accurate and stable result.

# How it Works
A Random Forest creates hundreds of individual Decision Trees. However, there are two tricks to make them work better together:
* Bagging (Bootstrap Aggregating): Each tree gets a slightly different, random subset of the data to study.
* Feature Randomness: Each tree can only look at a random selection of "features" (hints) when making a split.

When it’s time to make a prediction, every tree in the "forest" votes. For a classification task, the forest picks the answer that got the most votes. For a numerical prediction, it takes the average.
