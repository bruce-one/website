---
title: Cast dates
---

<div style='display: flex; justify-content: center;'>
  <h4 style='margin-right: 0.5rem;'>Cast dates</h4>
</div>
<table>
  {% for event in site.data.cast.cast %}
  <tr>
    <td style='padding-right: 3vw'>
      {{ event.description }}
    </td>
    <td>
      {{ event.date }}
    </td>
  </tr>
  {% endfor %}
</table>
