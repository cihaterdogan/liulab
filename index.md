---
---

# Yunlong Liu Lab's Website

An engaging 1-3 sentence description of your lab.

{% include section.html %}

## Highlights

{% capture text %}

Welcome to Dr. Yunlong Liu’s laboratory in the Center for Computational Biology and Bioinformatics at Indiana University School of Medicine. Our team is dedicated to employing systems biology approaches to decipher the molecular mechanisms of gene regulation that play critical roles in complex diseases such as cancer, addiction, and neurodegenerative disorders. Specific research areas include developing and implementing cutting-edge experimental assays and innovative computational algorithms in understanding the functions of genetic variants in complex diseases, designing methodologies on analyzing multimodal high-dimensional data, and understanding regulatory mechanisms and translational impact of alternative splicing in cancer and other diseases. All these areas involve multi-disciplinary components, including functional genomics, genetics, computational and statistical modeling, computer science/engineering, and data management.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
