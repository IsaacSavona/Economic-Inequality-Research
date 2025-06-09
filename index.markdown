---
layout: home
title: Economic Inequality Research
---

Welcome to my collection of Pluto.jl notebooks on inequality.  
Click any of the notebooks below to explore:

<ul>
  {% for file in site.static_files %}
    {% if file.extname == ".html" and file.path contains "src/" %}
      <li><a href="{{ file.path | relative_url }}">{{ file.name }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
---
