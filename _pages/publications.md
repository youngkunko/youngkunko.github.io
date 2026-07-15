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

{% for post in site.publications reversed %}
  {% unless post.venue contains "RECOMB" or post.venue contains "Bio" or post.venue contains "bio" %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}

## BioInformatics

{% for post in site.publications reversed %}
  {% if post.venue contains "RECOMB" or post.venue contains "Bio" or post.venue contains "bio" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
