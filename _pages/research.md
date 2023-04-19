---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<img style="float: center; padding: 10px 10px 10px 10px;" src="http://katjensen.github.io/images/Under-Construction-Sign.png" width=300>

{% for post in site.research %}
  {% include archive-single.html %}
{% endfor %}
