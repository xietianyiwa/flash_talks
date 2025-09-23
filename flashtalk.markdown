---
layout: page
permalink: /flash_talks/
title: Flash Talks
---

{% for post in site.categories.flash_talks %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}