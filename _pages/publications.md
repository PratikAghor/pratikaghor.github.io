---
layout: archive
title: ""
layout: single
permalink: /publications/
author_profile: true
header:
  overlay_image: /assets/images/headers/chandra-TC.png
  overlay_filter: 0.2
---
# Submitted

{% include base_path %}

{% for post in site.submitted reversed %}
  {% include archive-single.html %}
{% endfor %}

# Published

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



