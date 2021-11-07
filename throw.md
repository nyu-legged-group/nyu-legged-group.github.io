# Whole-Body Optimization of Long-Distance Throw for a Humanoid in Double Support
### Dongdong Lui, Yuhang Lin, Alexander Koldy, Vikram Kapila

## Abstract
In recent years, there has been a growing interest in the use of optimal control techniques for diverse application
scenarios being envisioned for humanoid robots. Throwing is a common human activity used in a variety of situations,
including sports, hunting, rescue, etc. Optimization approaches have previously been considered to maximize the simulated
throw performance for humans. Experimental approaches for improving human throw performance have been restricted
to observation and mimicry of high performing athletes. In the case of robotics, prior research on throw performance
improvement using optimization has been limited to simulations studies, with scant research considering experimental validation. 
To address this research gap, in this effort, we consider the optimal design, experimental implementation, and analysis
of a whole-body throwing motion in a double support humanoid robot with the use of a differential dynamic programming
(DDP) approach. We provide results from repeated experiments to demonstrate that the proposed DDP method significantly
improves the throwing performance for a 23 degrees-of-freedom humanoid robot in contrast to a previously proposed key-frame
(KF) method. With the framework of this paper, a humanoid robot can perform highly dynamic whole-body throwing tasks, achieving 
optimal throwing distance while maintaining balance stability.

## Code
```
The code is copyrighted by the authors. Permission to copy and use 
 this software for noncommercial use is hereby granted provided: (a)
 this notice is retained in all copies, (2) the publication describing
 the method (indicated below) is clearly cited, and (3) the
 distribution from which the code was obtained is clearly cited. For
 all other uses, please contact the authors.
 
 The software code is provided "as is" with ABSOLUTELY NO WARRANTY
 expressed or implied. Use at your own risk.

This code provides an implementation of the method described in the
following publication: 

Dongdong Liu, Yuhang Lin, Alexander Koldy, and Vikram Kapila    
"Whole-Body Optimization of Long-Distance Throw for a Humanoid in Double Support (ICRA)". 
```

## Concept
**The concept of a humanoid throwing motion: (a) initial pose, (b) preparation pose, (c) throw pose, and (d)  recovery pose. A ball is released from the robot's right gripper at the end of the throw phase.**
<div align="center">
<img src="https://raw.githubusercontent.com/nyu-legged-group/nyu-legged-group.github.io/main/docs/assets/img/robot throw.PNG"/>
</div>

## Simulation
**Simulated joint positions for differential-dynamic programming (DDP) approach.\ Lower extremity:**
<div align="center">
<img src="https://raw.githubusercontent.com/nyu-legged-group/nyu-legged-group.github.io/main/docs/assets/img/Lower.png"/>
</div>

**Upper extremity:**
<div align="center">
<img src="https://raw.githubusercontent.com/nyu-legged-group/nyu-legged-group.github.io/main/docs/assets/img/Lower.png"/>
</div>

## Results



