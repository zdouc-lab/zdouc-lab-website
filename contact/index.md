---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is part of the [Department of Pharmaceutical Sciences](https://pharmaceutical-sciences.univie.ac.at/), [Division of Pharmacognosy](https://pharmcog.univie.ac.at/), University of Vienna.
Feel free to reach out to us!

{%
  include button.html
  type="email"
  text="mitja.zdouc@univie.ac.at"
  link="jane@smith.com"
%}
{%
  include button.html
  type="phone"
  text="+43 1 4277 77352"
  link="+43-1-4277-77352"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/E96icvHNq3B6Wk8w8"
%}

{% include section.html %}

{% include section.html dark=true %}

{% capture col1 %}
Division of Pharmacognosy

Department of Pharmaceutical Sciences

University of Vienna

Josef-Holaubek-Platz 2, Room 2G153

1090 Vienna, AUSTRIA
{% endcapture %}

{% capture col2 %}
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
