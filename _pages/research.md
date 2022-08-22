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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<!-- Things to do here: describe my research interests in greater detail, what problems have I studied, and what problems am I interested in? describe papers and link to arxiv. create research statement document (?). -->

There's nothing here yet.
