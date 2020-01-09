---
layout: single
author_profile: true
toc: true
toc_label: "Scanning Electrochemical Microscopy"
permalink: /Research/Scanning_Electrochemical_Microscopy
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


Microelectrodes
================================

<p align="justify">
There are multiple types of microelectrode used in the literature, the main variance being the shape and therefore properties of the active area. Microelectrode geometries are large in number, including spherical, hemispherical, disc, line and ring shapes.<sup>1</sup><br>
<br>
The electrochemistry of a microdisc electrode occurs at the cross section of a conductive wire at the tip of the microelectrode. This is surrounded by glass insulation, and connected to a copper wire by a metal epoxy. The glass insulation is then sealed shut with a non-conductive epoxy resin to prevent the copper wire from detaching. A schematic diagram for this design is shown in Figure 1. Metal wire for the construction of microelectrodes is available in multiple materials and diameters. Anything less than around 50 &mu;m is generally considered to be a microelectrode.<sup>2</sup><br>
</p>
<br>
<img align="center" width="50%" src="/images/SECM/Fig 1.png">
<br>
<i><b>Figure 1:</b> Schematic diagram showing the principle components of a microelectrode.</i><br>
<br>
<p align="justify">
The key parameter of a microelectrode that determines most of its properties is the electrode radius. The small size of the active area, commonly between 10<sup>−8</sup> cm<sup>2</sup> and 10<sup>−4</sup> cm<sup>2</sup>, gives a microelectrode a number of distinct advantages over macroelectrodes. For instance, when the surface of the electrode is biased, a layer of oppositely charged ions will become attracted to the electrode surface. The surface will therefore become charged, behaving like a capacitor. The characteristic time taken to resolve this capacitance (<i>&tau;</i>) is proportional to the radius of the electrode used and so a very small electrode allows the double layer charging current to be very rapidly resolved. If a sufficient time passes before measurement, then the microelectrode records a steady state current, where the current is independent of the timescale, and is directly proportional to the concentration of electroactive species in solution.<sup>3</sup><br>
</p>
<div class="grid-container">
  <div class="grid-item">
	<div class="container">
	  <img align="center" width="20%" src="/images/Sensing/Eq_Steady_State.png">
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
As well as high temporal resolution, microelectrodes offer excellent spatial resolution. Bringing the electrode in close proximity to a surface can provide information about the conductivity and the topography of that surface.4 Continually scanning the probe over the surface therefore allows for the generation of a topographical image of the surface, hence the name scanning electrochemical microscopy (SECM).<sup>5</sup>
</p>

Electrodes for SECM
=========================

<p align="justify">
Before looking into SECM itself there is an important consideration that needs to be made regarding the electrode itself. When moving at electrode close to a substrate, it is important to know the precise tip to substrate distance (<i>d</i>), as shall be discussed here. This presents an experimental challenge when working with microelectrodes, as it is very difficult to approach an electrode perfectly perpendicular to a substrate, either due to an angled approach or the presence of an angle at the tip of the microelectrode itself. To minimise the impact of this contact angle, electrodes for SECM are made to have a very small total tip size. This means than a slightly angled approach will result in a minimal error in the calculated tip to substrate distance.<br>
<br>
The use of small geometry electrodes presents an additional complication in calculations, as the small geometry means that the diffusion field at the electrode tip now extends around the back of the electrode. The expression for the limiting current given in Equation 2 must be adjusted to take this into account by multiplying Equation 2 by a geometry dependent beta factor. There are a number of different approximations for this beta factor, with one of the most accurate given by Equation 3<sup>6</sup><br>
<br>
</p>
<div class="grid-container">
  <div class="grid-item">
	<div class="container">
	  <img align="center" width="70%" src="/images/SECM/Eq_Steady_State_Beta.png">
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
where <i>R</i><sub>g</sub> is the ratio of the total electrode tip radius (<i>a</i><sub>total</sub>) to the electroactive disc radius (<i>a</i>). All theoretical models for the mass transport limited current (<i>i</i><sub>lim</sub>) will be based on this new beta model. 
</p>

Modes of SECM
==================

<p align="justify">
There are a number of different modes of SECM depending on the desired information,<sup>1, 7</sup> far too many in fact to discuss in detail here. The first mode to consider is the feedback mode. This can be divided into two categories, positive and negative feedback, although the basic technique is similar in both cases. In all cases, the tip of the microelectrode is brought into close proximity to the surface of interest in the presence of some electrochemically active redox mediator. This mediator is a species that can undergo a rapid single electron transfer at a known potential. There are a number of different mediators that may be chosen,<sup>1</sup> the choice is normally made based on other species present in solution to minimize interference. For example, [Ru(NH<sub>3</sub>)<sub>6</sub>]<sup>3+</sup> is a popular mediator, but has a similar redox potential to dissolved oxygen, and so is only used in deaerated solutions.<sup>8</sup> Solutions containing oxygen require a mediator with a more positive redox potential, such as ferrocene. Mediators may undergo reductions or oxidations at the electrode, but for simplicity they shall be discussed in terms of oxidation reactions throughout this page.<br>
<br>
</p>

Negative Feedback mode
--------------------------
<p align="justify">
When the electrode tip is in the bulk solution, the tip experiences rapid diffusion of the mediator towards the electrode from all directions, giving the steady state current that is characteristic of microelectrodes. However, if this is brought into close proximity to an insulating surface the diffusion of the mediator to the electrode becomes blocked. This barrier to the diffusion of the mediator results in a decrease in the measured current, with the current becoming progressively lower as the electrode moves closer to the electrode surface. This is defined as negative feedback.<br>
<br>
<img align="center" width="100%" src="/images/SECM/Fig 2.gif">
<br>
<i><b>Figure 2:</b> Schematic diagram showing the negative feedback mode of SECM. Left) Schematic microelectrode moving towards an insulating surface. As the electrode moves closer to the substrate, diffusion of R to the electrode tip becomes hindered. Right) Approach curve for negative feedback SECM. L is defined as the tip – substrate distance (d) divided by the electroactive radius (a). As the tip moves closer to the substrate (low L) the current rapidly decreases. On contact with the substrate (L = 0) the theoretical current is zero, although experimentally a small current is usually seen due to the contact angle of the electrode.</i><br>
<br>
Negative feedback can therefore provide high resolution about the surface being probed. The resolution is defined by the electroactive area of the electrode being used, with modern probes able to be fabricated right down to the nanometer scale. In the case of negative feedback, the magnitude of the current is defined by the tip to substrate distance, as given by Equation 4 <sup>9</sup><br>
</p>
<div class="grid-container">
  <div class="grid-item">
	<div class="container">
	  <img align="center" width="70%" src="/images/SECM/Eq_Negative_Feedback.png">
	</div>
  </div>
  <div class="grid-item">
	<div class="container">
	  (4)
	</div>
  </div>
</div>

<p align="justify">
<br>
where <i>Ni</i><sub>T</sub> is the normalised current, where <i>N</i> = <i>i / i</i><sub>lim</sub> and <i>L</i> is the normalised tip-substrate distance, where <i>L</i> = <i>d / a</i>. <br>
<br>
Scanning the electrode over the surface allows the changes in topography to be extracted from the measured current.<sup>10</sup> Experimentally this may be done by keeping the electrode at the same vertical position and tracking the change in current, or the tip-substrate distance can be constantly adjusted to ensure a constant current and the change in tip-substrate distance recorded, though the recorded information should be identical in both cases.
</p>

Positive Feedback Mode
---------------------------------------
<p align="justify">
When the electrode approaches a conductive substrate a different situation is seen. The conductive substrate still blocks the diffusion of the mediator towards the electrode. However, after the mediator is oxidised at the electrode tip, it may be reduced back to its initial state at the substrate. This provides a rapid regeneration of the mediator in close proximity to the electrode. Now, the current increases as the electrode is moved closer to the substrate, as the electrode sees an increased rate of mediator regeneration. This is defined as positive feedback. <br>
<br>
<img align="center" width="100%" src="/images/SECM/Fig 3.gif">
<br>
<i><b>Figure 3:</b> Schematic diagram showing the positive feedback mode of SECM. Left) Schematic microelectrode moving towards a conductive surface. As the electrode moves closer to the substrate, O generated at the electrode tip may be reduced back to R by the substrate. This provides a regeneration of the starting material close to the substrate. B) Approach curve for positive feedback SECM. As the tip moves closer to the substrate (low L) the current rapidly increases due to the regeneration of the redox mediator. On contact with the substrate (L = 0) the theoretical current is infinite, although experimentally of course this is not seen.</i><br>
<br>
For positive feedback the expression for the recorded current is more complicated than for negative feedback, since the recorded current is down to contributions from both the distance between the tip and the substrate and the conductivity of the substrate. A more complex relation has been defined, as given by Equation 5.<sup>11</sup><br>
</p>
<div class="grid-container">
  <div class="grid-item">
	<div class="container">
	  <img align="center" width="80%" src="/images/SECM/Eq_Positive_Feedback.png">
	</div>
  </div>
  <div class="grid-item">
	<div class="container">
	  (5)
	</div>
  </div>
</div>

<p align="justify">
<br>
Where the beta factor is defined in Equation 3, and the alpha factor is defined by Equation 6.<sup>11</sup><br>
</p>
<div class="grid-container">
  <div class="grid-item">
	<div class="container">
	  <img align="center" width="80%" src="/images/SECM/Eq_Positive_alpha.png">
	</div>
  </div>
  <div class="grid-item">
	<div class="container">
	  (6)
	</div>
  </div>
</div>

<p align="justify">
<br>
It is therefore possible to find information about the localised reactivity of a surface using combinations of positive and negative feedback experiments, where negative feedback is first used to find the topographical information, followed by positive feedback to find the surface reactivity.
</p>

Generation-Collection Mode
--------------------------------------------------

<p align="justify">
SECM is also useful for more dynamic systems than a conductive or non-conductive systems. There are a number of cases where it is desirable to detect the release of some electroactive species from a surface. This is particular common in biological cell studies, where SECM can be used to detect the release of electroactive species across a cell membrane. The expression for this mode of detection is similar to that of positive feedback, although the magnitude of the current is now determined by the rate of product release, rather than by the rate of product regeneration. <br>
<br>
<img align="center" width="100%" src="/images/SECM/Fig 4.gif">
<br>
<i><b>Figure 4:</b> Schematic diagram showing the generation-collection mode of SECM. A) Schematic microelectrode moving towards a substrate capable of generating a redox active species. As the electrode moves closer to the substrate, it is able to detect the redox active R that is being released. B) Approach curve for positive feedback SECM. As the tip moves closer to the substrate (low L) the current rapidly increases due to the detection of redox active R. The O’ produced at the electrode tip may be the same species being consumed at the substrate, or may be a different species entirely depending on the system. The source of R could be an electrochemical process, as shown here, or could be due to diffusion across a membrane.</i><br>
<br>
</p>

Scanning Mode
---------------------------------------
<p align="justify">
So far, we have only seen examples where the substrate is behaving homogeneously across the entire surface. Many real surfaces show regions of high conductivity in an otherwise insultating surround, or vice versa. By sweeping the SECM tip across the electrode surface, it is possible to reveal these conductive sites as regions of high current in a low current sweep.<br>
<br>
<img align="center" width="100%" src="/images/SECM/Fig 5.gif">
<br>
<i><b>Figure 4:</b> Schematic diagram showing the scanning mode of SECM. Left) Schematic microelectrode sweeping over a substrate with insulating and conducting regions. As the electrode moves over a conductive area, R is regenerated giving an increase in the current. B) SECM current sweep over a conductive site on an insulating substrate. As the tip moves over the conductive site, the current increases, then decreases once the substrate is insulating once more.</i><br>
<br>

By continually sweeping across the surface, it is possible to build up a current map highlighting regions of high conductivity.<br>
</p>

Our goals
==============

Goal 1 – Detect the release of biologically useful compounds 
---------------------------------------------------------------------------------------
<p align="justify">
The research page on <a href="/Research/Electrochemical_Sensing" target="_blank" >Electrochemical Sensing</a> discussed the fabrication of an enzymatic biosensor for the detection of ᴅ-serine. Combining this biosensor with SECM would allow for the detection of localised release of ᴅ-serine from real biological systems.<br>
<br>
</p>

Goal 2 – Study the localised corrosion of steel samples 
-------------------------------------------------------------------------------
<p align="justify">
Many stainless steels are subjected to pitting corrosion, where the steel breaks down at small active sites in the steel surface. Analysing the local reactivity of steel samples could provide insights into the mechanism of this breakdown. 
</p>

Our Methods
=====================

Localised Detection of ᴅ-Serine
-------------------------------------------------------
<p align="justify">
Our long term goal in this work is to use an enzymatic biosensor to detect the localised release of ᴅ-serine from neuronal tissue.<sup>12, 13</sup> Before we can move to real cell environments we first need to verify the method using a model system. This will involve the detection of ᴅ-serine release from a model substrate with a known, regular geometry. The aim here is to verify that the electrochemical image recorded from the ᴅ-serine detection matches the known geometry of our substrate. The substrate we chose was ᴅ-serine-loaded agar sealed in a glass capillary. The cross section of this capillary then provided a circular geometry, where ᴅ-serine can diffuse slowly out of the agar into solution, and then will be detected by the microelectrode. This is a form of generation-collection SECM, where the SECM is effectively detecting the rate of ᴅ-serine diffusion across the agar-electrolyte boundary. <br>
<br>
<img align="center" width="50%" src="/images/SECM/Fig 6.png">
<br>
<i><b>Figure 4:</b> A) Schematic diagram for the SECM detection of ᴅ-serine release from a model agar substrate. Explanations for the structure and function of the biosensor can be found <a href="/Research/Electrochemical_Sensing" target="_blank" >here</a>. B) Electrochemical image recorded using SECM over the opening of the ᴅ-serine/agar filled capillary. The deep red hot spot corresponds to the geometry of the capillary cross section, showing a high level of spatial resolution. Figure taken from reference 13.</i><br>
<br>
When we compare the electrochemical image with the real geometry, we get a good agreement between the size of the capillary cross section and the size of the hot spot on the electrochemical image. This allows us to advance this work towards real cell environments, where we can be confident that the electrochemical image is a true representation of the location of the ᴅ-serine release. <br>
<br>
</p>

Imaging the Localised Corrosion of Stainless Steel
----------------------------------------------------------------------------------
<p align="justify">
Corrosion resistant stainless steels are alloys containing a range of metals, primarily a Fe and Cr mix, with certain amounts other stabilizing agents such as Ti ,Mo or Nb. Broadly, the corrosion resistance of stainless steels come from the formation of a Cr-rich passive layer at the electrode surface, which acts as a physical barrier toward further corrosion. Unfortunately, the surface of the steel is heterogeneous, and SEM imagery reveals Ti-rich inclusions dotted around the surface. These form during the steel manufacture stage, as they precipitate carbon and nitrogen impurities out of the steel to help make the steel less brittle. SECM imaging is able to reveal the different properties of heterogeneous metal surface to give insights into the reactions occurring at the surface, and to allow the prediction and detection of localised corrosion events.<sup>14</sup><br>
<br>
<img align="center" width="100%" src="/images/SECM/Fig 7.png">
<br>
<i><b>Figure 4:</b> A) Side on and B) end on view of the microelectrode used to record all electrochemical images in this work. C) SEM image of TiN inclusions seen in a stainless steel surface. D) SECM image of the same region of the steel surface. Green-yellow hot spots correspond to the more conductive TiN inclusions within the insulating Cr oxide surface. Figure taken from reference <sup>15</sup></i><br>
<br>
<br>
SECM imaging of the corroded steel surface shown negative feedback at the insulating Cr-rich passive layer, but positive feedback at the Ti-rich inclusions. This is important, as this high conductivity at the inclusions means that the inclusions are in contact with non-oxidised metal, and not just with the passive Cr oxide. This highlights that these sites can act as reactive initiation sites for corrosion reactions, and so provides evidence for the role of these inclusions in pitting corrosion and the breakdown of the passive layer. 
</p>

TL;DR
======

<ul>
<li><p align="justify">SECM allows for the localised detection of surface topography and reactivity.</p></li>
<li><p align="justify">In combination with enzymatic biosensors, we are able to detect the release of the neurotransmitter ᴅ-serine from a model substrate.</p></li>
<li><p align="justify">Comparing regions of positive and negative feedback can reveal reactive regions within the passive film of stainless steels, indicating their role in localised corrosion and passive film failure.</p></li>
</ul>


Recommended Resources
======================

<ul>
  <li><p align="justify"> A. Bard and M. Mirkin, <i>Scanning Electrochemical Microscopy</i> Taylor & Francis. (<b>2012</b>) <a href="https://www.crcpress.com/Scanning-Electrochemical-Microscopy/Bard-Mirkin/p/book/9781439831120" target="_blank" >Direct Link</a> </p></li>
  <li><p align="justify"> Polcari, D., Dauphin-Ducharme, P. and Mauzeroll, J. Scanning Electrochemical Microscopy: A Comprehensive Review of Experimental Parameters from 1989 to 2015. <i>Chem. Rev.</i>, <b>116</b>, 13234-13278 (<b>2016</b>). <a href=" https://pubs.acs.org/doi/10.1021/acs.chemrev.6b00067" target="_blank" >Direct Link</a></p></li>
  <li><p align="justify"> Zoski, C. G. Review—Advances in Scanning Electrochemical Microscopy (SECM). <i>J. Electrochem. Soc.</i>, <b>163</b>, H3088-H3100 (<b>2016</b>). <a href=" http://jes.ecsdl.org/content/163/4/H3088.abstract" target="_blank" >Direct Link</a></p></li>
  <li><p align="justify">Payne, N. A., Stephens, L. I. and Mauzeroll, J. The Application of Scanning Electrochemical Microscopy to Corrosion Research. <i>Corrosion</i>, <b>73</b>, 759-780 (<b>2017</b>). <a href="https://pubs.rsc.org/en/content/ebook/978-1-84755-893-0" target="_blank" >Direct Link</a></p></li>
</ul>



References
===============





1.	Polcari, D., Dauphin-Ducharme, P. and Mauzeroll, J. <i>Chem. Rev.</i>, <b>116</b>, 13234-13278 (<b>2016</b>).
2.	Zoski, C. G., Handbook of Electrochemistry, <i>Elsevier Science</i> (<b>2007</b>).
3.	Bard, Allen and Faulkner, L., Electrochemical Methods: Fundamentals and Applications, <i>John WIley & Sons.</i> (<b>2000</b>).
4.	Bard, A. J., Fan, F. R. F., Kwak, J. and Lev, O. <i>Anal. Chem.</i>, <b>61</b>, 132-138 (<b>1989</b>).
5.	Bard, A. J. and Mirkin, M. V., Scanning Electrochemical Microscopy, Second Edition, <i>Taylor & Francis</i> (<b>2012</b>).
6.	Lefrou, C. and Cornut, R. <i>Chem. Phys. Chem.</i>, <b>11</b>, 547-556 (<b>2010</b>).
7.	Zoski, C. G. <i>J. Electrochem. Soc.</i>, <b>163</b>, H3088-H3100 (<b>2016</b>).
8.	Bard, A. J., Parsons, R. and Jordan, J., Standard Potentials in Aqueous Solution, <i>Taylor & Francis,</i> (<b>1985</b>).
9.	Cornut, R. and Lefrou, C. <i>J. Electroanal. Chem</i>, <b>608</b>, 59-66 (<b>2007</b>).
10.	Kwak, J. and Bard, A. J. <i>Anal. Chem.</i>, <b>61</b>, 1221-1227 (<b>1989</b>).
11.	Lefrou, C. <i>J. Electroanal. Chem.</i>, <b>592</b>, 103-112 (<b>2006</b>).
12.	Polcari, D., et al. <i>Anal. Chem.</i>, <b>86</b>, 3501-3507 (<b>2014</b>).
13.	Polcari, D., Perry, S. C., Pollegioni, L., Geissler, M. and Mauzeroll, J. <i>ChemElectroChem</i>, <b>4</b>, 920-926 (<b>2017</b>).
14.	Payne, N. A., Stephens, L. I. and Mauzeroll, J. <i>Corrosion</i>, <b>73</b>, 759-780 (<b>2017</b>).
15.	Gateman, S. M., et al. <i>npj Mat. Deg.</i>, <b>2</b>, 5 (<b>2018</b>).

