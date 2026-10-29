---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Baryonic feedback is now one of the largest systematic uncertainties limiting cosmology on small scales. My research program addresses it by combining fast physical models, thousands of simulations, and multi-probe survey data (X-ray, microwave, and weak lensing), turning small-scale structure from a systematic into a cosmological probe in the era of eROSITA, XRISM, the Simons Observatory, and LSST. The approach has three steps: quantify astrophysical systematics with simulations, build fast forward models that predict multi-wavelength observables, and confront them with survey data using simulation-based inference and machine learning.

Research interests
======
* Computational, theoretical, and statistical modeling of galaxy clusters, groups, and massive galaxies, and their observational signatures in X-ray and microwave
* Galaxy clusters and groups as cosmological probes
* Physical processes in the intracluster medium: gas motions, turbulence, and non-thermal pressure
* Diffuse emission from the intergalactic and circumgalactic medium
* Astronomical software development

Current projects
======

**Baryon Pasting.** Baryon Pasting (BP) is a fast model I developed that adds realistic gas physics (cooling, star formation, supernova and AGN feedback) to dark-matter-only simulations. Applied to the 2.1 Gpc Uchuu simulation, it produced X-ray and Sunyaev–Zel'dovich (SZ) maps for 75 million halos ([Lau et al. 2025](https://arxiv.org/abs/2411.00108)). I have since made it differentiable, so that cosmology and feedback parameters can be fit directly to survey data. Through the Baryon Factory effort, I am applying BP to a range of simulations (Backlight, AGORA, PINOCCHIO, Mucho-Uchuu) and to the Local Volume Complete Cluster Survey (LoVoCCS).

**eROSITA: cosmology and feedback.** I led the first measurements of the X-ray angular power spectrum of groups and clusters in eFEDS and eRASS1 ([Lau et al. 2023](https://arxiv.org/abs/2204.13105), [2025](https://arxiv.org/abs/2410.22397)), obtaining S<sub>8</sub> = 0.80<sup>+0.02</sup><sub>−0.01</sub>, consistent with the early Universe. In the CAMELS circumgalactic-medium project, comparing eROSITA data with thousands of simulations showed that existing feedback models over- or under-predict the hot gas around galaxies ([Lau et al. 2025](https://arxiv.org/abs/2412.04559)). As a member of the FornaX Collaboration, I use the Euclid Flagship simulations to model how baryonic physics shapes the selection and scaling-relation scatter of groups and clusters in the FornaX X-ray survey.

**XRISM: gas motions and non-thermal pressure.** Building on my interpretation of the Hitomi observations of the Perseus cluster ([Lau et al. 2017](https://arxiv.org/abs/1705.06280)), I confront XRISM/Resolve data with cluster simulations passed through the same analysis chain as the data, including a study of non-thermal pressure with TNG-Cluster ([Lau, Ota & Nagai 2026](https://arxiv.org/abs/2608.04757)) and an analysis of sloshing-driven gas motions in Abell 2029 ([Uchida et al. 2026](https://arxiv.org/abs/2608.14415)). I lead the simulation and theory component of a XRISM Key Project proposal led by Prof. Naomi Ota.

**Does baryonic feedback explain the S<sub>8</sub> tension?** The clumpiness of matter predicted from the cosmic microwave background is higher than what late-time measurements such as weak lensing find. Feedback from stars and black holes smooths the matter distribution on small scales and could explain part of this gap. I am combining Baryon Pasting with simulation-based inference and applying it to eROSITA X-ray data for more than ten thousand optically selected groups and clusters, to measure how much feedback the data allow and whether it is enough to reconcile early- and late-time S<sub>8</sub>.

Earlier work
======
At Chicago and Yale, I showed that residual gas motions bias hydrostatic cluster masses through non-thermal pressure ([Lau et al. 2009](https://arxiv.org/abs/0903.4895), [2013](https://arxiv.org/abs/1306.3993); [Nelson et al. 2014](https://arxiv.org/abs/1308.6589)), predicted merger-induced gas motions ([Nagai et al. 2013](https://arxiv.org/abs/1307.2251)), and characterized cluster shapes ([Lau et al. 2011](https://arxiv.org/abs/1003.2270), [2012](https://arxiv.org/abs/1201.2168), [2021](https://arxiv.org/abs/2006.09420)) and gas clumping and accretion in cluster outskirts ([Nagai & Lau 2011](https://arxiv.org/abs/1103.0280); [Lau et al. 2015](https://arxiv.org/abs/1411.5361); [Aung, Nagai & Lau 2021](https://arxiv.org/abs/2012.00977)).
