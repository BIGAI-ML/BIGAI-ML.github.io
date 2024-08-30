---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}

# Full time

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: Researcher" %}
{% include list.html data="members" component="portrait" filters="role: Engineer" %}

{% include section.html background="images/background.jpg" dark=true %}

# Intern

{% include section.html %}

{% capture content %}

{% include list.html data="members" component="portrait" filters="role: Intern" %}

{% endcapture %}

{% include grid.html style="square" content=content %}