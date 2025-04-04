---
title: The Lab
nav:
  order: 5
  tooltip: R&D Blog
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
  data="posts" 
  component="post-excerpt"
  filter="for == 'thelab'"
%}
