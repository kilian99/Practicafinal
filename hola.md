---

---

# {{site.title}}



# Posts sobre artistas

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Formateo de texto

En Markdown, puedes hacer:

- **Negrita** con `**Hola**`
- *Itálica* con `*Hola*`
- ~~Tachado~~ con `~~Hola~~`

## Listas

### Leyendas Real Madrid

- CR7
- Zidane
- Kroos
- Di Estefano

### Mejores jugadores de la actualidad

1. Vini Jr
2. Jude Bellingham
3. Kroos
4. Lunin

## Enlaces e Imágenes

[Prueba](index.html)

[Jugadores](madrid.md)

[Google](https://www.google.com)

![Imagen Ejemplo](https://ichef.bbci.co.uk/ace/ws/640/cpsprodpb/10413/production/_100697566_hi045932006.jpg)

## Libros

> MIL OJOS ESCONDE LA NOCHE
>
> - JUAN MANUEL DE PRADA

## Prueba

```python
print("Hola, mundo!")
