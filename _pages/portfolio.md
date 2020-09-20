---
layout: archive
permalink: /portfolio/
title: "Portfolio and Projects"
author_profile: true
header:
  image: "/images/laser-defender.png"
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
