---
layout: default
title: "Home"
---
  <h2 STYLE="margin: 30px 20px 0px 20px">Quantum Researcher</h2>
  <em STYLE="margin: 0px 20px 0px 20px">In a superposition of physics, musics, and books!</em>
<br>
<hr style="border-top: 1px solid #537188;margin-left:2;margin-right:2">
{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
