---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
a Ph.D. student in Earth Science and Engineering (ErSE) program at KAUST. My research focus includes seismic processing, deep learning, and seismic inverse problems. I am keen on developing my skills on programming and deep learning tools such as Python, PyTorch, Tensorflow, etc. Feel free to contact me to discuss about collaboration or job opportunities!

<div class="row">
{% include about/skills.html title="Tech Stack" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
<h2 class="mb-3">Experience</h2>
{% include about/timeline.html %}
</div>

<div class="row">
<h2 class="mb-3">Education</h2>
{% include about/education.html %}
</div>