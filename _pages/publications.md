---
title: Publications
permalink: /publications/
layout: single
author_profile: true
---

{% for publication in site.data.publications %}
  <a href="{{ publication.url }}" style="text-decoration: underline; color: black;">{{ publication.title }}</a>
  {{ publication.authors }}. <i>{{ publication.venue }}</i> ({{ publication.date }}).
{% endfor %}



