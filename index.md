---
layout: default
---

# Wer ich bin

Ich bin ein Arbeitssoziologe.

# Neuigkeiten

{% for post in site.posts %}
* [{{post.title}}]({{ post.url }})
{% endfor %}
