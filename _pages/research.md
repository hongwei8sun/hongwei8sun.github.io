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
Figure 1. Schematic framework of the Plume-in-Grid (PiG) model (a global Eulerian model with an embedded Lagrangian plume model). 
<br />

Stratospheric transport, dynamics, and aerosol processes.
------
To understand how the background circulation (e.g., BDC, QBO, tropopause folding) influences particle transport in the stratosphere, I use a ***Lagrangian trajectory model*** (driven by ERA5 data) to simulate particle transport in the stratosphere based on a stratospheric aerosol injection (SAI) strategy (All particles have initial locations at tropical lower stratosphere) under present-day conditions. Based on the simulating results, I: <br />
1. Quantify particles’ number, flux, lifetime, and tropospheric sinks in different stratospheric regions (i.e., tropical, mid-lat, polar regions), as shown in Figure 2. ([Sun et al., 2024](https://www.nature.com/articles/s41612-024-00664-8)). <br />
2. Evaluate particles’ tropospheric sinks that are co-located with tropopause folding mainly beneath the mid-lat jet stream. <br />
3. Explore the mechanisms of how QBO modulates the stratosphere-to-troposphere particle flux (ST-flux) crossing the tropopause, as shown in Figure 3. <br />
4. Find a zonal asymmetry of poleward transport for particles in the tropical lower stratosphere ([Sun et al., 2023](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2023GL105371)). <br />
<br />

<p align="left">
<img width="800" alt="image" src="https://github.com/hongwei8sun/hongwei8sun.github.io/assets/45275555/cab7f734-2ca9-4022-a6bd-4fb179fca3b9"> 
</p>
Figure 2. Particle number N (red values with the unit of particles), number flux F (blue values with a unit of particles
per year), and lifetime L (purple values with a unit of years) in or between different stratospheric regions (black boxes) during the steady-state stage. 
<br />
<br />

<p align="left">
<img width="800" alt="image" src="https://github.com/user-attachments/assets/232f56b0-a53c-41cb-a85f-6bc2335ab101"> 
</p>
Figure 3. Two mechanisms of how QBO influences stratosphere-to-troposphere flux (ST-flux). <br />


Aerosol-Cloud Interactions (ACI) in Marine Boudary Layer.
------

Because aerosol-cloud interactions are the most uncertain climate forcing in the Earth system, it is important to better understand the aerosol-cloud interactions, especially how they will change with climate. We carries out ***large eddy simulations (LES)*** of a 3-day stratocumulus-to-cumulus transition (SCT) along an airmass-following trajectory in the Northeast Pacific Ocean. By perturbing aerosol concentrations within the marine boundary layer (MBL) in the SCT simulations, we evaluate aerosol-cloud interactions in both the present day as well as in a double-CO2 climate (Figure 4).  <br />

<p align="left">
<img width="900" alt="image" src="https://github.com/user-attachments/assets/e3cede2e-4d06-46dd-9c7d-f590cac5178e">
</p>
Figure 4. Responses of stratocumulus clouds to different aerosol concentrations (clean vs. polluted) in the Northeast Pacific marine boundary layer in the present day (CTL) and in a warmer future (2xCO2, P2CO2). Aerosol-cloud interactions can be represented by the differences between clean vs. polluted cases. <br />
<br />

We find that aerosol-induced cloud changes, including first (Twomey effect) and second adjustments of cloud fraction and liquid water path (LWP) indirect effects of aerosols, tend to be inhibited in a double-CO2 climate (Figure 5). The LWP adjustment is more sensitive to global warming than the Twomey effect. By decomposing the aerosol-induced cloud radiative effect change (ΔCRE), we find that the aerosol-induced cloud fraction change (ΔCF) shows the largest contribution to ΔCRE in our simulations. Aerosol-induced droplet number concentration change (ΔNc) shows a cooling effect, while the LWP change shows a warming effect that is consistent with aerosol-induced cloud thinning. <br />

Overall, the cooling effect associated with increased aerosol concentrations will weaken in a double-CO2 climate. Our results can also help to understand and predict the cooling potential of marine cloud brightening (MCB) in a changing climate.  <br />

<p align="left">
<img width="900" alt="image" src="https://github.com/user-attachments/assets/e3b96af1-4733-4aab-83a2-3819d3724149" />
</p>
Figure 5. Aerosol-cloud interactions, including the first (Twomey effect) and second (LWP adjustment) indirect effects of aerosols. <br />


Climate engineering (geoengineering).
------

We design injection strategies by selecting combinations of injection latitudes and longitudes to increase particle lifetime subject to various constraints. For each altitude, we examine uniform injection in the tropics as a reference along with three other improved injection strategies. Instead of using fixed injection locations in the whole injection period, our three improved injection strategies (i.e., Latitude, Lat-lon, and Balanced) have injection locations that vary with season to maximize particle lifetime. The four injection strategies are: <br />
1. Uniform: particles are uniformly injected in the tropical area using all injection points (Nx × Ny). <br />
2. Latitude: particles are injected uniformly across all longitudes (Nx) at one selected latitude for each season to maximize particle lifetime. <br />
3. Lat-lon: particles are injected at a single point for each season to maximize particle lifetime. <br />
4. Balanced: particles are injected from one or several points each season, chosen to maximize particle lifetime subject to an interhemispheric balance constraint (i.e., the difference of particle lifetime between the NH and SH should be less than 1%). This is achieved by a Linear Programming (LP) solver described in ([Sun et al., 2023](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2023GL105371)).
<br />

<p align="left">
<img width="800" alt="image" src="https://github.com/hongwei8sun/hongwei8sun.github.io/assets/45275555/c3edf598-db13-4259-9845-254a35c7668e">
</p>
Figure 6. Mean stratospheric lifetime of particles injected at different injection altitudes for four different injection strategies. The table in the orange box shows three metrics that evaluate particle lifetime from the four injection strategies at 20 km. <br />



Others.
------
### Atmospheric aerosols and chemistry:
Implementing size-resolved stratospheric sulfate aerosol in a chemistry transport model to simulate Pinatubo volcano eruption (Sun and Eastham, in preparation). <br />

### Renewable energies & environment:
Using the ***WRF Model*** to simulate the climatic impacts of wind farms, which are parameterized as the momentum sink and turbulence source in the planetary boundary layer (PBL) scheme. ([Sun et al., 2018](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2017JD028028)). <br />

### Machine learning:
Using a ***convolutional neural network (U-Net)*** to separate cirrus clouds and aircraft contrails based on satellite images (Hu and Sun, in preparation). <br />


