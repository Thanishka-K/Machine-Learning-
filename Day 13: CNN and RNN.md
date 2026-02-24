# 1. Convolutional Neural Networks (CNN)
CNNs are designed to "see" patterns in space (like the pixels in a photo). Instead of looking at every pixel individually, they look at small patches to find edges, then shapes, then objects. 
* How it works: It acts like a filter (convolution) that slides over an image to find patterns and then shrinks the data (pooling) to keep only the most important parts.
* Best for: Images, videos, and medical scans.
* The Upside: You don't have to tell it what a "nose" looks like; it learns to find it on its own.
* The Downside: It needs thousands of pictures to learn and can get confused if an object is tilted or upside down. 

# 2. Recurrent Neural Networks (RNN)
Think of it as: "The Ear/Memory" 👂
RNNs are designed to understand data that comes in a specific order. They don’t just look at what’s happening now; they remember what happened a split second ago to make sense of the current moment. 
* How it works: It uses a loop (recurrence) to pass information from one step to the next, like remembering the first half of a sentence to understand the last word.
* Best for: Translating languages, Siri/Alexa (speech), and predicting stock market trends.
* The Upside: It’s great at "context"—knowing that the word "bank" means something different in a river vs. a financial story.
* The Downside: It has a "short-term memory" problem (it forgets the beginning of long sequences) and is notoriously difficult to train.

