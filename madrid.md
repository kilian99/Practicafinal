---
layout: default

---


{% for real in site.data.realmadrid  %}
<table style="border=1px">
   {{ real.nombre}}  tiene {{real.edad}} años
</table>


{% endfor %}