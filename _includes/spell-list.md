<ul>
{%- for spell in include.spells -%}
<li>
  <a href="{{ include.page }}#{{ spell.name }}">
    {{ spell.name }}
  </a>
</li>
{% endfor %}
</ul>