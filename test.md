---
title: Testing 1 2 3
---
# Testing

{{ site.title }}   

### Jake's Files
{% for f in site.jake %}
 <a href="{{f.url|relative_url}}">{{f.title}} - {{f.url}}</a>
{%  endfor %}
### Ben's Files
{% for f in site.collections[0].files %}
 {{f.name}}
 <a href="{{f.url|relative_url}}">{{f.title}} - {{f.url}}</a>
{%  endfor %}

Pages json...

{{site.pages|json}}
