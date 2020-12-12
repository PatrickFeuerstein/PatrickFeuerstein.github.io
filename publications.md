---
layout: post
---

## Ausgewählte Publikationen neu


  {% for post in site.posts %}

      {{ post.url }} {{ post.title }}

  {% endfor %}


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
