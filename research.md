---
layout: page
title: ""
---

## Doctoral Research

Microscale fluid-structure interactions (FSIs) have aroused the attention of the scientific community because internal flows in compliant micro-conduits are 
often encountered in microfluidics. Although previous studies investigated the microscale FSIs from various perspectives, a unified understanding of the physics is lacking. My doctoral research aims to put forward a general theoretica framework for microscale flows in compliant micro-conduits. I have constructed a 
**reduced one-dimensional (1D) FSI model**, with which, I have analyzed the **steady responses**, the **nonlinear dyanmics** and the **stabilities** of various 
microscale FSI systems, providing new insights into the physics of FSIs at the microscale.    

### 1. Inertialess flow in compliant microchannel: nonlinear flow rate-pressure drop relation

![](/assets/research-fig1.png)Figure 1. (a) A typical rectangular microchannel with a deformable top wall. (b) The predicted deformed fluid-solid interface at the leading order. (c) The nonliear flow rate-pressure drop relation at steady state. The curves are from the predictive theory, while the dots are experimental data published by *Gervais et al (2006)*.

Due to FSI, the pressure drop required to maintain a steady flow varies nonlinearly with the flow rate, significantly deviating from the classic Poiseuille's law in rigid conduits. We have analyzed the FSI in a commonly used thick-walled microchannel (Figure 1a) in the regime of inertialess flow based on the perturbation method. We successfully derived a [first fitting-parameter-free theory](https://doi.org/10.1098/rspa.2019.0513) to predict the nonlinear flow rate-pressure drop relation, which rationalizes the experimental measurements performed MIT in 2006 (Figure 1c). 

### 2. Generalization: microscale FSI with finite fluid inertia

As many microfluidic devices are operated under higher flow rates, finite fluid inertia needs to be taken into account when investigating the microscale FSIs. We would like to develop [a generalized theory(](https://aip.scitation.org/doi/10.1063/5.0062252) which accounts for finite fluid inertia and applies to microchannel systems with different geometrical properties. Noting that most of microchannels are made slender, we first extend the classic **lubrication approximation** for the flows by incluidng finite fluid inertia through a scaling analysis. Then, we show that, with linear elasticity, across a large range of wall thickness, the wall slenderness makes the wall deform like a **Winkler foundation**. The two findings motivates us to build a reduced system shown in Figure 2a. 

![](/assets/research-fig2.png)Figure 2. (a) The deformed steady state of the reduced FSI system. (b) An example of the time evolution of the fluid-solid interface shape from the undeformed intial state. In this case, the system is found to be linearly unstable. 

### 3. Towards dynamics: FSI-induced global instabilities

We further take the unsteadiness from the fluid and solid inertia into account. We reduce the FSI system consistenly from 3D to 1D, without introducing any fitting parameters. The [new 1D FSI model]() is the first reduced model considering the microscale FSI. The steady and unsteady behaviors of the model agree quanlitatively well with previous experimental observations. Importantly, **global unstable modes** can be induced by FSI in the 1D system. This observation bolsters the idea of **enhancing microcale mixing by leveraging FSIs**. The time evolution of the fluid-solid interface in the globally unstable case is shown in figure 2b. Also see an example [video here](https://youtu.be/E5_Nze4sW_Q)). 

{% include embed.html url="https://youtu.be/E5_Nze4sW_Q" %}

## Ongoing research
1. Analyze the nonlinear dynamics of the [new 1D FSI model]() through Galerkin truncation
2. Investigate the FSIs in a compliant tube with prescribed oscillatory pressure drop with reduced modeling and direct numerical simulations via [SvFSI of SimVascular](https://simvascular.github.io/docssvFSI.html).

## Past research

1. Steady-state scalings and the linear stability of a one-dimensional system with lubrication flows coupled with nonlinear Euler-Bernoulli Beam.
2. **Master's thesis:** Predicting ship motions in waves using the indirect time-domain method
   - Derived a new Kramers-Kronig relations for ships with forward constant speed
   - Wrote a solver with FORTRAN to predict ship motions in time domain by transforming the hydrodynamic coefficients from the frequency-domian simulations based on the boundary element method
   - Studied the parametric roll of ships by calculating the restoring forces on the instantaneous wet surfaces
   
