---
---

Welcome to the home page for the lab of Andrew Su. Our group works in the field of bioinformatics, both developing and applying computational tools for biomedical discovery. We have a particular emphasis on open source, open data, and open science. We are located at [Scripps Research](https://scripps.edu) in sunny La Jolla, California. 


{% include section.html %}

{% capture text %}

We are interested in how to efficiently manage and mine biomedical knowledge, and we are also interested in applying bioinformatics tools to identify testable new hypotheses.

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
  flip=false
  style="bare"
  text=text
%}

{% capture text %}

A great way to learn about our work is to see what we've published.  Browse or search our full list of publications here.

{%
  include button.html
  link="pubs"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="pubs"
  title="Our Publications"
  flip=true
  text=text
%}

{% capture text %}

Our team is made up of graduate students, postdoctoral researchers, programmers and staff, and we come from backgrounds ranging from experimental biology to computer science to bioinformatics. Meet the team!

{%
  include button.html
  link="team"
  text="Meet the team"
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