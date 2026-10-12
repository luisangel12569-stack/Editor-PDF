# Editor de PDF

App web para editar PDFs en el navegador, como si fuera Word: cambiar palabras, borrar cuadros, imágenes y firmas.

Usa [PDF.js](https://mozilla.github.io/pdf.js/) para mostrar el PDF y [pdf-lib](https://pdf-lib.js.org/) para editarlo y guardarlo. No necesita servidor: abre `index.html` en el navegador.

## Plan
1. Visor web: abrir un PDF y ver sus páginas ✅
2. Editar texto ✅
3. Borrar y mover cuadros, imágenes y firmas ✅
4. Borrado seguro y publicar con GitHub Pages ✅

## Herramientas de páginas
Marca páginas con su casilla y usa: **Eliminar**, **Extraer** (descarga un PDF nuevo), **Añadir PDF** (después de la última página marcada, o al final) y **Separar** (ZIP con un PDF por rango, ej. `1-3, 4-6`; vacío = cada página). Con **Organizar** ves miniaturas y arrastras páginas para cambiar el orden (si arrastras una marcada, se mueven todas las marcadas). Al añadir un PDF, sus páginas quedan marcadas para llevarlas donde quieras.
