# Day 5 K-Nearest Neighbor
A very intuitive, "social" algorithm. K-Nearest Neighbors is based on one simple idea: "Birds of a feather flock together". It assumes that similar data points exist in close proximity to each other.

## How it Works
Unlike the other algorithms, KNN doesn’t really "learn" a complex formula. Instead, it just stores all the training data.
When you give it a new data point to classify, it calculates the distance (usually a straight line) between the new point and every other point in its memory.
Finds the "K" closest points (where K is a number you choose, like 3 or 5).
Takes a vote. If 4 out of 5 neighbors are "Red," the new point is labeled "Red."

## Real-World Example: Real Estate "Comparison"
If we want to know if a house is in a "Luxury" or "Budget" category, we don't necessarily need a complex formula. We can just look at the 5 houses closest to it.
If 4 of the neighbors are luxury mansions with pools, the house is likely "Luxury."
If the neighbors are all small studio apartments, the house is likely "Budget."
KNN does exactly this, but it can use more than just physical distance—it can look at "distance" in terms of price, age, or number of rooms.

## The "K" Factor
Choosing the right K is the most important part:Small K (e.g., K=1): The model is too sensitive. If one neighbor is a weird outlier, the model will get confused.
Large K (E.g., K=100): The model becomes too blurry. It starts looking at neighbors that aren't actually that similar.
