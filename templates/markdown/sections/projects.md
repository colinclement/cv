{% extends "section.md" %}

{% block body %}
<table style="width:100%">
{% for p in items %}
<tr>
  <td>{{ p.keywords }}</td>
  <td>
    <strong>{{ p.title }}</strong>    <br>
    {{ p.details }}
  </td>
</tr>
{% endfor %}
</table>

{% endblock body %}
