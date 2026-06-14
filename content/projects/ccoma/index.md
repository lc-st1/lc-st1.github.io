---
title: CCoMa
date: 2023-09-25
links:
  - type: site
    url: https://github.com/lc-st1/CCoMa
---

The Cable-actuated Continuum Manipulators (CCoMa) Python package is a plugin I wrote for simulating tension-driven soft robots in the PyBullet environment. It was created as part of my work in the Soft Machines and Electronics Lab at Case Western Reserve University under the mentorship of Dr. Changyong Cao. The CCoMa package implements flexible continuum manipulators using a beam-deflection approximation of elastic behavior. It allowed the lab to experiment with training reinforcement learning-based approaches to controlling soft manipulators. The full package and documentation can be found on my GitHub at https://github.com/lc-st1/CCoMa.


## Cable-actuated Continuum Manipulatos (CCoMa)


The goal of this project was the implementation of a simulation package that could predict the motion of a flexible robot manipulator based on the tension of the cables embedded within it. The effect of both cable routing and manipulator geometry were both included in the simulation, as this was used to train a machine learning model on the control of soft manipulators. As shown in several of the videos, a system was implemented for customizing the cable routing and robot geomtry while loading the simulation. This was used to test various setups, as shown in the videos below. The first features a double-segmented manipulator with straight cable routing, while the second features the same geometry with helical cable routing. This is the configuration in which the cables wrap around each segment in a spiral rather than run straight through. This produced a significantly different motion when the same tension was applied to each cable.

<video width="640" height="360" controls>
  <source src="double_segment_straight_cables.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<video width="640" height="360" controls>
  <source src="double_segment_helical_cables.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

A similar setup was simulated with a shorter geometry consisting of a single cable-driven segment.

<video width="640" height="360" controls>
  <source src="single_segment_straight_cables.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
<video width="640" height="360" controls>
  <source src="single_segment_helical_cables.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

Variations on the geometry of the robot were also tested, as a tapered segment is shown below.

<video width="640" height="360" controls>
  <source src="tapered_segment_control_demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

This project was made possible by the Soft Machines and Electronics Lab at Case Western Reserve University, under the guidance of Dr. Changyong Cao.