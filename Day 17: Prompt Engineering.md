# Day 17: Prompt Engineering & Optimization
## ​The Concept
​Prompt Engineering is the process of structuring text that can be interpreted and understood by a generative AI model. It is not just "asking a question"; it is providing enough context, constraints, and examples so the model provides a high-quality, professional response.

## ​Technical Terms
​* Zero-Shot Prompting: Asking the AI a task without any examples (e.g., "Translate this to French: Hello").
* ​Few-Shot Prompting: Providing a few examples within the prompt to show the model the desired pattern before asking it to perform the task.
* ​Chain of Thought (CoT): Encouraging the model to "think step-by-step." This significantly improves performance on complex reasoning or math tasks.
* ​System Prompts: High-level instructions that define the AI's "persona" (e.g., "You are a senior data scientist who explains things simply").

## ​Real-World Scenario: Automating Code Documentation
​Imagine you want an AI to write the README for your current GitHub repository:
* ​Bad Prompt: "Write a readme for my ML repo." (Result: Too generic).
* ​Engineered Prompt: "You are a Technical Writer. Look at these 16 files [List of your Day 01-16 files]. Create a professional README.md table with columns for 'Day', 'Topic', and 'Key Technical Term'. Use a clean, academic tone."
​* Result: A perfectly formatted table that matches your specific work.
