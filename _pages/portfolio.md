---
layout: archive
class: wide
permalink: /portfolio/
title: "Portfolio and Projects"
author_profile: true
---

<style>
  .tag {
    display: inline-block;
    border: 1px solid #bf7c00;
  }

</style>

{% for post in site.posts %}
  <h2>{{ post.title }}</h2>
  <hr/>
  <p>{{ post.excerpt }}</p>
  {% for tag in post.tags %}
    <p>hello</p>
  {% endfor %}
  <a class="btn" href="{{ post.url }}">Read more</a>
{% endfor %}
