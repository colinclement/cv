{% extends "section.md" %}

{% block body %}
<table style="width:100%">
{% for r in items %}
<tr>
  <td>{{ r.dates }}</td>
  <td>
    <strong>{{ r.place }}</strong>, {{ r.advisor }} <br>
    ({{ r.area }})
  </td>
</tr>
{% endfor %}
</table>

{% endblock body %}
