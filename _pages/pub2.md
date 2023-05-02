---
title: pub2
permalink: /pub2/
layout: single
author_profile: true
---

{% for publication in site.data.publications %}
  <h3>{{ publication.title }}</h3>
  <p>{{ publication.authors }}. "{{ publication.title }}" <i>{{ publication.venue }}</i> ({{ publication.date }}).</p>
  <p><a href="{{ publication.url }}">Link</a></p>
{% endfor %}

- title: "My First Publication"
  authors: "John Doe, Jane Smith"
  venue: "Journal of Jekyll"
  date: "January 1, 2023"
  url: "http://example.com/publication1/"


