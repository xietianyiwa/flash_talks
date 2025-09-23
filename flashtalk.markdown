---
layout: page
permalink: /flash_talks/
title: Flash Talks
---
From February to March 2025, I gave a series of Maths Flash Talks at Rockford Manor School, Dublin. The goal is to show the fun side of maths, convince more students that it is not boring. The talks are meant to be accessible to even 1st year students (~12 year olds), but entertaining for all. You can find also find notes to the talks here.

{% for post in site.categories.flash_talks %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}