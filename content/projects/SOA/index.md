---
title: Sensor Observability Analysis
summary: Sensor Observability Analysis aims to quantify the quality of sensor observations of task-space quantities based on the robot configuration.

tags:
  - SOA
  - active
date: '2022-01-01T00:00:00Z'
# draft: true

# Optional external URL for project (replaces project detail page).
external_link: ''

# image_preview: 'img/SOAbanner.jpg'

image: 
  caption: 
  focal_point: Smart

links:
  - icon: 
    icon_pack: 
    name: T-RO 2024 Paper
    url: https://www.researchgate.net/publication/370687950_Sensor_Observability_Analysis_for_Maximizing_Task-Space_Observability_of_Articulated_Robots
  - icon: 
    icon_pack: 
    name: IROS 2022 Presentation
    url: https://www.youtube.com/watch?v=W8IQpi4CBZg
  # - icon: researchgate
  #   icon_pack: ai
  #   name: ResearchGate
  #   url: https://www.researchgate.net/project/Sensor-Observability-Analysis
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

<!-- Sensor Observability Analysis, akin to the kinematic manipulability index, aims to quantify the quality of sensor observations of task-space quantities based on the robot configuration for optimization purposes. -->

Sensor Observability Analysis, akin to the kinematic manipulability index, is a novel performance metric for articulated robotic mechanisms.
The goal is to analyse and evaluate the performance of robot-mounted distributed directional or axial-based sensors to observe specific axes in task space as a function of joint configuration.
For example, joint torque sensors are often used in serial robot manipulators and assumed to be perfectly capable of estimating end effector forces, but certain joint configurations may cause one or more task-space axes to be unobservable as a result of how the joint torque sensors are aligned.
The proposed sensor observability analysis provides a method to analyse the cumulative quality of a robot configuration to observe the task space.
The resultant metrics can then be used in optimization and in null-space control to avoid sensor observability singular configurations or to maximize sensor observability in particular directions.
Parallels are drawn between sensor observability and the traditional kinematic Jacobian for the particular case of joint torque sensors in serial robot manipulators.
Compared to kinematic analysis using the Jacobian in serial manipulators, sensor observability analysis is shown to be more generalizable in terms of analysing non-joint-mounted sensors and can potentially be applied to sensor types other than for force sensing, e.g., link-mounted proximity sensors.
We demonstrate the utility and importance of sensor observability in physical interactions using simulations and experiments of a custom 3-DOF robot and the Baxter robot.

**Related Research Items**: 
* C. Y. Wong and W. Suleiman, "Sensor Observability Analysis for Maximizing Task-Space Observability of Articulated Robots," in *IEEE Transactions on Robotics*, 2024. (Accepted)
  * [ResearchGate Link](https://www.researchgate.net/publication/370687950_Sensor_Observability_Analysis_for_Maximizing_Task-Space_Observability_of_Articulated_Robots)
* C. Y. Wong and W. Suleiman, "Sensor Observability Index: Evaluating Sensor Alignment for Task-Space Observability in Robotic Manipulators," *2022 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*, Kyoto, Japan, 2022, pp. 1276-1282.
  * [IEEE *Xplore* Link](https://ieeexplore.ieee.org/document/9982209)
  * [ResearchGate Link](https://www.researchgate.net/publication/362629254_Sensor_Observability_Index_Evaluating_Sensor_Alignment_for_Task-Space_Observability_in_Robotic_Manipulators)
  * [IROS 2022 Presentation (Kyoto, Oct 2022)](https://www.youtube.com/watch?v=W8IQpi4CBZg)
