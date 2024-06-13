---
layout: default

---

<table style="width: 60%; border: 1px solid black; border-collapse: collapse;">
   <tr>
      <th style="border: 1px solid; padding: 10px;">Nombre</th>
      <th style="border: 1px solid; padding: 10px;">Notas</th>
      <th style="border: 1px solid; padding: 10px;">Sexo</th>
   </tr>

   {% for gente in site.data.gente  %}
   <tr>
      <th style="border: 1px solid; padding: 10px;">{{gente.nombre}} </th>  
      <th style="border: 1px solid; padding: 10px;">{{gente.notas}} </th>
      <th style="border: 1px solid; padding: 10px;">{{gente.sexo}} </th>
   </tr>
   {% endfor %}


</table>