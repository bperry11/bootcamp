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

Collections with links

{% for c in site.collections %}
 {{c.label}} - <br>
 {% for f in c.files %}
  <a href="{{f.path| remove: '_'}}">f.name</a> <br>
 {% endfor %}
 <hr>
{%  endfor %}
