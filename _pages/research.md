---
permalink: /research/
title: "Current Research Areas"
author_profile: true
redirect_from: 
  - /research
  - /research.md
---

These are areas of research I am actively working on! For a comprehensive list of previous work, please see [my CV page](https://marisapetrusky.github.io/cv/).

## Hypersonic Aerothermodynamics
Arguably, the most dangerous part of any planetary exploration mission is the entry of a spacecraft through a planet’s atmosphere. Spacecraft must rapidly decelerate from entry velocities upwards of 40 times the speed of sound, resulting in the compression and heating of gas via a hypersonic shock layer. Accurate numerical simulations of this intense flow regime are essential for designing safe and optimized spacecraft, particularly when delicate instrumentation and astronauts are inside.

At sufficiently high entry speeds, a fraction of gas is ionized via the shock layer to form a plasma. These ionized species carry electric charge, leading to the formation of electric fields. Conventionally, plasma electrostatics are neglected in entry flow simulations, as calculation of electric fields can be prohibitively computationally expensive. However, advances in computing technology have lessened this limitation. Research into plasma electrostatics of hypersonic entry flows has direct application in mitigation of radio communications blackout, detection of radiation signatures of hypersonic flight, magnetohydrodynamic (MHD) flow control and propulsion, and more!

## Plasma Sheaths
In the presence of a wall, a negative charge deficit will appear in a plasma, as the lightweight electrons will recombine at the wall at a faster rate than ions. To resolve this charge deficit, a thin boundary layer of non-neutral plasma forms at the wall, which forms a potential barrier that adjusts itself such that the flux of ions and electrons to the wall are equal. Plasma sheaths form in almost all practical plasma devices, such as fusion reactors or vacuum chambers, but can also form on hypersonic vehicles if the surrounding gas is sufficiently ionized. Technologies such as electron transpiration cooling (ETC) seek to take advantage of this plasma sheath in order to cool the vehicle.

A critical gap in literature is that a majority of classical plasma sheath theory is developed for fully ionized plasmas. Verifying whether classical theory can be applied to rarefied, weakly ionized plasmas in nonequilibrium flows is crucial for understanding plasma electrostatics in hypersonic flight conditions.

## Discrete-Velocity Methods
Study of rarefied gas flows necessitates the use of kinetic modeling methods, as continuum assumtions breakdown and traditional computational fluid dynamics (CFD) codes cannot be used. Particle-based methods, such as Direct Simulation Monte Carlo (DSMC) or Particle-in-Cell (PIC), have been successfully used to study this regime for decades. However, for certain problems, particle-based methods suffer from statistical noise, especially when attempting to resolve trace species, infrequent chemical reactions, or highly spatially varying flows. Reducing this statistical noise comes at increased computational expense. 

Discrete-velocity (also known as continuum-kinetic or grid-based kinetic) methods directly compute the time evolution of the probability density function of the flow according to the Boltzmann transport equation, allowing for deterministic simulation of flow properties. The cost of discretizing both configuration and velocity space is high, but can be alleviated with optimization and adaptive mesh techniques. Discrete-velocity methods are widely used throughout plasma physics and astrophysics applications, and are beginning to gain popularity in high-speed flow analysis.

## STEM Education
As someone who frequently got lost in math class, I am very passionate about improving STEM education. Our science communication skills should not just be reserved for the general public, they are equally valuable and appreciated in the classroom! My current work centers on incorporating dialogic learning methods in STEM classrooms. Dialogic learning refers to use of dialogue or discussion exercises to enhance learning through co-construction of knowledge. Student outcomes include better engagement throughout the lecture, improved communication and reasoning skills, and a stronger sense of community with peers and educators. However, applying dialogic learning concepts in STEM classrooms takes some creativity and trial-and-error. I am always happy to share successes and failures from my teaching and mentoring experiences!
