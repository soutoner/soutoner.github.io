# [](#languages) {{ site.data[page.lang].lang }}
* * *
{{ site.data[page.lang].mother_tongue }}: {{ site.data[page.lang].first_language }}

{{ site.data[page.lang].other_languages }}:
{% for l in site.data[page.lang].languages %}
* {{ l.language }} &mdash; {{ site.data[page.lang].proficiency }}: {{ l.level }}
{% endfor %}
