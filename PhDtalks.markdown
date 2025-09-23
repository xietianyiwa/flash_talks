---
layout: page
permalink: /PhDtalks/
title: PhD Talks
---

<a href="https://github.com/xietianyiwa/flash_talks/blob/gh-pages/PhDtalks_PDF/Mcintyre's Theorem Talk.pdf"target="_blank">McIntyre's Theorem</a>; SoSe 2025, Seminar "Introduction to Stability Theory"

{% for post in site.categories.phdtalks %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}