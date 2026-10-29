# Venezuela Entrelíneas

Sitio de [venezuelaentrelineas.com](https://venezuelaentrelineas.com): noticias buenas de Venezuela y el archivo de *Leer Entrelíneas*.

Está hecho con Jekyll y se publica gratis con GitHub Pages. Cada cambio en la rama `main` queda publicado en uno o dos minutos.

## Publicar una noticia

Crea un archivo en `_posts/` con el nombre `AAAA-MM-DD-titulo-corto.md`:

```markdown
---
layout: post
title: "Título de la noticia"
categoria: Comunidad
resumen: Una o dos frases que aparecen en la portada.
autor: Nombre de quien escribe
imagen: /assets/img/nombre-de-la-foto.jpg   # opcional
---

Texto de la noticia.
```

## Páginas

- `index.html`: portada con las últimas noticias.
- `nuestra-historia.md`, `leer-entrelineas.md`, `participa.md`: páginas fijas.
- `assets/css/style.css`: estilos.
