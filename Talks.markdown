---
layout: page
permalink: /talks/
title: Talks and Teaching
---
<h4>PhD Talks </h4>

<a href="https://www.maths.ox.ac.uk/node/81136">Towards H10 in mixed characteristic Henselian valued fields</a> Advanced Class Logic, Oxford.

<a href="/PDF/Mcintyres_Theorem.pdf">McIntyre's Theorem</a> SoSe 2025, Seminar "Introduction to Stability Theory".

<a href="/PDF/Perfectoid Fields.pdf">Perfectoid Fields</a> WiSe 2025, Seminar "Almost Mathematics".

<h4>Flash Talks </h4>

From February to March 2025, I gave a series of Maths Flash Talks at Rockford Manor School, Dublin. The goal is to show the fun side of maths and encourage more girls to try it. The talks are meant to be accessible to even 1st year students (~12 year olds), but entertaining for all. You can find the notes to the talks here.

{% for post in site.categories.flash_talks %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}