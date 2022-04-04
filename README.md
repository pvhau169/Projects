# Minimal Visualized Examples

## Chemical Source Underwater Environment Simulation
<img src="./images/simulation.gif" width=300 align="middle">  
An example of chemical source underwater environment. In which, the water flows from left to right. The initial concentration of the source is 0.8 out of 1.0. The odor packets are spawned at every time step and traveling under effect of the mean water flow and a sinuous fluctuation. In general, the odor plume has a cone shape.

## Remotely chemical source localizing via timeseries classification
<p float="left">
<img src="./images/sensing_simulation.gif" width=300 ">  
<img src="./images/sensing_predict.gif" width=100 ">  
</p>
The underwater simulation (left) and the heat map prediction which tells the source location respect to agent's current location (right).
The autonomous agent has predefined trajectory which repeats going straight to left and right. At each timestep, the agent can sense the chemical concentration whithin its range (yellow circle), and measure the water flow force to infere the chemical source location.
In this episode simulation, based on the strong water flow is from top right to bottom left, the agent can infer the source location is at top of predicting the image. When agents receive some chemical concentration, it can tell the source is at the top right.


## Chemical plume tracking using deep reinforcement learning
<p float="left">
<img src="./images/seeking_simulation.gif" width=300 ">  
<img src="./images/seeking_trajectory.gif" width=100 ">  
</p>
In this episode simulation, based on the strong water flow is from top right to bottom left. The agent is trained to track the chemical plume to seek the chemical source.


## Image Caption Generating
<img src="./images/image_caption_generating.png" width=400 align="middle">  


