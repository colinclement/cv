{% extends "section.md" %}

{% block body %}

<table style="width:100%">
{% for activity in items %}
<tr>
  <td class="col-md-2">{{ activity.year }}</td>
  <td> {{ activity.title }} </td>
</tr>
{% endfor %}
</table>
{% endblock body %}
