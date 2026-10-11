# Barúc

Aplicación web para gestión de publicadores.

## Contenido

- `index.html`: área administrativa / dashboard de prueba.
- `formulario.html`: formulario público independiente.
- `assets/logo-baruc.png`: logo proporcionado para Barúc.
- `.nojekyll`: evita que GitHub Pages intente procesar el sitio con Jekyll.

## Importante antes de publicar

Esta versión es **frontend de prueba**. Los informes enviados desde `formulario.html` se guardan únicamente en el `localStorage` del dispositivo que los envía. Eso sirve para comprobar el flujo y la interfaz, pero **no es todavía el almacenamiento compartido de la congregación**.

La siguiente fase debe conectar Barúc con **Google Apps Script + Google Drive**. Ahí se centralizarán los datos, tarjetas S-21-S, PDFs, asistencia y exportación ZIP.

No colocar datos reales de publicadores en un repositorio público de GitHub.
