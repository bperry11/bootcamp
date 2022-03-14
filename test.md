---
title: Testing 1 2 3
---
# Testing

{{ site.title }}   

{{ page.url }}

Nav

### Jake's Files
{% for f in site.jake %}
 <a href="{{f.url}}">{{f.title}} - {{f.url}}</a>
{%  endfor %}
### Ben's Files
{% for f in site.ben %}
 <a href="{{f.url}}">{{f.title}} - {{f.url}}</a>
{%  endfor %}
