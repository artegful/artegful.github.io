---
layout: archive
permalink: /portfolio/
title: "Portfolio and Projects"
author_profile: true
---

{% for post in site.posts %}
  <h2>{{ post.title }}</h2>
  <hr/>
  <p>{{ post.excerpt }}</p>
  <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}
