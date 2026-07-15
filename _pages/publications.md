---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Selected Publications

{% assign selected_permalinks = "/publication/2026-03-01|/publication/2019-11-14|/publication/2018-08-20|/publication/2015-10-17" %}
{% for post in site.publications reversed %}
  {% if selected_permalinks contains post.permalink %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## BioInformatics

{% for post in site.publications reversed %}
  {% if post.venue contains "RECOMB" or post.venue contains "Bio" or post.venue contains "bio" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
