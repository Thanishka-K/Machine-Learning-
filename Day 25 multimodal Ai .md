# Day 25: Multi-Modal AI & CLIP (The Bridge between Text and Vision)
## The Concept
Most models you’ve studied so far are "Single-Modal" (they only handle text or only handle images). Multi-Modal AI can understand and relate information from different types of data simultaneously. CLIP (Contrastive Language-Image Pre-training), developed by OpenAI, is the most famous example. It was trained on millions of images and their captions to understand how words and pictures relate to each other.
* Technical Terms for Your Notebook
* Joint Embedding Space: A mathematical "map" where a picture of a dog and the word "dog" are placed very close to each other.
* Contrastive Learning: The training method where the model learns to "match" the correct image-text pairs and "push away" the incorrect ones.
* Zero-Shot Transfer: Because CLIP understands general concepts, it can identify objects it was never specifically "trained" to see just by reading a description of them.
* Latent Representation: The compressed numerical version of an image or text that the AI uses to "think".
## Real-World Scenario: Searching Your Photos
* Think about when you search your phone’s gallery for "Beach":
* The Process: Your phone doesn't just look for a file named "beach." It uses a Multi-Modal model to look at your photos and find images that have a high "similarity score" to the concept of a beach.
* The Result: It shows you photos of sand and water, even if you never tagged them. This is CLIP-style technology in action.
