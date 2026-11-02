# Game Design Archive

Biblioteca web de recursos para videojuegos. HTML, CSS y JavaScript vanilla. Incluye categorías, búsqueda, filtros, fichas modales y textos ES/EN.

## Uso local
Abre `index.html` o ejecuta `python -m http.server 8000` desde esta carpeta.

## Publicación en GitHub Pages

El repositorio incluye el workflow `.github/workflows/pages.yml`, que publica automáticamente el contenido de esta carpeta.

**Activación inicial obligatoria (una sola vez):**
1. Abre [Settings → Pages](https://github.com/ErikPardo06/Dise-os/settings/pages).
2. En **Build and deployment → Source**, selecciona **GitHub Actions**.
3. Guarda si GitHub muestra el botón.
4. Abre [Actions](https://github.com/ErikPardo06/Dise-os/actions) y comprueba que **Deploy Game Design Archive to GitHub Pages** termina en verde.

Después, cada push que modifique `game-design-archive/` volverá a publicar la web automáticamente.

URL esperada: https://erikpardo06.github.io/Dise-os/

Si el primer despliegue falla con `Configure Pages`, normalmente Pages aún no está habilitado para el repositorio o la fuente no está en **GitHub Actions**. Selecciona esa fuente y vuelve a ejecutar el workflow.

## Añadir recursos
Edita `js/data.js` y añade un objeto a `window.ASSETS`. Categorías: materials, buildings, vehicles, weapons, characters, environments, props. Estados: concept, progress, completed. Estilos: realistic, stylized, sci-fi, low-poly. Las imágenes deben guardarse dentro de `assets/images/` y referenciarse con una ruta relativa.

## Limitaciones
Versión estática: los datos se editan en el código; no hay login, base de datos ni panel de edición web.
