---
layout: post
title:  "Revisited equilibrium solution of Fishbone and Moncrief torus for extended GRMHD simulations"
author: Lauren
categories: [ GRMHD]
image: 
featured: true
---
[Akhil Uniyal et al. 2024](https://arxiv.org/html/2406.16309v1)

This paper focuses on testing gravity theories by examining matter dynamics near compact objects using General Relativistic Magnetohydrodynamics (GRMHD) simulations. A GRMHD simulation is a computer model that scientists use to understand how high temperature, electrically charged gas behaves around extremely dense and heavy objects in space, like black holes and neutron stars. It combines the rules of how gravity works with the rules of how magnetic fields and fluids work together. Traditionally, high-resolution 3D GRMHD simulations in Kerr spacetime have been used to study magnetized accretion flows, using the Fishbone-Moncrief (FM) torus solution. In this paper, the authors present more general accretion torus solutions for stationary, axisymmetric, non-Kerr space images using the FM approach. This approach allows scientists to set up realistic initial conditions for the study of accretion disks around compact objects. It integrates the principles of neural relativist and hydrodynamics to create models that can be used in detailed GRMHD simulations, providing valuable insights into the behavior of matter in extreme gravitational fields. 

To test the stability of these solutions, 2D GRHD simulations were performed on FM tori in non-Kerr spacetimes. They used the JP parametrized metric (mathematical framework used to describe deviations from the standard Kerr metric, representing that spacetime around a rotating black hole in general relativity) to introduce non-Kerr deformations and observed that the torus remained stable over long-term evolution despite non-zero deformation parameters. The oscillation of maximum density and its power spectral density (PSD) were analyzed, showing that FM tori in non-Kerr space times behaved similarly to those in Kerr space times, indicating their stability and an applicability for GRMHD simulations. 

The paper emphasizes the need for a new simulation library for magnetized accretion flows in non-Kerr space times, which is crucial for testing gravity theories via black hole shadow images. Existing libraries are well-developed for Kerr spacetimes, but non-Kerr simulations are essential for comprehensive testing. The authors computed generic initial conditions for FM torus solutions applicable to any non-Kerr stationary, axisymmetric, asymptotically flat spacetime and plan to report further applications using MHD simulations soon. 

As a conclusion, the generalized FM torus solution would be very useful for creating new GRMHD libraries in extended Kerr black holes. 