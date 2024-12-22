# Lagrangian Neural Network (LNN)

Project on the Lagragian NN for the class of MLPAP.

- Implementation of a Baseline NN to predict $\ddot q_i$ from $[q_i, \dot q_i]$ and Euler iterative integration to recreate a trajectory starting from initial conditions.
- Revisit of a LNN developped by Miles Cranmer.
- Optimization of the different hyper parameters.
- Creation of visuals and animation.
- Checking energy conservation.

Studied systems :
- Double pendulum (including chaotic trajectories).
- 2 and 3 coupled pendulums with a torsion rod.
- Adaptibility to any system with a $(q, \dot q)$ physical description.

Concrete example with the LNN for the double pendulum : 

![](https://github.com/PyNoe/LNN/blob/main/Visuals/double_pendulum_sub2.gif)

Accuracy example with two coupled pendulums with a torsion rod :

![alt text](https://github.com/PyNoe/LNN/blob/main/Visuals/PendulesCouplés_torsion.jpg)
