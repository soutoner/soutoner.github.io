# [](#projects) {{ site.data[page.lang].project }}
* * *
{% for p in site.data[page.lang].projects %}
## {% if p.link %} <a href="{{ p.link }}" target="_blank">{{ p.title }}</a> {% else %} {{ p.title }} {% endif %}
### {{ p.position }} &bull; {{ p.from }} &mdash; {{ p.to }}
{{ p.description }}
<p class="show-print"><i>{{ p.link }}</i></p>
{% endfor %}
