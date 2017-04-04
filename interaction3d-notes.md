# Exploration and Virtual Camera Control in Virtual Three Dimensional Environments

1990 Colin Ware

This paper discusses and evaluates three different metaphors for virtual camera controls in VEs: 

- eyeball in hand 
- scene in hand: good for closed objects; not good for moving through an interior
- flying vehicle control: best for navigating through through an interior; poor for moving around a closed object

Evaluations are carried based on three "toy environments": SIGNS, MAZE and CUBE.

*Useful discussions on how 3D UI metaphors help the interaction process in relation to different tasks.*

*Evaluation tasks are interesting.*

# Did “Minority Report” Get It Wrong? Superiority of the Mouse over 3D Input Devices in a 3D Placement Task

2009 François Bérard 

This paper compares the performance effeciency in accomplishing 3D placement task using both 2D mouse and 3 DoF input devices. The 2D mouse outperformed the 3D input device. 

*Useful discussion on the mouse preference problem in 3D interaction.*

*List past literature that found 3D inputs outperformed 2D mouse.*

# A Survey of Design Issues in Spatial Input

1994 Ken Hinckley

This is a powerful survey paper that reviews almost all 3D interactions before 1994. It groups observations into two categories as human perception-based design and ergonomic-based design issues. 

From the perceptual standpoint, this paper suggests a set of strategies to help user s to better perceive a 3D VE based on previous literature. They suggested a distinction between *understanding* 3D vs. *experiencing* 3D: people are good at experiencing 3D but do not innately understand 3D. They argue that performing 3D tasks is general, is a result of sub-conscious perception of 3D space. This is a process that has not been understood well. Previous paper demonstrated a number of issues that they found in user study to facilitate 3D space perception, including:

- Spatial references
- Relative gestures vs. absolute gesture
- Bimanual interaction
- Multi-sensory feedback
- Physical constraints
- Headtracking
- Reduce DoF
- Control metaphor (see 1990 Colin Ware)

Ergonomics issues includes:
- Integrate multi-DoF rapid coarse manipulation with slower but more precise manipulation techniques.
- Integrate 2D interaction with 3D interaction in a unified framework: hybrid interface.
- Allow users to adjust postures when interacting with 3D objects: recalibration mechanism is one way to alleviate the fatigue.





# Exploring Gameplay Experiences on the Oculus Rift

2015 Tan

This paper examines the user experience in the actual gameplays with Oculus Rift. They find that the cybersickness is still prevalent on the Rift. However, the uncomfortableness hardly affects immersion. Users are obsessed with the immersion with the existence of the cybersickness. They further provides several insights for designing games for the Rift. 

*Useful summery of the previous work on the user study with HMD: what kind of problems the HMD has.*

*Insights are useful for designing content for the Rift/HMDs.*

# 3D User Interfaces: New Directions and New Perspectives

2008 Bowman

A symposium survey paper on 3D User Interface reflecting on the state of the art in 2008. 

**Multisensory Input for Improved Performance**

- Provide a *pipeline with six steps* to design the combination of different input devices.
- Discuss input device design issues: 
  - each input device has specific *sensory feedback* (e.g joystick's counterforce); it is important to match its feedback with the task.
  - provide simultaneous and separate DoF though an ergonomic arrangement of various sensors; 

**3D Interfaces for Multidisplay Environments**

- Describe techniques to manage windows and text (2D GUI) in multi-screen environment:

  - perspective cursor
  - perspective window

**Guidelines for Easy-to-Use 3D Interaction Techniques**

Useful discussions on the importance of constraints in 3DUI:
- 2D tasks are cognitively simpler than 3D
- 2D input devices are advantageous: less hand fatigue and more accuracy

**3D UIs for and beyong VR**

3D UIs are not necessary to only support VR. They should be able to impact both VR and ordinary desktop. But there are several questions to answer:
- Research must provide evidence that *3D UIs have significant advantages over desktop-style interactions*: empirical studies that compare 3D UIs to 2D UIs are conducted. 
- Find out areas where interaction is problematic and 3D UIs will be a good fit: gaming like kinect, wii; large display in public space to provide interactions with people standing up and walking around. 

# Separating the Effects of Level of Immersion and 3D Interaction Techniques

2006 McMahan

This paper evaluates the importance of immersion and 3D interaction techniques by separating them. They made several good points:

- Unlike the *presence*, immersion is measurable. The immersion is defined as *"the objective level of fidelity of the sensory stimuli produced by a technological system"*. 

- Immersion consists of resolution, FoV, stereoscopy, field of regard(number of CAVE walls) etc.

- They pick stereoscopy and field of regard as variables of immersion.

- They pick DO-IT, GOGO and HOMER as variables of interaction techniques, within which DO-IT is the Desktop-Based Technique.

- They pick a 3D manipulation task as the evaluation task.

They conclude that the interaction technique has a significant effect on task performance, while the two variables of immersion did not.

*Their study is not sufficient since stereoscopy becomes important within arm distance, while their setup places objects in distant positions.*

They also conclude that for distant object manipulations, 3D interaction techniques work significantly better than 2D desktop-based interactions.

# A Survey of 3D Object Selection Techniques for Virtual Environments

2013 Argelaguet 

A review paper that surveys 3D selection techinques, including human control models and existing selection techniques.

- Human pointing models:
 - Fitts Law: estimate the movement time according to the target size.
 - optimized initial impulse model: a twe phase model that describes the process of acquisition task. Ballistic phase: fast and inaccurate movement toward the target; Corrective phase: slow and accurate movement executed in close loop feeback until objects are acquired.

- 3D Selection Classification
 - selection tool: shape (ray, cone, cube and sphere); some selection techniques allow users to change to shape during intereaction.
 - DoF
 - disambiguation mechanism
 - cd ratio
 - motor and visual space relationship