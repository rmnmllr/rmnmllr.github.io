---
layout: page
title: Optoboard System
description: 
img: assets/img/optobox-open-full-vtrx-powerbox_preview.jpeg
importance: 1
category: work
related_publications: false
---

The Optoboard System is the optical-electrical conversion system dedicated to the readout of the ATLAS [[1](https://doi.org/10.1088/1748-0221/3/08/S08003)] Inner Tracker (ITk) Pixel detector [[2](https://cds.cern.ch/record/2285585)] intended for the High Luminosity LHC (HL-LHC) [[3](https://e-publishing.cern.ch/index.php/CYRM/issue/view/127), [4](https://www.worldscientific.com/doi/abs/10.1142/9581)] era.
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
The number of Optoboards depends on the number of data links coming from a particular sub-detector of the ITk Pixel detector.

<div class="row justify-content-sm-center">
    <div class="col-sm-9 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/optobox-open-full-vtrx-powerbox.jpeg" title="Optobox" class="img-fluid rounded z-depth-1" %}
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

## My involvement

I actively developed the design, testing and commissioning of the Optoboard and the powering- and monitoring distribution system, including mechanical services, up until pre-production.
This includes a detailed characterisation of radiation-hard buck point-of-load power
converters and possible cooling strategies.
I have gained fundamental knowledge of operation, calibration and tuning of silicon pixel detectors for the commissioning and validation of the Optoboard System.
Furthermore, I built a documentation website and created a highly active support channel with more
than 50 users for the distributed Optoboards at various international detector test sites for streamlined,
efficient collaboration.

The aggregation in the ITk Pixel Detector data transmission chain is performed by the low-power Gigabit
Transceiver (lpGBT) chip, controllable through a two wire bus (I2C) or optical link.
I designed and developed the Python control and testing software (including a GUI) optoboard felix to enable users
to carry out fast configuration for hundreds of registers and perform testing routines, such as jitter and bit error rate
tests, for commissioning of data transmission chains.