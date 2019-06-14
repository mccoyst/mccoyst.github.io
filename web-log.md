---
layout: basic
title: Blah Blah Blah
---
{% for post in site.posts %}
 * [{{ post.title }}]({{ post.url }})
{% endfor %}
