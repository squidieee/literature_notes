- Introduction

  - Contribution: an empirical study aimed at evaluating the benefits of a Spherical Perspective-Corrected Display for spatial reasoning.

- Related Work

- 3DPS Display

  - design rationale
  - implementation
  - performance

- User Study: Evaluation of spatial reasoning with 3DPS

  - Mental Rotation Task
  - Experimental Setup
    - hardware: a spherical screen/planar screen + three projectors + camera + IR source
    - software: unity based texture rendering
  - Experimental Design
      1. Viewing Conditions: 3DPS+Touch and 2D display+Touch
      2. Experimental Variables: 
         - Independent variables: viewing condition (2 levels) and rotation angle (3 levels)
         - Dependent variables: error rate and completion time
      3. Possible extraneous factors: 
        - Resolution: viewing conditions have the same resolution
        - Latency (we need a way to estimate and improve the latency)
        - Lighting
        - Registration error: Each subject needs to do viewpoint calibration before using 3DPS
        - Tracking error (magnetic interference): Subjects are not wearing any metal stuff.
  - Participants & Procedure
  - Result
    - Two-way RM ANOVA + pairwise t-test