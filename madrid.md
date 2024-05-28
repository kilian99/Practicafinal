---
layout: default

---

<table style="width: 60%; border: 1px solid black; border-collapse: collapse;">
   <th style="border: 1px solid; padding: 10px;">Nombre</th>
   <th style="border: 1px solid; padding: 10px;">Edad</th>
   {% for real in site.data.realmadrid  %}
   <th style="border: 1px solid; padding: 10px;">{{ real.nombre}} </th>  
   <th style="border: 1px solid; padding: 10px;">{{real.edad}} </th>
</table>


{% endfor %}