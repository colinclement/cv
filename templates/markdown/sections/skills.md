{% extends "section.md" %}

{% block body %}
<table style="width:100%">
{% for item in items %}
<tr>
  <td class='col-md-2'>{{ item.title }}</td>
  <td >
{{ item.details }}
  </td>
</tr>
{% endfor %}
</table>
{% endblock body %}
