---
title: Home
---

# Genome Data Science Lab

{:.center}

{% include section.html full=true %}

{% include banner.html image="images/banner.jpg" %}

{% include section.html %}

# Highlights

{% capture text %}
We are looking at fundamental biological and medical problems through the lens of data science, machine learning and mathematical modelling. Gene and protein expression regulation, metabolism and protein engineering are what keep us out of bed in the morning.

{%
  include link.html
  link="research"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/ds.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Our motto is reproducible science, see our work and tools.

{%
  include link.html
  link="tools"
  text="Browse our tools"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/source_code.jpg"
  link="resources"
  title="Our Tools"
  flip=true
  text=text
%}

{% capture text %}

We are an interdisciplinary team working collaboratively on computational and experimental problems. We are highly engaged in collaborative work and believe in 1+1=5. 

{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/group_2021.png"
  link="team"
  title="Our Team"
  text=text
%}
