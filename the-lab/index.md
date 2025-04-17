---
title: The Lab
nav:
  order: 5
  tooltip: R&D Blog
---

# {% include icon.html icon="fa-solid fa-microscope" %}The Lab

{% capture text %}
Welcome to **The Lab** - where schematics come to life and the solder never cools.

Step inside our behind-the-scenes journal for experiments, builds, and the occasional glorious failure. From circuit sketches and fried prototypes (many of which you can see evolving on our [**Prototypes**](/projects/prototypes) page) to in-depth walk-throughs of our analog pedals ([**D.R.A.T**](/projects/drat)), digital explorations ([**GlitchCraft**](/projects/glitchcraft)), synth experiments ([**SynthWorks**](/projects/synthworks)), and hybrid creations ([**Gene-Splice**](/projects/gene-splice)) - this is where ideas mutate into machines.
{% endcapture %}

{% include feature.html
  image="images/projects/the-lab.png"
  text=text
%}

### Expect:

- Glitchy concepts
- Unstable waveforms
- Unexpected results

_We don’t post on a schedule._ We post when the voltage feels right.

---

*Filed entries may be chaotic. That’s kind of the point.*

{% include section.html %}

## Recent Findings

Catch up on our latest sonic dissections and experimental outcomes:

{% include list.html 
  data="posts" 
  component="post-excerpt" 
  limit="3" 
%}

{% include section.html %}

## Search the Archives

Looking for something specific? Delve into the chaos:

{% include search-box.html %}

{% include search-info.html %}

## All Entries

Explore the full spectrum of our experiments:

{%
  include list.html
  data="posts"
  component="post-excerpt"
%}