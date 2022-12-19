# Sarsa and Q-learning Agents in a Maze

## Envirionment Descriptions

**NOTE**: The code written for the environment is not my doing, it is given for the assignment.

**Policies:**
- If the person crashes into the maze walls or black rocks, he will stand where is and gets 3 negative points.
- If he falls in a pound and then gets out, he will het 10 negative points.
- He gets tired in the way, so, He gets a -0.5 point for each step he takes.

**Step method of the class GridworldEnv:**
* It takes a number as input and make the person take a step. 0. up 1. right 2. down 3. left
* Output of the step method: (state, reward, done, info) "done" is a flag determining whether the person has reached the end or not.

## Approشches Taken
* Implemented Sarsa and Q-learning agents
* Decreased alpha and epsilon parameters during the training, and compared the results with the case in which these parameters were during the training.
* Calculated regret for each episode and plotted it in the end.



