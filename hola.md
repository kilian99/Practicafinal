---

---

# {{site.title}}

## Welcome to {{site.title}} {{page.title}} 
<ul>
{% for page in site.pages %}
  <li>
    <a href="{{ page.url }}">{{ page.title }}</a>
  </li>
{% endfor %}
</ul>

# Posts sobre artistas

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


# Hola Mundo

Bienvenidos al archivo `hola.md`. Aquí estoy probando algunas funcionalidades básicas.

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

[Google](https://www.google.com)

![Imagen Ejemplo](https://ichef.bbci.co.uk/ace/ws/640/cpsprodpb/10413/production/_100697566_hi045932006.jpg)

## Libros

> MIL OJOS ESCONDE LA NOCHE
>
> - JUAN MANUEL DE PRADA

## Prueba

```python
print("Hola, mundo!")
