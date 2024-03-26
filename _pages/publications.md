---
layout: archive
title: "Selected publications"
permalink: /publications/
author_profile: true
---

Full publication list at [(Google Scholar Profile)](https://scholar.google.com/citations?user=4c7lOjIAAAAJ&hl=en)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
