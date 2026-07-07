---
title: "Research"
layout: single
sitemap: true
permalink: /research/
author_profile: true
toc: true
toc_label: "Research"
toc_icon: "gear"
toc_sticky: true
---

My research lies at the development of bio-based materials, their production and applications in high value added applications. I have involved in following research projects include:
- Inpactus
- From Fossil to Forest 
- Ligold

## Novel Synthesis of Starch Betainate by Transesterification

I develop a novel two-step synthesis of starch betainate (SB) using transesterification as a more sustainable and high-purity alternative to conventional etherification methods. I successfully converted starch into cationic esters by reacting it with methyl betainate in both aprotic solvents (DMF and DMSO) and via solid-state ball milling under various pH conditions. While the solution-based method in DMF achieved a higher degree of substitution (up to 0.4), the solvent-free ball milling approach was notably efficient, reaching a degree of substitution of 0.04 within just two hours while minimizing polymer degradation. Ultimately, the study concludes that these transesterification routes produce biodegradable, non-toxic cationic starches with high purity and no undesired coloring, offering a promising alternative for industrial applications such as papermaking and wastewater treatment. This methodology was published  [(Article)](https://www.sciencedirect.com/science/article/pii/S0141813021011569) in the International Journal of Biological Macromolecules and protected through [national and international patent filings](https://patentscope.wipo.int/search/en/WO2022168011). 

<figure>
  <img src="/assets/images/Fig.2. HNMR_MeBetCl_SB.jpg">
  <figcaption>1H NMR spectra of: a) MeBetCl (DMSO‑d6); b) starch (D2O); c) starch betainate obtained in alkaline medium, Experiment 2 in Table 1 (D2O). HDO signal has been cut.
</figcaption>
</figure>

* **Skills learning:** Starch chemistry, Organic synthesis, NMR, FTIR, TGA, Elemantal analysis
* **Online learning:** ML models are trained dynamically during the simulation itself, requiring the ocean model to be differentiable.


## Synergetic Enhancement of Paper Printability and Whiteness

I studied synergetic effect between highly substituted cationic starches and Pluronic triblock copolymers that significantly enhances the inkjet printing quality of office papers. While individual components like starch betainate or Pluronic P123 only moderately increased the gamut area (by 8.9% and 6.8%, respectively), their combined application in paper coatings resulted in a 16–18% improvement. A key discovery is that starch betainate (a cationic ester) serves as a superior alternative to traditional cationic ethers because it quenches optical brightening agents (OBA) to a much lesser extent, thereby preserving paper whiteness while simultaneously improving ink density and gamut volume. Ultimately, the binary interaction between these components facilitates better ink fixation and binder penetration, offering a more effective and biodegradable route for high-quality paper coatings. This study was published in the Cellulose Journal of [Article](https://link.springer.com/article/10.1007/s10570-021-04206-w).

<figure>
  <img src="/assets/images/GA1.png" width="1000px" alt="">
  <figcaption>A hybrid climate model combines a traditional dynamical core with machine-learned parameterizations.
</figcaption>
</figure>




* **Offline learning:** ML models are trained on outputs from high-resolution simulations or observational datasets before being incorporated into the ocean model.
* **Online learning:** ML models are trained dynamically during the simulation itself, requiring the ocean model to be differentiable.

During my work with the [M2LInES Team](https://m2lines.github.io/), I focused on offline approaches to hybrid modeling. I began by diagnosing eddy fluxes from high-resolution MOM6 simulations using filtering and coarse-graining techniques. I then trained ML models on these offline datasets using PyTorch. To evaluate the model’s performance in an online setting, I integrated it into the MOM6 code base. 
However, offline-learned parameterizations often encounter numerical instability when coupled with the full model, highlighting the potential advantages of online approaches.

As part of the [DJ4Earth project](https://dj4earth.github.io/), I supervise students applying online learning techniques to improve ocean eddy parameterizations. In this approach, the machine-learned parameterization is trained alongside the simulation, requiring a differentiable ocean model with an adjoint. We implement this method using the ocean model Oceananigans, and train the ML models in Julia.

Related publications: [Balwada, ..., Loose et al.](https://doi.org/10.21105/jose.00241), JOSE (2024);
[Yu, ..., Loose et al.](https://proceedings.neurips.cc/paper_files/paper/2023/hash/45fbcc01349292f5e059a0b8b02c8c3f-Abstract-Datasets_and_Benchmarks.html), NeurIPS (2023)

## Ocean Mesoscale Eddies and their Parameterizations

Further, I also explored nanocellulose‑based coating formulations to enhance paper printing and barrier properties. Nanocellulose samples were produced using mechanical refining, enzymatic pretreatment, TEMPO‑oxidation, and sodium‑periodate oxidation followed by cationization with Girard’s reagent. Combined with starch betainate, betaine hydrochloride, and Pluronics, these systems significantly improved paper surface properties and printability. The work resulted in a publication in Nanomaterials [Article](https://www.mdpi.com/2079-4991/12/16/2853), [national and international patent filings] (https://patentscope.wipo.int/search/en/WO2024023648), and ongoing pilot/industrial trials with partner company.

<figure>
  <img src="/assets/images/KE.png" width="1000px" alt="">
  <figcaption>Left: The kinetic energy field in NeverWorld2: a high-resolution idealized model that I used for studying the ocean energy cycle.
Right: A schematic of the ocean energy cycle.
</figcaption>
</figure>

Ocean mesoscale eddies are energetic motions that have horizontal scales of tens to hundreds of kilometers.
Despite their relatively small scale, these eddies play an important role in transporting momentum, heat, salt, carbon, and nutrients throughout the world's oceans.

My research focused on the energy cycle of the ocean mesoscale eddy field: its generation, its interaction with the large-scale flow, and its dissipation. 
To investigate this cycle, I used high-resolution ocean models, aiming to improve the representation of mesoscale processes in global ocean models.

Additionally, I studied, implemented, and compared different mesoscale eddy parameterizations—specifically, Gent & Williams (1990) and Greatbatch & Lamb (1990)—from both theoretical and numerical modeling perspectives. 
My research explored how these parameterizations interact with the ocean model's vertical coordinate system, providing insights into the consistency between theoretical frameworks and numerical implementations.

Related publications: [Loose et al.](https://doi.org/10.1175/JPO-D-22-0083.1), JPO (2022);
[Loose et al.](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2022MS003518), JAMES (2023);
[Marques, Loose et al.](https://gmd.copernicus.org/articles/15/6567/2022/), GMD (2022). 

## Adjoint Modeling in the North Atlantic

<figure>
  <img src="/assets/images/sensitivity_teleconnections.png" alt="">
  <figcaption> 
Left: Near-surface currents that are the mediator of oceanic teleconnections in the North Atlantic.
Right: An adjoint-derived sensitivity map that highglights ''sensitive spots'' where wind anomalies can trigger heat transport anomalies across the Iceland-Scotland ridge (yellow-black line) months or years later.  
</figcaption>
</figure>

The seas around Greenland, Iceland, and Norway transport heat from the North Atlantic toward the Arctic.
I used adjoint-derived sensitivities in the [ECCO](https://ecco-group.org/) state estimate to identify drivers and locations that affect ocean heat transport in this region. Due to oceanic teleconnections, high-latitude heat transport is sensitive to local and remote(!) wind forcing.

Related publications:
[StoryMap](https://www.ecco-group.org/storymaps.htm?id=43);
 [Loose et al.](https://doi.org/10.1029/2020JC016112), J. Geophys. Res (2020);
Loose, [PhD Dissertation](http://bora.uib.no/handle/1956/24456), 2019.


## Uncertainty Quantification & Observing System Design

<figure>
  <img src="/assets/images/QND.png" alt="">
  <figcaption> 
The Global Ocean Observing System (GOOS) consists of an eclectic mix of satellite and in-situ platforms. Designing optimal observing strategies that account for complementarity and redundancy of observational assets is an unsolved scientific and computational challenge.
</figcaption>
</figure>

Ocean observing systems are expensive to build and maintain, and therefore have to be designed carefully. Important questions to consider include:
- What dynamical information is contained in already existing observation networks? 
- What is the optimal instrument configuration, which is both cost-efficient and capable to monitor key processes and ocean variability?

To tackle these questions, I performed quantitative observing system design, through a combination of Bayesian inverse methods and uncertainty quantification in a data assimilation framework. By means of these computational tools, quantitative observing system design suggests an optimal observing strategy and supports effective instrument placements in the future.

Related publications: [Loose et al.](https://doi.org/10.1029/2020JC016112), J. Geophys. Res (2020); 
[Loose and Heimbach](https://doi.org/10.1029/2020MS002386), JAMES (2021);
[Fujii et al.](https://www.frontiersin.org/articles/10.3389/fmars.2019.00417/full), Front. Mar. Sci. (2019).
[v. Schuckman et al.](https://doi.org/10.1016/j.marpol.2025.106922), Marine Policy (2025).

## Development of Open Source Software Tools

I am engaged with developing open-source software tools in Python and Julia to enable our Earth Science community to perform data analysis and modeling in an efficient and reproducible way. 
I have led the development of two open-source Python packages: [GCM-Filters](https://gcm-filters.readthedocs.io/en/latest/) and [ROMS-Tools](https://roms-tools.readthedocs.io/en/latest/).

<figure>
  <img src="/assets/images/roms_grid.png" alt="">
  <figcaption> 
A ROMS grid created with the open-source Python package ROMS-Tools.
</figcaption>
</figure>
`ROMS-Tools` is a Python package for creating the input files that are necessary to run a ROMS simulation. This includes creating a grid, tidal, boundary, and atmospheric forcings, initial conditions, and more! 

<figure>
  <img src="/assets/images/filter_intro.png" alt="">
  <figcaption> 
Filtering surface relative vorticity from a global 0.1 degree MOM6 simulation with the open-source Python package GCM-Filters.
</figcaption>
</figure>
`GCM-Filters` is a Python package that allows scientists to perform spatial filtering analysis in an easy, flexible, efficient, and reproducible way. `GCM-Filters` is designed to work with gridded data that is produced by General Circulation Models (GCMs) of ocean, weather, and climate. 
Check out [this presentation](https://noraloose.github.io/ams2022-talk) on GCM-Filters!

Related publications: [Loose et al.](https://doi.org/10.21105/joss.03947), JOSS (2022); 
[Grooms, Loose et al.](https://doi.org/10.1029/2021MS002552), JAMES (2021).

