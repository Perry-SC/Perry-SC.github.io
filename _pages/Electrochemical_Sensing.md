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

Background
============

<p align="justify">
Electrochemical sensors a widely used throughout numerous areas of industrial and medical fields. At their simplest, they rely on the relationship between the measured current at an electrode and the concentration of species in solution. The exact relationship between these is dependent on the nature of the experiment and the geometry of the electrode being used, but the basic principle remains the same. At a large electrode, if a sufficiently large overpotential is applied, the relationship between the current and the concentration is given by the Cottrell equation.<sup>1</sup><br>
</p>

<div class="grid-container">
  <div class="grid-item">
	<div class="container">
	  <img align="center" width="30%" src="/images/Sensing/Eq_Cottrell.png">
	</div>
  </div>
  <div class="grid-item">
	<div class="container">
	  (1)
	</div>
  </div>
</div>

<p align="justify">
<br>
where <i>i</i> is the current at the electrode, <i>n</i> is the number of electrons transferred, <i>F</i> is Faraday's constant, <i>A</i> is the electroactive area, <i>D</i> is the diffusion coefficient, <i>c</i><sup>&#8734;</sup> is the bulk concentration, and <i>t</i> is the time after the initiation of the potential step. As the electrode becomes smaller (diameter of a microelectrode < 25 &mu;m) the relationship changes, and the current is instead given by a more complex equation.<sup>2</sup><br>
</p>

<div class="grid-container">
  <div class="grid-item">
	<div class="container">
	  <img align="center" width="45%" src="/images/Sensing/Eq_Microelectrode.png">
	</div>
  </div>
  <div class="grid-item">
	<div class="container">
	  (2)
	</div>
  </div>
</div>

<p align="justify">
<br>
where <i>a</i> is the radius of the microelectrode and all other parameters are the same as for Equation 1. This change in relationship is due to the changing diffusion profile depending on the size of the electrode. At a very small electrode, radial diffusion become very important, as electroactive species in solution can diffuse from all around the electrode to react at the edges. This type of diffusion can also happen at a larger electrode of course, but at a larger electrode the contribution from these edge effects is negligible relative to the overall size of the electroactive area, and so it is assumed that all mass transport towards a large electrode is perpendicular towards the electrode surface. The contribution of edge effects to the current at a microelectrode is described as hemispherical diffusion, due to the characteristic shape of the diffusion field.<sup>3</sup><br>
<br>
<img align="center" width="100%" src="/images/Sensing/Fig 1.png">
<br>
<i><b>Figure 1.</b> Diffusion regimes to a large planar electrode (left) and a microelectrode (right). The hemispherical shape of the microelectrode diffusion layer is responsible for its characteristic electrochemical behavior.</i><br>
<br>
This hemispherical diffusion raises a further interesting property of microelectrodes. As the timescale of experiments becomes longer, the first term in Equation 2 becomes negligibly small. If a sufficient time passes before measurement, then the microelectrode records a steady state current, where the current is independent of the timescale, and is directly proportional to the concentration of electroactive species in solution. The origins of these properties are discussed in more detail <a href="/Research/Kinetics_and_Digital_Simulation" target="_blank" >here</a>.<br>
</p>

<div class="grid-container">
  <div class="grid-item">
	<div class="container">
	  <img align="center" width="20%" src="/images/Sensing/Eq_Steady_State.png">
	</div>
  </div>
  <div class="grid-item">
	<div class="container">
	  (3)
	</div>
  </div>
</div>

<p align="justify">
<br>
This is clearly useful for electrochemical sensing, as the steady state current allows for a rapid read out of the concentration of electroactive analyte. Further discussion on the properties of microelectrodes can be found <a href="/Research/Scanning_Electrochemical_Microscopy" target="_blank" >here</a>. The situation becomes more complicated when considering analytes that are not electrochemically active. One common solution is to use enzymatic biosensors, which shall be discussed here.<br>
</p>

Theory and function of enzymatic biosensors
---------------------------------------------

<p align="justify">
The core concept of an enzymatic biosensor is to take advantage of the reaction between an enzyme and its substrate, and use that naturally occurring biological reaction to produce an electrochemical signal. This could be either by generating of by consuming an electroactive species in solution, which can then be detected by normal electrochemical methods. We have been interested in a class of oxidase enzymes that generate stoichiometric amounts of some redox active species as part of their standard function. One of the most popular enzymatic biosensor is the glucose biosensor, which is used worldwide by people with diabetes.<sup>4</sup> Similar biosensors can also be built for ᴅ-serine<sup>5</sup> and ʟ-lactate,<sup>6</sup> which produce stoichiometric amounts of H<sub>2</sub>O<sub>2</sub> and NADH respectively.<sup>7</sup><br>

<br>
<img align="center" width="70%" src="/images/Sensing/Fig 2.png">
<br>
<i><b>Figure 2.</b> Enzymatic degradation of A) ᴅ-serine using DAAO, and subsequent detection of H<sub>2</sub>O<sub>2</sub> at a platinum electrode and B) ʟ-lactate using LDH, and subsequent electrochemical detection of NADH at a platinum electrode. Figure taken from reference 7.</i><br>
<br>

However, it is not as simple as adding enzyme to an analyte solution and then using an electrode to measure the concentration of peroxide. There are a number of reasons this would not work. High quality enzymes are too expensive for this to be feasible on a larger scale. Also, it is unlikely that the enzyme will react all of the available analyte, which would result in the electrochemical probe underestimating the concentration of the original analyte. Also, peroxide itself is unstable and will decompose under working conditions at a relatively fast rate. Enzymatic biosensors therefore need to be developed in a way to get around these issues.<br>
<br>
The solution to this has been to immobilise the enzyme onto the tip of a microelectrode.<sup>7-9</sup> This allows the enzyme to produce stoichiometric amounts of peroxide as it encounters ᴅ-serine in solution. Since the peroxide is generated in close proximity to the electrode surface, it is rapidly reduced with minimal mass transport limitations. As long as the enzyme reaction is sufficiently fast, the electrochemical response can be treated as if it were solely coming from the ᴅ-serine in solution.<br>

<br>
<img align="center" width="70%" src="/images/Sensing/Fig 3.png">
<br>
<i><b>Figure 3.</b> Diagram of the fully fabricated biosensor. Inset focuses on the tip of the biosensor, showing the enzyme layer (orange), size exclusion polymer layer (blue) and platinum surface of the microelectrode (grey). Figure taken from reference 7.</i><br>
<br>

Using microelectrodes as the scaffold for a biosensor comes with a number of distinct advantages. Most are centred on the small size, which gives excellent temporal and spatial resolution. This allows microelectrode biosensors to provide information regarding not just how much of an analyte is there, but also precisely where it came from. This has a number of potential applications, particularly in neuroscience where the origin of a number of neurotransmitters is still uncertain.<sup>8, 9</sup> You can read more about applications of microelectrodes to the localised detection of electroactive species <a href="/Research/Scanning_Electrochemical_Microscopy" target="_blank" >here</a>.<br>
<br>

</p>

Practical applications
------------------------

<p align="justify">
When thinking about real world applications of enzymatic biosensors, it is important to consider exactly where the final product will be used. Most simple biosensor designs function very well under lab conditions, where only the analyte is present in solution. However, real working solutions often have other chemicals present that are also electroactive. These may contribute to, or in some cases entirely mask the electrochemical response from the peroxide, which greatly reduces the sensitivity and the accuracy of enzymatic biosensors. This is particularly true of biosensors with biological applications, since common media such as blood or cerebral spinal fluid have large concentrations of a number of redox active species.<sup>9</sup><br>
<br>
The focus of research in this area is usually divided into three targets. First is to develop enzymes with high turnover rates in order to maximise the rate of target detection. This gives a larger current response at the biosensor relative to the concentration of the analyte. Second is to increase the selectivity of the system. Usually this does not need to be done for the enzyme, but instead focuses on the electrode scaffold to prevent redox reactions occurring with other species in solution. Sometimes selecting an appropriate potential where only the target is reacted is sufficient, although usually extra measures are needed. Finally, it is important to improve the sensitivity of the biosensor. Having a large signal at a biosensor with a small concentration gives a high signal to noise ratio. This allows precise measurements of minute concentrations of analyte, which are often needed with real biological systems. <br>
<br>
</p>

Our goals
===========

Goal 1 - Enhance selectivity
-----------------------------

<p align="justify">
Enhancing the selectivity of a biosensor cannot be simply done through the application of a specific potential. It is most efficiently done by restricting access to the electrode surface to all species other than the analyte, in our case H<sub>2</sub>O<sub>2</sub>.<br>
<br>
</p>


Goal 2 - Enhance sensitivity
------------------------------

<p align="justify">
The sensitivity of our biosensor is determined by the current recorded per mole of peroxide. Simply put, if we can record a large current with a small concentration of peroxide, we are able to quantify lower concentrations of our analyte using the same enzyme in the same biosensor set-up.<br>
<br>
</p>


Part 1 - Selectivity enhancement with size exclusion polymers
===============================================================

<p align="justify">
The size exclusion performance of our biosensor comes from the use of a porous polymer at the electrode surface. The electrodeposition of <i>m</i>-phenylene diamine produces a porous, non-conductive porous polymer (PPD), where the pores are small enough to allow for peroxide diffusion, whilst also blocking potentially interfering electrochemically active compounds such as ascorbic acid.<br>

<br>
<img align="center" width="70%" src="/images/Sensing/Fig 4.png">
<br>
<i><b>Figure 4.</b> Selectivity of the biosensor towards electroactive interferences before and after electrodeposition of varying thicknesses of the permselective PPD layer. The interferences were ascorbic acid (AA), serotonin (5-HT), dopamine (DA), 3,4-dihydroxyphenylacetic acid (DOPAC), 5-hydroxyindoleacetic acid (5-HIAA), homovanillic acid (HVA), and hydrogen peroxide (H<sub>2</sub>O<sub>2</sub>). The current was recorded at 500 mV vs. Ag/AgCl. Error bars represent 95% confidence interval (n=10) Figure taken from reference 9.</i><br>
<br>

Unfortunately, the presence of a blocking layer at electrode surface will always also reduce the current from peroxide oxidation, since the diffusion path is now less straightforward and a significant proportion of the surface active sites are now blocked. However, the gains in terms of selectivity from the use of this size exclusion layer is well worth the payment in terms of the current recorded.<br>
<br>
</p>

Part 2 - Sensitivity enhancement with targeted surface roughness
==================================================================

<p align="justify">
Since the sensitivity of our sensor is being reduced by the size exclusion layer, it is important to enhance the sensitivity of our biosensor by some other means. This has been achieved by moving away from the biosensor design at focusing on the electrochemistry of peroxide oxidation. The oxidation mechanism of H<sub>2</sub>O<sub>2</sub> requires an initial adsorption of H<sub>2</sub>O<sub>2</sub> onto the electrode surface before an electron can be transferred. This results in a highly surface dependent process, and so a finely tuned electrode surface can have a significant impact on the overall current passed for the same concentration of H<sub>2</sub>O<sub>2</sub>. More information on the surface dependence of H<sub>2</sub>O<sub>2</sub> can be found <a href="/Research/Oxygen_Reduction" target="_blank" >here</a>.<br>
<br>
There are a number of studies into the enhancement of an electrode surface for peroxide oxidation, involving complicated surface modifications and microstructures, such as the use of platinum or gold nanoparticles,<sup>10, 11</sup> carbon nanotubes,<sup>12, 13</sup> metal nanowires,<sup>14</sup> or metal oxides,<sup>15, 16</sup> to name just a few. However, it is possible to achieve similar effects through much simpler means, by roughening the surface using a simple polishing regime. This increases the current from H<sub>2</sub>O<sub>2</sub> oxidation by two means.<br>
<br>
Firstly, the roughening of the electrode results in a greatly increased surface area, and so a greater number of binding sites are available for H<sub>2</sub>O<sub>2</sub> oxidation. The increased surface area is expressed in terms of the roughness factor (<i>R</i><sub>f</sub>) Secondly, the roughening reveals a number of step, edge and other defect sites. These high energy sites favour the oxidation of H<sub>2</sub>O<sub>2</sub> at lower overpotentials, which enhances the turnover rate of the electrode, and so can further increase the sensitivity.<br>

<br>
<img align="center" width="70%" src="/images/Sensing/Fig 5.png">
<br>
<i><b>Figure 5.</b> A) Recorded mass transport limited currents (<i>i</i><sub>lim</sub>) at DAAO ᴅ-serine biosensors with varying <i>R</i><sub>f</sub> for different concentrations of ᴅ-serine. All biosensors were fabricated starting from the same microelectrode, using the same thickness of size exclusion polymer layer and enzyme deposition technique. Biosensors were fabricated from electrodes where <i>R</i><sub>f</sub> was 4.5 (green), 5.8 (grey), 7.3 (red), 10.3 (blue), 13.6 (orange) and 16.1 (black). Error bars represent the 95% confidence interval (n = 9). Oxidation currents are presented as blank corrected currents. B) Calculated limit of detection (LOD) for each roughness biosensor, taking LOD as three times the standard deviation of the blank, divided by the gradient of the calibration curve in A. Figure taken from reference 7.</i><br>
<br>

As with most aspects of electrochemistry, the roughening of the electrode for enhanced selectivity has a potential drawback. The increased surface area increases the charging current at the electrode. This is a non-Faradaic current from the attraction of oppositely charged ions to the charged electrode surface. This has to pass before a quantitative current related to the H<sub>2</sub>O<sub>2</sub> concentration can be recorded. We can get around this by using a sufficiently small electrode. Since the charging current is proportional to the electrode area, a small electrode can fully pass its charging current within a few microseconds, and so we are able to significantly roughen our electrode to increase the selectivity without negatively impacting the electrode responses time. In fact, surprisingly we found that roughening the electrode actually reduced the response time, defined as the time taken to reach 90% of the mass transport limited current given by Equation 3. This highlights the role of the additional high energy defect sites in favouring the kinetics of the peroxide oxidation.<br>

<br>
<img align="center" width="70%" src="/images/Sensing/Fig 6.png">
<br>
<i><b>Figure 6.</b> Response time (<i>t</i><sub>res</sub>) for H<sub>2</sub>O<sub>2</sub> oxidation at a bare platinum surface (red) and at platinum surface in the presence of a size exclusion polymer layer (blue), and for ᴅ-serine detection at an enzymatic biosensor (black). Error bars represent the 95% confidence interval (<i>n</i> = 9). In all cases, response times shown were calculated at the same 25 &mu;m diameter electrode, which was subsequently electrodeposited with polymer to obtain the blue points, and then made into a full biosensor to obtain the black points. All <i>t</i><sub>res</sub> were recorded in 25 &mu;M analyte solution in PBS. Figure taken from reference 7.</i><br>
<br>

</p>

TL;DR
========

<ul>
  <li><p align="justify">Enzymatic biosensors detect non-electroactive species by enzyme reactions with a target molecule, which produces stoichiometric amounts of some redox active species.</p></li>
  <li><p align="justify">Most works focus on the enzyme activity, but significant improvements can be made by focusing on the electrochemistry of the redox active analyte.</p></li>
  <li><p align="justify">Roughening an electrode before using it as an enzymatic biosensor favours the oxidation of the stoichiometric H<sub>2</sub>O<sub>2</sub> oxidation through the larger surface area and additional high energy binding sites.</p></li>
  <li><p align="justify">Rougher electrodes give lower limits of detection and faster response times.</p></li>
</ul>


Recommended Resources
==========================

<ul>
  <li><p align="justify">S. Perry, <i>Transient Studies at Microelectrodes</i>, thesis submitted to University of Southampton. <a href="https://eprints.soton.ac.uk/387227/" target="_blank" >Direct Link</a></p></li>
  <li><p align="justify">A. F. P. Turner; Biosensors: Sense and Sensibility; <i>Chem. Soc. Rev.</i>, <b>42</b>, 3184-3196, (<b>2013</b>). <a href="https://doi.org/10.1039/C3CS35528D" target="_blank" >Direct Link</a></p></li>
  <li><p align="justify">S. C. Perry, S. M. Gateman, J. Sifakis, L. Pollegioni, J. Mauzeroll; Enhancement of the Enzymatic Biosensor Response through Targeted Surface Roughness <i>J. Electrochem. Soc.</i>, <b>165</b>, G3074-G3079, (<b>2018</b>). <a href="https://doi.org/10.1149/2.0121812jes" target="_blank" >Direct Link</a></p></li>
  <li><p align="justify">A. Bard and L. Faulkner, <i>Electrochemical Methods: Fundamentals and Applications</i>, John Wiley & Sons, NY. <a href="https://www.wiley.com/en-us/Electrochemical+Methods%3A+Fundamentals+and+Applications%2C+2nd+Edition-p-9780471043720" target="_blank" >Direct Link</a></p></li>
  <li><p align="justify">D. Pletcher, <i>A First Course in Electrode Processes</i>, Royal Society of Chemistry, Cambridge. <a href="https://pubs.rsc.org/en/content/ebook/978-1-84755-893-0" target="_blank" >Direct Link</a></p></li>
</ul>



References
============

1.	Pletcher, D., <i>A First Course in Electrode Processes</i>, Royal Society of Chemistry, Cambridge (<b>2009</b>).
2.	Bard, A. and Faulkner, L., <i>Electrochemical Methods: Fundamentals and Applications</i>, John Wiley & Sons, New York, NY (<b>2000</b>).
3.	Perry, S. C., <i>Transient Studies at Microelectrodes</i>, thesis submitted to University of Southampton (<b>2016</b>).
4.	Turner, A. P. F., <i>Chem. Soc. Rev.</i>, <b>42</b>, 3184-3196 (<b>2013</b>).
5.	Pollegioni, L., Langkau, B., Tischer, W., Ghisla, S. and Pilone, M. S. <i>J. Biol. Chem.</i>, <b>268</b>, 13850-13857 (<b>1993</b>).
6.	Rathee, K., Dhull, V., Dhull, R. and Singh, S. <i>Biochem. Biophys. Rep.</i>, <b>5</b>, 35-54 (<b>2016</b>).
7.	Perry, S. C., Gateman, S. M., Sifakis, J., Pollegioni, L. and Mauzeroll, J. <i>J. Electrochem. Soc.</i>, <b>165</b>, G3074-G3079 (<b>2018</b>).
8.	Polcari, D., et al. <i>Anal. Chem.</i>, <b>86</b>, 3501-3507 (<b>2014</b>).
9.	Polcari, D., Perry, S. C., Pollegioni, L., Geissler, M. and Mauzeroll, J. <i>ChemElectroChem</i>, <b>4</b>, 920-926 (<b>2017</b>).
10.	Huang, J., et al. <i>Mat. Sci. Eng. C</i>, <b>28</b>, 1070-1075 (<b>2008</b>).
11.	Jena, B. K. and Raj, C. R. <i>Electroanal. </i>, <b>19</b>, 816-822 (<b>2007</b>).
12.	Dagar, K. and Pundir, C. S. <i>Enzyme Microb. Technol.</i>, <b>96</b>, 177-186 (<b>2017</b>).
13.	Zhu, Z., et al. <i>Sensors</i>, <b>12</b>, 5996 (<b>2012</b>).
14.	Kurbanoglu, S. and Ozkan, S. A. <i> Electrocatal.</i>, <b>9</b>, 252-257 (<b>2018</b>).
15.	Shi, X., et al. <i>Microchim. Acta</i>, <b>181</b>, 1-22 (<b>2014</b>).
16.	Yu, J., Liu, S. and Ju, H. <i>Biosens. Bioelectron.</i>, <b>19</b>, 401-409 (<b>2003</b>).
