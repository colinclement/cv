{% extends "section.md" %}

{% block body %}
<table style="width:100%">
{% for i in items %}
<tr>
  <td class='col-md-1'>{{ i.semester }}</td>
  <td><strong>{{ i.name }}</strong> ({{ i.short }}), {{ i.position }}</td>
</tr>
{% endfor %}
</table>
{% endblock body %}
