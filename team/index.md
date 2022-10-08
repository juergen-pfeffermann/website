---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}

{:.center}

{% include section.html background="images/banner-bottom.png"%}

_But my memory reaches back even to the Elder Days. Eärendil was my sire, who was born in Gondolin before its fall; and my mother was Elwing, daughter of Dior, son of Lúthien of Doriath. I have seen three ages in the West of the world, and many defeats, and many fruitless victories._ --- Elrond, Lord of Rivendell

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{% capture text %}
The Austrian Science Fund (FWF) is Austria's central funding organization for basic research. Currently funded projects are:

- Rohit's project
- Simon's project
  {:.center} {% endcapture %}

{%
  include feature.html
  image="images/FWF.svg"
  link="https://www.fwf.ac.at/en/"
  title="FWF Austrian Science Fund"
  text=text
%}
