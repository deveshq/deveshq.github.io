---
layout: default
title: "Home"
---
  <h2 STYLE="margin: 30px 20px 0px 20px">Quantum Researcher</h2>
  <em STYLE="margin: 0px 20px 0px 20px">In a superposition of physics, musics, and books!</em>
<br>
<p style="margin-left:0.5;margin-right:0.5;">
<hr style="border-top: 1px solid #537188">
</p>
{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
