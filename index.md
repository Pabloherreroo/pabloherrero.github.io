---
layout: default
title: Home
---

# Welcome 👋

Hi! I’m **Pablo Herrero Ortiz** — an engineer passionate about **Reinforcement Learning, AI for Robotics, and Embedded Systems**.

This digital portfolio showcases my:

- Projects
- Experience timeline
- Education
- Technical background

👉 You can learn more **[About Me](/about/)** or explore some of my **recent work** below.

---

## Featured Projects

{% for project in site.data.projects limit:3 %}

### 🔧 {{ project.title }}

{{ project.desc }}

📅 **{{ project.date }}**  
🛠️ **Tools:** {{ project.tools | join: ", " }}

{% if project.repo %}
🔗 **Repository:** [View on GitHub](https://github.com/{{ project.repo }})
{% endif %}

---

{% endfor %}

---

## Contact

💼 **LinkedIn:**  
[linkedin.com/in/pabloherreroortiz](https://linkedin.com/in/pabloherreroortiz)

💻 **GitHub:**  
[github.com/pabloherreroo](https://github.com/pabloherreroo)

📫 **Email:**  
pablo.herrort@gmail.com
