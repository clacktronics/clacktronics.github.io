---
layout: default
title: EuroClack
---

EuroClack is a series of open source hardware euro rack synthesizer modules. The idea is that they are cheap to produce by oneself and follow a simple layout system for fast prototyping.


{% for repository in site.github.public_repositories %}
{% capture repprefix %}{{repository.name | slice: 0,9}}{% endcapture %}
{% if repprefix == "EuroClack" %}
* [{{ repository.name }}]({{site.url}}/{{ repository.name }}/)
{% else %}
{{ repository.name }}
{% endif %}
{% endfor %}
