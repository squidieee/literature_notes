# Chunking and Phrasing and the design of human-computer dialogues

William Buxton 1986

 This paper talks about how to design user interface pragmatics so that we can accelerate the process whereby novices begin to perform like experts. Experts and novices differ in the coarseness of granularity with which they view the constituent elements of a particular problem or task. Novices are attentive to low-level details. With experts, these low-level details can be performed automatically.

- One major problem is the cognitive load imposed by remembering the tokens and their orders of a command. The approach is to limit the number of arguments to a command. (eg: 1-step move vs. 2-step copy n' paste)
- When compound task is necessary, breaks it into sub-tasks. Sub-tasks require the "glue" to tie them together. (eg: select from a pop-up menu = invoke the menu + navigate to select + select, the tension of the finger holding down the button is the "glue" which provides constant feedback that we are in a temporary state.)

# User studies and Usability Evaluations: From Research to Products

I. Scott Kackenzie 2015

- **What is Research**	Three definition of research:
  - careful search
  - collecting information about a particular subject
  - push the frontier in light of new facts
- **Categorization of Research** Three categories of research methods:
  - Observations study: 
    - Qualitative, rather than quantitative
    - Focus on *why or how*, as opposed to *what, where or when*
    - Goal is to understand human thoughts, feelings, attitude, emotion, passion, sensation, reflection, expression, mood, outlook, opinion, manner, style, approach, strategy...
    - Methods include: field study, expert reviews, contextual inquiries, interviews, case studies, focus groups, think aloud protocols, walkthroughs...
    - Studied in a natural setting, as opposed to constrained and artificial setting
    - **Usability Evaluation** is an example of observational method.
  - Experimental method:
    - Include independent and dependent variables
    - Controlled methodology brings prevision
    - **User Study** is an experiment with human subjects.
  - Correlational research:
    - Looking for relationships between variables
    - Quantitative
    - Provide a balance between relevance and precision
- Internal Validity & External Validity:
  - Interval validity: outcomes observed in the study really exist
  - External validity: outcomes observed are broadly applicable to other people
  - **User Study** focuses on Internal validity while **Usability Evaluation** focuses on External validity
- Difference between **User Study** and **Usability Evaluation**
  - User Study is performed early after research but before engineering and design; Usability evaluation is performed late (on a prototype) after engineering and design but before product release.
  - User Study is controlled with independent variables; Usability Evaluation is observational without a particular independent variable.
  - User Study has low-level details. The task is constrained to avoid extraneous influences and to provide capability to distinguish the levels of independent variables. Usability Evaluation is high-level. The task is natural and unconstrained. The goal is to reflect how end-user interacts with the UI and uncover potential problems.

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