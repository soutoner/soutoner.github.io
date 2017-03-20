<ul class="show-print">
  {% if site.contact.website %}
    <li><i class="fa fa-globe fa-2x" aria-hidden="true"></i> <i>{{ site.contact.website }}</i></li>
  {% endif %}
  {% if site.contact.email %}
    <li><i class="fa fa-envelope fa-2x" aria-hidden="true"></i> <i>{{ site.contact.email }}</i></li>
  {% endif %}
  {% if site.contact.linkedin %}
    <li><i class="fa fa-linkedin fa-2x" aria-hidden="true"></i> <i>{{ site.contact.linkedin }}</i></li>
  {% endif %}
  {% if site.contact.github %}
    <li><i class="fa fa-github fa-2x" aria-hidden="true"></i> <i>{{ site.contact.github }}</i></li>
  {% endif %}
  {% if site.contact.stack_overflow %}
    <li><i class="fa fa-stack-overflow fa-2x" aria-hidden="true"></i> <i>{{ site.contact.stack_overflow }}</i></li>
  {% endif %}
</ul>

