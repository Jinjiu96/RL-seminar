Assignment 3: Tabular Reinforcement Learning in the OpenAI gym

This assignment introduces you to the wonderful world of the OpenAI gym. With a very simple interface, the Gym allows you to interact with a plethora of interesting environments, of which:

- Simulated 3D robots (Mujoco and Roboschool)
- The Atari games
- The OpenAI Gym Retro package allows you agent to play any GameBox, NES, SNES, GameCube or Sega Genesis game

This assignment contains a mostly-empty main.py file, that shows how to create a Gym environment. Your tasks are the following:

- Create a simple tabular Q-Learning agent (same as in Assignment 2), with the exploration strategy of your liking. No points given for this, this is a prerequisite. Do Assignment 2 if you want points for this agent :) .
- 6 points: extend that agent with Experience Replay or Eligibility traces (when seen during the lectures). If you find a way to have experience replay and eligibility traces at the same time, please come to my office so that we can write a paper together.
- 6 points: find a way to support continuous-states environment (instead of numbered states, your agent observes Numpy arrays that are vectors of floats, such as x,y coordinates in a room). You can use neural networks (when seen during the lectures), or any other creative way. Test this with a simple environment such as LunarLander. This task can be combined with the previous one.
- 6 points: successfully learn LunarLander. LunarLander is successfully learned when the mean cumulative reward reaches 200.

The last 2 points will be given depending on how well and cleanly you implement the tasks. Also, grading is flexible (as usual, the goal is not to give bad grades). If you don't want to do one of the tasks, do the other ones very well and everything will be alright. Feel free to send me an email (dsteckel@ai.vub.ac.be) if you have a question, or an idea of a task for which you want points.
