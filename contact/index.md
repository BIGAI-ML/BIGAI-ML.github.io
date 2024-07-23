---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Feel free to contact us

{%
  include button.html
  type="email"
  text="dylan.liqing@gmail.com"
  link="dylan.liqing@gmail.com"
%}
{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/@39.9871957,116.3046691,20.42z?entry=ttu"
%}

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

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
1
{% endcapture %}

{% capture col2 %}
2
{% endcapture %}

{% capture col3 %}
3
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
