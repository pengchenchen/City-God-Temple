---
title: City God Temple
layout: index
---

<div id="introduction">
  <p>
  introduction
  </p>
</div>

<table id= "pictures">

  <div id= "exhibit">

   {% for exhibit in site.exhibits %}
      <div id = "grid_cell">
          <a href = "{{ exhibit.url | relative_url }}"><img src="{{ exhibit.index_image_url }}" width=200px height=200px></a>
          <p><a href = "{{ exhibit.url | relative_url }}"> {{ exhibit.name }} </a></p>
      </div>
   {% endfor %}

</div>

</table>
