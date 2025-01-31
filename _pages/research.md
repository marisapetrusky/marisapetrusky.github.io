---
permalink: /research/
title: "Research Interests"
author_profile: true
redirect_from: 
  - /research
  - /research.md
---

# Hypersonic Entry Flows
Arguably, the most dangerous part of any planetary exploration mission is the entry of a spacecraft through a planet’s atmosphere. Spacecraft must rapidly decelerate from entry velocities upwards of 40 times the speed of sound, resulting in the compression and heating of gas via a hypersonic shock layer. Accurate numerical simulations of this intense flow regime are essential for designing safe and optimized spacecraft, particularly when delicate instrumentation and astronauts are inside.

At sufficiently high entry speeds, a fraction of gas is ionized via the shock layer to form a plasma. These ionized species carry electric charge, leading to the formation of electric fields. Conventionally, plasma electrostatics are neglected in entry flow simulations, as calculation of electric fields can be prohibitively computationally expensive. However, advances in computing technology have lessened this limitation, and more detailed investigations of plasma electrostatics are possible.

Research into plasma electrostatics of hypersonic entry flows has direct application in mitigation of radio communications blackout, detection of radiation signatures of hypersonic flight, magnetohydrodynamic (MHD) flow control and propulsion, and more!

# Plasma Sheaths
In the presence of a wall, a negative charge deficit will appear in a plasma, as the lightweight electrons will recombine at the wall at a faster rate than ions. To resolve this charge deficit, a thin boundary layer of non-neutral plasma forms at the wall, which forms a potential barrier that adjusts itself such that the flux of ions and electrons to the wall are equal. Plasma sheaths form in almost all practical plasma devices, such as fusion reactors or vacuum chambers, but can also form on hypersonic vehicles if the surrounding gas is sufficiently ionized. Technologies such as electron transpiration cooling (ETC) seek to take advantage of this plasma sheath in order to cool the vehicle.

A critical gap in literature is that a majority of classical plasma sheath theory is developed for fully ionized plasmas. Verifying whether classical theory can be applied to rarefied, weakly ionized plasmas in nonequilibrium flows is crucial for understanding plasma electrostatics in hypersonic flight conditions.

# Discrete-Velocity Methods
Study of rarefied gas flows necessitates the use of kinetic modeling methods, as continuum assumtions breakdown and traditional computational fluid dynamics (CFD) codes cannot be used. Particle-based methods, such as Direct Simulation Monte Carlo (DSMC) or Particle-in-Cell (PIC), have been successfully used to study this regime for decades. However, for certain problems, particle-based methods suffer from statistical noise, especially when attempting to resolve trace species, infrequent chemical reactions, or highly spatially varying flows. Reducing this statistical noise comes at increased computational expense. 

Discrete-velocity (also known as continuum-kinetic or grid-based kinetic) methods directly compute the time evolution of the probability density function of the flow according to the Boltzmann transport equation, allowing for deterministic simulation of flow properties. However, the cost of discretizing both configuration and velocity space for a probability density function can be highly computationally expensive as well. Usage of discrete-velocity methods is still relatively new and uncommon compared to their particle-based counterparts. Thus, research into discrete-velocity methods centers on reducing computational expense as well as determining which problems discrete-velocity methods are best suited for.
