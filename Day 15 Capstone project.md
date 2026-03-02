# Day 15: Sentiment Analysis (The Capstone)
The Concept
Sentiment Analysis (also known as Opinion Mining) is a sub-field of NLP that uses Machine Learning to determine the "emotional tone" of a piece of text. Instead of just understanding the words, the model understands the feeling behind them.
Technical Breakdown for your Log
* The Task: Binary or Multi-class Classification.
* Vectorization: You can't feed "words" into a math model. You must convert them into numbers using techniques like:
* Bag of Words (BoW): Counting how many times each word appears.
* TF-IDF: Giving more weight to unique, meaningful words and less to common words like "the."
* The Model: You can use Logistic Regression (Day 2) for speed or an RNN (Day 14) for better context.

## Technical Steps (The Workflow)
* Pre-processing: Lowercase the text, remove punctuation, and remove "stop words" (is, a, the).
* Tokenization: Split sentences into individual words.
* Feature Extraction: Turn those words into a matrix of numbers.
* Classification: The model outputs a probability (e.g., 0.9 = Positive, 0.1 = Negative).

## Real-World Scenario: Movie Reviews
Imagine you are a data scientist at Netflix:
Input: A user writes: "I hated the ending, it was so slow!"
Processing: The model identifies negative-weighted tokens like "hated" and "slow."
Result: The system flags the review as Negative (Sentiment Score: 0.15).
Action: This helps Netflix decide which shows to cancel or promote.
