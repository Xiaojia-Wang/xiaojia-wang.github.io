---
layout: page
title: ""
---

## Doctoral Research

Microscale fluid-structure interactions (FSIs) have aroused the attention of the scientific community because internal flows in compliant micro-conduits are 
often encountered in microfluidics. Although previous studies investigated the microscale FSIs from various perspectives, a unified understanding of the physics is 
lacking. My doctoral research aims to put forward a general theoretica framework for microscale flows in compliant micro-conduits. I have constructed a 
**reduced one-dimensional (1D) FSI model**, with which, I have analyzed the **steady responses**, the **nonlinear dyanmics** and the **stabilities** of various 
microscale FSI systems, providing new insights into the physics of FSIs at the microscale.    

### 1. Inertialess flow in compliant microchannel: nonlinear flow rate-pressure drop relation

![](/assets/research-fig1.png)Figure 1. (a) A typical rectangular microchannel with a deformable top wall. (b) The predicted deformed fluid-solid interface at the leading order. (c) The nonliear flow rate-pressure drop relation at steady state. The curves are from the predictive theory, while the dots are experimental data published by *Gervais et al (2006)*.

Due to FSI, the pressure drop required to maintain a steady flow varies nonlinearly with the flow rate, significantly deviating from the classic Poiseuille's law in rigid conduits. We have analyzed the FSI in a commonly used thick-walled microchannel (Figure 1a) in the regime of inertialess flow based on the perturbation method. We successfully derived a fitting-parameter-free theory to predict the nonlinear flow rate-pressure drop relation, which rationalizes the experiment done by MIT in 2006 (Figure 1c). Please refer to our [recent paper](https://doi.org/10.1098/rspa.2019.0513) for details.

### 2. Generalization: microscale FSI with finite fluid inertia

As many microfluidic devices are operated under higher flow rates, finite fluid inertia needs to be taken into account when investigating the microscale FSIs. We generalize our findings for inertialess microscale flows in compliant microchannels in two aspects, taking advantage of the fact that most of microchannels are made slender. First, we perform a scaling analysis to show that the lubrication approximation is applicable even with finite fluid inertia included. The key finding is that, due to the slenderness of the channel, the flow pressure varies along the streamwise direction only at the leading order. Second, the scaling analysis for the solid deformation shows that with linear elasticity, across a large range of wall thickness, the wall slenderness makes the deformations of cross-sections at different flowwise locations decouple from each other. The two findings motivates us to build a reduced system shown in Figure 2a. Please refer to our [recent paper](https://aip.scitation.org/doi/10.1063/5.0062252) for detailed discussions.

![](/assets/research-fig2.png)Figure 2. (a) The deformed steady state of the reduced FSI system. (b) An example of the time evolution of the fluid-solid interface shape from the undeformed intial state. In this case, the system is found to be linearly unstable. 

### 3. Towards dynamics: FSI-induced global instabilities

We further take the unsteadiness from the fluid and solid inertia into account. We reduce the FSI system consistenly from 3D to 1D, without introducing any fitting parameters. The new 1D FSI model is the reduced model considering the microscale FSI. The steady and unsteady behaviors of the model have a lot of similarities with previous experiments. Importantly, the model admits an inflated steady state as shown in Figure 1a, and we find that, there exist linear unstable global modes with respect to this steady state if the wall is compliant enough and the flow rate exceeds certain critical value. In the linearly unstable case, the system is undergoing self-sustained oscillation, with transverse waves propagating along the interface back and forth (figure 2b; also see an example [video here](https://youtu.be/E5_Nze4sW_Q)). Please check our [preprint]() for details. 

{% include embed.html url="https://youtu.be/E5_Nze4sW_Q" %}

## Past research

1. Steady-state scalings and the linear stability of a one-dimensional system with lubrication flows coupled with nonlinear Euler-Bernoulli Beam.
2. **Master's thesis:** Predicting ship motions in waves using the indirect time-domain method
   - Derived a new Kramers-Kronig relations for ships with forward constant speed
   - Wrote a solver with FORTRAN to predict ship motions in time domain by transforming the hydrodynamic coefficients from the frequency-domian simulations based on the boundary element method
   - Studied the parametric roll of ships by calculating the restoring forces on the instantaneous wet surfaces
   
