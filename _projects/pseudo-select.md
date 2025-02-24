---
layout: page
title: Pseudo Random Pair Matching
description: 
img: assets/img/pseudo-select_title_preview.png
importance: 1
category: fun
related_publications: false
---

This is a fun little project I did for a school at which my partner is teaching.
The goal was to match pairs of school classes in a pseudo random process.
The pairs were determined by the teachers but should appear random for the students.

So I created a script for an interactive grid-based pair matching game with a visually engaging blinking effect in the web browser.
It initializes a 5x5 grid with predefined strings in each field.
Users start the game by clicking a button, triggering random blinking across the fields and at the end the script selects and highlights predefined pairs, ensuring no pair is repeated.

A live version of the script can be found [here](https://muellerr.web.cern.ch/blink/) or an example in the GIF below.

<div class="row justify-content-sm-center">
    <div class="col-sm-9 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/pseudo-select.gif" title="Pseudo select gif" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An example GIF of the matching showing class names of a public school.
</div>

This script demonstrates proficiency in $$\texttt{JavaScript}$$, $$\texttt{HTML}$$ and $$\texttt{CSS}$$, showcasing the ability to create interactive and visually engaging web applications.
The students were very excited by the "random" selection process and did not notice the predefined pairs.