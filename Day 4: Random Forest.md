## Day 4: Random Forest

A more powerful evolution of a Decision Tree is a the Random Forest. If a Decision Tree is a single expert, a Random Forest is a committee of experts.
This is an "Ensemble Learning" method, meaning it combines multiple models to get a more accurate and stable result.

# How it Works
A Random Forest creates hundreds of individual Decision Trees. However, there are two tricks to make them work better together:
* Bagging (Bootstrap Aggregating): Each tree gets a slightly different, random subset of the data to study.
* Feature Randomness: Each tree can only look at a random selection of "features" (hints) when making a split.

When it’s time to make a prediction, every tree in the "forest" votes. For a classification task, the forest picks the answer that got the most votes. For a numerical prediction, it takes the average.

# Real-World Example: Movie Recommendations
Imagine you want to know if you'll like a new Sci-Fi movie.
Tree 1 looks at the director and says "Yes."
Tree 2 looks at the lead actor and says "No."
Tree 3 looks at the runtime and says "Yes."
Tree 4 looks at the budget and says "Yes."
The Random Forest sees three "Yes" votes and one "No." It concludes: "You will probably like this movie." Because it consulted many trees, it's less likely to be wrong just because one specific detail (like the actor) was off.
