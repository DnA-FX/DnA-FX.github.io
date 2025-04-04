---
title: Gene-Splice
nav:
  order: 4
  tooltip: Hybrid Pedals/Mods
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

## Highlighted

{%
  include list.html
  data="pedals"
  component="pedal-excerpt" 
  filter="brand == 'gene-splice'"  
%}
