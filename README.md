# Diplomado de Facilitadores en Tanatología — Cecura Guadalajara

Landing page del Diplomado de Facilitadores en Tanatología de Cecura Guadalajara, A.C.
Inicio: 11 de septiembre 2026 · Modalidad híbrida · 120 h, 12 módulos.

## Estructura

```
index.html      Página completa
styles.css      Estilos
assets/         Imágenes (fotos optimizadas a JPG < 300 KB)
```

Sitio estático sin dependencias ni build. Para verlo en local basta con abrir
`index.html` en el navegador, o levantar un servidor simple:

```bash
python3 -m http.server 8000
```

## Publicación

Publicado con GitHub Pages desde la rama `main`.

## Nota sobre las imágenes

Las fotos originales en PNG (~10 MB c/u) no se versionan — están excluidas en
`.gitignore`. En el repo viven únicamente las versiones JPG optimizadas
(1600 px de ancho, menos de 300 KB cada una).
