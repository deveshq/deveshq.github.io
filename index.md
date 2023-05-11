---
layout: default
title: "Home"
---
  <img alt="profile" src="/assets/profile.png" hight=100 width = 100 STYLE="margin: 10px 0px 0px 0px">
<center>
  <h3 STYLE="margin: 2px 20px 0px 20px">Quantum Research Associate, Qulabs Software India</h3>
  <em STYLE="margin: 0px 20px 0px 20px">In a superposition of physics, musics, and books!</em>
</center>
<br>
<hr style="border-top: 1px solid #537188; width:92%; margin-left:4% !important; margin-right:4% !important;">
{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
