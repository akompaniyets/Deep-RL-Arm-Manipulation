# Deep RL Arm Manipulation #
#### Robotics Software Engineering ####
#### Term 2 ####
#### Project 4 ####

_Concepts/Skills Learned:_
  * Reinforcement Learning:
    * Markov Decision Process
    * Policies
    * State-value functions
    * Bellman Expectation Equation
    * Action-value functions
    * Q-learning algorithm
    * OpenAI Gym
  * Deep RL (Deep Q-Network): PyTorch
  * Recurrent Neural Networks (RNNs): LSTMs

---

_Project Description:_

The fourth project of term 2 introduced the field of reinforcement learning, or RL. The fundamentals of RL were first discussed, specifically in regards to building action-reward schematics. This basic understanding of RL was developed further with an introduction to the Q-learning algorithm, a more organized and defined means of building action-state relationships, while integrating reward, learning rate, and discount parameters. OpenAI Gym was implemented in testing this algorithm, allowing a virtual robot to learn how to play simple games and accomlish simple tasks (such as balancing a stick on a pedestal), following appropriate parameter tuning.

RL understanding was futher expanded with an introduction to deep RL, which substitutes a specifically defined algorithm (with pre-defined actions and states) with a neural network, allowing a robot to develop its own understanding, or "learning", of which actions lead to the most desired results. PyTorch was implemented in both building and testing deep RL networks, which was further built-upon with a C++ API to allow said networks to learn to play simple games successfully.

Ultimately, the Python-encoded deep RL network was used within a C++ template to allow a robotic arm to learn a very specific movement (touching a small cylinder with its gripper's base). The C++ application had extensively modified parameters, especially in its reward functions and values, as well as various hyperparameters. Furthermore, long short-term memory (or LSTM) was also introducted to allow the application to have a functional memory base of successful/preferred actions or states. 
     
   For a full report of how this was accomplished, see the included write-up: 
   
   [Deep RL Arm Manipulation Write-Up](https://github.com/akompaniyets/Deep-RL-Arm-Manipulation/blob/master/Project%204%20Write-Up.pdf)
   
   This particular project was based largely on the Nvidia Jetson Reinforcement Lab, found [here](https://github.com/dusty-nv/jetson-reinforcement).
