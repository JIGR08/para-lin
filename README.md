# Birthday+ — guía rápida

Abre `index.html` con cualquier navegador. No requiere instalación ni internet.

## Personalizar

1. Abre `index.html` en un editor de texto.
2. Busca `EDITA AQUÍ`. Debajo están las listas `photos`, `videos` y `letters`.
3. Cambia los títulos, notas y el contenido `body` de cada carta.
4. Guarda tus archivos en carpetas como `media/fotos/` y `media/videos/`.
5. Para una foto real, cambia el contenido del bloque `.art` por una etiqueta como:

```html
<img src="media/fotos/amigas.jpg" alt="Las dos sonriendo">
```

Agrega al CSS: `.art img{width:100%;height:100%;object-fit:cover}`.

Para video, dentro del modal utiliza:

```html
<video controls playsinline src="media/videos/recuerdo.mp4"></video>
```

Agrega al CSS: `.media-box video{width:100%;height:100%;object-fit:contain}`.

Puedes duplicar o borrar objetos completos dentro de cada lista; las tarjetas se generan automáticamente.
