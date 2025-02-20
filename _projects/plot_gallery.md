---
layout: page
title: Plot gallery
description: 
img: 
importance: 2
category: work
related_publications: false
---

I made this project because I got annoyed from sharing many data analysis results (plots, diagrams etc.) in person-to-person chats.
After a while most plots get lost in the chat window and one has to tidously search for them again.

I therefore had the idea of creating a small web-based PHP/Javascript script that scans directories for image formats (PNG, JPG, GIF etc.) and displays them in a gallery.
The gallery is interactive meaning the images can be enlarged for better inspection and one can download the image in the format they prefer.
There is also a small navigation to browse through the different directories.
Also a button is implemented to show all images in all sub-directories of the selected directory.

<div class="row justify-content-sm-center">
    <div class="col-sm-9 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/plot_gallery_example1.png" title="Plot gallery screenshot" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A screenshot of the plot gallery in action. These are silicon carbide results hosted on my CERN website.
</div>

This enormously simplified the exchange of results where 100s of plots are generated; I can link to one and the interested reader can also inspect different plots (for example correlations, log axis and so on) if wanted without me resending the plots.