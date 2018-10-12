# Two-hand Pointing

## iSith-Intersection-Based Spatial Interaction for Two Hands

Wyss 2006

[todo]

## Symmetric bimanual interaction

Balakrishnan 2000

This paper investigates factors that may influence symmetric bimanual interaction performance, including visual integration, distance between targets and tracking speed. They used a bimanual symmetric tracking task that requires users to (i) track two separate objects simultaneously with two cursors controlled by two hands and (ii) track one integrated object with one cursor controlled by two hands together. The task is slightly from pointing since the visual stimulus of target were presented continuously, rather than one after another in Fitts Law. 

They claimed different definitions of *parallelism* and *symmetry* for bimanual performance. Performance could be parallel (occur simultaneously) and yet asymmetric in terms of error and time measures. They also proposed a new metric a new metric to quantify the degree of parallelism by taking the ratio of the two hand’s m-metric derived from Masliah's multi-DoF metric. They found even when users are given a task with identical, symmetric role assignments for each hand, they do not always perform the task in a parallel, symmetric manner.



## A haptic interface for two-handed 6DOF manipulation-SPIDAR-G&G system

Murayama 2004

This paper presents a bi-manual haptic system in VE. They used a bimanual manipulation task which used non-dominant hand to grab the object and dominant hand to point the target on the object, essentially an asymmetric bimanual pointing task. They measure completion time to evaluate their system and compared to an uni-manual condition. 

Good asymmetric bimanual task. Adding more metrics to this task may help to understand the asymmetric nature of bimanual interaction.

# Two-Hand Coordination: Psychology Track

# Multi-degree Input Coordination: HCI Track 

## Quantifying coordination in multiple DOF movement and its application to evaluating 6 DOF input devices
Zhai 1998

A good paper that evaluates the coordination of multiple DoF movement when conducting various 3D tasks. It explores how well user can control multiple DoF at the same time. The "wellness" is defined as the coordination of the motor performance. 

It investigates how to measure coordination for a given trial of motor performance as: 
- Simultaneity: Percentage duration of multiple DoF co-activated over the entire time of operation. But it does not account for the magnitude of the control actions in each DoF.

- Time-on-target and correlation:  Recording simultaneous time-on- target (STOT) in all pairs of degrees of freedom as well as all three at once, in addition to TOT (time-on-target) in each of the component dimensions. If the percent STOT was equal to the product of the component TOTs, then the components may be considered independent (uncoordinated). If greater, they were positively correlated (coordinated); if less, negatively correlated (discoordinated). However, both TOT and correlation as coordination measures have drawbacks. One of them is that these two measures do not account for perfect trials.

- Efficiency: It compares the "shortest" trajectory with actual trajectory for translation and likewise for rotation. Author suggested the coordination measure proposed in the paper can be applied to research beyond 6 DOF input devices such as coordination for two-hand computer input. 

Details of more measurement data using correlation and TOT can be found in following paper: 
*Investigating Coordination in Multidegree of Freedom Control I: Correlation Analysis in 6 Dof Tracking*
*Investigating Coordination in Multidegree of Freedom Control II: Correlation Analysis in 6 Dof Tracking*
Zhai 1997

In this experiment, author used the efficiency measurement rather than STOT and correlation. They claimed although efficiency measure was sensitive enough to reveal performance differences, this is not necessary the only “correct” measure to quantify coordination in multiple DoF tasks. 

This efficiency measure does not provide any numerical value to represent the simultaneous coordination of the translation and rotation DOF. It provides a global measure of the coordination but not local simultaneous coordination. 

## Influence of degrees of freedom's manipulation on performances during orientation tasks in virtual reality environments

Veit 2009

This paper investigates the influence of the integration and separation of DoFs on the users’ performances during 3D orientation tasks. They believe in certain situations of interaction, reducing the number of DoF simultaneously manipulated may lead to better performances. 

 They proposed a new metric which can measure the number of DoF simultaneously manipulated during an orientation task. It's called MDS (Magnitude of DOF’s Separation) measurement defined as:

MDSi = (|Vx −Vy|+|Vx −Vz|+|Vy −Vz|)/ 2 / (Vx + Vy + Vz)

By dividing time into small segments, they computed velocity for each axis for ti ~ ti+1. Then MDSi is 1 if only one axis is moving and 0 if all axis are moving with the same magnitude.

In the experiment, they used a set of performance metrics as well as the coordination metric MDS to analyze user's task performance, including:

- Performance metrics:

  - Angular difference: final orientation between target and manipulated object
  - Completion Time
  - Coarse completion time: first time the difference is smaller than 20 degree
  - Fine completion time: first time the difference is smaller than 10 degree

- Coordination metric: MDS

They found 50% of the time, users manipulates only two DOF at the same time, suggesting that during the orientation task, the users are only able to partially integrate the manipulation of all the DOF at the same time. One possible explanation is that because of the task complexity and the user’s incapacity to find the optimal path toward the target, they may try to decompose the task into more simple orientations. 
They also found that when providing a multi-DoF and a single-DoF interaction technique, the performance data is better with single-DoF technique.