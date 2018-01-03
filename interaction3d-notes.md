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
     - tool control: 
       - virtual hand
       - virtual ray: has the problem of eye-hand visibility mismatch; occlusion selection
     - cd ratio: control-display ratio which determins how translation/rotation of input are transfered to the selection tool; can be static (isomorphic) or dynamic (GO-GO); cd ratio <1 means increasing the area affording direct manipulation at the cost of decreasing accuracy
     - motor and visual space relationship: 
         - coupled
         - decoupled: proprioceptive feedback no longer suffices and visual feedback is critical.
     - disambiguation mechanism: 
          - manual (Grossman's depth ray and flow ray): flexible at the cost of cognitive load
          - heuristic (ranking the objects with disambiguity when selection happens);
          - behavior (continuously ranking objects before selection happens): particularly useful for selecting moving targets
            Tradeoff between mechanisms depends on the flexibility, density and size of objects. Heuristic and behavior methods do not introduce further selections, at the cost of unwanted selections and thus require users to repeat selections.
     - selection trigger:
       - event: press to select (triggered when pressing), hold to select (triggered when releasing )and dwell to select (triggered when a fixed amount of time passsed). The first one suffers from Heisenberg effect.
       - gesture: pinch (improved version: AirTap and Thumb Trigger)
       - voice
- Selection requirements:
  - provide rapid selection
  - be accurate and error-proof
  - be easy to understand and control
  - produce low levels of fatigue

# The Object Inside: Assessing 3D Examination with a Spherical Handheld Perspective-Corrected Display

Berard 2017

This paper conducts a user study using a graph tracing task ( or object examination task as they named it). This study compared the task performance of a handheld spherical FTVR, an traditional screen and physical counterparts. They found the digital interfaces are more efficient than the physical shape. The traditional 2D interface with touchpad outperforms spherical FTVR.

*The physical object is in cube shape that has seams. It may not be fair to compare it with spherical display and traditional 2d display. Also it has limitations on the nature lighting: not enough contrast between object and background; specular reflection from the box; etc.*

# Recent Advances in Augmented Reality
Behringer 2001
A survey paper that complements previous survey paper (Azuma's "A Survey of Augmented Reality"in 1997) by presenting new advances in AR. 

They define **Enabling technologies** as advances in the basic technologies needed to build compelling AR environments. Examples include displays, tracking, registration and calibration:
- Displays
  - Head Mounted displays: optical see-through and video see-through displays. Optical see-throughs can be further divided as transparent screen and virtual retinal displays. (hololens, oculus)
  - Handhelp displays: hand-held, flat-panel LCD displays that provides video see-through-based augmentations. (pcubee)
  - Projection displays: virtual information is projected directly on the physical objects to be augmented. (CAVE, spheree)
- Tracking: typically head-tracking systems employ hybrid-tracking techniques to exploit strengths and compensate weekness of individual tracking technologies. (see SCAAT as a multi-sensor fusion method)
- Calibration: AR systems generally require extensive calibration to produce accurate registration with measurements  including camera parameters, field of view, sensor offsets, object locations, distortions and so forth.

User interfaces and interaction: 
- Multiple displays to leverage the advantages of indivisual displays
- Tangible interfaces

Human factors:
- Latency: for close range tasks, a simple rule of thumb is that one ms of delay causes 1 mm of error.
- Depth perception: stereo helps with depth perception, but current display technology causes additional problems (accommodation-vergence conflicts, low resolution and dim displays (?)). Consistent registrarion is important in depth perception!
- Adaptation
- Fatigue and eye strain


# Virtual Reality on a WIM: Interactive Worlds in a Miniature
Stoakley 1995
This paper introduces a third-person perspective combined with first-person perspective on a HMD, called "World in Miniature" (WIM). The WIM metaphor augments the HMD with a hand-help miniature copy of the virtual world. This allows users to select, navigate, path plan and visualize the immersive world through multiple third-person view-points and different scales.
**Bimanual interaction** is implemented by having the non-dorminant hand holding a physical board with a polhemus sensor and the dorminant hand grabbing a tennis ball with a polhemus sensor and two buttons attached. The user can examine the miniature model by moving the board and use the ball to point to select either the miniature model or objects in the immersive environment. 
*This can be thought as a 3D map in a first-person game.*
*They find props are very important to guide user's motion so that the user won't find themselves into uncomfortable positions to rotate objects. Possibly because 1. passive haptic feedback from props gives clue about how to interact and 2. props set constraints on user's motion. *
*They also tried pen rather than ball and found that pen is most appropriate for manipulation when they are constrained to a plane. A pen on the surface does not appear to expressive enough to capture object rotation well.*

# The Rockin' Mouse: Integral 3D Manipulation on a Plane

Balakrishnan 1997

An influential paper that describes the design rationale and evaluation of a 3D mouse. It is also a rare paper that actually beat the mouse in terms of task performance. It has good discussions on: 1. what's good about the mouse and 2. what's the problem of the mouse for 3D.

1. What's good about the Mouse?
   - Physical form factor: arm on the plane, less fatigue, good for both precise movement and relaxed movement.
   - Stability: large area contacting with surface, so it damps the hand tremor. In contrast, stylus can transmit, sometimes even amplify hand tremor.
   - Relative mode: mouse moves in relative mode that reports its position relative to some keypoints. So the amount of arm movement can be small and does not require much effort.
   - Device to cursor mapping: natural
2. What's the mouse's problem for 3D manipulation: does not inherently support 3D operations. Multiple methods are developed to solve it:
   - Hot-key solution: switch between movement in the three axes. Problem: unnatural; user has to remember hot keys, move cognitive load.
   - Virtual widgets: associated with a particular transformation. Decompose a 3D task into several 1D/2D ones. Problem: tasks like 3D motion path requires simultaneous manipulations of all three dimensions.

Then they compared their Rockin' 3D Mouse with normal 2D Mouse using a 3D position task. They found their 3D Mouse has better task performance with less time spent.

# Rotating Virtual Objects with Real Handles

Colin Ware 1999

This paper conducts a series of experiments that tried to find out why rotating in virtual environment is far slower than it takes to rotate a real object. They find out: 

1. Placing the hand in the same spot as the virtual object appears will improve the task performance.
2. The result failed to support the idea that it is important for the shape of an object held in the hand to be the same as the shape of the object seen.
3. The results failed to show an advantage of two handed rotation vs. one handed input.
4. Whether the object is being rotated to a new, randomly determined orientation will greatly influence the task performance, compared to always rotating to the same position.

*Good experiment setup: Look at these experiments setups in details when designing rotation/scaling task!*

# 3D Contour Perception for Flow Visualization

Colin Ware 2006

This paper investigates the Rendering issues and Perception issues when visualizing with trajectory-based data. [Rendering] They found that when contours are rendered as shaded tubes, users can perform accurate judgments. [Perception] This combined with stereoscopic and kinetic depth cues results in most consistently good judgment.

*Use the rendering suggestions in the user study.*

# Pointing at 3D targets in a stereo head-tracked virtual environment

Teather 2011

This paper presents three experiments that examine 3D pointing task in FTVR using Fitts' Law. They implemented several pointing techniques: *Pen Touch*, *Pen Ray*, *Mouse Cursor*, *Floating Cursor* and *Sliding Cursor*. 

They conducted Fitts' Law experiments on these pointing techniques and found fully 3D motions are less well modeled with Fitts' Law.

# Cursors for 3D Pointing

# LOP-cursor: Fast and precise interaction with tiled displays using one hand and levels of precision

# Disambiguation canvas: A precise selection technique for virtual environments

# Increasing Selection Accuracy and Speed through Progressive Refinement

# Asymmetric Division of Labor in Human Skilled Bimanual Action: The Kinematic Chain as a Model

Guiard 1987

One of the most influential paper on the theoretical foundation of bimanual interaction. It provides three high-order principles that appear to determine the asymmetry of human bimanual gestures. The three principles are:

- The non-dominant hand defines the spatial reference to the dominant hand. It contributes an important stabilizing action to the achievement of the global act. 

- The non-dominant and dominant hand has contrast in the spatial-temporal scale of motion: fine motion with right-hand and coarse motion with left-hand.

- Non-dominant hand initializes the action earlier than that of the dominant hand.

Some experiments have been conducted to support these principles as evidence, as well as some observations of activities like writing and golfing. 

# Selection performance based on classes of bimanual actions

Ulinski 2009 [todo]

A technical report on bimanual selection. They compare four selection strategies regarding symmetric and synchronous conditions. They found that no class of bimanual selection was a significant contributor to reduce or increase physical demand. But asynchronous action significantly increases cognitive load.

Need to first read their selection paper. This report does not explain clearly on selection techniques.

# Two handed selection techniques for volumetric data
Ulinski 2007

Three distinct two-handed selection techniques for volumetric data have been developed. They are all based on a selection box for gross selection: Hand-On-Cornder, Hand-In-Middle and Two-Corners. 

These selection techniques were evaluated in terms of accuracy, completion time, ease of use, physical workload and ease of learning. They found the Two-Corner (TC) approach performs selection with the most accuracy at the cost of staticsically significant amount of arm strain. They concluded the symmetric property makes TC method outperform others which are asymmetric. 

*Their Conclusion on symmetric property may be biased given that the box shape is symmetric. Selection techniques use other geometric primitives may have different conclusions.*
*Their evaluation setup is worth learning.*

# Perceiving real-world viewpoint changes
Daniel Simons 1998

A research report on the distinction between object rotations and viewpoint motions. Both object rotations and viewpoint motions generate the same retina image, but this report focuses on distinguishing the mechanisms of object rotations and viewpoint motions. Viewpoint motions potentially provide more information than object orientations, including but not limited to the spatial reference (visual information), vestibular and proprioceptive information. But they did not compare the task performances of object orientation and viewpoint movement conditions. Instead, they compared the effect of changing retina projections in the condition of rotation and movements. They found even when orientation changes and viewpoint changes produced the same changes to the retinal projection, accuracy was disrupted only in the orientation condition, not in the movement condition.

