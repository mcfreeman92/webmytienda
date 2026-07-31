# webmytienda

Sitio web de la app myTienda — landing page / guía de uso para dueños y encargados de negocio.

## Contenido

- `index.html` — página única, sin dependencias externas (estilos embebidos, íconos en SVG inline).
- `.github/workflows/pages.yml` — despliega `index.html` a GitHub Pages en cada push a `main`.

## Publicar en GitHub Pages

1. Fusionar esta rama a `main`.
2. En **Settings → Pages**, elegir **Source: GitHub Actions** (solo hace falta la primera vez).
3. El workflow `Deploy static content to Pages` publica el sitio automáticamente.
