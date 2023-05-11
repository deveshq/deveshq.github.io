---
layout: default
title: "Home"
---

### Quantum Researcher
***In a superposition of physics, musics, and books!***
<br>
<br>
<br>
<hr>
<br>
{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
