---
layout: page
permalink: /talks/
title: Talks
---
<h2>PhD Talks </h2>

<a href="https://github.com/xietianyiwa/xietianyiwa.github.io/blob/gh-pages/PhDtalks_PDF/Mcintyres_Theorem.pdf" target="_blank">McIntyre's Theorem</a> SoSe 2025, Seminar "Introduction to Stability Theory".

<h2>Flash Talks </h2>

From February to March 2025, I gave a series of Maths Flash Talks at Rockford Manor School, Dublin. The goal is to show the fun side of maths, convince more students that it is not boring. The talks are meant to be accessible to even 1st year students (~12 year olds), but entertaining for all. You can find also find notes to the talks here.

{% for post in site.categories.flash_talks %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}