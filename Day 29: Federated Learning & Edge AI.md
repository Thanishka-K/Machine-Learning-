# Day 29: Federated Learning & Edge AI

## The Concept
Traditional ML requires all data to be sent to a central server (like Google or AWS) for training. Federated Learning flips this: the model travels to the data. The model trains locally on your device, and only the "learning" (mathematical weights) is sent back to the cloud. Edge AI refers to running these models directly on hardware (like a Raspberry Pi or a phone) so they work instantly without internet.

## Technical Terms
* On-Device Training: Training a model directly on a user's hardware rather than a powerful server.
* Privacy-Preserving AI: Techniques like Federated Learning that ensure personal raw data never leaves the user's device.
* Model Quantization: Shrinking a massive model (like an LLM) so it can fit into the small memory of a mobile phone without losing too much accuracy.
* Inference Latency: The time it takes for a device to give a result. Edge AI has near-zero latency because it doesn't wait for a server response.

## Real-World Scenario: Smart Keyboards 
Think about the "Next Word Prediction" on phone:
* The Privacy Problem: We don't want a company reading every private text we type to train their AI.
* The Federated Solution: Phone learns specific slang and typing habits locally.
* The Global Update: At night, while itcharges, it sends a "summary" of what it learned to the main server. This summary is combined with millions of others to make the keyboard smarter for everyone, but the actual messages stay on phone.
