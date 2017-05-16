---
title: SOCIONICAL
---

SOCIONICAL was an [Information and Communication Technologies Project](http://cordis.europa.eu/fp7/ict/home_en.html) funded under European Union (EU) [Seventh Framework Programme (FP7)](http://cordis.europa.eu/fp7/) from 2009 to 2013, which aimed to develop Complexity Science based modelling, prediction and simulation methods for large scale socio-technical systems.  SOCIONICAL had 14 Partners in ten different countries.<!--break-->

SOCIONICAL focused on the specific example of Ambient Intelligence (AmI) based smart environments. A key component of such environments is the ability to monitor user actions and to adjust its configuration and functionality accordingly. Thus, the system reacts to human behaviour while at the same influencing it. This creates a feedback loop and leads to a tight entanglement between the human and the technical system. At the same time there is dynamic, heterogeneous human-human, human-technology, and technology-technology communication leading to ad-hoc coupling between components and different feedback loops. The project studied global properties and emergent phenomena that arise in AmI based socio-technical systems from such local feedback loops and their coupling on two concrete scenarios: transportation and emergency/disaster.

SOCIONICAL took a parallel, multi facetted research approach. Thus, it addressed analytical methods, complex networks based representations, and agent based models. The advances in modelling and prediction were be verified by large scale, distributed simulation driven by real life data.


### Publications and websites

* Mitleton-Kelly & Lukowicz, "**Introduction: The SOCIONICAL FP7 project and an outline of the volume**", book chapter in *Co-evolution of Intelligent Socio-technical Systems*, part of the series Understanding Complex Systems pp 3-18, April 2013, DOI:[10.1007/978-3-642-36614-7_1](http://dx.doi.org/10.1007/978-3-642-36614-7_1)
* The official [socionical.eu website](http://www.socionical.eu) went offline some time after October 2016.  However, [an archived version of the website is available](https://web.archive.org/web/20161008193003/www.socionical.eu).
* The EU's community research and development information service (CORDIS) has [a webpage on SOCIONICAL](http://cordis.europa.eu/project/rcn/89519_en.html).
* Newsletters:
  * [Socionical_Newsletter_Mar2012.pdf]($BUCKET/projects/socionical/Socionical_Newsletter_Mar2012.pdf)
  * [Socionical_Newsletter_Sep2011.pdf]($BUCKET/projects/socionical/Socionical_Newsletter_Sep2011.pdf)
* Policy briefs:
  * Oct 2011: [Communicating the nature of an emergency incident to passengers soon after it happens]($BUCKET/projects/socionical/Socionical_PB_EM_COM.pdf)
  * May 2010: [Improving traffic safety around a motorway accident site using Ambient Intelligence technologies]($BUCKET/projects/socionical/Socionical_PB_TR_SF.pdf)

### SOCIONICAL App

#### Vienna Marathon on 15 April 2012

A major trial of the Socionical app was conducted during the Vienna Marathon on 15 April 2012.

<iframe src="https://player.vimeo.com/video/40857398" width="740" height="555" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<p><a href="https://vimeo.com/40857398">Crowd Density during the Vienna City Marathon 2012 (Vienna, AT)</a> from <a href="https://vimeo.com/user9263714">Martin Wirz</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

This visualization shows the development of the crowd density during the Vienna City Marathon 2012. The "hotter" (i.e. black -> red -> yellow) regions are, the denser the crowd was at that location.

The data has been recorded by a smartphone application collecting live sensor data from users. It has been developed by the Tobias Franke of the [Embedded Intelligence Group, DFKI Kaiserslautern](http://www.dfki.de/web/forschung/ei) and the [Institute for Pervasive Computing, Linz](http://www.pervasive.jku.at).

The data is being collected in near real-time (delay ~ 1. min) directly from the mobile phones. This allows for an instantaneous heat map visualization. We used the CoenoSense platform ([Wirz et. al, 2012](http://dx.doi.org/10.1007/978-3-319-00395-5_46)) developed by Martin Wirz of the [ETH Zurich's Wearable Computing Lab](http://www.ife.ee.ethz.ch/research/wearable-and-mobile-computing-platforms.html) to collect and data and generate this visualization.

The overall system allows event organizers and emergency services to gain an almost-live insight into the crowd dynamics at large scale events.

The software has been developed as a part of the SOCIONICAL research project.

#### 2011 Lord Mayor's Show in London

Visualisation of the Lord Mayor's Show procession on 12 November 2012, using data from the  Socionical app (S-app). The app and visualisation were developed by Passau University and ETH Zurich and all arrangements for the trial of the S-app were made by LSE working with the Pageant Master, who organises the Show, and all the relevant emergency services.

<iframe src="https://player.vimeo.com/video/32171490" width="740" height="416" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<p><a href="https://vimeo.com/32171490">Crowd Density at the Lord Mayor&#039;s Show 2011 (London, UK)</a> from <a href="https://vimeo.com/user9291390">Tobias Franke</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

The visualization above shows the development of the crowd density during the 2011 Lord Mayor's Show in London. The "hotter" (i.e. red) the blobs are, the denser the crowd was at that location.

The data has been gathered by a smartphone application collecting live sensor data from users. It has been developed by Tobias Franke of the University of Passau's Embedded System Lab.
The heatmap and the corresponding visualization have been realized by Martin Wirtz of the ETH Zurich's Wearable Computing Lab.

Prof. Eve Mitleton-Kelly (director of the Complexity Group at the London School of Economics) was involved in the development as policy maker.

The overall system allows emergency services to gain an almost-live insight into the crowd density at large scale events. The software has been developed as a part of the Socionical research project.


## Related events

<div class="events-listing">
  <div class="events-listing-group">
    {% assign events = site.events | where:"project","SOCIONICAL" %}
    <ul class="events-listing-posts">
      {% for event in events %}
        {% include post-listing-entry.html post=event %}
      {% endfor %}
    </ul>
  </div>
</div>