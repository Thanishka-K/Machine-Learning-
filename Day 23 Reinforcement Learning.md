# Day 23: Reinforcement Learning (Learning by Interaction)
## The Concept
Reinforcement Learning is a type of machine learning where an Agent learns to make decisions by performing actions in an Environment to maximize a Reward. It is modeled after how humans and animals learn—by receiving "points" for good moves and "penalties" for mistakes.
## Technical Terms 
* Agent: The AI "player" that is learning (e.g., a robot or a character in a game).
* Environment: The world the agent lives in and interacts with.
* State (S): The current situation or "snapshot" of the agent's world.sAction (A): What the agent chooses to do (e.g., move left, jump, or stay still).
* Reward (R): The feedback the agent gets (positive for success, negative for failure).
* Policy (\pi): The "strategy" or rulebook the agent develops to decide which action to take in a given state.
## Key Algorithm: Q-Learning
This is a popular RL algorithm that helps the agent learn the "value" of an action. It uses a Q-Table to store the expected future rewards for every possible action in every possible state.
Real-World Scenario: Training a Self-Driving Car
Imagine you are training a car to navigate a track:
The Goal: Complete the lap as fast as possible without crashing.
* Positive Reward: +10 points for every 10 meters driven safely.
* Negative Reward: -100 points for hitting a barrier.
* The Learning: At first, the car (Agent) crashes constantly. Over thousands of "episodes," it learns that steering slightly left when it sees a curve (State) leads to a higher Reward.

## Turn phone on
