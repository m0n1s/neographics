---
layout: default
title: "Neographics"
permalink: /
---

# Neographics

a faster, open-source replacement for Pebble's graphic routines.

Foreword:

Not all functions that will be implemented are in this list, and not all
    functions in this list are implemented. Those in the Rebble Trello team
    can view my progress via the `Graphics API` board.

\- [jneubrand](https://github.com/jneubrand)

---

<ul id="toc">
{% for x in site.data.docs %}
{% assign item = x %}
{% include toc.html %}
{% endfor %}
</ul>

---

{% assign depth = 2 %}
{% for x in site.data.docs %}
{% assign item = x %}
{% include docs.html %}
{% endfor %}
