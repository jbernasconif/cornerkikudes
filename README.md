# Corner Kikudes — GitHub Pages

Este repositorio publica la app en GitHub Pages. `index.html` es la app completa, autocontenida.

## Publicar

1. Crea un repositorio en GitHub (por ejemplo `corner-kikudes`).
2. Sube el contenido de esta carpeta a la rama `main`.
3. En el repositorio: **Settings → Pages → Source: Deploy from a branch → Branch: main / (root) → Save**.
4. En un minuto la app está en `https://TU-USUARIO.github.io/corner-kikudes/`.

## Incrustar tus datos

`index.html` arranca vacío. Para que salga con tus torneos, liga y jugadores ya cargados:

1. Abre `incrustar-datos.html` en tu navegador (doble clic, no hace falta servidor).
2. En la app actual: botón **Datos → Copiar texto**.
3. Pega ese texto en la herramienta y pulsa **Generar index.html**.
4. Se descarga un `index.html` nuevo con tus datos dentro. Sustituye el de este repositorio y sube.

Los datos se cargan **sólo la primera vez** que alguien abre la página en un dispositivo; después
cada uno guarda sus cambios en su propio navegador. Para actualizar la "copia maestra", repite
el proceso y vuelve a subir.

## Actualizar la app

Cuando haya una versión nueva de la app, repite el paso de incrustar datos con el `index.html`
nuevo (la herramienta acepta cualquier versión).
