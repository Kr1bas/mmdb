---
layout: none
---
{% for manga in site.mangas %}
			<code>
				{"uuid":"{{ manga.uuid }}","dir":"{{manga.img-dir}}"}
			</code>
{% endfor %}