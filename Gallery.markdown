---
title: Gallery
layout: Gallery
---

<div id=exhibit>

{% for exhibit in site.exhibits %}

  <div id = "grid_cell">
    <a href = "{{ exhibit.url | relative_url }}"><img src="{{ exhibit.index_image_url }}" alt="{{ exhibit.introduction }}" width=200px height=200px></a>
    <a href = "{{ exhibit.url | relative_url }}"><p> {{ exhibit.name }} </p></a>
    <p> Time: {{ exhibit.time }} </p> 
 </div>

{% endfor %}

</div>
