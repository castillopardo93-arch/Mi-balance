# Mi Balance para iPhone (PWA)

Versión instalable de Mi Balance, con dashboard, movimientos editables, categorías independientes y sincronización con Google Drive.

## Contenido

- `index.html`: app completa.
- `manifest.webmanifest`: configuración instalable.
- `sw.js`: service worker para caché de interfaz y uso con conectividad limitada.
- `icons/`: iconos para iOS y navegadores.
- `LEEME_PUBLICACION_IPHONE.txt`: guía de publicación y configuración de Google Drive.

## Requisitos

- Alojar los archivos en un origen HTTPS.
- Configurar Google Drive API y una credencial OAuth web cuyo origen autorizado coincida con el dominio publicado.
- En iPhone, abrir la URL en Safari y usar **Compartir → Añadir a pantalla de inicio**.

**Nota:** es una PWA instalable, no una app nativa distribuida por App Store. La sincronización remota requiere autorización de Google y conexión a internet.
