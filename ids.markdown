---
layout: none
---
{% for manga in site.mangas %}
{"uuid":"{{ manga.uuid }}","dir":"{{manga.img-dir}}"}
{% endfor %}