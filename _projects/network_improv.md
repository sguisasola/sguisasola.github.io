---
layout: page
title: networked improvisation
description: who hears whom?
img: assets/img/networkimprov.png
importance: 1
category: work
related_publications: 
---

I organized collective improvisations with four graduate students in the University of California, Irvine’s program in Integrated Composition, Improvisation, and Technology. The four musicians, at the time of the experiments, had experience improvising together for two years. There were two guitarists, a saxophonist, and a violinist.

Each musician could hear the others only through headphones and I could control who heard whom. In other words, I
governed the “creativity networks.” During the sessions, the musicians knew there were networks,
but were unaware of the underlying topologies; they knew who they heard but not who heard them.

<div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/session1.png" title="Session 1" class="img-fluid rounded z-depth-0" %}
        <div class="caption">
            Session 1
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/session2.png" title="Session2" class="img-fluid rounded z-depth-0" %}
        <div class="caption">
            Session 2
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/session3.png" title="Session3" class="img-fluid rounded z-depth-0" %}
        <div class="caption">
            Session 3
        </div>
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/session4.png" title="Session4" class="img-fluid rounded z-depth-0" %}
        <div class="caption">
            Session 4
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/session5.png" title="Session5" class="img-fluid rounded z-depth-0" %}
        <div class="caption">
            Session 5
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/session6.png" title="Session6" class="img-fluid rounded z-depth-0" %}
        <div class="caption">
            Session 6
        </div>
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/session7.png" title="Session7" class="img-fluid rounded z-depth-0" %}
        <div class="caption">
            Session 7
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/session8.png" title="Session8" class="img-fluid rounded z-depth-0" %}
        <div class="caption">
            Session 8
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/session9.png" title="Session9" class="img-fluid rounded z-depth-0" %}
        <div class="caption">
            Session 9
        </div>
    </div>
</div>
<div class="caption">
    The nine improvisation sessions.
</div>
 </div>   
  
I am currently collaborating with the <a href="https://marghetislab.github.io/">Marghetis Lab</a> at the <a href="https://www.ucmerced.edu">University of California, Merced</a> to analyze the audio data from the improvisations and to look for patterns in coordination across the network topologies. 

For instance, the R Shiny app below shows the correlations between pairs of tracks. The x-axis is track number and the facets (0, 1, and 2) show the connection between the pair of tracks (0 = no connection, 1 = just one person hears the other, 2 = they hear each other). The regression tests the effect of connections and track on the correlations for "step sizes" and "turn angles" (which come from a 20-D representation of the audio tracks). 

<iframe height="400" width="100%" frameborder="no" src="https://l3nx8g-santiago-guisasola.shinyapps.io/network_improv/"> </iframe>

Stay tuned for more!