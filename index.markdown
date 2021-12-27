---
title: City God Temple
layout: index
---

<div id="introduction">
  <p>
  </p>
</div>

<table id=pictures>

  <div id=exhibit>
  {% for exhibit in site.exhibits %}
  <div id = "grid_cell">
    <img src="{{ exhibit.Index_image_url }}" width=200px height=200px>
    <p> {{ exhibit.Title }} </p>
 </div>

{% endfor %}

</div>


</table>
