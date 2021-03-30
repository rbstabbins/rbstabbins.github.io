---
layout: page
title: Research
permalink: /research/
---
Here is a brief introduction to some of the research I am currently and have previously been involved with.
It is my ambition to write some short blog posts that elaborate on the themes introduced here.

### Spectral Imaging Simulations for Planetary Surface Exploration
---

In preparation for the landing of Rosalind Franklin at Oxia Planum in the summer of 2023, I've been developing software to simulate the imaging chain of PanCam. Given a description of an environment, in terms of topography and material distribution, and skylight illumination conditions, the software answers the question of what will PanCam see?

This involves two sub-questions: 

1. How is the light incident on PanCam translated into a digital image, noise and all? and
2. How do the environmental features of the Martian landscape translate the Sun light incident on the top of the atmosphere into the light field that an imaging system can sample?

Addressing the first question has involved building a software simulator for a generic camera system, that relaxes the usual assumptions of detector linearity, field angle independence, and an interest in RGB response only, that are invalid for PanCam. The software translates the available component level information of a camera system into approximations of continuous functions, that map from the directional spectral radiance field incident at the camera pupil to the irradiance at the imaging plane, its spectral attentuation according to each of the 22 multispectral filters of the PanCam Wide-Angle Cameras, and the Bayer Pattern of the High-Resolution Camera.

Addressing the second question has essentially involved extending the well developed methods of computer graphics from the 3-vector processing of trichromacy, to hyperspectral n-vectors, depending on the resolution required. Typically the rountines I run operate in the VNIR domain, from ∼ 380nm to 1100nm, in 1nm intervals.

This research has been published in my doctoral thesis, available soon.

### Geochemistry to Geology for ExoMars 2022: Visible to Near-Infrared Spectral Variability
---

My work with the Planetary Surfaces group at the Natural History Museum has the broad objective of preparing for exploitation of the multispectral sampling that the PanCam Wide Angle Cameras afford, by incorporating the prior knowledge of the landing site mineralogy, obtained from orbit, into the analysis process.

The initial phase of the project has focussed on the identification of the mineral hematite.
Obvs. put much more detail in here also.

**Spectral Imaging Analysis Software**

A brief description of my work for ExoSpec


