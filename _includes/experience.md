# [](#experience) {{ site.data[page.lang].experience }}
* * *
{% for e in site.data[page.lang].experiences %}
## {{ e.position }}
### {{ e.company }} &bull; {{ e.from }} &mdash; {{ e.to }}
{{ e.description }}
{% endfor %}
