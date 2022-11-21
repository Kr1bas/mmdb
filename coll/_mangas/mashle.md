---
title: "Mashle"
title-original: "Mashle"
genres: ["shonen"]
story: "Hajime Kōmoto"
designs: "Hajime Kōmoto"
editor: "Star Comics"
volumes: [1,2,3,4,5,6,7]
variants: [1,2]
---
# {{page.title}}
{% if page.story == page.designs %}
## {{page.story}}
{% else %}
## {{page.story}} - {{page.designs}}
{% endif %}
### {{page.editor}}

{% for vol in page.volumes %}
	<img src="img/mashle/mashle-"{{vol}}".jpg"></img><br/>
{% endfor%}


{% for var in page.variants %}
	<img src="img/mashle/mashle-"{{var}}"-variant.jpg"></img><br/>
{% endfor%}