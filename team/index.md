---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}

# Full time

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role == 'Researcher'" %}
{% include list.html data="members" component="portrait" filter="role == 'Engineer'" %}

{% include section.html background="images/background.jpg" dark=true %}

# Intern

{% include section.html %}

{% capture content %}

{% include list.html data="members" component="portrait" filter="role == 'Intern'" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
