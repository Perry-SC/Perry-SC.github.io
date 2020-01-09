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

Oxygen reduction mechanism
=======================

<p align="justify">
The oxygen reduction reaction (ORR) is a much discussed reaction in electrochemistry. The ORR is a complex multi-electron reduction, and may proceed via multiple pathways. Which pathway is followed seems to be determined by a combination of factors, including pH, electrode material, crystal face, roughness, electrolyte and rate of mass transport. The simplest pathway possible is the direct, four-electron reduction. Even this can occur by two different pathways, depending on the pH. Under acidic conditions, the reduction involves four electrons and four protons,<sup>1</sup> whereas basic conditions produce four equivalents of hydroxide ions.<sup>2</sup> For simplicity, the acidic route is discussed here.
<br>
</p>

<div class="grid-container">
  <div class="grid-item">
	<div class="container">
	  O<sub>2</sub> + 4H<sup>+</sup> + 4<i>e</i><sup>-</sup> 	&#8652; 	2H<sub>2</sub>O
	</div>
  </div>
  <div class="grid-item">
	<div class="container">
	  <i>E</i><sup>0</sup> = 1.229 V vs. SHE
	</div>
  </div>
  <div class="grid-item">
	<div class="container">
	  (1)
	</div>
  </div>
</div>
<br>

<p align="justify">
As well as the four electron reduction pathway, the ORR may instead proceed via a two electron pathway, going via a peroxide intermediate. The generated peroxide may be subsequently reduced to give water, or may diffuse into the bulk solution and dissociate. It is possible for the oxygen produced from the decomposition of peroxide to be subsequently reduced, provided the peroxide is not lost to the bulk solution before the decomposition occurs. This can be thought of as a cyclic process, with two electrons transferred to give peroxide, followed by a chemical step to regenerate the starting dioxygen. If the regenerated oxygen is completely reduced to water, then the overall reduction is then a complete four electron reduction process.<br>
<br>
</p>

<div class="grid-container">
  <div class="grid-item">
	<div class="container">
	  <p>O<sub>2</sub>+ 2H<sup>+</sup> + 2<i>e</i><sup>-</sup> &#8652; H<sub>2</sub>O<sub>2</sub></p>
	  <p>H<sub>2</sub>O<sub>2</sub> + 2H<sup>+</sup> + 2<i>e</i><sup>-</sup> &#8652; 2H<sub>2</sub>O</p>
	  <p>H<sub>2</sub>O<sub>2</sub> &#8652; H<sub>2</sub>O + ½ O<sub>2</sub></p>
	</div>
  </div>
  <div class="grid-item">
	<div class="container">
	  <p><i>E</i><sup>0</sup> = 0.700 V vs. SHE</p>
	  <p><i>E</i><sup>0</sup> = 1.760 V vs. SHE</p>
	  <p> </p>
	</div>
  </div>
  <div class="grid-item">
	<div class="container">
	  <p>(3a)</p>
	  <p>(3b)</p>
	  <p>(3c)</p>
	</div>
  </div>
</div>
<br>

<p align="justify">
During the ORR at an electrode surface, a combination of both the two and four electron pathways may be observed at any one time. This leads to the complex reaction scheme proposed by Wroblowa <i>et al.</i>, as is shown in Figure 1<br>
<br>
<img align="center" src="/images/ORR/Fig 1.png"><br clear="all">
<br>
<i><b>Figure 1</b>: Schematic diagram for the two and four electron ORR pathways, depicting the mass transport of O<sub>2</sub>from bulk solution to be adsorbed on the electrode surface (<i>k</i><sub>m</sub>), then four electron reduction to water (<i>k</i><sub>1</sub>). Alternatively, two electron reduction to H<sub>2</sub>O<sub>2</sub> (<i>k</i><sub>2</sub>), followed by further two electron reduction to water (<i>k</i><sub>3</sub>), diffusion in to the bulk (<i>k</i><sub>m</sub>), or decomposition to O<sub>2</sub> and H<sub>2</sub>O (<i>k</i><sub>4</sub>). </i><br>
<br>

A further method of peroxide decomposition is also possible, whereby the peroxide splits in to two HO<sup>&#8226;</sup> radicals.<sup>7</sup> These can then undergo a further single electron reduction each, to give an overall four electron reduction.<sup>8</sup>
<br>
</p>

<div class="grid-container">
  <div class="grid-item">
	<div class="container">
	  <p>O<sub>2</sub> + 2H<sup>+</sup> + 2<i>e</i><sup>-</sup>	&#8652;	H<sub>2</sub>O<sub>2</sub></p>
	  <p>H<sub>2</sub>O<sub>2</sub> &#8652;	2HO<sup>&#8226;</sup></p>
	  <p>HO<sup>&#8226;</sup> + H<sup>+</sup> + <i>e</i><sup>-</sup> &#8652; H<sub>2</sub>O</p>
	</div>
  </div>
  <div class="grid-item">
	<div class="container">
	  <p><i>E</i><sup>0</sup> = 0.670 V vs. SHE</p>
	  <p>&emsp;</p>
	  <p><i>E</i><sup>0</sup> = 2.330 V vs. SHE</p>
	</div>
  </div>
  <div class="grid-item">
	<div class="container">
	  <p>(4a)</p>
	  <p>(4b)</p>
	  <p>(4c)</p>
	</div>
  </div>
</div>
<br>

<p align="justify">
More complex mechanisms have also been proposed, whereby the oxygen is reduced via a series of single electron reduction steps via radical intermediates. This seems feasible, as radical species have been detected during the ORR by surface enhanced infra-red adsorption spectroscopy (SEIRAS)<sup>9</sup> and scanning electrochemical microscopy (SECM).<sup>8</sup><br>
</p>

<div class="grid-container">
  <div class="grid-item">
	<div class="container">
	  <p> O<sub>2</sub> + <i>e</i><sup>-</sup> &#8652; O<sub>2</sub><sup>&#8226; −</sup></p>
	  <p> O<sub>2</sub> + 2H<sup>+</sup> + 3<i>e</i><sup>-</sup> &#8652; HO<sup>&#8226;</sup> + OH<sup>-</sup></p>
	  <p> HO<sub>2</sub><sup>−</sup> + H<sub>2</sub>O + <i>e</i><sup>-</sup> &#8652; HO<sup>&#8226;</sup>  + 2OH<sup>-</sup></p>
	  <p> O<sub>2</sub><sup>&#8226; −</sup> + AH &#8652; HO<sub>2</sub><sup>&#8226;</sup> + A<sup>−</sup></p>
	  <p> O<sub>2</sub><sup>&#8226; −</sup> + HO<sub>2</sub><sup>&#8226;</sup> &#8652; HO<sub>2</sub><sup>−</sup> + O<sub>2</sub></p>
      <p>HO<sub>2</sub><sup>&#8226;</sup> + <i>e</i><sup>-</sup> &#8652; HO<sub>2</sub><sup>−</sup></p>
      <p>HO<sub>2</sub><sup>−</sup> + AH 	&#8652; H<sub>2</sub>O<sub>2</sub> + A<sup>−</sup></p>
	</div>
  </div>
  <div class="grid-item">
	<div class="container">
	  <p><i>E</i><sup>0</sup> = -0.330 V vs. SHE</p>
	  <p><i>E</i><sup>0</sup> = 0.803 V vs. SHE</p>
	  <p><i>E</i><sup>0</sup> = 0.184 V vs. SHE</p>
	  <p>&emsp;</p>
                  <p>&emsp;</p>
                  <p><i>E</i><sup>0</sup> = -0.744 V vs. SHE</p>
                  <p>&emsp;</p>	
                </div>
  </div>
  <div class="grid-item">
	<div class="container">
	  <p>(5a)</p>
	  <p>(5b)</p>
	  <p>(5c)</p>
	  <p>(5d)</p>
	  <p>(5e)</p>
	  <p>(5f)</p>
	  <p>(5g)</p>
	</div>
  </div>
</div>
<br>

<p align="justify">
Referring to Figure 1, if the rate of mass transport (<i>k</i><sub>m</sub>) is greater than the rate of peroxide reduction (<i>k</i><sub>3</sub>), then the rate of diffusion of peroxide away from the electrode increases. This leads to less oxygen being completely reduced, and so the apparent number of electrons involved in the reaction becomes less than four. This has previously been observed on rotating disc electrodes at varying rotation rates,<sup>10-11</sup> on microelectrodes of varying size<sup>11</sup> and on nanoelectrodes of varying size<sup>1</sup>. If the number of electrons transferred was measured during this process, this would give an idea of the interplay between the two and four electron pathways. The efficiency of a metal when it comes to catalysing the ORR is a fair indicator of whether the reduction will proceed via an overall two or four electron reduction, as it will determine the relative sizes of <i>k</i><sub>m</sub> and <i>k</i><sub>3</sub>. Different metals also exhibit a preference for different mechanisms.<br>
<br>
Whether by direct two electron reduction, or by the above steps via radical intermediates, hydrogen peroxide is inevitably formed in some small amount during the ORR. This may be subsequently reduced to give an overall 4 electron pathway, or may diffuse into the bulk solution. Interestingly, as well as the pH changing the mechanism of the reduction, it can also change the number of electrons transferred during the reduction. A larger pH decreases the number of electrons transferred from four to two. It has been proposed that this reduction is due to the increased degree of surface poisoning by hydroxide ions, which are available in greater concentrations in basic solution.<sup>12</sup> Adsorbed hydroxide favours the desorption of hydrogen peroxide and so inhibits further reduction, resulting in only two electrons being transferred per oxygen molecule.<sup>2</sup><br>
</p>

Adsorption on platinum metal surfaces
-----------------------------------------------------

<p align="justify">
All mechanisms for oxygen reduction begin with an initial adsorption of oxygen onto the electrode surface,<sup>10</sup> and with platinum being one of the most popular materials for oxygen reduction catalysts, the adsorption of oxygen onto its surface has been well researched. The adsorption of oxygen onto the catalyst surface is clearly a hugely important stage in the oxygen reduction mechanism. A number of different possibilities exist for the adsorption of oxygen onto a metal surface.<sup>11</sup>

<img align="center" src="/images/ORR/Fig 2.png"><br clear="all">
<br>
<i><b>Figure 2</b>: Schematic diagrams for varying modes of adsorption of oxygen on platinum</i><br>
<br>

The Griffith model is a side on adsorption mode, with two oxygen atoms bound to a single metal atom.<sup>12</sup> Oxygen adsorbs by binding 2<i>&pi;</i> orbitals with the empty 5d<sub>z<sup>2</sup></sub> of the metal atom, with some degree of back bonding from partially filled d<sub>xy</sub> or d<sub>yz</sub> metal orbitals to the antibonding 2<i>&pi;</i>* of the oxygen molecule.<sup>6</sup> The bridge model is a similar arrangement, but with one oxygen atom adsorbing per metal atom.<sup>13</sup> Strong adsorption indicates a greater degree of back bonding, which weakens the oxygen-oxygen bond, thus promoting dissociative adsorption. Both of these models result in the adsorption of both oxygen atoms to the metal surface. This favours the four electron reduction pathway, as two bonds formed per oxygen molecule helps to hinder the diffusion of peroxide away from the electrode surface.<sup>6, 14, 15</sup> The Pauling mode of adsorption is an end on adsorption mode.16 Adsorption is through a <i>&sigma;</i> bond between the <i>&sigma;</i>  orbital of the oxygen molecule into the metal d<sub>z<sup>2</sup></sub> orbital. The oxygen molecule is now kept perpendicular to the metal surface. This does not give the oxygen molecule the chance to dissociate at the electrode surface, and so favours two electron reduction, with peroxide being the end product. <br>
<br>

There are also other factors that will affect how oxygen reduction proceeds. The rate of oxygen reduction is proportional to the active area of the electrode in question. This means that the ORR current can be reduced by poisoning the electrode surface with a strongly binding species. In the case of platinum, a very effective poison is CO gas. CO is able to strongly bind to the platinum when held at a negative potential, and will out compete any other gaseous species adsorbing.<sup>17</sup> A similar effect is seen when using certain electrolytes. In the case of the potassium salts, the binding energy of the anion in decreases following I<sup>-</sup> > Br<sup>-</sup> > Cl<sup>-</sup> > ClO<sub>4</sub><sup>-</sup>.<sup>18</sup> It would therefore be expected that the rate of the reduction of O<sub>2</sub> dissolved in KClO<sub>4</sub> would be faster than O<sub>2</sub> dissolved in the same concentration of KI. In fact, it has been reported that the addition of as little of 4 ppm of Cl<sup>-</sup> gives an order of magnitude decrease in the ORR activity.<sup>19</sup><br>
<br>

Perchlorate has been observed to not adsorb at all, but instead remains as part of the double layer around the electrode surface.<sup>20</sup> Interestingly, bisulfate does adsorb onto the metal surface despite being analogous in structure to the perchlorate. The binding of sulfate to Pt metal surface is also quite different to the binding of halide ions in nature as well as bond strength due to the shape of the anion. The bisulfate anions bind most strongly to the Pt(111) crystal face due to the symmetry match between the C<sub>3v</sub> bisulfate anion and the (111) surface.<sup>21</sup> The poisoning effect of bisulfate results in the ORR activity in sulfate solutions following the trend Pt(111) < Pt(100) < Pt(110).<sup>22</sup> The spherical halides on the other hand can pack more closely onto the Pt(100) crystal face, resulting in increased adsorption onto this surface. Catalytic activity in halide anions therefore follows the trend Pt(100) < Pt(111) < Pt(110). This same pattern is also seen in perchlorate experiments,<sup>23</sup> and so much ORR research is conducted in perchlorate based electrolytes.<br>
<br>

It is worth noting that, although there is a clear trend in the activities of single crystal faces, the ORR mechanism may not be so simple on polycrystalline or multifaceted surfaces. Polycrystalline suface provide the possibility of migration of adsorbed species between crystal faces,<sup>24</sup> and can provide enhanced activity due to catalytically active step, edge and defect sites.<sup>25</sup> A similar effect has been seen by manipulating the size of platinum particles, which changed the nature of the adsorption sites available, having the corresponding effect on catalytic activity.<sup>26</sup><br>
<br>

A strong adsorption onto the metal surface corresponds to greater donation of electron density from the metal surface onto oxygen. The donation of electron density reduces the activation energy of the first three electron reduction steps, but raises the energy for the reduction of Pt-OH. This is why a strong binding energy of oxygen acts to reduce the catalytic activity of a material, as adsorbed OH<sub>ads</sub> acts to poison the electrode surface when the activation energy for its reduction becomes too high.<sup>14</sup> Differences in the nature of adsorption can also explain differences in the reduction pathway. Strong adsorption of oxygen allows the oxygen to dissociate on the metal surface. This allows complete four electron reduction, which is observed on platinum and platinum family metals. Metals on which oxygen adsorbs more weakly cannot break this O-O bond, and so two electron reduction is favoured. Such materials include mercury, gold and also carbon and oxide covered metals. Single free adsorption sites result in an end-on adsorption of oxygen. This favours the production of peroxide as an end product, as formed peroxide is easily released before further reduction takes place. Side-on adsorption of oxygen requires two adsorption sites side by side adsorption sites to be free. When this form of adsorption is seen, four-electron reduction is favoured as both oxygen atoms are direct contact with the electrode surface.<sup>6</sup><br>
</p>

Computational screening of materials for oxygen reduction
------------------------------------------------------------------------------------

<p align="justify">
Many different materials have been probed for their use as potential oxygen reduction catalysts. These range from pure metal catalysts such as Pt,<sup>27, 28</sup> Ag<sup>29</sup> or Au,<sup>30</sup> alloys of these metals with other transition metals such as PtCo<sup>27</sup> or PtAu,<sup>31</sup> zero platinum catalysts such as Fe/C/N<sup>32</sup> or TiO<sub>2</sub>/C<sup>33</sup> and also metal free catalyst materials such as nitrogen doped carbon,<sup>34</sup> or carbon nanotubes.<sup>35</sup> In all cases, platinum is used as a benchmark for comparing catalytic activity of varying materials.<br>
<br>
Platinum electrodes show a preference for the complete four electron reduction. It has been suggested that platinum follows an ECE mechanism, whereby the first electrochemical step generates the peroxide via two electron reduction, which then undergoes a chemical change, such as a decomposition or protonation step, before undergoing the further two electron reduction.<sup>8</sup> However, it is worth noting that ECE mechanisms tend to feature a homogeneous chemical step, where the chemical reaction occurs in solution. This is not the case for the ORR as the chemical step would involve the oxygen species adsorbed onto the electrode surface. These steps are all rapid, and so the voltammetry shows the four electron total reduction as one simple reduction wave. Gold, on the other hand, gives a well-defined `two-wave' reduction. This features a plateau in the mid-range potentials where there is a stable region of two electron reduction of oxygen to peroxide, as seen in Figure 3.<br>

<br>
<img align="center" width="45%" src="/images/ORR/Fig 3.png">
<img align="center" width="45%" src="/images/ORR/Fig 4.png"><br clear="all">
<br>
<i><b>Figure 3</b>: 2 mV s<sup>-1</sup> linear sweep voltammogram of ORR in aerated 0.1 M KClO<sub>4</sub> on a 25 &mu;m diameter Pt electrode (left) and Au electrode (right). The sweep started at 1 V vs. RHE, proceeding in a negative direction.<sup>36</sup></i><br>
<br>

This difference between gold and platinum has also been seen when reducing oxygen at platinum nanoparticles on a gold support, where it has been observed that the two electron reduction at the gold substrate is facilitated by the removal of the peroxide by further two electron reduction at the platinum nanoparticles.<sup>30</sup> At more negative potentials a second wave is seen, which corresponds to the two electron reduction of peroxide, although this requires a considerable overpotential due to the low energy of binding between peroxide and gold.<sup>37</sup> It was found that the rate of the second two electron reduction exhibits very little potential dependence, even at very negative potentials, suggesting that the issue of the large overpotential needed to give the reduction is avoided by the peroxide decomposing into more easily reducible species, such as OH<sub>ads</sub>.<sup>38</sup><br>
<br>
Platinum metal is a popular electrode material thanks to its well defined electrochemistry, and due to its excellent catalytic activity for the ORR. One reason that it is suitable for this is that its metal-oxygen binding energy (Delta;<i>E</i><sub>O</sub>) is of an intermediate value. This means that it is not so weak that oxygen binding is disfavoured, but not so strong that binding is irreversible. This is important because the oxygen reduction reaction proceeds via adsorption steps. This results in a high catalytic activity for the reaction, which is demonstrated in the volcano plot shown in Figure 5.

<br>
<img align="center" width="80%" src="/images/ORR/Fig 5.png"><br clear="all">
<br>
<i><b>Figure 4</b>: Volcano plot showing the catalytic activity for ORR for various metals against their oxygen binding energies (&Delta;<i>E</i><sub>O</sub>). Values for &Delta;<i>E</i><sub>O</sub> were taken from reference 39. </i><br>
<br>

The excellent correlation between binding energy and catalytic activity shows that the strength of the interaction between oxygen and the metal catalyst is incredibly important, which makes &Delta;<i>E</i><sub>O</sub> a useful descriptor for the evaluation of catalytic materials. It can be seen that, whilst platinum is the highest metal listed in Figure 6, it is not the highest catalytic activity possible. According to the trend across the other metals, it appears that a slight reduction in &Delta;<i>E</i><sub>O</sub> could in fact provide an increase in the catalytic activity of the material. The strength of the Pt-O bond is also an indicator of whether the metal will favour two of four electron reduction, as strong Pt-O bonds can facilitate the breaking of the O-O bond. Weaker Pt-O bonding will therefore make it more likely that the O-O bond will not be broken until after two electron reduction steps, favouring the formation of hydrogen peroxide.<sup>40</sup><br>
<br>

When developing a material for the efficient catalysis of the ORR, it is common to aim for the peak of the volcano plot. One well researched way to achieve this is by alloying platinum with other metals, which has the effect of altering the binding energy towards oxygen. However, calculation of binding energies of alloyed metals is far more complicated than performing the same calculations for a pure metal. It is computationally difficult to simulate the presence of both metal atoms in appropriate number and position, as well as accounting for interactions between both atoms affecting the energies of their orbitals. Inevitably, a number of approximations have to be used. One commonly used approximation is to use the calculation of the d-band energy as an approximation for &Delta;<i>E</i><sub>O</sub>. The d-band energy is defined as the difference between the d-band centre and the Fermi level. The d-band centre itself is determined by the number of occupied d orbitals and the d-band width, which is a function of coordination number, orbital size, and interatomic distance.<sup>31</sup>

The Hammer-N&oslash;rskov model uses the d-band energy to evaluate the reactivity of a catalyst surface. Metals with a low d-band energy bind most adsorbates more strongly than an equivalent site on a different metal with a higher energy.<sup>41</sup> A plot of d-band energy against catalytic activity would therefore produce a volcano plot in the same way as a plot of catalytic activity against &Delta;<i>E</i><sub>O</sub>. Alloying platinum with a 3d transition metal lowers the platinum d-band center, giving weaker adsorption of oxygen. This effect has been found to be greatest for early and smaller transition metals.<sup>42</sup> A number of other methods have also been suggested after study using DFT. Such as the dissociative binding energy of oxygen on the metal surface,<sup>43</sup> the M-OH bond strength,<sup>44</sup> and the alloy lattice parameter as a descriptor for oxygen reduction activity. <sup>45, 46</sup><br>
<br>

It has also been suggested that alloying can be exploited to reduce the impact of poisoning species on limiting the ORR, such as alloying Pt with Co or V to weaken the adsorption of the poisoning OH<sub>ads</sub> layer, making the catalyst more efficient.<sup>47-49</sup> Importantly, is has been show that the ORR followed the same mechanism despite the alloying.<sup>28, 50</sup> meaning that comparison of the alloys to pure platinum metal is appropriate. A further practical reason for alloying platinum with other metals is simply cost. A platinum nanoparticle with a core of a transition metal minimises the amount of platinum metal involved in catalyst. All platinum used is kept on the electrode surface, and so is in contact with the solution and therefore is catalytically active.<sup>51</sup><br>
<br>

It is of course worth noting that these theoretical calculations come with a number of limitations. Most of the calculations will assume a single crystal face, single metal atom, or small cluster of atoms for the substrate material, which is rarely representative of a real experimental system. Also, it has been reported that predicting the d-band for alloys is difficult, as it is hard to be sure of the extent of hybridisation and/or charge transfer between the orbitals of the differing neighbouring metals.<sup>52</sup> There is also the added complication of which metal the adsorbate may preferentially bind to in a bi-metallic system. This is often circumvented by assuming the co-alloyed metal is beneath the surface, and so only a single metal is involved in the adsorption. This seems appropriate, as it has been reported that for PtCo alloys, a place exchange occurs between Pt and Co.
This results in a Pt skin forming on top of a PtCo alloy sublayer.<sup>47</sup> The same group also  reported that, in the case of a Pt<sub>3</sub>Fe alloy, an annealed alloy with a significant Pt skin has significantly different electronic characteristics to an alloy with the same atomic ratio, but with the iron sputtered on the surface.<sup>53</sup> The calculations also assume a static metal lattice during the adsorption. This may not be appropriate, as it has recently been shown that platinum undergoes a significant lattice expansion during oxygen adsorption. This binding affects the electronic character surface by raising the d-band centre, stabilising the binding of adsorbates.<sup>54</sup>
<br>
</p>

Our Goals
==========

Goal 1 – Experimental calculation of oxygen binding energy
------------------------------------------------------------------------------

<p align= "justify">
Experimental correlations between adsorption and activity are few, with most predictive analysis coming purely from computation analysis. These studies are powerful but are limited by a number of assumptions that must be made in order to carry out calculations with available computational power. We aim to get around this by defining a purely experimental means of predicting the activity of a material towards the ORR.<br>
<br>
</p>

Goal 2 - Applications to hydrogen peroxide electrosynthesis
------------------------------------------------------------------------

<p align="justify">
So far, we have been focusing on the four-electron reduction of oxygen to water. However, a material that is proved unsuitable for favouring this full reduction may be suited to favour the two electron reduction of O<sub>2</sub> to H<sub>2</sub>O<sub>2</sub> in order to provide an electrosynthetic route to this useful chemical.
</p>


Part 1 - Experimental calculation of oxygen binding energy
=================================================

<p align="justify">
This work focuses on the phenomenon of the pre-adsorption of O<sub>2</sub> onto metal surfaces during electrochemical reduction. It is normally assumed that the adsorption of O<sub>2</sub> onto the catalyst surface occurs at a biased electrode before the first electron is transferred. However, we have been able to detect the presence of oxygen adsorbed onto an electrode even when it is not biased. This can be easily quantified by simply immersing an electrode into solution, allowing the O<sub>2</sub> to pre-adsorb, and then performing stripping voltammetry experiments to quantify.

<br>
<img align="center" src="/images/ORR/Fig 6.png"><br clear="all">
<br>
<i><b>Figure 5</b> a) Linear sweeps for the ORR at A 25 &mu;m diameter platinum electrode in 0.1 M KClO<sub>4</sub> recorded by sweeping from OCP to 0.0 V vs. RHE at 100 mV s<sup>-1</sup>, showing the current response in argon purged solution with the adsorbed oxygen layer (<i>I</i><sub>exp</sub>, black), the background current response recorded in argon purged solution after the pre-adsorbed oxygen layer had been consumed (<i>I</i><sub>b</sub>, red) and the result of the subtraction of the background from the experimental linear sweep, showing a peak due to the reduction of the pre-adsorbed oxygen layer (<i>I</i><sub>ads</sub>, blue). Background subtraction using deoxygenated solution shows that we are reducing pre-adsorbed O<sub>2</sub>, and not platinum oxide. b) Potential waveform used for recording the black linear sweep voltammogram for the reduction of pre-adsorbed oxygen. c) Potential waveform used for recording the red linear sweep voltammogram for the background processes.<sup>36</sup> </i><br>
<br>
After recording this pre-adsorbed O<sub>2</sub> at Pt electrodes, we were able to repeat these measurements with a number of different metals and metal alloys. This showed a sigmoidal relationship between the charge associated with the reduction of pre-adsorbed O<sub>2</sub> correlated and the binding energies for the from DFT calculations. This correlation allows for a simple electrochemical stripping experiment to be used to analyse materials for the ORR.<sup>55, 56</sup><br>
<br>
<img align="center" width="80%" src="/images/ORR/Fig 7.png"><br clear="all">
<br>
<i><b>Figure 6</b>: Kinetic current for the ORR at 0.45 V vs. RHE (<i>i</i><sub>k</sub>) against the theoretical binding energy for O (&Delta;<i>G</i><sub>O</sub>) and the charge from the reduction of pre-adsorbed oxygen (<i>Q</i>). The sigmoidal relationship between <i>i</i><sub>k</sub> and <i>Q</i> allows <i>Q</i> to be used as a descriptor for ORR activity.<sup>56</sup> </i><br>
<br>
</p>

Part 2 – Electrochemical synthesis of hydrogen peroxide
=================================================

<p align="justify">
One area of the ORR that has started to receive increased interest recently is the electrochemical synthesis of H<sub>2</sub>O<sub>2</sub>. Here, instead of looking for the best possible binding energy for the four-electron reduction of O<sub>2</sub>, we now look for materials that favour the two-electron reduction just to H<sub>2</sub>O<sub>2</sub>. In fact, researchers have found a similar volcano plot relating the binding energy of OH and OOH adsorbed intermediates with the activity towards H<sub>2</sub>O<sub>2</sub> electrosynthesis.<br> 
<br>
Since the reduction of O<sub>2</sub> is reversible, it is possible to electrochemically synthesise H<sub>2</sub>O<sub>2</sub> both by the two-electron reduction of O<sub>2</sub> and by the two-electron oxidation of H<sub>2</sub>O. A volcano type relationship between binding energy and activity is seen for both the oxidative and reductive routes, although the materials of preference are different for both routes; for the reductive routes PdAu alloys and N-doped carbons are best, for the oxidative routes BiVO<sub>4</sub> and WO<sub>3</sub> oxides perform best. 
<br>
<img align="center" width="80%" src="/images/ORR/Fig 8.png"><br clear="all">
<br>
<i><b>Figure 7</b>: Theoretical limiting potential (<i>U</i><sub>L</sub>) against Gibbs binding energies for *OOH (&Delta;<i>G</i><sub>HOO*</sub>) and *OH (&Delta;<i>G</i><sub>HO*</sub>), for H<sub>2</sub>O<sub>2</sub> electrosynthesis by oxygen reduction (green) and water oxidation (blue). <i>U</i><sub>L</sub> represents the smallest overpotential where both electron transfers are downhill in free energy. Materials are categorized as pure metals (grey), metal alloys (yellow), carbon based (black) and metal oxides (red). The dashed lines represent the theoretical volcano, where the peak gives the position of a theoretical optimum catalyst. Figure was drawn from data in refs 57 (square), 58 (circle), 59 (triangle) 60 (diamond) and 61 (pentagon). For many materials, the exact <i>U</i><sub>L</sub> depends on the surface site (step, edge, basal plane etc.) so the most favourable <i>U</i><sub>L</sub> is shown in each case. </i><br>
<br>
As with studies of the four-electron ORR, research into the two-electron route to H<sub>2</sub>O<sub>2</sub> focuses on moving materials towards the peak of the volcano in order to maximise selectivity towards the two-electron pathway over the full four-electron route. Another important consideration here is the rate of reaction. As the overpotential is increased, the reaction starts to favour further electron transfers, which reduces the overall yield of H<sub>2</sub>O<sub>2</sub>. This raises a problem when comparing the efficiency of materials, as most materials can be made to produce H<sub>2</sub>O<sub>2</sub> with high selectivity if a low enough overpotential is applied. However, these materials are quickly proved to be unsuitable as soon as the reaction rate is increased to industrially relevant operating conditions. This work will look to extend both the selectivity and the operating rate of reaction of our catalyst materials, in order to produce H<sub>2</sub>O<sub>2</sub> on an industrially viable scale.<br>


</p>

TL;DR
=======

<ul>
  <li><p align="justify">O<sub>2</sub> is highly surface dependent, and relies on the adsorption of O<sub>2</sub> onto the electrode before reduction can take place</p></li>
  <li><p align="justify">The strength of the bond between the metal and the oxygen is a useful descriptor for catalytic activity. This value can be calculated computationally, or approximated experimentally by quantifying the amount of oxygen that pre-adsorbs onto an unbiased electrode. </p></li>
  <li><p align="justify">Just as electrodes can be designed to favour four-electron reduction, tuning catalysts to different binding energies can be used to create other materials suitable for H<sub>2</sub>O<sub>2</sub> electrosynthesis.</p></li>
</ul>


Recommended Resources
======================

<ul>
  <li><p align="justify">S. Perry, <i>Transient Studies at Microelectrodes</i>, thesis submitted to University of Southampton. <a href="https://eprints.soton.ac.uk/387227/" target="_blank" >Direct Link</a></p></li>
  <li><p align="justify">S. C. Perry, D. Pangotra, L. Vieira, V. Sieber, L. Wang, C. Ponce de Leon, F. Walsh; <i>Nature Reviews Chemistry</i>, <b>3</b>, 442-458, (<b>2019</b>). <a href="https://www.nature.com/articles/s41570-019-0110-6(200107)1:2<105::AID-FUCE105>3.0.CO;2-9" target="_blank" >Direct Link</a></p></li>
  <li><p align="justify">N. M. Markovic, T. J. Schmidt, V. Stamenkovic, P. N. Ross; Oxygen Reduction Reaction on Pt and Pt Bimetallic Surfaces: A Selective Review; <i>Fuel Cells</i>, <b>1</b>, 105-116, (<b>2012</b>). <a href="https://doi.org/10.1002/1615-6854(200107)1:2<105::AID-FUCE105>3.0.CO;2-9" target="_blank" >Direct Link</a></p></li>
  <li><p align="justify">A. Bard and L. Faulkner, <i>Electrochemical Methods: Fundamentals and Applications</i>, John Wiley & Sons, NY. <a href="https://www.wiley.com/en-us/Electrochemical+Methods%3A+Fundamentals+and+Applications%2C+2nd+Edition-p-9780471043720" target="_blank" >Direct Link</a></p></li>
  <li><p align="justify">D. Pletcher, <i>A First Course in Electrode Processes</i>, Royal Society of Chemistry, Cambridge. <a href="https://pubs.rsc.org/en/content/ebook/978-1-84755-893-0" target="_blank" >Direct Link</a></p></li>
</ul>



References
===============

1.	Chen, S. and Kucernak, A., <i>J. Phys. Chem. B</i>, <b>108</b>, 3262-3276 (<b>2004</b>).
2.	Song, C. and Zhang, J., in <i>PEM Fuel Cell Electrocatalysts and Catalyst Layers: Fundamentals and Applications</i>, Zhang, J. Editor, p. 89-134, <i>Springer London</i>, (<b>2008</b>).
3.	Wroblowa, H. S., Yen Chi, P. and Razumney, G. <i>J. Electroanal. Chem.</i>, <b>69</b>, 195-201 (<b>1976</b>).
4.	Gara, M., et al. <i>Phys. Chem. Chem. Phys.</i>, <b>15</b>, 19487-19495 (<b>2013</b>).
5.	Noël, J.-M., Latus, A., Lagrost, C., Volanschi, E. and Hapiot, P., <i>J. Am. Chem. Soc.</i>, <b>134</b>, 2835-2841 (<b>2012</b>).
6.	Adžić, R. R., in <i>Electrocatalysis</i>, Lipkowski, J. and Ross, P. N. Editors, p. 197-242, <i>John Wiley & Sons, Ltd, New York, NY</i> (<b>1998</b>).
7.	Birkin, P. R., Elliott, J. M. and Watson, Y. E. <i>Chem. Commun.</i>, 1693-1694 (<b>2000</b>).
8.	Pletcher, D. and Sotiropoulos, S. <i>J. Electroanal. Chem.</i>, <b>356</b>, 109-119 (<b>1993</b>).
9.	Marković, N. M. and Ross, P. N., <i>Surf. Sci. Rep.</i>, <B>45</b>, 117-229 (<b>2002</b>).
10.	Keith, J. A. and Jacob, T., <i>Angew. Chem. Int. Ed.</i>, <b>49</b>, 9521-9525 (<b>2010</b>).
11.	Yeager, E., <i>J. Mol. Catal.</i>, <b>38</b>, 5-25 (<b>1986</b>).
12.	Griffith, J. S. <i>Proc. R. Soc. London. Ser. A.</i>, <b>235</b>, 23-36 (<b>1956</b>).
13.	Yeager, E., Razaq, M., Gervasio, D., Razaq, A. and Tryk, D., <i>Proc. Electrochem. Soc.</i>, <b>92</b>, 440-473 (<b>1993</b>).
14.	Gattrell, M. and MacDougall, B., in <i>Handbook of Fuel Cells</i>, W. Vielstich, A. Lamm, Gasteiger, H. A. and Yokokawa, H. Editors, p. 443-464, <i>John Wiley & Sons, New York, NY</i> (<b>2010</b>).
15.	Sidik, R. A. and Anderson, A. B. <i>J. Electroanal. Chem.</i>, <b>528</b>, 69-76 (<b>2002</b>).
16.	Pauling, L., <i>Nature</i>, <b>203</b>, 182-183 (<b>1964</b>).
17.	J. C. Amphlett, et al. <i>Am. Chem. Soc. Div. Fuel Chem.</i>, <b>38</b>, 1477-1482 (<b>1993</b>).
18.	Katsounaros, I., et al. <i>Phys. Chem. Chem. Phys.</i>, <b>15</b>, 8058-8068 (<b>2013</b>).
19.	Shinozaki, K., Zack, J. W., Richards, R. M., Pivovar, B. S. and Kocha, S. S., <i>J. Electrochem. Soc.</i>, <b>162</b>, F1144-F1158 (<b>2015</b>).
20.	Teliska, M., Murthi, V. S., Mukerjee, S. and Ramaker, D. E., <i>J. Phys. Chem. C</i>, <b>111</b>, 9267-9274 (<b>2007</b>).
21.	Ciapina, E. G., et al. <i>Electrochem. Commun.</i>, <b>60</b>, 30-33 (<b>2015</b>).
22.	Grgur, B. N., Marković, N. M. and Ross, P. N., <i>Can. J. Chem.</i>, <b>75</b>, 1465-1471 (<b>1997</b>).
23. Marković, N. M., Adžić, R. R., Cahan, B. D. and Yeager, E. B., <i>J. Electroanal. Chem.</i>, <b>377</b>, 249-259 (<b>1994</b>).
23.	Komanicky, V., Menzel, A. and You, H. <i>J. Phys. Chem. B</i>, <b>109</b>, 23550-23557 (<b>2005</b>).
24.	Attard, G. A. and Brew, A., <i>J. Electroanal. Chem.</i>, <b>747</b>, 123-129 (<b>2015</b>).
25.	Imaoka, T., Kitazawa, H., Chun, W.-J. and Yamamoto, K., <i>Angew. Chem. Int. Ed.</i>, <b>54</b>, 9810-9815 (<b>2015</b>).
26.	Gasteiger, H. A., Kocha, S. S., Sompalli, B. and Wagner, F. T., <i>App. Catal. B</i>, <b>56</b>, 9-35 (<b>2005</b>).
27.	Paulus, U. A., et al., <i>Electrochim. Acta</i>, <b>47</b>, 3787-3798 (<b>2002</b>).
28.	Sleightholme, A. E. S., Varcoe, J. R. and Kucernak, A. R. <i>Electrochem. Commun.</i>, <b>10</b>, 151-155 (<b>2008</b>).
29.	Fernández, J. L., Wijesinghe, M. and Zoski, C. G., <i>Anal. Chem.</i>, <b>87</b>, 1066-1074 (<b>2015</b>).
30.	Xin, H., Holewinski, A., Schweitzer, N., Nikolla, E. and Linic, S., <i>Top. Catal.</i>, <b>55</b>, 376-390 (<b>2012</b>).
31.	Lefèvre, M., Proietti, E., Jaouen, F. and Dodelet, J.-P., <i>Science</i>, 324, 71-74 (<b>2009</b>).
32.	Baez, V. B. and Pletcher, D., <i>J. Electroanal. Chem.</i>, <b>382</b>, 59-64 (<b>1995</b>).
33.	Masa, J., Xia, W., Muhler, M. and Schuhmann, W. <i>Angew. Chem. Int. Ed.</i>, <b>54</b>, 10102-10120 (<b>2015</b>).
34.	Zhang, H.-J., Li, H., Deng, C., Zhao, B. and Yang, J., <i>ECS Electrochem. Lett.</i>, <b>4</b>, H33-H37 (<b>2015</b>).
35.	Andoralov, V. M., Tarasevich, M. R. and Tripachev, O. V. <i>Russ. J. Electrochem.</i>, <b>47</b>, 1327-1336 (<b>2011</b>).
36. Perry, S. C., <i>Transient Studies at Microelectrodes</i>, Thesis submitted to University of Southampton, 26<sup> Jan 2016.
37.	Zurilla, R. W., Sen, R. K. and Yeager, E., <i>J. Electrochem. Soc.</i>, <b>125</b>, 1103-1109 (</b>1978</b>).
38.	Nørskov, J. K., et al. Origin of the Overpotential for Oxygen Reduction at a Fuel-Cell Cathode. <i>J. Phys. Chem. B</i>, <b>108</b>, 17886-17892 (<b>2004</b>).
39.	Jia, Q., et al. The Role of Ooh Binding Site and Pt Surface Structure on ORR Activities. <i>J. Electrochem. Soc.</i>, <b>161</b>, F1323-F1329 (<b>2014</b>).
40.	Hammer, B., <i>Top. Catal.</i>,<b>37</b>, 3-16 (<b>2006</b>).
41.	Kitchin, J. R., Nørskov, J. K., Barteau, M. A. and Chen, J. G. <i>J. Chem. Phys.</i>, <b>120</b>, 10240-10246 (<b>2004</b>).
42.	Lee, K. R., Jung, Y. and Woo, S. I., <i>ACS Comb. Sci.</i>, <b>14</b>, 10-16 (<b>2012</b>).
43.	Xin, H., Holewinski, A. and Linic, S. <i>ACS Catal.</i>, <b>2</b>, 12-16 (<b>2012</b>).
44.	Jalan, V. and Taylor, E. J., <i>J. Electrochem. Soc.</i>, <b>130</b>, 2299-2302 (<b>1983</b>).
45.	Mukerjee, S., Srinivasan, S., Soriaga, M. P. and McBreen, J., <i>J. Electrochem. Soc.</i>, <b>142</b>, 1409-1422 (<b>1995</b>).
46.	Stamenković, V., Schmidt, T. J., Ross, P. N. and Marković, N. M., <i>J. Phys. Chem. B</i>, <b>106</b>, 11970-11979 (<b>2002</b>).
47.	Spanos, I., Dideriksen, K., Kirkensgaard, J. J. K., Jelavic, S. and Arenz, M. <i>Phys. Chem. Chem. Phys.</i>, <b>17</b>, 28044-28053 (<b>2015</b>).
48.	Gentil, R. and Villullas, H. M., <i>J. Solid State Electrochem.</i>, <b>20</b>, 1119-1129 (<b>2016</b>).
49.	Marković, N. M., Schmidt, T. J., Stamenković, V. and Ross, P. N. <i>Fuel Cells</i>, <b>1</b>, 105-116 (<b>2001</b>).
50.	Scofield, M. E., Liu, H. and Wong, S. S. <i>Chem. Soc. Rev.</i>, <b>44</b>, 5836-5860 (<b>2015</b>).
51.	Xin, H., Schweitzer, N., Nikolla, E. and Linic, S., <i>J. Chem. Phys.</i>, <b>132</b>, 111101 (<b>2010</b>).
52.	Stamenkovic, V. R., et al., <i>Nat. Mater.</i>, <b>6</b>, 241 (<b>2007</b>).
53.	Erickson, E. M., et al. <i>Anal. Chem.</i>, <b>86</b>, 8368-8375 (<b>2014</b>).
54.	Perry, S. C. and Denuault, G., <i>Phys. Chem. Chem. Phys.</i>, <b>17</b>, 30005-30012 (<b>2015</b>).
55.	Perry, S. C. and Denuault, G., <i>Phys. Chem. Chem. Phys.</i>, <b>18</b>, 10218-10223 (<b>2016</b>).
56.	Shi, X., et al., <i>Nat. Commun.</i>, <b>8</b>, 701 (<b>2017</b>).
57.	Siahrostami, S., et al., <i>Nat. Mater.</i>, <b>12</b>, 1137 (<b>2013</b>).
58.	Chen, S., et al., <i>J. Am. Chem. Soc.</i>, <b>140</b>, 7851-7859 (<b>2018</b>).
59.	Lu, Z., et al., <i>Nat. Catal.</i>, <b>1</b>, 156-162 (<b>2018</b>).
60.	Viswanathan, V., Hansen, H. A. and Nørskov, J. K. <i>J. Phys. Chem. Lett.</i>, <b>6</b>, 4224-4228 (<b>2015</b>).

