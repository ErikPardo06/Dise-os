# Game Design Archive

Biblioteca web de recursos para videojuegos. HTML, CSS y JavaScript vanilla. Incluye categorías, búsqueda, filtros, fichas modales y textos ES/EN.

## Uso local
Abre `index.html` o ejecuta `python -m http.server 8000` desde esta carpeta.

## Publicación
Para publicar esta carpeta como sitio independiente, configura GitHub Pages para servir desde una rama/carpeta que contenga estos archivos. También puedes mover su contenido a la raíz del repositorio si quieres que la página principal del repositorio sea la biblioteca.

## Añadir recursos
Edita `js/data.js` y añade un objeto a `window.ASSETS`. Categorías: materials, buildings, vehicles, weapons, characters, environments, props. Estados: concept, progress, completed. Estilos: realistic, stylized, sci-fi, low-poly. Las imágenes deben guardarse dentro de `assets/images/` y referenciarse con una ruta relativa.

## Limitaciones
Versión estática: los datos se editan en el código; no hay login, base de datos ni panel de edición web.
