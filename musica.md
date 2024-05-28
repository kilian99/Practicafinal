---
layout: default

---

<table style="width: 60%; border: 1px solid black; border-collapse: collapse;">
   <tr>
      <th style="border: 1px solid; padding: 10px;">Nombre</th>
      <th style="border: 1px solid; padding: 10px;">Edad</th>
      <th style="border: 1px solid; padding: 10px;">Seguidores</th>
   </tr>

   {% for artista in site.data.artistas  %}
   <tr>
      <th style="border: 1px solid; padding: 10px;">{{artista.nombre}} </th>  
      <th style="border: 1px solid; padding: 10px;">{{artista.edad}} </th>
      <th style="border: 1px solid; padding: 10px;">{{artista.seguidores}} </th>
   </tr>
   {% endfor %}


</table>