---
layout: page
title: Optoboard System of the ATLAS ITk Pixel Detector
description: 
img: assets/img/optobox-open-full-vtrx-powerbox.jpg
importance: 1
category: work
related_publications: false
---

The Optoboard System is the optical-electrical conversion system dedicated to the readout of the ATLAS Inner Tracker (ITk) Pixel detector intended for the High Luminosity LHC (HL-LHC) era.
This pivotal component of the ITk Pixel detector data transmission chain contains at its heart a PCB, the Optoboard, that hosts a series of ASICs intended to aggregate electrical data links and subsequently convert them to optical signals for transmission to the ATLAS counting rooms via fibre optical cables.
<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/optoboard.jpg" title="Optoboard front" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/optoboard_back.jpg" title="Optoboard back" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Photos of the Optoboard's front and back.
</div>
The second function operates in the reverse sense where optical signals are converted to electrical links and disseminated to the modules providing clock and command signals.

The Optoboards are hosted in a mechanical structure known as an Optobox, up to eight Optoboards may reside inside an Optobox.
The number of Optoboards depends on the number of data links coming from a particular sub-detector of the ITk Pixel.

<div class="row justify-content-sm-center">
    <div class="col-sm-9 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/optobox-open-full-vtrx-powerbox.jpg" title="Optobox" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An open Optobox with 8 Optoboards inside.
</div>

The Optoboxes are then housed in a mechanical structure known as Optopanel.
Inside an Optopanel there are 28 Optoboxes and there are four Optopanels at each end of the ATLAS ITk Pixel detector.

<div class="row justify-content-sm-center">
    <div class="col-sm-7 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/optopanel_side.jpg" title="Optopanel rendering" class="img-fluid rounded" %}
    </div>
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/optopanel_locations.jpg" title="Optopanel locations" class="img-fluid rounded" %}
    </div>
</div>
<div class="caption">
    Rendering of the Optopanel and its multiple locations (yellow) on the ATLAS detector.
</div>
