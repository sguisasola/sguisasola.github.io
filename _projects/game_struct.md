---
layout: page
title: combinatorial structure of games
description: from individual preferences to externalities
img: assets/img/games.png
importance: 2
category: work
giscus_comments: false
---

The bulk of my theoretical research is in structural game theory, which builds on previous work by Donald G. Saari and Daniel T. Jessie (see <a href="https://link.springer.com/book/10.1007/978-3-030-35847-1"> their book </a> here) and which is developed in collaboration with Saari. The motivation has been to model creativity, collaboration, and coordination in multi-agent systems. The work also stems from the <a href="../network_improv">networked improvisations</a>, which have shown that two critical components in an analysis of group creativity are: (1) the topology of the creativity network, and (2) whether different participants accept or reject the leads put forth by others as improvements. So far, the results of this work elucidate how to begin modeling such systems in the 2-strategy case for any number of agents and in the 2-agent and 3-strategy case.

The full details and derivation can be found in Ch.2 of my <a href="../../publications">PhD dissertation</a>. In summary, an agent's utility function in the 2-strategy case for any $$n$$ number of agents is given below (note that the agent is chosen to be agent 1 to simplify the summation indices and each $$t_i$$ denotes agent $$i$$'s strategy, either $$+1$$ or $$-1$$).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/utility.png" title="utility function" class="img-fluid rounded z-depth-0" %}
    </div>
</div>

The utility function above is in decomposed form: $$\pi^N$$, $$\pi^B$$, and $$\pi^K$$ denote the *Nash*, the *Behavioral*, and the *Kernel* components of the decomposition, respectively.

As mentioned, this work builds on a previous fundamental decomposition developed by Saari and Jessie. As such, the  orthogonal properties of the original decomposition are preserved: all information required to calculate Nash equilibria (and related solution concepts) is contained in the *Nash* component, the *Kernel* component is simply a scaling constant, and the remaining *Behavioral* component, while containing no *Nash* information, contains important contributions to the game's payoff structure.

Upon inspection of the components, one sees that, in all, each coefficient (be it $$\xi$$, $$\zeta$$, or $$\kappa$$) arises from a combination of agents, where the entire utility function is built using *all* combinations of agents. In fact, the *Nash* terms are built using combinations of agents that include the original agent in question, while the *Behavioral* terms are built using combinations of agents that exclude the original agent in question. The *Kernel* term is simply the empty combination. This shows that *Behavioral* terms can be interpreted to be *externalities*, since the payoff contributions for these terms depend on the strategies chosen by the *other* agents.

I will be giving a talk on these results in the upcoming <a href="https://meetings.ams.org/math/jmm2024/meetingapp.cgi/Paper/32892">Joint Mathematics Meetings 2024</a>.