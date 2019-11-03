---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

[Academic Vitae](https://zdinakmg.github.io/files/zdinakmg_cv.pdf)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
