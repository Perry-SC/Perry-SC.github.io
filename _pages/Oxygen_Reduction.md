---
layout: single
author_profile: true
toc: true
toc_label: "Oxygen Reduction"
permalink: /Research/Oxygen_Reduction
---

<style>

.grid-container {
  display: grid;
  grid-template-columns: 60% 30% 10%;
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

The oxygen reduction reaction is an electrochemical mechanism that involves the conversion of oxygen to water. The mechanism is incredibly complex, involving oxygen binding to the electrode surface and four electron transfer steps via a number of surface-bound intermediates. Often, the mechanism is approximated as a two-step procedure: oxygen is first reduced to hydrogen peroxide (H<sub>2</sub>O<sub>2</sub>) as an intermediate, which is the further reduced to water.

<img align="center" src="/images/ORR/Fig 1.png">
<figcaption>Figure 1: Schematic diagram for the two and four electron oxygen reduction pathways, depicting the mass transport of O<sub>2</sub> from bulk solution to be adsorbed on the electrode surface (<i>k</i><sub>m</sub>), then four electron reduction to water (<i>k</i><sub>1</sub>). Alternatively, two electron reduction to H<sub>2</sub>O<sub>2</sub> (<i>k</i><sub>2</sub>), followed by further two electron reduction to water (<i>k</i><sub>3</sub>), diffusion in to the bulk (<i>k</i><sub>m</sub>), or decomposition to O<sub>2</sub> and H<sub>2</sub>O (<i>k</i><sub>4</sub>).</figcaption>

# The problem

The interest in oxygen reduction chemistry comes from the fuel cell community. A number of promising designs use oxygen reduction as part of the power providing reactions. In order to be efficient it is vital that the oxygen reduction reaction is efficient as possible, i.e. we want oxygen to be fully reduced to water, not partially reduced to hydrogen peroxide. Unfortauntely, every material studied currently produces at least a little hydrogen peroxide as part of its operation. A sizeable part of modern research efforts is therefore dedicated to trying to make oxygen reduction more efficient. 

# Our research

Oxygen reduction is strongly surface dependent. The idea material needs to have a strong enough bond with oxygen so that it is held there until it is fully reduced, but not so strong that by-products of the reaction are not released by the electrode, preveting further reactions taking place. 

<img align="center" width="80%" src="/images/ORR/Fig 5.png">
<figcaption>Figure 2: Volcano plot showing the catalytic activity for oxygen reduction (ORR) for various metals against the bond stength between oxygen and that metal (&Delta;<i>E</i><sub>O</sub>). Metals closer to the top of the peak have the ideal intermediate bond strength, and so are better oxygen reduction catalysts. No metal is currently at the peak, so we still have room for improvement.</figcaption>

Our work has looked at new ways to calculate how strongly oxygen binds to different materials, providing a quick and simple way to estimate if a material will be suitable as an oxygen reduction catalyst. We do this by measuring how much oxygen binds to the surface of the electrode when no reaction is taking place. This has a direct relationship to catlayst activity, which is much easier to produce that the high end computational calculations that currently have to be performed. 

Another area of research goes in a very different direction by instead focussing on hydrogen peroxide. Peroxide is a valuable chemical, wish a number of household and industrial uses. If we can design a catalyst that release the peroxide before it is reduced to water, we can produce a cheap and safe means of producing useful amounts of peroxide. The reactions shown in Figure 1 are also reversible, meaning that is it possible to convert both water and oxgen to peroxide. We are therefore designing a reactor capable of performing both of these reactions at the same time, allowing us to produce twice as much peroxie for the same energy input. 

If you're interested in a more detailed overview of this research area you can check it out [here](/Research/Oxygen_Reduction_full).

You can also see some of the individual projects from this area that we have recently published in the areas of [detecting oxygen binding]({% post_url 2015-10-19-ORR-paper %}), [calculate catalyst activity]({% post_url 2016-03-21-ORR-paper %}) and [producing hydrogen peroxide from water and oxygen]({% post_url 2019-06-19-h2o2-review %}).

# Recommended Resources

- S. Perry, <i>Transient Studies at Microelectrodes</i>, thesis submitted to University of Southampton. <a href="https://eprints.soton.ac.uk/387227/" target="_blank" >Direct Link</a>
- S. C. Perry, D. Pangotra, L. Vieira, V. Sieber, L. Wang, C. Ponce de Leon, F. Walsh; <i>Nature Reviews Chemistry</i>, <b>3</b>, 442-458, (<b>2019</b>). <a href="https://www.nature.com/articles/s41570-019-0110-6" target="_blank" >Direct Link</a>
- N. M. Markovic, T. J. Schmidt, V. Stamenkovic, P. N. Ross; Oxygen Reduction Reaction on Pt and Pt Bimetallic Surfaces: A Selective Review; <i>Fuel Cells</i>, <b>1</b>, 105-116, (<b>2012</b>). <a href="https://doi.org/10.1002/1615-6854" target="_blank" >Direct Link</a>
- A. Bard and L. Faulkner, <i>Electrochemical Methods: Fundamentals and Applications</i>, John Wiley & Sons, NY. <a href="https://www.wiley.com/en-us/Electrochemical+Methods%3A+Fundamentals+and+Applications%2C+2nd+Edition-p-9780471043720" target="_blank" >Direct Link</a>
- D. Pletcher, <i>A First Course in Electrode Processes</i>, Royal Society of Chemistry, Cambridge. <a href="https://pubs.rsc.org/en/content/ebook/978-1-84755-893-0" target="_blank" >Direct Link</a>


