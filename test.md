---
title: Testing 1 2 3
---
# Testing

{{ site.title }}   

{{ page.url }}

Collections...

{{ site.collections }}

Iterates...

 <ul>
  {% for c in site.collections %}
  <li> c.collection </li>
    

  {% endfor %}
</ul>
