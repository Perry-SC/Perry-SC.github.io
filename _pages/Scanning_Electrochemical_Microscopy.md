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

# Overview

Scanning electrochemical microscopy (SECM) is an electrochemical microprobe technique with a wide variety of uses. The core concept is to take an electrode with a very small tip (thinner than a human hair) and moving it over a surface that you're interested in. The current measured at the tip of the electrode can tell you about the size, texture and reactivity of the surface. This gives us some really high precision data, where the resolution is defined by the size of the electrode tip - if we want more detail we just use a smaller tip! 

Simple experiments involve moving the electrode in a straight line over the surface that we are interested in. The graph we get then gives peaks and troughs that tell us a lot about that surface. 

<img src="/images/SECM/Fig 5.gif" width="100%">
<figcaption>Figure 1. Schematic diagram showing the scanning mode of SECM. Left) Schematic microelectrode sweeping over a substrate with electrically insulating and conducting regions. As the electrode moves over a conductive area, the tip detects an increase in the current. B) SECM current sweep over a conductive site on an insulating substrate. As the tip moves over the conductive site, the current increases, then decreases once the substrate is insulating once more. Full details of how this works can be found <a href="/Research/Scanning_Electrochemical_Microscopy_full">here</a>.</figcaption>

If we want to make things more intersting, we can perform multiple scans over the same surface, convert our currents into a colour map, and build up an image or our surface. Different colours can correspond to different height or reactivity depending on our interests. This same technique can also be done to detect the emission of interesting species from an object, which has been achieved to detect the release of certain chemicals from live cell samples. The size of the signal is proportional to the amount of that species released, so we can simultaneously get location and concentration information as we record.

<img src="/images/SECM/hot-spot.png" width="50%">
<figcaption>Figure 2. SECM image recorded by sweeping over an active surface. The reactive spot shows up as a bright red area on an unreactive blue background.</figcaption>

# The Problem

The signal at the tip of our electrode is defined by both the distance between the ti and the surface, and also by the reactivity of that surface. The means if we have a rough and reactive surface it can challenging to tell the difference between which signal is a texture peak, and which is a reactivity peak. 

Another challenge is that SECM relies on reactions happening at the electrode surface. But what if we want to try to detect something interesting that doesn't react at our electrode? We can also have problems when there are too many active species in solution; imagine that we want to detect one single species during our scan, but there are ten species reacting at the electrode surface. We need to design an electrode that only gives a signal when the right species is detected.

# Our research

There are a number of excellent theoretical models out there that have been developed to try to tell the difference between a texture signal and a reactivity signal. We have been working on a way to tell the difference by carefully changing our experimental conditions, so that we can separately record one image for the surface, then a second image to look at the reactivity. Every experimental system requires different conditions, which takes a lot of work, but it's well worth it to get the high precision data out at the end! We have employed this technique to probe the surface of steel when it is rusting in water. We found areas of high conductivity in the steel surface, and were able to show that these points were the initation sites where rust would begin in an otherwise protected surface. 

The detection of non-reactive species is a more challenging field, and requires careful modifications of the electrode tip surface. There are a number of different paths we can take here. One option is to add a "size-exclusion layer". This works like a seive at the electrode surface, so small species can pass through to be detected, but larger species are kept away. Another option is to take advantage of biological systems that can detect things that electrochemistry cannot.  We have done this for D-serine detection (an important chemical in the brain). It is difficult to detect this electrochemically, but we can attach an enzyme that reacts with D-serine to our tip surface, then use the electrode to monitor the enzyme activity to find where the D-serine is, and how much is around.

If you're interested in a more detailed overview of this research area you can check it out [here](/Research/Scanning_Electrochemical_Microscopy_full). You can also find a section specifically about applications of enzymes in electrochemical sensors [here](/Research/Electrochemical_Sensing).

You can also see some of the individual projects from this area that we have recently published in the areas of [increasing SECM sensitivity]({% post_url 2018-07-27-biosensor-paper %}), [using enzymes with SECM]({% post_url 2017-01-30-Biosensor-paper %}) and [showing localised steel corrosion]({% post_url 2018-02-14-Corrosion-paper %}).

Recommended Resources
======================

- A. Bard and M. Mirkin, <i>Scanning Electrochemical Microscopy</i> Taylor & Francis. (<b>2012</b>) <a href="https://www.crcpress.com/Scanning-Electrochemical-Microscopy/Bard-Mirkin/p/book/9781439831120" target="_blank" >Direct Link</a>
- Polcari, D., Dauphin-Ducharme, P. and Mauzeroll, J. Scanning Electrochemical Microscopy: A Comprehensive Review of Experimental Parameters from 1989 to 2015. <i>Chem. Rev.</i>, <b>116</b>, 13234-13278 (<b>2016</b>). <a href=" https://pubs.acs.org/doi/10.1021/acs.chemrev.6b00067" target="_blank" >Direct Link</a>
- Zoski, C. G. Review—Advances in Scanning Electrochemical Microscopy (SECM). <i>J. Electrochem. Soc.</i>, <b>163</b>, H3088-H3100 (<b>2016</b>). <a href=" http://jes.ecsdl.org/content/163/4/H3088.abstract" target="_blank" >Direct Link</a>
- Payne, N. A., Stephens, L. I. and Mauzeroll, J. The Application of Scanning Electrochemical Microscopy to Corrosion Research. <i>Corrosion</i>, <b>73</b>, 759-780 (<b>2017</b>). <a href="https://pubs.rsc.org/en/content/ebook/978-1-84755-893-0" target="_blank" >Direct Link</a>