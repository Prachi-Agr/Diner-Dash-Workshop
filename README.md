# **Diner Dash Workshop**

## Overview
The Diner Dash workshop provides an interactive avenue for participants to learn about Reinforcement Learning (RL). Diner Dash is a game where a single waiter makes complex decisions on customer seating arrangements, taking orders, serving food and many others. In groups of 2 or 3, participants would test out RL baselines and compete with one another for the highest score in the Diner Dash simulator. 

## Official Schedule
#### 4 August 2020, Tuesday
| **Time** | **Programme** |
| - | - |
| 9am | [Introduction to Reinforcement Learning](#Introduction-to-Reinforcement-Learning) |
| 10am | [Diner Dash Introduction](#Diner-Dash-Introduction) |
| 10:30am | [Diner Dash Challenge Briefing](#Diner-Dash-Challenge) |
| 11am | [Start of Challenge](#Diner-Dash-Challenge) |
| 4pm  | [Random seeds given for testing, Submission portal opens](#Submission-platform-and-leaderboard) |
| 9pm  | [Cut off for submissions, Participants can check the leaderboard for winners](#Submission-platform-and-leaderboard) |

## Introduction to Reinforcement Learning
Speaker: [Akshay Narayan](https://www.comp.nus.edu.sg/cs/bio/anarayan/)

Background of this field of RL (both theoretical and practical applications)

## Diner Dash Introduction
Author of the Diner Dash Simulator: Siwei

Please refer to the [diner dash repo](https://github.com/AdaCompNUS/diner-dash-simulator) for more information.

## Diner Dash Challenge
### Prerequisites
- Basic knowledge of Python
- A stable internet connection
- A Google account

### Objective
Using RL, maximise the average rewards from 100 games/episodes of Diner Dash.

### Challenge Platform
We will be using Google Colab for this challenge. The challenge template and further instructions are provided [here](https://github.com/AISG-Technology-Team/Diner-Dash-Workshop/blob/master/Challenge_Template.ipynb). Please open the notebook in colab and create a copy in your gdrive.

### Submission Format
- Google Colab Notebook (.ipynb)
    - Please ensure that it is fully ran
    - Output matches the submitted json file
- Json file (.json)
    - With names of members in the group (Please do not change the key name "names")
        ```
        "names": "john, mary, bryan"
        ```
    - With lists of actions in order of random seeds given (Please do not change the key name "actionDict")
        ```
        # Assuming 2 random seeds with 2 algos (randomAgent & PPO)
        "actionDict": {
            "randomAgent": 
                [[6, 45, 32, 53, 4],
                 [27, 3, 12, 34, 1]],
            "PPO":
                [[13, 42, 31, 2, 4, 8],
                 [31, 14, 15, 18, 35, 56, 46]]        
                }
        ```

A sample submission can be found [here](https://github.com/AISG-Technology-Team/Diner-Dash-Workshop/tree/master/sample_submission).

### Submission platform and leaderboard
Please use this [website](https://aisummerschool.aisingapore.org/) for submissions as well as viewing the leaderboard.

## Additional Resources
- [RL Stable Baselines Repo](https://github.com/hill-a/stable-baselines)
- [RL Stable Baselines Tutorial + Colab Notebooks](https://github.com/araffin/rl-tutorial-jnrr19)
- [Deep Q-learning (DQN) Tutorial](https://www.analyticsvidhya.com/blog/2019/04/introduction-deep-q-learning-python/)
- [RL Library for tensorflow](https://github.com/tensorflow/agents): [TF agent DQN Tutorial](https://github.com/tensorflow/agents/blob/master/docs/tutorials/1_dqn_tutorial.ipynb)

## Acknowledgements
### Tutorial Speaker
- [Akshay Narayan](https://www.comp.nus.edu.sg/cs/bio/anarayan/)

### Diner Dash Simulator
- Siwei

### AI Singapore (Organisers)
- Dr Winkler
- Benjamin Chua
- Linxu
- Haixun
- Sean

[Back to top](#Diner-Dash-Workshop)