---
layout: default
title: EuroClack
---

EuroClack is a series of open source hardware euro rack synthesizer modules. The idea is that they are cheap to produce by oneself and follow a simple layout system for fast prototyping.

  {% for post in site.posts %}

  * [{{ post.title }}]({{ post.url }})

  {% endfor %}


  {% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
  {% endfor %}
