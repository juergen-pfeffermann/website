---
title: Website
---

# Acknowledgment @ GreeneLab

Thanks to [**github.com/greenelab**](https://github.com/greenelab/lab-website-template) for providing this template! If I decide to continue working on this website I shall give you some feedback on how intuitive I find working with the template and your documentation.

Kind regards!

{% include section.html dark=false full=true %}
{% include banner.html image="images/banner-bottom.png" %}

{% include section.html %}
{%
  include feature.html
  image="images/3din_SecYEG+SecA.PNG"
  link="research"
  title="PDB 3din: SecYEG + SecA (tyrosines in SecA are highlighted)"
  text="Look at this, I have been using [PyMol](https://pymol.org/2/) a bit today. I have usually found detailed reporting or discussions on minute movements within protein substructures as inferred from crystal or cryo-EM structures tedious; yet following these elaborations by simultaneously reproducing them in PyMol could help."
%}
{%
  include feature.html
  image="images/Solvay_conference_1927.jpg"
  link="https://en.wikipedia.org/wiki/Solvay_Conference"
  title="An image taken at the Fifth Solvay conference on physics in 1927"
  text="This is an image of researchers. Many of them are quite well known. We might not be that famous but our research also has impact -- at least I hope so."
  flip=true
%}
