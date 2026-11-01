# Lector veloz

Lector de lectura rápida (RSVP) que corre 100% en el navegador. Acepta texto pegado, TXT, PDF y EPUB.

## Publicar en GitHub Pages

1. Creá un repositorio nuevo en GitHub (por ejemplo `lector-veloz`), público.
2. Subí `index.html` y este `README.md` a la raíz del repo.
3. Andá a **Settings → Pages**.
4. En **Build and deployment**, elegí **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guardá.
5. Después de 1-2 minutos la app queda en `https://TU-USUARIO.github.io/lector-veloz/`.

## Notas

- No hace falta `Code.gs` ni Apps Script: es un solo archivo estático.
- Las librerías (pdf.js y JSZip) se cargan desde cdnjs, así que se necesita conexión a internet.
- La velocidad, el tamaño y la posición de lectura se guardan en `localStorage` del navegador.
