---
layout: page
title: "Presentations"
permalink: /presentations
author_profile: true
---
<a name="top"></a>
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

## Invited Talks

<div class="message">
  “Compression of reactive gas pocket in a water-filled pipe.” Women in Aerospace Symposium, <em>Stanford University</em>, 31 May − 1 June 2018.
</div>

<div class="message">
  “Thermal Ignition of Gaseous Mixtures: Experiments and Simplified Modeling.” Invited Seminar, Department of Mechanical and Aerospace Engineering, <em>University of California, San Diego</em>, 26 February 2018.
</div>

<div class="message">
 “Thermal Ignition of Gaseous Mixtures: Experiments and Simplified Modeling.” Fluids Seminar, Department of Mechanical Engineering, <em>University of California, Berkeley</em>, 22 February 2018.
</div>

<div class="message">
  “Compression Ignition of Reactive Gas Pocket in Water-Filled Pipe.”  Fluid Mechanics Research Conference, <em>California Institute of Technology</em>, 6 February 2018.
</div>

<div class="message">
  “Thermal Ignition of Gaseous Mixtures: Experiments and Simplified Modeling.” AME Seminar, Department of Aerospace and Mechanical Engineering, <em>University of Southern California</em>, 24 January 2018.
</div>

<div class="message">
  “Quantitative imaging of ignition of gaseous mixtures.” Invited Seminar, Department of Mechanical Engineering, <em>University of Rochester</em>, 15 December 2017.
</div>

<div class="message">
  “Thermal ignition by moving hot particles.” Invited Seminar, <em>Sandia National Laboratories</em>,  Albuquerque, 19 September 2017.
</div>

<div class="message">
  “Thermal ignition by moving hot particles.” Invited Seminar, <em>University of Tennessee Space Institute</em>, Tullahoma, 14 July 2017.
</div>

<div class="message">
  “Thermal ignition by moving hot particles.” Invited Seminar, <em>Sandia National Laboratories</em>,  Livermore, 20 February 2017.
</div>

<div class="message">
  “Thermal ignition by moving hot particles.” Invited Seminar, <em>Air Force Research Laboratory</em>,  Edwards AFB, 26 May 2016.
</div>

<div class="message">
  “Thermal ignition by moving hot particles.” Thermo/Fluids Research Seminar, Mechanical and Aerospace Engineering Department, <em>University of California, Los Angeles</em>, 13 May 2016.
</div>

<div class="message">
  “Ignition of <em>n</em>-hexane-air by moving hot particles: mechanism and effect of particle diameter.”  Fluid Mechanics Research Conference, <em>California Institute of Technology</em>, 15 July 2015.
</div>

<div class="message">
  “Ignition of <em>n</em>-hexane-air mixtures by moving hot spheres.”  Fluid Mechanics Research Conference, <em>California Institute of Technology</em>, 28 January 2014.
</div>

<div class="message">
  “Assessing the risk of accidental explosions in aircraft by heated particles.” Women in Aerospace Symposium, <em>Massachusetts Institute of Technology</em> 18-19 April 2013.
</div>

<div class="message">
  “Ignition of nitrogen diluted hexane-oxygen mixtures by moving heated particles.” Fluid Mechanics Research Conference, <em>California Institute of Technology</em>, 19 February 2013.
</div>

<div class="message">
  “Statistical analysis of spark ignition of lean H2-N2O mixtures.” Fluid Mechanics Research Conference, <em>California Institute of Technology</em>, 10 January 2012.
</div>

<a href="#top">Back to top</a>
{% for post in site.presentations reversed %}
  {% include archive-single.html %}
{% endfor %}
