---
layout: page
title: Physics Data Analysis
description: 
img: assets/img/fig_U_1_feynman_diagram_drell-yan.png
importance: 1
category: work
related_publications: false
---

The longer title of my analysis project is:
Search for third generation leptoquarks in $$pp \to \tau\tau$$ final states.

While an extensive description of the underlying motivation and theory behind the search can be found in my thesis, Ch.1 and 3 [[1](https://doi.org/10.48549/4717)], the following shall give a quick introduction to also non-physicists:

What is labelled as "search" is predominantly a Standard Model [[2](https://en.wikipedia.org/wiki/Standard_Model)] measurement of the fiducial differential cross section of two leptons (a family of elementary particles that also includes the electron) with at least one $$\tau$$-lepton.
A theorised third generation leptoquark could negatively interfere with Standard Model $$\tau\tau$$ final states through the high mass tail of the $$bb \to \tau\tau$$ process as postulated by effective field theories:

<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-5 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/fig_U_1_feynman_diagrams.png" title="U1 Feynman diagrams" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The Feynman diagrams describing the generation and resonance with leptoquarks, denoted as U1.
    A possible interference signal is the right-most diagram, with two taus in the final state.
    The *b* and anti-*b* quarks are coming from the energy of proton proton collisions inside the ATLAS detector.
</div>

In simplified term "*negatively* interfere" means that less $$\tau$$ leptons appeared (e.g. are counted) in the dataset as was expected from the Standard Model prediction.

There is a lot going into simply counting particles that would be beyond the scope of this project description.
All details of the full analysis are in Ch. 3 of [[1](https://doi.org/10.48549/4717)] and the paper is sheduled for publication in 2025.

## My involvement

I developed a $$\texttt{Python}$$ framework for fitting the maximum likelihood estimator of the leptoquark signal strength with the statistical framework $$\texttt{cabinetry}$$ [[3](https://github.com/scikit-hep/cabinetry)] and determining the sensitivity to leptoquarks in absence of unblinded data.
I carried out my work during 2022-2023 and the fitting framework is still (with some modifications of course) used today.

My contribution had a direct input to the background event generation, so events without leptoquark interference, and application of the kinematic cuts of possible signal events.
The framework also provided a way to efficiently produce statistical results and provide them to the analysis group for rapid development of the analysis strategy.
