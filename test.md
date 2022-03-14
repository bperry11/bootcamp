---
title: Testing 1 2 3
---
# Testing

{{ site.title }}   

{{ page.url }}

Collections...

{{ site.collections }}

Below is the urls...

{% for c, f in site.collections %}
  {{ f.url }}
{% endfor %}
