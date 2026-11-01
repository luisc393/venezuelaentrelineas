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

## Subir un número de Leer Entrelíneas o Vértice

1. Guarda el PDF en `assets/pdf/leer-entrelineas/` o `assets/pdf/vertice/` (revisa antes que no tenga teléfonos, direcciones ni correos personales).
2. Guarda la portada (JPG, unos 800 px de ancho) en `assets/img/portadas/`.
3. Crea un archivo en `_entrelineas/` (por ejemplo `157.md`) o en `_vertice/` (por ejemplo `02.md`) copiando uno de los que ya existen y cambia número, fecha, titular, resumen y sumario.

El número aparece solo en la sección correspondiente, con su página propia.

## Páginas

- `index.html`: portada con las últimas noticias.
- `leer-entrelineas.md` y `vertice.md`: secciones de la hemeroteca, con la historia de cada publicación.
- `nuestra-historia.md`, `participa.md`: páginas fijas.
- `assets/css/style.css`: estilos.
