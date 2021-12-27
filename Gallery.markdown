---
title: Gallery
layout: Gallery
---

{% for exhibit in site.exhibits %}


<img href="{{ exhibit.Main-image-url }}" width=500px>
<p> {{ exhibit.Title }} </p>

{% endfor %}

There should be a photo but we can't see it<img scr="https://upload.wikimedia.org/wikipedia/commons/thumb/0/03/What%27s_a_Love_Dart%3F.webm/220px--What%27s_a_Love_Dart%3F.webm.jpg" alt="hello" width=200px height=200px>
