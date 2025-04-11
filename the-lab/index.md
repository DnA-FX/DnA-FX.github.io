---
title: The Lab
nav:
  order: 5
  tooltip: R&D Blog
---

# {% include icon.html icon="fa-solid fa-microscope" %}The Lab
{% capture text %}
Welcome to **The Lab** — where schematics come to life and the solder never cools.

This is the behind-the-scenes journal for our experiments, builds, and breakdowns. From circuit sketches and failed prototypes to full walk-throughs of our weirdest gear — this is where ideas mutate into machines.

Whether it's pedal design deep-dives, hybrid synth experiments, or cryptic notes from the Gene-Splice bench, you'll find it all here.
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

{% include search-box.html %}

{% include search-info.html %}

## Posts

{% 
  include list.html 
  data="posts" 
  component="post-excerpt"
%}
