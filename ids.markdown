---
layout: none
---
<pre><code>
{"list":[
{% for manga in site.mangas %}
{"uuid":"{{ manga.uuid }}","dir":"{{manga.img-dir}}"},
{% endfor %}
]}
</code></pre>


<hr>

{{site.mangas | jsonify}}