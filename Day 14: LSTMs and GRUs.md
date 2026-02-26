# Day 14: LSTMs and GRUs
While standard RNNs have a short-term memory problem, Long Short-Term Memory (LSTM) and Gated Recurrent Units (GRU) were designed to remember information for long periods. They are the reason AI can maintain the context of a long paragraph or a complex musical piece.

* The Problem: The Vanishing Gradient
In a standard RNN, as the sequence gets longer, the information from the beginning starts to wash out or disappear.

By the time the model gets to the end of a book chapter, it has "forgotten" the names of the characters introduced in the first paragraph.
LSTMs and GRUs solve this by using internal gates to regulate the flow of information.

## How LSTMs Work (The Three Gates)
* An LSTM node is like a complex filing cabinet with three specific security guards:

* Forget Gate: It looks at the new data and decides what information from the past is no longer useful and should be deleted.

* Input Gate: It decides which parts of the new incoming information are worth adding to the long-term memory.

* Output Gate: It decides which parts of the stored memory should be used to influence the prediction at this specific moment.
