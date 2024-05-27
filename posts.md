---
layout: default

---


{% for real in site.data.realmadrid  %}
   {{ real.nombre}}  tiene {{real.edad}} años



{% endfor %}