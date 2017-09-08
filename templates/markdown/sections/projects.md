{% extends "section.md" %}

{% block body %}
<table class="table table-hover">
{% for p in items %}
<tr>
  <td class='col-md-3'>{{ p.keywords }}</td>
  <td>
    <strong>{{ p.title }}</strong>    <br>
    {{ p.details }}
  </td>
</tr>
{% endfor %}
</table>

{% endblock body %}
