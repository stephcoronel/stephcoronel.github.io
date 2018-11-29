---
layout: page
title: "Research"
permalink: /research/
author_profile: true
---
<a name="top"></a>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include toc.html %}
{% include base_path %}

## Ignition

### Compression ignition

In a nuclear power plant, a reactive mixture of hydrogen-oxygen-steam can be generated within the piping system by either radiolysis or a severe accident that results in oxidation of the fuel and core material. Water-hammer events in piping systems with pockets of reactive gases trapped between liquid water may have caused explosions and damaged piping systems at two nuclear power plants in 2002.

![water](/MySite/assets/waterhammer.png){:width="250px" .center-image} 

Pressure surges and water-hammer type transients in two-phase flow of reactive mixtures have also been proposed as a cause of explosions within piping systems in chemical processing plants. With these motivations, we are studying through modeling and experiments the potential for ignition by water-hammer events in a water-filled piping system containing a gas volume composed of a hydrogen-oxygen mixture. The experiments indicate the presence of Rayleigh-Taylor and/or Richtmyer-Meshkov instabilities at the interface between the water and reactive gas.

![compression](/MySite/assets/compression.gif){:width="100px" .center-image} 

The instability of the water-gas interface under water-hammer (impulsive) loading results in the creation of a highly distorted interface and the dispersion of liquid water into the reactive gas. This has significant implications for inhibiting the ignition process and must be accounted for in any realistic evaluation of this hazard.

### Hot particle ignition
<a href="#top">Back to top</a>

Hot particle hazards are present in the transportation, industrial, nuclear, and mining sectors. Could these hazards lead to an accidental explosion?

![hazards](/MySite/assets/hazards.png){:width="250px" .center-image}

During my PhD, I experimentally and numerically studied ignition by moving hot surfaces. The fuel of interest was n-hexane (kerosene surrogate). I designed an experiment, shown below, that could heat small particles and then inject them into a flammable environment.

![vessel](/MySite/assets/experiment.png){:width="250px" .center-image}

Visualization of the ignition and flame propagation of n-hexane-air by moving hot particles is shown below; the first and second gifs correspond to no-ignition and ignition, respectively.

![gif1](/MySite/assets/hexane1.gif){:width="100px" .center-image} ![gif2](/MySite/assets/hexane22.gif){:width="100px" .center-image}

The effect of equivalence ratio on particle/flame interation for n-hexane-air is shown below.

![flames](/MySite/assets/flames.png){:width="400px" .center-image}

### Numerical hot surface ignition
<a href="#top">Back to top</a>

To understand the physical and chemical processes of a reactive gas adjacent to a hot surface, a simple 1D transient numerical simulation was performed. In the simulation, a wall is impulsive heated and subsequently there is growth of the thermal boundary until ignition takes place.

![hexane](/MySite/assets/hexane_air.png){:width="500px" .center-image}

Ignition takes place slightly away from the hot surface; at this location, chemical energy release is able to overcome heat losses to the wall and the temperature is sufficiently high to allow for chemical reactions to propagate.

![temperature](/MySite/assets/temperature_profiles.png){:width="500px" .center-image}

## Optical Diagnostics
### Interferometry and interferogram processing
<a href="#top">Back to top</a>

The following schematic describes the optical system, shearing interferometry, used to visualize ignition by moving hot particles and the subsequent flame propagation.

![interferometer](/MySite/assets/optical_setup.png){:width="500px" .center-image}

Converting raw interferograms to quantitative temperature fields requires substantial image post-processing. For the example shown below, the flow is axisymmetric, therefore, the inverse Abel transform can be used to convert the optical phase difference, Δφ to refractive index. Details on the methodology are found here.

![process](/MySite/assets/flowchart.png){:width="400px" .center-image}

The resulting experimental temperature field compared with a simulated temperature field is shown below.

![result](/MySite/assets/temperature.png){:width="250px" .center-image}

## Fuel Properties
### Flame characterization
<a href="#top">Back to top</a>

The hazard posed by an accidental explosion must be considered by assessing the flame properties, such as laminar burning speed, of the flammable mixtures of interest. In collaboration with Prof. Rémy Mével and Prof. Sally Bane, I have investigated the laminar burning speeds of n-hexane-air and hydrogen and nitrous oxide mixtures from spherically expanding flames.

![construction](/MySite/assets/construction.gif){:width="100px" .center-image}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
