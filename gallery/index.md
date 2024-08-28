---
title: Gallery
nav:
  order: 3
  tooltip: Activities and more
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}Gallery

## TongPlan

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/research.jpg"
  caption="Research"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/team.jpg"
  caption="Team"
%}

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/gallery/1.jpg"
  caption="Team"
%}

{% endcapture %}

{% include cols.html col1=col3 col2=col1 col3=col2%}

## Activities

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/gallery/2.jpg"
  caption="Research"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/gallery/3.jpg"
  caption="Team"
%}

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/gallery/4.jpg"
  caption="Team"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3%}
