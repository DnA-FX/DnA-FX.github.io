---
title: About
nav:
  order: 6
  tooltip: Project Team
---

# {% include icon.html icon="fa-solid fa-users" %}Meet the Creative Minds

## Who We Are
{% capture text %}
**D&A Effects** (a.k.a. **DnA-FX**) is the ongoing creative playground of Daniel Aldrich (better known as **Drat**) and the brilliant mind of backyard synth designer & audio enthusiast **Tyler Aben**. What started as a shared passion for crafting unique sounds in our own sound design _lab_ has evolved into this collection of exciting projects. We're tinkerers, musicians at heart, and dedicated explorers in the world of audio.
{% endcapture %}

{% include feature.html
  image="images/profiles/team-32.png"
  text=text
%}
{% include section.html %}
## Our Design Team
{% include list.html data="members" component="portrait" filter="role == 'designer'" %}

## Our Philosophy

More than just building tools, our mission is to merge the precision of engineering with the boundless possibilities of sonic experimentation. We strive to create pedals and mods that aren't just functional pieces of gear, but inspiring instruments in their own right. Whether we're chasing classic analog warmth or embracing digital chaos, we're driven to build the tools that empower us – and hopefully others - to **sculpt our own sonic DNA.**

## Exploring Our Soundscapes

- [**D.R.A.T.**](/projects/drat): Focused on **Analog** guitar and bass effects.
- [**GlitchCraft**](/projects/glitchcraft): Diving into **Digital** and DSP effects.
- [**SynthWorks**](/projects/synthworks): Creating **Synth**-centric tools and modules.
- [**Gene-Splice**](/projects/gene-splice): Our **Hybrid** and **Collaboration** experiments.

{% include section.html background="images/background.jpg" dark=true %}
## With Gratitude to Our Supporters
The journey of D&A Effects wouldn't be the same without the incredible support and inspiration from the musicians who have embraced our creations. While a complete list would be endless, we want to express our sincere appreciation to some of the notable artists who have offered their continued encouragement, valuable input, and unwavering dedication.
{% include section.html %}
## Featured Musicians
{% include list.html data="members" component="portrait" filter="role == 'musician'" %}