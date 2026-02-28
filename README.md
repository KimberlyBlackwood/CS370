# CS370
Machine Learning

Cs 370 Project Two Design Defense
SNHU
Kimberly Blackwood
Professor Hawk
February 15,2026


When it comes to problem solving human decision-making incorporates ethical judgments, social considerations, and empathy. These components  are difficult to determine but crucial in many real-world contexts. Humans depend on intuition and experience to ultimately solve problems. Ai’s problem solving is based on logic and grounded in data. It can process vast amounts of information without the influence of fatigue or emotional bias, making decisions based purely on mathematical models. For this assignment we will look at the approach of problem solving for humans and AI.
Human vs Machine Problem-Solving Approach
Steps a human being would take to solve this maze:
•	Plan moves 
•	Visualize the maze
•	Try several different paths
•	Rethink failure
•	Try new path

Steps my intelligent agent is taking to solve this pathfinding problem:
•	Take actions.
•	Gets rewards.
•	Over several episodes learns the path that leads to the treasure.
•	Decisions over time is guided by Q-values(Tosic.M,2025).

The similarities and differences between these two approaches:

Similarities:
•	Through experience they both learn.
•	Minimizing wrong moves is a priority.

Differences:
•	From the start humans use memory and logic. 
•	Machines depend on reward agents and  need many episodes. 
Assess the purpose of the intelligent agent in pathfinding.
The difference between exploitation and exploration: 
Exploration – a way to discover the best path by trying new moves.

Exploitation – taking the best know move from knowledge learned(MindMap AI, 2025)
What is the ideal proportion of exploitation and exploration for this pathfinding problem? 
The ideal proportion of exploitation and exploration for this pathfinding problem includes 
•	Early episodes: 80% exploration, 20% exploitation (high epsilon).
•	Later episodes: 10% exploration, 90% exploitation (low epsilon).


Explain your reasoning.
By doing  this  the agent will locate good paths early in the game and use them effectively.
How can reinforcement learning help to determine the path to the goal (the treasure) by the agent (the pirate)?
Rewards for right actions are given by Reinforcement learning(e.g. +10 for treasure, -1 for no treasure).The agent learns which sequences of actions lead to maximum rewards. For example, the  fastest and shortest path to gain the treasure.
Evaluate the use of algorithms to solve complex problems.
How did you implement deep Q-learning using neural networks for this game?
I built a neural network that maps states to Q-values (predicted future rewards).
The Q-learning formula:
Q(s, a) = reward + gamma * max(Q(s’, a’))
I used:
Replay memory to stabilize training.
Mini-batches to learn better Q-values.
Neural net to approximate Q-values instead of using a table.




References
MindMap AI.(2025). Goal-Based Agents & Pathfinding Explained. https://mindmapai.app/mind-mapping/goal-based-agents-and-pathfind
Tosic,M.(2025). Human Minds and Machine Learning Models. https://medium.com/data-science/human-minds-vs-machine-learning-models-c66c809194b4




<img width="468" height="666" alt="image" src="https://github.com/user-attachments/assets/d4f9941a-e05b-471a-9b66-48771f40b1a1" />
