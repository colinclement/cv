{% extends "section.md" %}

{% block body %}
<table style="width:100%">
{% for award in items %}
<tr>
  <td class='col-md-2'>{{ award.year }}</td>
  <td>
    {{ award.title }}
    <!-- {% if award.descr %} -->
    <!-- <ul><li>{{ award.descr }}</li></ul> -->
    <!-- {% endif %} -->
  </td>
</tr>
{% endfor %}
</table>
{% endblock body %}
