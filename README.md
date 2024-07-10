# -2048-Game-Reinforcement-Learning
Developed a Deep Q-Network model to optimize gameplay in the 2048 game, focusing on reward maximization and strategic navigation.

To have this code fully running you need to install the following packages:
* stable_baselines3: to use the DQN model from this library 
* shimmy:
* manim & libcairo2-dev ffmpeg\texlive texlive-latex-extra texlive-fonts-extra \texlive-latex-recommended texlive-science \tipa libpango1.0-dev
:these are used to visualize our game for the demo. 
* gym: to use the game environment you need to import gym

* installation instructions *
pip install stable_baselines3

pip install shimmy

!sudo apt update
!sudo apt install libcairo2-dev ffmpeg \
    texlive texlive-latex-extra texlive-fonts-extra \
    texlive-latex-recommended texlive-science \
    tipa libpango1.0-dev
!pip install manim
!pip install IPython --upgrade

* You also need to import the following libraries:
import numpy as np
import gym
import gym.spaces as spaces
from gym.utils import seeding
import gymnasium as gym
from stable_baselines3 import DQN
from manim import *
import numpy as np
import gym
from stable_baselines3 import DQN
import gym.spaces as spaces
from gym.utils import seeding
from manim import config






