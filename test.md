---
title: Testing 1 2 3
---
# Testing

{{ site.title }}   

### Jake's Files
{% for f in site.jake %}
 <a href="{{f.url|relative_url}}">{{f.title}} - {{f.url}}</a>
{%  endfor %}
### Site Files
{% for f in site.static_files %}
 {{f.path}}
 <a href="{{f.path|relative_url}}">{{f.name}} - {{f.path}}</a>
{%  endfor %}

Collections

{% for c in site.collections %}
 {{c.label}} - <br>
 {% for f in c.files %}
  {{f.path}} <br>
 {% endfor %}
 <hr>
{%  endfor %}
