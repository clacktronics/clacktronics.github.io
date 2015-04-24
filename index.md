---
layout: default
title: Clack.pw
---

Programming Lab of Ben Barwise - tests and experiments. Grapes on the vine, chilli crab, tumbling blocks, lapsang souchong and whatnot.
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>