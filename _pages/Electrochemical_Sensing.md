---
layout: single
author_profile: true
toc: true
toc_label: "Electrochemical Sensing"
permalink: /Research/Electrochemical_Sensing
---

<style>

.grid-container {
  display: grid;
  grid-template-columns: 90% 10%;
  background-color: #ffffff;
  padding: 0px;
}
.grid-item {
  background-color: #ffffff;
  border: 0px solid #ffffff;
  padding: 0px;
  text-align: left;
}

</style>

# Overview

The field of electrochemical sensing is incredibly broad, and has been applied to almost every conceivable sensing target from metal contamination in wastewater to neurotransmitters in the brain. The core concept is to have a known electrochemical reaction at at electrode surface. The current measured will then be proportional to the concentration of that species in solution. 

Different species require different amounts of energy to react at our electrode, so we can control this by applying a specific voltage to our electrode sensor. This is particularly powerful for metal detection, as dissolved metals have very well defined voltage windows where they are electrochemically active. We can also make chanegs to the electrode itself to change the type of information that we record. Very small electrodes can be inserted into samples so we can not only find out how much is there, but also where it is coming from (read more about this [here](/Research/Scanning_Electrochemical_Microscopy)). 

# The problem

In a model system with one single species in a beaker in the lap this works pretty much every time, but things get more complicated when we move to real environments where we might want to apply our sensors. Most real environments, especially in cells and other biological systems, contain huge numbers of different species that react at our electrode, making it impossible to determine how much of our target is there amongst that massive background signal. In other cases, the species we want to detect just doesn't react at the electrode at all, so we need to find other ways to use our electrode to detect it.

# Our research

We are particularly intrested in the detection of species that do not directly react at the electrode surface. Instead, we attach an enzyme to the electrode. The enzyme breaks down the species that we want to detect, and in doing so creates a second species (hydrogen peroxide) that we can detect electrochemically. This new enzyme-electrode combination forms a new biosensor, where the amount of hydrogen peroxide that we detect defines how much of target was detected by the enzyme. 

<img align="center" width="70%" src="/images/Sensing/Fig 3.png">
<figcaption>Figure 3. Diagram of the fully fabricated biosensor. Inset focuses on the tip of the biosensor, showing the enzyme layer (orange), size exclusion polymer layer (blue) and platinum surface of the microelectrode (grey). This particular biosensor uses ᴅ-amino acid oxidase (DAAO) to break down ᴅ-serine, which produces hydrogen peroxide (H<sub>2</sub>O<sub>2</sub> that is detected at the electrode.</figcaption>

The next challenge is to make sure that our current signal is only being produced by our target species, rather than the many other possible sources in our environment. There are a number of different paths we can take here. One option is to add a "size-exclusion layer". This works like a seive at the electrode surface, so small species can pass through to be detected, but larger species are kept away. This works well for our biosensor, as hydrogen peroxide is a small enough molecule to pass through. Unfortunately, some of the peroxide will be blocked, and so the size-exclusion layer does reduce our signal somewhat. A second line of research therefore looks at ways to change the electrode surface to boost the current signal. This allows us to get all the benefits of that size-exclusion layer without losing too much signal. 

If you're interested in a more detailed overview of this research area you can check it out [here](/Research/Electrochemical_Sensing_full). You can also find a section specifically about localised detection using electrochemical sensors [here](/Research/Scanning_Electrochemical_Microscopy).

You can also see some of the individual projects from this area that we have recently published in the areas of [increasing biosensor sensitivity]({% post_url 2018-07-27-biosensor-paper %}) and [using biosensors with scanning electrochemical microscopy]({% post_url 2017-01-30-Biosensor-paper %}).


Recommended Resources
==========================

- S. Perry, <i>Transient Studies at Microelectrodes</i>, thesis submitted to University of Southampton. <a href="https://eprints.soton.ac.uk/387227/" target="_blank" >Direct Link</a>
- A. F. P. Turner; Biosensors: Sense and Sensibility; <i>Chem. Soc. Rev.</i>, <b>42</b>, 3184-3196, (<b>2013</b>). <a href="https://doi.org/10.1039/C3CS35528D" target="_blank" >Direct Link</a>
- S. C. Perry, S. M. Gateman, J. Sifakis, L. Pollegioni, J. Mauzeroll; Enhancement of the Enzymatic Biosensor Response through Targeted Surface Roughness <i>J. Electrochem. Soc.</i>, <b>165</b>, G3074-G3079, (<b>2018</b>). <a href="https://doi.org/10.1149/2.0121812jes" target="_blank" >Direct Link</a>
- A. Bard and L. Faulkner, <i>Electrochemical Methods: Fundamentals and Applications</i>, John Wiley & Sons, NY. <a href="https://www.wiley.com/en-us/Electrochemical+Methods%3A+Fundamentals+and+Applications%2C+2nd+Edition-p-9780471043720" target="_blank" >Direct Link</a>
- D. Pletcher, <i>A First Course in Electrode Processes</i>, Royal Society of Chemistry, Cambridge. <a href="https://pubs.rsc.org/en/content/ebook/978-1-84755-893-0" target="_blank" >Direct Link</a>