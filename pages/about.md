---
layout: page
title: About
permalink: /about/
weight: 1
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>

I started my academic journey with a **dual Bachelor's degree in Industrial Electronics and Automation + Computer Engineering** at the **University of Deusto** in Bilbao, Spain, and I am currently pursuing an **MSc in Artificial Intelligence & Engineering Systems** at the **Eindhoven University of Technology**, in the Netherlands.  

All my professional experience has been carried out alongside my studies, and I am deeply grateful for the opportunities I’ve had to work on impactful projects and internships. These experiences have shaped my curiosity and drive to grow in diverse branches of engineering, as well as continuing to learn about AI.  

What truly excites me is the **application of emerging technologies in industrial and real-world environments**, and I hope to contribute to meaningful change by being at the forefront of this wave of innovation. Topics such as Edge AI, Industrial Automation, Robotics, Embedded Systems, and even some of their use cases in sectors as distant as medicine and finance are of particular interest to me.

I am a naturally **curious** person with interests of all kinds, and I enjoy exploring new ideas and learning continuously. Outside of work and study, I love **sports** such as basketball and tennis, traveling, exploring different cultures, and expanding my knowledge of **history and geography**, always trying to understand the world a little better.  

If you happen to like this page and want to connect, feel free to reach out! I’d be happy to chat about any projects or ideas :) 

<div class="row">
{% include about/skills.html title="Software Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Engineering Skills" source=site.data.engineering-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

{% include about/skills.html title="Language Skills" source=site.data.language-skills %}

<div class="row">
  <div class="col-lg-6 col-md-12 mb-4">
    {% include timeline-work.html %}
  </div>
  <div class="col-lg-6 col-md-12 mb-4">
    {% include timeline-academic.html %}
  </div>
</div>
