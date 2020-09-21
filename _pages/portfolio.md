---
layout: archive
classes: wide
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
  <img class="full" src="/images/{{ post.title }}.png" alt="">
  <p>{{ post.excerpt }}</p>
  <a href="{{ post.url }}" class="btn btn--inverse">Read More</a>
{% endfor %}
