---
layout: default
title: "Neographics"
permalink: /
---

<h1>Neographics</h1>
a faster, open-source replacement for Pebble's graphic routines.


<ul id="toc">
{% for x in site.data.docs %}
{% assign item = x %}
{% include toc.html %}
{% endfor %}
</ul>

{% assign depth = 2 %}
{% for x in site.data.docs %}
{% assign item = x %}
{% include docs.html %}
{% endfor %}
