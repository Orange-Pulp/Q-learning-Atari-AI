# Ms-Pac-Man-AI

(Some stuff about Q-learning and how this bot works) ▼
This is an AI bot that can learn to play MS Pac-man using Open-AI gym and Q-learning! The idea of Q-learning is fairly simple, 
this bot will randomly move in all four directions of the Pac-man maze and record how the actions play out. If it finds a 
pattern or trick that will allow it to stay alive longer it will save that and use it later. This maximum reward viariable is called the Q-value, and is used to train tons of different kinds of AI including this one. Currently this AI can survive till around 1,500 points in Ms Pacman right out of the box, as I included a pre-trained neural network to start with. Of-course the AI is always learning and evolving, so the longer you run the training algorithm the more it will learn.

(Some things on how to go about using it) ▼
Open-ai gym is the training enviroment that I am using for this project. Gym is a really cool bit of software made with training AI as the main focus. There are over 100 Atari games in gym that this AI can learn to play, and even more things including real world simulations. Here is the github link for getting this up and running https://github.com/openai/gym  
I also used the scientific computing module numpy  which can be found here https://github.com/numpy/numpy

Of course you can also just type "pip install numpy" or "pip install gym" in a terminal window to install those dependencies

IMPORTANT STUFF:
The Path in the "Super Pac AI.py" and the "Train the AI" script will need to be changed to where you keep this file on your computer so that it can read in the training data. This is because the location of files is never the same across all computer platforms. If you have this file stored direcly on your desktop then the path would probably look something like this:
/Users/(Name of user logged in)/Desktop/Q learning Atari AI/Pac-man AI stuff/config to get to the config file,  or something like that.

Thanks for reading this and have fun with your Pac-man AI! 
