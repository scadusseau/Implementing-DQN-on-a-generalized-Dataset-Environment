# Implementing-DQN-on-a-generalized-Dataset-Environment
This project is an academic work. It is a step in the design of a generalized DQN algorithms framework.
The environment was designed for a dataset, with a generalised architecture, in order to train a same agent on various environments.

Here, the agent is a soccer team. The goal is to be the champion of the world. The agent can choose to encounter any team in the dataset, that contains statistics about each team. Those statistics indicates the level of the team, and the final result is evaluated regarding the teams levels. The particularity of this environment is that the source is a dataset (other environments usually use images or vectors).

This environment is very basic and could be improved in order to be more realistic (and more complex).
-Other's team score does not vary, but it could be changing after each encounter, in order to add more stochasticity 
-Draw results are not considered in this version, but could be taken in count, for wider possibilities.
