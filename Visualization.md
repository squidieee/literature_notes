# Human factors in visualization research

Melanie Tory 2004

This paper reviewed known methodology for doing human factors research, with specific emphasis on visualization. It also reviewed current human factors research in visualization to provide a basis for future investigation.

**Categorization**	Visualization techniques have been traditionally categorized into two major areas:

- *scientific visualization*: which involves scientific data with an inherent physical component.
- *information visualization*: which involves abstract, nonspatial data

They introduced  new terminology:
- *Continuous model visualization*: encom- passes all visualization algorithms that use a continuous model of the data, and is roughly analogous to *scientific visualization*.
- *Discrete model visualization* includes visualization algorithms that use discrete data models and roughly corresponds to *information visualization*.

**Why Visualization**	They summarized how visualizations can provide cognitive support through a number of mechanisms:

1) Increased Resource

- parallel processing: "In psychology, parallel processing is the ability of the brain to simultaneously process incoming stimuli of differing quality.Parallel processing is a part of vision in that the brain divides what it sees into four components: color, motion, shape, and depth. These are individually analyzed and then compared to stored memories, which helps the brain identify what you are viewing The brain then combines all of these into the field of view that you see and comprehend."

- Offload work to the perceptual system: with an appropriate visualization, some tasks can be done using simple perceptual operations.
- External memory: visualizations are external data representations that can reduce demands on human memory.
- Increased storage and accessibility: visualizations can store large amounts of information in an easily accessible form.

2) Reduced Search

- Grouping: visualizations can group related information for easy search and access.
- High data density: visualizations can represent a large quantity of data in a small space.
- Structure: Imposing structure on data and tasks can reduce task complexity.

3) Enhanced Recognition

- Recognition instead of recall
- Abstraction and aggregation: selective omission and aggregation of data acan allow higher level patterns to be recognized

4) Perceptual Monitoring: using pre-attentive visual characteristics allows monitoring of a large number of potential events.

5) Manipulable Medium: interactive exploration through manipulation of parameters can allow different patterns to be recognized.

**How to design Visualization Techniques**

1) Task-based Design: Task analysis allows designers to define detailed functional specifications and user interface limitations. Structured task analysis methods include observation, interviews, and surveys of potential users. See [Springmeyer1992] for details. Another researcher described task analysis as the investigation of a wide range of factors, includes:
- personal, social, and cultural characteristics of users
- user preferences and values
- goals and how users achieve them
- user knowledge, experience, and thought processes
- physical environment
- tasks to be performed with the system
- problems users would like to see the system solve
- other tasks that must be performed while using the system (to give an idea of the user’s cognitive load)

System designers can use the results of task analysis (guidelines, requirements, and constraints) to design useable and useful systems.

*The results of task analysis are usually the implication or impact of a study, including guidelines (eg. motion parallax is important in xx task; applications reply on xx task should include motion parallax), requirements (eg. identify sub-tasks that must be performed while using the system; identify user background and knowledge required for the task) and constraints (eg. physical or cognitive constraints of a user performing the task: chunk of memory; multi-DoF control overhead).*

2) Perception-based Design
Cognition and perception theories can help designers find faults in current systems and develop new ideas that should be effective. Many perception-based design guidelines are described by Ware for *Discrete model visualization*. The paper gives a list of guidelines to follow when designing visualization interface while satisfying the perception needs of human. 

*They are nice discussions similar to Ware's Information Visualization book but more concentrated so high-level to follow. See paper for details before designing visualization interface.* 

[Springmeyer1992] A characterization of the scientific data analysis process. 

**Research Examples**

1) Improving Perception in Visualization Systems:Several papers have looked at how our knowledge of perception can be used to improve visualization design (eg. depth-of-focus, encoding color).

2) Interaction Metaphor: Interacting with 3D visualizations can be challenging because mapping movements of a 2D mouse to actions in 3D space is not straightforward. Research has shown that manipulating objects relative to each other is easier than using absolute coordinates. In addition, interaction may be easier when the interface is directly related to the task through task-specific props.

*They did not discuss too much on how to interact with data via navigation, selection etc, but rather just briefly discuss different aspects of input methods and the importance of this area.*

3) Fidelity of 3D graph models:Improving realism is not too relevant to visualization because the goal is to represent data, not to display a realistic image of the world. Applications more relevant to visualization include increasing rendering speed (to enable interactive data exploration) and reducing image artifacts (to enhance perception and prevent incorrect interpretations of data).

4) Transfer Functions

5) Detail and Context Displays: One way to increase the amount of information displayed is to make the display larger. However, large displays still have limited space. Increasing the screen size will not always solve this problem. Specifically, studies could consider when, if, and how increasing display size and resolution affects visualization task performance.

*They discussed a bit on resolution and size but not on other factors such as form, display shape etc.*

6) Human-Computer Cooperation

Most visualization systems are designed so that humans and computers can cooperate, each performing the tasks they do best. Computers can easily store and display data, but humans are better at interpreting data and making decisions. Although this idea is very useful, it is possible for computers to play a more active role in the visualization process than simply presenting data and providing an interface for data manipulation.


# Visual Information in Surface and Depth Perception: Reconciling Pictures and Reality

Vishwanath2010

A chapter in the vision science book "*Perception beyond inference: The information content of visual processes*". It discusses: 
(1) why do we see depth in pictures even when the predominance of visual information suggests otherwise?
(2) why does pictorial depth appear qualitatively different from "real" depth.

It makes following interesting points:
- The perception of relative depth (depth order, surface slant, 3D shape) and the perception of absolute depth (egocentrically scaled depth separation) are dissociable and distinct.
- The perceltual vividness of depth under binocular viewing (plastic effect) is not an epiphenomenon resulting from stereoscopic depth processing.

**How to Model the Cue Combination**
The Cue combination is presented as Bayesian-inference framework, where percepved scene interpretation (S) is that with the highest posterior probability given the sensory image (Image): 
P(S | Image) = P(Image | S) * P(S) / P(Image)

In words, the probablitity of the scene interpretation given the sensory image is proportional to the probability of the image given the interpretation multiplied by the prior probability of such scenes in the world: the more frequent a person received an image given such interpretation in the past -> the more likely they will interpretate the current image in that way. 

if we consider the image as a set of statistically indepedent image cues (texturem, shading etc), the model can be written as:
P(S | Image) ~ P(Cue1 | S) * P(Cue2 | S) * P(Cue3 | S) ... P(S)

In the modal priors approach, the ratio of probabilities for the scene interpretation S to the probablities of the complement of S, indicated as !S (all interpretations other than S):
P(S3d | Image) / P(!S3d | Image) = P(Image | S3d) * P(S3d) / (P(Image | !S3d) * P(!S3d))

The interpretation selected by the visual system should therefore be the one with the highest posterior ratio. This indicates: if we have a particular image measure or cue that we believe the visual systems uses to make interpretations, the measured values or resolution of that cue obtained in the image must be as high as the real world to garrantee the interpratation. 

**Exocentric and Egocentric Depth are distinct**
The relative depth information mostly obtains in both pictorial and real objects. It is the egocentric depth that is missing from the 2D picture. The author believes the plastic effect is linked to the egocentric distance infornation. 

**Realism and Absolute Depth**
The plastic effect is in essnece the qualitiative perceptual experience that makes objects appear "real", "touchable or graspable", and where one feels a visual "immersion"  and "embodiment" in space. Each of theses experiences is crucially linked to the vivid sense that we can successfully interact with the object through motor actions. Successful motor interactions has a singular prerequisite: reliable *egocentrically defined perceptual estimates of spatial properties* such as distance, direction and size. 

**Duality of Picturial and Real Depth**
The fact that the plastic effect appears dissociable from the perception of 3D surface structure supports the notion that there are two ways in which we can experience the depth: not the pictorial and real space, but rather between relative and egocentric depth. 


# A characterization of the scientific data analysis process

todo