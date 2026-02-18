# Day 8: Summarising the 7 days

## Day 1: Linear Regression
The Concept: Predicting a continuous number (like price, weight, or temperature) based on the relationship between variables. It tries to draw the "best-fit line" through data points.

Scenario: Real Estate Pricing. You look at the square footage of houses in your neighborhood to predict how much a house will sell for.
Input: 1,500 sq. ft.
Output: $300,000.

## Day 2: Logistic Regression
The Concept: Despite the name "regression," this is for classification. It predicts the probability of something belonging to a category (usually Yes/No or 0/1).

Scenario: Spam Detection. An email comes in; the model looks for keywords like "Free" or "Winner" to decide if the email is "Spam" or "Not Spam."

## Day 3: Decision Trees
The Concept: A flowchart-like structure where you make decisions based on data features. It splits the data into branches until it reaches a final "leaf" or answer.

Scenario: Bank Loan Approval. The tree asks: Is the credit score > 700? (Yes/No) \rightarrow Is the income > $50k? (Yes/No) \rightarrow Approve Loan.

## Day 4: Random Forest
The Concept: An "ensemble" method. Instead of one Decision Tree, you build a forest of many trees and let them "vote." This prevents the model from being too biased or overfitting.

Scenario: Medical Diagnosis. Instead of asking one doctor (one tree), you ask a panel of 100 doctors (the forest). If 80 of them agree on a diagnosis, that’s your final result.

## Day 5: K-Nearest Neighbors (KNN)
The Concept: A "birds of a feather flock together" approach. To classify a new point, the model looks at the K closest data points (neighbors) and assigns the most common category among them.

Scenario: Recommender Systems. If you like Inception and Interstellar, and your "neighbor" (someone with similar taste) also likes The Prestige, the system recommends it to you.

## Day 6: K-Means Clustering
The Concept: An unsupervised algorithm. It doesn't have labels (like "Spam" or "Not Spam"). Instead, it looks at raw data and groups similar items into "clusters."

Scenario: Customer Segmentation. A clothing brand takes its entire customer list and groups them into "Budget Shoppers," "Luxury Buyers," and "Trend Seekers" based on their spending habits.

## Day 7: Support Vector Machines (SVM)
The Concept: Finds the "best boundary" (hyperplane) that separates two classes with the maximum margin possible. It’s like building a very wide road between two groups to keep them clearly apart.

Scenario: Handwriting Recognition. Separating an image of a handwritten "4" from a "9" by finding the most distinct geometric differences between the two shapes.
