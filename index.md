---
layout: default
title: "Home"
---
<body>
  <h2>Quantum Researcher</h2>
  <br><br>
  <em>In a superposition of physics, musics, and books!</em>
</body>
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
