---
layout: default

---

<table style="width: 60%; border: 1px solid black; border-collapse: collapse;">
   <tr>
      <th style="border: 1px solid; padding: 10px;">Nombre</th>
      <th style="border: 1px solid; padding: 10px;">Edad</th>
      <th style="border: 1px solid; padding: 10px;">Titulos</th>
      <th style="border: 1px solid; padding: 10px;">Imagen</th>
   </tr>

   {% for real in site.data.realmadrid  %}
   <tr>
      <th style="border: 1px solid; padding: 10px;">{{ real.nombre}} </th>  
      <th style="border: 1px solid; padding: 10px;">{{real.edad}} </th>
      <th style="border: 1px solid; padding: 10px;">{{real.titulos}} </th>
      <th style="border: 1px solid; padding: 10px;">{{real.imagen}} </th>
   </tr>
   {% endfor %}


</table>