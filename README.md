# Minimal Visualized Examples

## Chemical Source Underwater Environment Simulation
<img src="./images/simulation.gif" width=300 align="middle">  
An example of chemical source underwater environment. In which, the water flows from left to right. The initial concentration of the source is 0.8 out of 1.0. The odor packets are spawned at every time step and traveling under effect of the mean water flow and a sinuous fluctuation. In general, the odor plume has a cone shape.

## Chemical Source Localizing via Remote Sensing
<p float="left">
<img src="./images/sensing_simulation.gif" width=300 ">  
<img src="./images/sensing_predict.gif" width=100 ">  
</p>
The underwater simulation (left) and the heat map prediction which tells the source location respect to agent's current location (right).
The autonomous agent has predefined trajectory which repeats going straight to left and right. At each timestep, the agent can sense the chemical concentration whithin its range (yellow circle), and measure the water flow force to infere the chemical source location.
In this episode simulation, based on the strong water flow is from top right to bottom left, the agent can infer the source location is at top of predicting the image. When agents receive some chemical concentration, it can tell the source is at the top right.


## Chemical Plume Tracking using Deep Reinforcement Learning
<p float="left">
<img src="./images/seeking_simulation.gif" width=500 ">  
<img src="./images/seeking_trajectory.gif" width=200 ">  
</p>
In this episode simulation, based on the strong water flow is from top right to bottom left. The agent is trained to track the chemical plume to seek the chemical source.

## Multi-Agent Object Localization and Classification via Reinforcement Learning
<p float="left">
<img src="./images/Multi_Agent_MNIST_Localization.gif" width=800 ">  
</p>
Multiple MNIST digits are replaced at random position in the environment. Training a neural network to process the observation history of multi-agent system to localize and classify the detected objects. Training a multi-agent reinforcement learning policy to efficiently explore the environment. The goal is finding, localizing, and classifying all the objects.
The first img is the environment example. The middle image is the observations of multi-agents system. The third image is the system's predictions of where and what digits are.


## Auto Image Caption
<img src="./images/image_caption_generating.png" width=600 align="middle">  


