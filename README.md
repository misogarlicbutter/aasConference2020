# aasConference2020

This is the repo for managing papers and code for the AAS/AIAA Conference 2020. 

The conference will be held August 9 - 13, 2020 at the Lake Tahoe Resort Hotel in South Lake Tahoe, CA. 

The abstract deadline is April 10, 2020. Notification of acceptance will be sent via email by May 9, 2020. More details can be found on the conference website https://www.space-flight.org/docs/2020_summer/2020_summer.html.  

# Meeting Notes

Meeting Notes will be organized from most recent date to the earliest date. 

## 2/24/2020 

Paper introduction feedback 
- title: "... with Sparse Dynamics Identification" 
- remove J.Q. Public 
- remove "trajectory optimization" 
- move references cited to right after name of authors (instead of at end of sentence) 
- benefit of dual quaternions is we can use other quat-based control laws 
- MPC + SINDY good for sudden changes in system 
- take out "predator-prey" model 
- discuss: SINDY + PC vs. adaptive control laws? Tsiotras address constraints? 
- what is the selling point of this paper 
- more literature review on MPC + dual quaternions 
- need at least 10 refs in intro  

## 1/29/2020 

MPC 
- Contact Joey about posing the MPC problem correctly

Present topic to Tim Lofquist

## 1/24/2020 

Simulation 
- Nonlinear equations --> Simulink 
- Build dynamic model, add noise 
- Generate x, y, z data 
- Use SINDy for state identification 
	- Get differential equations 
	
Controller 
- MPC (model-predictive control) or reinforcement learning 
- Add disturbances, check controller performance 
- Compare design
	- which system is more intuitive, easy to use? 
	
Dual quaternions 
- Need to use kinematics + dual quaternion equations 

NASA Fellowship 
- Possible: swarm project at Ames 
- Phase 1 proposal due: Feb 21, 2020
	
### Tasks
- Review literature 
- Write introduction 
- Come up with paper title 
- Use Mendeley with LaTeX? 

## 1/17/2020 

Focus on 3 topics: 

1. MPC (model-predictive control) 
2. SINDy 
3. Dual Quaternions 

### Tasks 
- Ask Max RPO proposal
- Ask Chriss RPO proposal 

## 12/2/2019

1. Reinforcement learning on CMGs
    	- Spacecraft attitude control + constraints 
        	- Actuator saturation 
    	- Adaptive dynamic programming 
    	- RL toolbox Matlab 
	
2. Reaction wheel speed/torque control 

3. Fuel slosh 

4. Key words: 
	- Reinforcement learning 
	- Adaptive dynamic programming 
	- Game theoretic optimal control 
	- SINDy: sparse identification of nonlinear dynamics 
	- dual quaternions 
	
Bong Wie: 
- Space Vehicles Dynamics and Control 
	- chapters 7, 11, 12 
	
