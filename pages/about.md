---
layout: page
title: About
permalink: /about/
weight: 1
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
I started my career by earning a BSc in Electronics Engineering, designing and testing circuit boards and embedded firmware. This hardware-first approach gives me a critical perspective on resource-constrained computing, which is essential for modern AI.

I am currently pursuing my MSc in AI, specializing in **Reinforcement Learning** and **MLOps** for real-time applications.

<div class="row">
{% include about/skills.html title="Software Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Engineering Skills" source=site.data.engineering-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
  <div class="col-md-6">
    {% include about/timeline-work.html %}
  </div>
  <div class="col-md-6">
    {% include about/timeline-academic.html %}
  </div>
</div>
