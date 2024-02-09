---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Other research team members in the Liu Lab include Jill Reiter, PhD (Visiting Assistant Research Professor), Wenting Wu, PhD (Assistant Research Professor), Hongyu Gao, PhD (Assistant Scientist), Guanglong Jiang, PhD (Bioinformatics Analyst), Rudong Li, PhD (Post-doctoral Fellow), Andy B. Chen, PhD (Post-doctoral Fellow), Muyi Liu, PhD (Post-doctoral Fellow), Xiaona Chu (Research Analyst/Technician), Kerry Sanders (Research Analyst/Technician), Edward R. Simpson, Steven Chen, Duojiao Chen, and Chuanpeng Dong.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

{% include section.html %}

{% include grid.html style="square" content=content %}
