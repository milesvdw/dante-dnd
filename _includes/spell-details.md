{% for spell in include.spells %}
  <h2><a name="{{ spell.name }}"></a>{{ spell.name }}</h2>
  <hr />
  <p>{{ spell.content | markdownify }}</p>
  <br />
{% endfor %}
