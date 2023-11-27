---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

I am interested in multiple testing, causal inference, and high dimensional reduction methods. Below are some of my previous or current research projects

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
