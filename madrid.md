---
layout: default

---


{% for real in site.data.realmadrid  %}
<table>
   {{ real.nombre}}  tiene {{real.edad}} años
</table>


{% endfor %}