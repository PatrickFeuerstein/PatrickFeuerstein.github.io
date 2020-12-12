---
layout: default
---

## Wer ich bin

Ich bin ein Arbeitssoziologe.

## Neugikeiten

{% for post in site.posts %}
* [{{post.title}}]({{ post.url }})
{% endfor %}
