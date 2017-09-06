{% extends "section.md" %}

{% block body %}

<table class="table table-hover">
{% for activity in items %}
<tr>
  <td class="col-md-2">{{ activity.year }}></td>
  <td> {{ activity.title }} </td>
</tr>
{% endfor %}
</table>
{% endblock body %}
