---
layout: default
lang: en
---

{% capture print_contact %}{% include print_contact.md %}{% endcapture %}
{% capture about_me %}{% include about_me.md %}{% endcapture %}
{% capture experience %}{% include experience.md %}{% endcapture %}
{% capture education %}{% include education.md %}{% endcapture %}
{% capture projects %}{% include projects.md %}{% endcapture %}
{% capture languages %}{% include languages.md %}{% endcapture %}
{% capture additional_references %}{% include additional_references.md %}{% endcapture %}

{{ print_contact | markdownify }}
{{ about_me | markdownify }}
{{ experience | markdownify }}
{{ projects | markdownify }}
{{ education | markdownify }}
{{ languages | markdownify }}
{{ additional_references | markdownify }}
