# [](#education) {{ site.data[page.lang].education }}
* * *
{% for e in site.data[page.lang].educations %}
## {{ e.degree }}
### {{ e.university }} &bull; {{ e.from }} &mdash; {{ e.to }}
{{ e.description }}
{% endfor %}
