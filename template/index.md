---
title: Template
description: Description for this page
nav:
  order: 10
  tooltip: Template for further pages

header: none
footer: none
header-dark: false
footer-dark: false
---

{% include section.html %}
Previous section of content

{%
  include section.html
  dark=false
  full=true
%}
{%
include banner.html
image="images/banner-bottom.png"
%}

{% include section.html %}
A figure. In a section. With hyperlink.
{%
include figure.html
image="images/juergen-pfeffermann.png"
caption="DalleE 2 generated this!"
link="members/juergen-pfeffermann"
width="50%"
%}
