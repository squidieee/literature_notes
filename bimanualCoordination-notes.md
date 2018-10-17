# Two-hand Pointing

## iSith-Intersection-Based Spatial Interaction for Two Hands

Wyss 2006

As an early work of bimanual pointing, this paper  introduced a concept of bimanual pointing for object selection and manipulation using two rays from two hand. It did not have an evaluation but just introducing of the concept.



## Symmetric bimanual interaction

Balakrishnan 2000

This paper investigates factors that may influence symmetric bimanual interaction performance, including visual integration, distance between targets and tracking speed. They used a bimanual symmetric tracking task that requires users to (i) track two separate objects simultaneously with two cursors controlled by two hands and (ii) track one integrated object with one cursor controlled by two hands together. The task is slightly from pointing since the visual stimulus of target were presented continuously, rather than one after another in Fitts Law. 

They claimed different definitions of *parallelism* and *symmetry* for bimanual performance. Performance could be parallel (occur simultaneously) and yet asymmetric in terms of error and time measures. They also proposed a new metric a new metric to quantify the degree of parallelism by taking the ratio of the two hand’s m-metric derived from Masliah's multi-DoF metric. They found even when users are given a task with identical, symmetric role assignments for each hand, they do not always perform the task in a parallel, symmetric manner.



## A haptic interface for two-handed 6DOF manipulation-SPIDAR-G&G system

Murayama 2004

This paper presents a bi-manual haptic system in VE. They used a bimanual manipulation task which used non-dominant hand to grab the object and dominant hand to point to the target on the object, essentially an asymmetric bimanual pointing task. They measure completion time to evaluate their system and compared to an uni-manual condition. 

Good asymmetric bimanual task. Adding more metrics to this task may help to understand the asymmetric nature of bimanual interaction.

## Influence of the bimanual frame of reference with haptics for unimanual interaction tasks in virtual environments

Ullrich 2011

They evaluate if Guiard’s theory of the bimanual frame of reference can be applied to interaction tasks in virtual environments (VE) with haptic rendering. Two conditions, one unimanual and bimanual, are used in the study. They applied an asymmetric bimanual insertion task. Non-dominant hand first touch to select, then dominant hand used a probe to insert into the target, similar to the peg-in-hole task. They observed whether users moved their non-dominant hands during the study.

They found that:

- Task completion times are significantly lower in the bimanual condition compared to the unimanual case, without significant impact on overall precision. Furthermore, the bimanual condition shows better mean accuracy over several measures, e.g., lateral displacement and penetration depth. 
- Participants with experience in performing medical procedures did not outperform the other participants
- They observed that several subjects actively used head tracking to get a better view. Consequently, they achieved better average results.

Their task is generic but derived from medical applications, quite similar to Hoffmann's peg-in-hole study. The bimanual movement is asynchronized and asymmetric. The data analysisi is mainly about performance (completion time and error). 

# Two-hand Selection

## Selection performance based on classes of bimanual actions

Ulinski 2009 

A technical report on bimanual selection. They compare four selection strategies regarding symmetric and synchronous conditions. They found that 

- Symmetric-synchronous technique was found to allow significantly faster completion time than any other techniques.

- No differences for accuracy was found between any of the four selection techniques.

- No class of bimanual selection was a significant contributor to reduce or increase Physical Load for experienced users. 

- Asynchronous action significantly increases Mental Load, especially when coupled with asymmetric interaction.

- Symmetric with Asynchronous interactions are less natural to use with significantly less ease of use.


## Two handed selection techniques for volumetric data

Ulinski 2007

Three distinct two-handed selection techniques for volumetric data have been developed. They are all based on a selection box for gross selection: Hand-On-Cornder, Hand-In-Middle and Two-Corners. 

These selection techniques were evaluated in terms of accuracy, completion time, ease of use, physical workload and ease of learning. They found the Two-Corner (TC) approach performs selection with the most accuracy at the cost of staticsically significant amount of arm strain. They concluded the symmetric property makes TC method outperform others which are asymmetric. 

*Their Conclusion on symmetric property may be biased given that the box shape is symmetric. Selection techniques use other geometric primitives may have different conclusions.*
*Their evaluation setup is worth learning.*



# Two-Hand Coordination: Psychology Track

## Asymmetric Division of Labor in Human Skilled Bimanual Action: The Kinematic Chain as a Model

Guiard 1987

One of the most influential paper on the theoretical foundation of bimanual interaction. It provides three high-order principles that appear to determine the asymmetry of human bimanual gestures. The three principles are:

- The non-dominant hand defines the spatial reference to the dominant hand. It contributes an important stabilizing action to the achievement of the global act. 
- The non-dominant and dominant hand has contrast in the spatial-temporal scale of motion: fine motion with right-hand and coarse motion with left-hand.
- Non-dominant hand initializes the action earlier than that of the dominant hand.

Some experiments have been conducted to support these principles as evidence, as well as some observations of activities like writing and golfing. 

## Effects of task characteristics on unimanual and bimanual movement times

Srinivasan 2013

This paper provides preliminary study to model bimanual Fitts Law in real world. They used a bimanual object transfer task to investigate how the size and tolerance of transferred object can influence task performance. In the task, subjects grab two objects with left and right hand and move them to two target locations. The operation is symmetric and independent for each hand. They measured each hand's MT in unimanual and bimanual conditions and compared them to see how bimanual operation can affect ID and MT.

They found:

- Bimanual tasks always started simultaneously, and the primary hand completed its motion with the same duration that would be expected for a unimanual task under the same conditions. The secondary hand movement duration, however, was dependent both on its own task, as well as the primary hand’s task demand. (Primary hand = hand first completed the task, not necessary to be dominant hand)

- The subjects almost always chose the left, slower hand as the primary hand when the tasks were symmetric. When tasks were asymmetric, the left hand was still chosen more often as the primary hand than the right.

Their study indicates:

- Modelling bimanual pointing requires detailed understanding of the *vision requirement* of the task, eg the distance between targets.

- *Hand synchronization is lost whenever one of the tasks is too difficult for the two tasks to be accomplished simultaneously*. If the two targets are high-precision targets, the task completions are sequenced, with the slower (non-preferred hand) generally finishing first, and the total task time extended as a result. This effect scales with the distance separating the two targets.

The study provides good real-world observations for developing bimanual interaction techniques as well as bimanual tasks.



## Bimanual and Unimanual Convergent Goal-Directed Movement Times

Hoffmann 2015

This paper compares the performance of unimanual and bimanual movement time using Fitts Law. They aimed at providing convergent bimanual data that can help to model bimanual pointing. 

They used three tasks, each has four conditions. The four conditions are: 

- (one-hand movement with probe in preferred hand)
- (one-hand movement with probe in non-preferred hand)
- (two-hand movement with probe in preferred hand)
- (two-hand movement with probe in non-preferred hand)

Three tasks are:
- Bimanual Fitts Law Task: notice this is not a symmetric task as one hand holds the context with the other hand pointing to the target.
- Peg-in-hole: similar to fitts law task, but it requires the probe inserted into the hole.
- Low ID tasks: same as previous two, but with low ID.

They found:
- The effects of using one or two hands for movements are generally not large. 
- In Fitts’ task and peg-in-hole,, 2-hand movements were faster than 1 hand only at higher IDs.

This paper also has interesting discussion on the divergent vs convergent bimanual movements. It is believed that the divergent bimanual movement caused divergent attention assigned to each hand so Fitts' Law does not model it well. For convergent movement, it fits better with Fitts' Law but still some there is still some divergency from model. It may be due to that tremor effect is amplified in single-hand condition. 


# Multi-degree Input Coordination Measurement

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


## Measuring the allocation of control in a 6 degree-of-freedom docking experiment

Masliah 2000

[todo]