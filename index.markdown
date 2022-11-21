---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

{{ site.mangas.pages }}

<hr>

{% for staff_member in site.mangas %}
  <h2>
    <a href="{{ staff_member.url }}">
      {{ staff_member.title }}
    </a>
  </h2>
{% endfor %}
