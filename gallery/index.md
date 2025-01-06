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

## Talk

{% capture talk1 %}
<figure style="max-width: 500px; margin: auto;">
  <iframe
    src="//player.bilibili.com/player.html?isOutside=true&aid=113779236933601&bvid=BV1VurVYzEXZ&cid=27725007364&p=1"
    scrolling="no"
    frameborder="no"
    allowfullscreen="true"
    style="width: 100%; height: 300px;"
  ></iframe>
  <figcaption>Whole Body Control</figcaption>
</figure>
{% endcapture %}

{% capture talk2 %}
<figure style="max-width: 500px; margin: auto;">
  <iframe
    src="//player.bilibili.com/player.html?isOutside=true&aid=113779270486904&bvid=BV1EFrVY1EaH&cid=27725072288&p=1"
    scrolling="no"
    frameborder="no"
    allowfullscreen="true"
    style="width: 100%; height: 300px;"
  ></iframe>
  <figcaption>Long Context Transfer from Language to Vision</figcaption>
</figure>
{% endcapture %}

{% include cols.html col1=talk1 col2=talk2 %}