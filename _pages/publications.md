---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
%  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Ruoyan Wang, Christopher Seay, and Jonathan Fortney. Atmospheres of Brown Dwarfs. In <em>AmericanAstronomical Society Meeting Abstracts #231</em>, volume 231 of <em>American Astronomical Society Meeting Abstracts</em>, page 450.10, Jan 2018.