---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: Alex Hokanson
layout: default
---
{% for work in site.data.workHistory %}
  <h1>{{ work.title }}</h1>
  <p>
    {{work.content}}
  </p>
{% endfor %}
