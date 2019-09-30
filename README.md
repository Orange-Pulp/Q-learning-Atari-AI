# Ms-Pac-Man-AI

This is an AI bot that can learn to play MS Pac-man using Open-AI gym and Q-learning! The idea of Q-learning is fairly simple, 
this bot will randomly move in all four directions of the Pac-man maze and record how the actions play out. If it finds a 
pattern or trick that will allow it to stay alive longer it will save that and use it later. After several games the AI will 
have figured out how to survive almost any game. Open-ai gym is the training enviroment that I am using for this project. There
are over 100 atari games that gym supports so you can even test this AI agent on several other classic atari games.  


Dependencies:
openai gym (for the AI training enviroment) https://github.com/openai/gym
numpy (for training the AI) https://github.com/numpy/numpy
Note you can also just type "pip install numpy" or "pip install gym" in a terminal window to install those dependencies

IMPORTANT:
The Path in the "Super Pac AI.py" script will need to be changed to where you keep this file on your computer, as the location
of files is never the same across computers.
