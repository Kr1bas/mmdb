---
layout: none
---
<pre><code>
{"list":[
{% for manga in site.mangas %}
{% if forloop.last %}
    {"uuid":"{{ manga.uuid }}","dir":"{{manga.img-dir}}"}
  {% else %}
    {"uuid":"{{ manga.uuid }}","dir":"{{manga.img-dir}}"},
  {% endif %}
{% endfor %}
]}
</code></pre>