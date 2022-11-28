{% for manga in site.mangas %}
			<code>
				{"id":"{{ manga.uuid }}","dir":"{{manga.img-dir}}"}
			</code>
{% endfor %}