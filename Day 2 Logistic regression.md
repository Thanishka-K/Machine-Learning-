# Day 2: Logistic Regression

While Linear Regression predicts numbers (like price or temperature), Logistic Regression is used for classification (predicting a category).
It’s the go-to algorithm when the answer we are looking for is "Yes/No," "True/False," or "Spam/Not Spam."

## How it Works
Instead of drawing a straight line that goes off to infinity, Logistic Regression uses a mathematical function called the "Sigmoid Function".
This function takes any input and "squashes" it into a value between 0 and 1. We then treat this value as a probability.
ex:If the output is 0.85, there is an 85% chance the item belongs to Class A.

## Real-World Example: Email Spam Filter
Imagine building a filter that decides if an incoming email is "Spam" or "Inbox."
* The Features (X): The model looks at things like the number of misspelled words, whether the sender is in your contacts, and if the word "FREE" appears in all caps.
* The Calculation: It assigns weights to these features. "FREE" in all caps might have a high weight for being Spam.
* The Output: The model calculates a score. For a specific email, it might get a result of 0.92.
* The Decision: Since 0.92 is greater than our 0.5 threshold, the model classifies the email as Spam and sends it to the junk folder.
