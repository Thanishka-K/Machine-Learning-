# Day 28: 
## The Concept
An AI Agent is a system that uses an LLM as its "brain" to reason, plan, and execute actions to achieve a specific goal. Unlike a standard chatbot that just responds to a prompt, an agent can use tools (like a web browser, a code interpreter, or a calculator) to solve complex, multi-step problems without human intervention.

## Technical Terms
* Reasoning & Planning: The ability of the agent to break a big goal (e.g., "Research and summarize the top 5 ML papers from this week") into smaller, logical steps.
* Tool Use (Function Calling): The process where the AI decides it needs external data and calls an API or runs a script to get it.
* ReAct Pattern (Reason + Act): A prompting strategy where the model explicitly writes out its "Thought," "Action," and "Observation" before providing a final answer.
* Memory (Short-term vs. Long-term): * Short-term: The current conversation context.
* Long-term: Using a Vector Database (like you learned in RAG) to remember facts over weeks or months.

## Real-World Scenario: The Autonomous Research Assistant
Imagine you give an AI Agent this task: "Find the current price of Bitcoin and send a summary to my WhatsApp."
* Plan: The agent realizes it doesn't know the live price.
* Action: It calls a "Google Search" tool.
* Observation: It sees the price is ₹70,000.
* Action: It calls a "WhatsApp API" tool to send the message.
* Final Response: It tells you, "Task completed."
