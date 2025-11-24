---
layout: archive
title: "Teaching & Outreach"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

<figure style="float:right; padding:4px; display:inline; width:50%">
    <img src='/images/outreach/PXL_20250921_173516013.jpg' alt='Hα telescope demonstration at the 2025 Cambridge Science Festival' />
    <figcaption> Hα telescope demonstration at the 2025 Cambridge Science Festival </figcaption>
</figure>

<figure style="float:right; padding:4px; display:inline; width:50%">
    <img src='/images/outreach/PXL_20240408_180530942.jpg' alt='My own telescope in Erie, PA for the 2024 total solar eclipse' />
    <figcaption> My own telescope in Erie, PA for the 2024 total solar eclipse  </figcaption>
</figure>

Seeing Jupiter's moons through a telescope as a child inspired my lifelong love of astronomy. In a world of screens, telescopes let us see genuine marvels of nature hidden in the black of the night sky. Over the years I have done various "sidewalk astronomy" events to give that opportunity to the public.



{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
