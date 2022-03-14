---
title: Testing 1 2 3
---
# Testing

{{ site.title }}   

{{ page.url }}

Collections...

{{ site.collections }}

Iterate...

 <ul>
  {% for c in site.collection %}
  <li> c.collection </li>
    

  {% endfor %}
</ul>
