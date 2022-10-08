---
name: Full name
image: images/image.png/jpg/tif
role: pi/phd/programmer
description: Fluorescence Microscopy
aliases:
links:
  orcid: 0000-0002-6184-6101
  email: juergen.pfeffermann@jku.at
  github: https://github.com/juergen-pfeffermann
  twitter: JPfeffermann
published: false
---

### It's me, I am working on this website

I am doing mainly things with microscopes. Unfortunately for the sake of this site, I do hardly take nice images.

{% include section.html %}
{%
  include feature.html
  image="images/OptoDArG.jpg"
  link="research"
  title="Photoswitching of model ion channels in lipid bilayers"
  text="The image shows single ion-conducting gramicidin A channels recorded in planar lipid bilayers containing a photolipid in two distinct configurations, termed *trans-* and *cis-*OptoDArG."
%}

{% include list.html
data="citations"
component="citation"
filter="page: juergen-pfeffermann" %}
