# self-driving-car-stories
This is my secret notebook which helps me to track my progress on writing SDC, AI-related master's thesis.

## Mind map

![](images/mindmap.png)

## Progress

1. Build AirSim on Linux, control the car remotely via ssh (31.10.2018)
![](https://media.giphy.com/media/2tRoKjX4R0ZEs5xkpr/giphy.gif)
	- build UnrealEngine 4.18 and Microsoft/AirSim
	- customize example Unreal project
	- set up ssh connection with proxy jump and remote port forwarding
	- run bare-bones `airsim` python script to control the car and capture images from camera
	- [full demo video](https://drive.google.com/file/d/1jrG0tF3Q46QNrw3CcDA4_jF6YP4jAxZw/view?usp=sharing)



		
		
# Useful commands
```
# Carla 0.9 from jenkins

# Save movie frames as pnf files to <...>/CarlaUE4/Saved/Screenshots/LinuxNoEditor/MovieFrame<...>.png
./CarlaUE4.sh -benchmark -fps=30 -dumpmovie
./CarlaUE4 -benchmark -fps=30 -dumpmovie
```
About VNC + VGL
https://github.com/CDAT/cdat/wiki/Remote-server-setup-for-VNC

Virtual Displays
https://towardsdatascience.com/how-to-run-unity-on-amazon-cloud-or-without-monitor-3c10ce022639

Nervana Coach alg descriptions:
https://nervanasystems.github.io/coach/algorithms/policy_optimization/ddpg/
	
Unity ML-agents student-teacher (imitation learning)
https://blogs.unity3d.com/2018/05/24/imitation-learning-in-unity-the-workflow/

Overtaking in ROS:
http://www.dcsc.tudelft.nl/~jalonsomora/docs/17-andersen-ITSC.pdf

Policy algorithms explained with math:
https://lilianweng.github.io/lil-log/2018/04/08/policy-gradient-algorithms.html

DDPG explained:
https://yanpanlau.github.io/2016/10/11/Torcs-Keras.html


Amazon AWS Autonomous manouvers with RL + demo videos
https://www.youtube.com/watch?v=UqoWv4IWkRc

## TODO
Visualization: https://tobloef.com/text2mindmap/
```
Thesis
	Simulators and environments
		Udacity v1
		Udacity v2
		Carla sim
		Microsoft/AirSim
		Deepdrive
		F1 2015 (telemetry)
		Dirt 3 (telemetry)
		Euro Truck Simulator 2
		Harbador, Tesla, Unity projects (source code not public)
	Methods to try
		Behavioral Cloning
		A3C Actor critic
		Supervised Learning
		Conditional Imitation Learning
		Pure Reinforcement Learning
	Goal(s) to achieve
		Lane keeping
		Parking
		Crossroads
		Following planned route with concious decisions (e.g. A*, safe turns)
		
	First steps to make
		1. Run different environments and estimate their capabilities (make detailed comparison)
		2. Try to run selected envs on remote machines using ssh (cluster) (AirSim/Carla/Udacity)?
		3. Collect most valuable links/papers (I have too much of junk resources, still)
		4. Write table of contents sketch
		5. Write abstract with goal(s) description and current SDC state
```
