---
layout: archive
permalink: /news
title: "Trench News"
author_profile: true
---

<div class="grid__wrapper">
  {% for post in site.posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>