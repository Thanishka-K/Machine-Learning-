# Day 6: K-Means Clustering
Today we move into Unsupervised Learning. Unlike the last five days, where we had an "answer key" (labels like "Spam" or "Price"), K-Means works with data that has no labels.
Its job is to find hidden groups on its own.

## How it Works
The "K" in K-Means stands for the number of groups (clusters) you want to find. The algorithm follows a simple dance:
* Initialization: It randomly picks $K$ spots in the data to be the "center" of each group (called Centroids).
* Assignment: Every data point looks at the centroids and attaches itself to whichever one is closest.
* Update: The centroids move to the actual center of the points that just joined them.
* Repeat: The points re-assign themselves to the moved centroids. This continues until the centroids stop moving.

## Real-World Example: T-Shirt Sizing
Imagine you are a clothing brand and you have the heights and weights of 10,000 customers. 
You can’t make a custom shirt for every single person, so you decide to create 3 sizes: Small, Medium, and Large.You set $K=3$.
The algorithm looks at the cloud of data and finds three distinct "centers" where people's body types naturally cluster.
The Result: Group 1 becomes your "Small" template, Group 2 "Medium," and Group 3 "Large." You didn't tell the computer what a "Medium" was; it discovered the most common middle ground for you.

## The Challenge: Choosing "K"
Since the data has no labels, how do you know if you should have 3 groups or 5?ML engineers use the "Elbow Method." 
You run the algorithm with different values of $K$ and graph the results. 
You look for the "elbow" of the curve—the point where adding more groups stops giving you significantly better results.
