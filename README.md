# Q-learning Atari AI

(Some stuff about Q-learning and how this bot works) ▼

This is an AI that can learn to play almost any atari game using Open-AI gym and Q-learning! The idea of Q-learning is fairly simple, this bot starts off making random moves with no knowledge of how to play the game. It is simply told to maximize a reward value called a "Q value". The better the bot plays the more reward it gets. The great thing about Q-learning is that it can be applied to almost anything without any previous knowledge of the task. There are hundereds of games in Open-ai gym that this bot can learn to play, so I invite you to experiment with it. 



(How to change games) ▼

You can change the game this AI plays by going to line 74 and changing the gym.make variable to any other game in the Open-AI gym library. Here is a link to all of the games.      https://gym.openai.com/envs/#atari



(Disclamer thing ▼)

This should work with any up to date version of open AI Gym. However, This Bot was built and optimized for tensorflow 1.15.0 
and may not work with some builds of tensorflow 2.0. I reccomend using a docker file or virtual enviroment if you regularly use tensorflow 2.




(Dependanciezzz) ▼

Open-AI gym
(Pip install gym) or   https://github.com/openai/gym


Numpy
(Pip install numpy) or  https://github.com/numpy/numpy


And lastly Google's own machine learning library tensorflow.   https://github.com/tensorflow/tensorflow


Thanks for reading this and have fun with your game bot! 
