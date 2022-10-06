---
title: Website
---

# Acknowledgment

{% capture text %} 
Thanks to **github.com/greenelab** for providing this template! If I decide to continue working on this website I shall give you some feedback on how intuitive I find working with the template and your documentation.

Kind regards,
Juergen Pfeffermann
{:.center}{% endcapture %}

{% include section.html %}

# PDB 3din: SecYEG + SecA (tyrosines in SecA are highlighted)

{% capture text %}
Look at this, I have been using PyMol a bit today. I have usually found detailed discussions on minute movements within crystal or cryo-EM structures tedious, yet following these elaborations by simultaneously reproducing them in PyMol could help. {:.center} {% endcapture %}

{%
  include feature.html
  image="images/3din_SecYEG+SecA.PNG"
  link="research"
  title="a random snap from PyMol (Schrödinger)"
  text=text
%}
