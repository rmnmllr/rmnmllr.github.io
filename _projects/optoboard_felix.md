---
layout: page
title: Optoboard Software
description: 
img: assets/img/fig_gui_v1_1_preview.jpg
importance: 1
category: work
related_publications: false
---

This project is a part of the [Optoboard System project](/projects/optoboard_system) but became big enough to showcase it in its own project.

The aggregation in the ITk Pixel Detector data transmission chain is performed by the low-power Gigabit Transceiver (lpGBT) chip, which is controllable through the I2C protocol [[1](https://community.nxp.com/t5/MQX-Software-Solutions-Knowledge/Introduction-to-I2C-Interface/ta-p/1120762)] or optical link.
The main, primary lpGBT chip has I2C controllers on it to further control secondary chips.

At early design stages no software was available to enable users to carry out configuration for hundreds of chip registers and perform testing routines for commissioning of the data transmission chain.
There only existed a terminal based interface for the optical link which could only be scripted through $$\texttt{BASH}$$.
I therefore designed and developed the software (including a GUI) named $$\texttt{optoboard_felix}$$ from the ground up in $$\texttt{Python}$$ with a long term solution in mind.

<div class="row justify-content-sm-center">
    <div class="col-sm-9 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/fig_gui_v1_1.jpg" title="GUI Screenshot" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A screenshot of an early version GUI from `optoboard_felix`.
</div>

At first $$\texttt{optoboard_felix}$$ utilised subprocesses to interact with the terminal interface but later we switched to much faster $$\texttt{C++}$$ libraries that accessed the read-out FPGA cards [[2](https://atlas-project-felix.web.cern.ch/atlas-project-felix/)] (where the optical transmitters are hosted) directly.
The software features control and configuration routines as well as statistical analysis of tests such as common data transmission tests like bit-error-rate limits.

Over several years the software was used both in our institute as well as at several other universities.
Its backend is now part of the online software $$\texttt{DeMi}$$ [[3](https://demi.docs.cern.ch/)] for the detector's system tests, integration and operation.

$$\texttt{optoboard_felix}$$ can be found in the public repository [on GitLab](https://gitlab.cern.ch/bat/optoboard_felix/).