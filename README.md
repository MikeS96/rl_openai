# Reinforcement Learning with OpenAI Gym

This repository aims to solve three basic challenges in OpenAI Gym with RL techniques.

<div  align="center">
<img src="./images/lunar_lander.gif" width="240" /> <img src="./images/mountain_car.gif" width="240" />  <img src="./images/pendulum.gif" width="240" /> 
</div>

## Description

There are four different main files in this repository which are listed as follows.

 1. `LunarLander.ipynb`
 2. `Mountain Car.ipynb`
 3. `Pendulum.ipynb`
 4. `Pendulum_Replay_Experince.ipynb`

As their name suggest, each file is related to one specific RL problem. In fact, to solve these tasks different RL techniques were employed. The **Lunar Lander** problem was solved using Semi-gradient Expected Sarsa with experience replay, **Mountain Car** used Semi-gradient Sarsa with tile coding for linear features' construction. Furthermore, The **Pendulum** task was tackled with two approaches: The first one used Policy-gradient methods (Actor-Critic) without experience replay, sadly, this approach did not solved the challenge. The second approach used the same policy-gradient technique but with experience replay to increase stability during training and solve the challenge.

The file `tiles3.py` is a Tile Coding python implementation by *Rich Sutton* to create linear features for RL problems with function approximation.

## Requirements

The following list provides the minimum requirements to run the project.

    matplotlib >= 3.2.1
    cv2 >= 3.4.0
    numpy >= 1.18.1
    tqdm >= 4.46.1
    torch >= 1.5.0
    gym >= 0.17.2

## Usage

To run the files, just use Jupyter Notebook and run the cells of the file you want to see.

    jupyter-notebook

For further description and explanation, please check the Notebooks.
