# Day 19: Object Detection & Image Segmentation
## The Concept
While Image Classification (Day 13) tells you what is in an image (e.g., "This is a car"), Object Detection tells you where it is by drawing a box around it. Image Segmentation goes even further by coloring every pixel that belongs to that object.
## Technical Terms for Your Notebook
* Bounding Box: The (x, y) coordinates that form a rectangle around a detected object.
* IoU (Intersection over Union): A metric used to evaluate how much your predicted bounding box overlaps with the actual object box.
* YOLO (You Only Look Once): A famous, high-speed algorithm that can detect multiple objects in a video frame in milliseconds. It is the industry standard for real-time detection.
* Transfer Learning: Using a model already trained on millions of images (like ResNet or VGG) and "fine-tuning" it for your specific task (e.g., identifying specific types of medicine bottles).
## Real-World Scenario: Autonomous Drones
Imagine you are coding a drone to navigate a forest:
* The Task: The drone needs to avoid trees while following a path.
* The CV Logic: A YOLO model runs on the drone's camera. It detects "Tree" with a 95% confidence score and draws a bounding box.
* The Action: The drone's navigation system calculates the distance to that box and adjusts its flight path in real-time.
