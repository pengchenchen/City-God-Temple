---
title: Gallery
layout: index
---

<div id=exhibit>

{% for exhibit in site.exhibits %}

  <div id = "grid_cell">
    <img src="{{ exhibit.Index_image_url }}" width=200px height=200px>
    <p> {{ exhibit.Title }} </p>
    <p> Time: {{ exhibit.Time }} </p> <p> Site: {{ exhibit.site }}  </p>
    <p> {{ exhibit.Introduction }} </p>
    <p> Story <br> {{ exhibit.Story }} <br> </p>
 </div>

{% endfor %}

</div>
