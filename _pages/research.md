---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

I am focusing on developing and applying different types of numerical models to study multiscale atmospheric processes and climate science. My main research interests include:  <br />

1. Large-scale stratospheric transport, dynamics, and aerosol processes.  <br />
2. Small-scale aerosol–cloud interactions within the marine boundary layer.  <br />
3. The application of (1) and (2) to climate intervention (geoengineering).  <br />

Developing a coupled multiscale model.
------
I created a Lagrangian plume model and coupled the new ***Lagrangian plume model*** into a ***global model*** to build a ***multiscale plume-in-grid (PiG) model*** ([Sun et al., 2022](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2021MS002816)). This coupled PiG model is able to resolve subgrid plumes (e.g., aircraft plumes), which cannot be resolved by conventional global models. <br />

<p align="left">
<img width="1433" alt="image" src="https://github.com/user-attachments/assets/83d32009-3c96-40b6-85a6-2f40540722c7" />
</p>
Figure 1. Schematic framework of the Plume-in-Grid (PiG) model (a global Eulerian model with an embedded Lagrangian plume model).  <br />
<br />


Stratospheric transport, dynamics, and aerosol processes.
------
To understand how the background circulation (e.g., BDC, QBO, tropopause folding) influences particle transport in the stratosphere, I use a ***Lagrangian trajectory model*** (driven by ERA5 data) to simulate particle transport in the stratosphere based on a stratospheric aerosol injection (SAI) strategy (All particles have initial locations at tropical lower stratosphere) under present-day conditions. Based on the simulating results, I: <br />
(1) Quantify particles’ number, flux, lifetime, and tropospheric sinks in different stratospheric regions (i.e., tropical, mid-lat, polar regions), as shown in Figure 2. ([Sun et al., 2024](https://www.nature.com/articles/s41612-024-00664-8)). <br />
(2) Evaluate particles’ tropospheric sinks that are co-located with tropopause folding mainly beneath the mid-lat jet stream. <br />
(3) Explore the mechanisms of how QBO modulates the stratosphere-to-troposphere particle flux (ST-flux) crossing the tropopause, as shown in Figure 3. <br />
(4) Find a zonal asymmetry of poleward transport for particles in the tropical lower stratosphere ([Sun et al., 2023](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2023GL105371)). <br />
<br />

<p align="left">
<img width="800" alt="image" src="https://github.com/hongwei8sun/hongwei8sun.github.io/assets/45275555/cab7f734-2ca9-4022-a6bd-4fb179fca3b9"> 
</p>
Figure 2. Particle number N (red values with the unit of particles), number flux F (blue values with a unit of particles
per year), and lifetime L (purple values with a unit of years) in or between different stratospheric regions (black boxes) during the steady-state stage. <br />
<br />

<p align="left">
<img width="800" alt="image" src="https://github.com/user-attachments/assets/232f56b0-a53c-41cb-a85f-6bc2335ab101"> 
</p>
Figure 3. Two mechanisms of how QBO influences stratosphere-to-troposphere flux (ST-flux). <br />


Aerosol-cloud interactions (ACI) in ***large eddy simulations (LES)***.
------
<p align="left">
<img width="900" alt="image" src="https://github.com/user-attachments/assets/e3cede2e-4d06-46dd-9c7d-f590cac5178e">
</p>
Figure 4. Responses of stratocumulus clouds to different aerosol concentrations (clean vs. polluted) in the Northeast Pacific marine boundary layer in the present day (CTL) and in a warmer future (2xCO2, P2CO2). Aerosol-cloud interactions can be represented by the differences between clean vs. polluted cases. <br />


Climate engineering (geoengineering).
------
<p align="left">
<img width="800" alt="image" src="https://github.com/hongwei8sun/hongwei8sun.github.io/assets/45275555/c3edf598-db13-4259-9845-254a35c7668e">
</p>
Figure 5. Mean stratospheric lifetime of particles injected at different injection altitudes for four different injection strategies. The table in the orange box shows three metrics that evaluate particle lifetime from the four injection strategies at 20 km. <br />



Others.
------
### Atmospheric aerosols and chemistry:
Implementing size-resolved stratospheric sulfate aerosol in a chemistry transport model to simulate Pinatubo volcano eruption (Sun and Eastham, in preparation). <br />

### Renewable energies & environment:
Using the ***WRF Model*** to simulate the climatic impacts of wind farms, which are parameterized as the momentum sink and turbulence source in the planetary boundary layer (PBL) scheme. ([Sun et al., 2018](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2017JD028028)). <br />

### Machine learning:
Using a ***convolutional neural network (U-Net)*** to separate cirrus clouds and aircraft contrails based on satellite images (Hu and Sun, in preparation). <br />


