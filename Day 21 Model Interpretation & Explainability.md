i# Day 21: Model Interpretation & Explainability 
## The Concept
Model Explainability is a set of processes and methods that allows human users to comprehend and trust the results and output created by machine learning algorithms. This is critical for high-stakes industries like healthcare or finance.
## Technical Terms
* Global Interpretability: Understanding the overall logic of the model (e.g., "In general, which features are most important for my house price model?").
* Local Interpretability: Understanding why the model made one specific prediction (e.g., "Why did the model reject this specific loan application?").
* SHAP (SHapley Additive exPlanations): A mathematical method based on game theory that assigns each feature an importance value for a particular prediction.
* LIME (Local Interpretable Model-agnostic Explanations): A technique that "probes" a complex model by testing it with slightly different data to see how the output changes.
## Real-World Scenario: Medical Diagnosis
Imagine a doctor using an AI to detect pneumonia in X-rays:
* The Black Box Problem: The AI says "Pneumonia," but the doctor doesn't know why.
* The XAI Solution: Using a tool like Grad-CAM, the AI generates a heatmap over the X-ray, highlighting the specific area of the lung that led to its decision.
* The Result: The doctor can verify if the AI is looking at the actual disease or just a shadow from the patient's clothing.
