---
layout: archive
title: "First (co) author publications"
permalink: /first_author_pubs/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.first_author_pubs reversed %}
  {% include archive-single.html %}
{% endfor %}
