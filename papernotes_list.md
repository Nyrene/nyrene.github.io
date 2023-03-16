---
layout: page
title:  "Posts"
id: papernoteslist
---

<ul>
  {% for post in site.categories.papernotes %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>