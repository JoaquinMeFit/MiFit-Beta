# MiFit — aplicación personal (versión 1.0)

Incluye interfaz oscura adaptable, plan semanal editable de siete días, registro de entrenamientos, comidas, despensa, progreso, recordatorio preferido, guardado local con IndexedDB, exportación/importación JSON y caché offline.

## Importante
Este proyecto todavía no está publicado en Internet ni instalado en tu iPhone. Para instalarlo como aplicación hay que alojarlo en una dirección HTTPS.

### Publicación gratuita con GitHub Pages
1. Crea/inicia sesión en GitHub y crea un repositorio llamado `mifit`.
2. Sube el contenido de esta carpeta a la raíz del repositorio.
3. En **Settings → Pages**, elige **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guarda.
4. Espera a que GitHub Pages genere la URL HTTPS.

### Instalar en iPhone
1. Abre la URL publicada en Safari.
2. Pulsa Compartir → **Agregar a pantalla de inicio**.
3. Confirma el nombre MiFit y pulsa Agregar.

### Datos y recordatorios
Los registros se guardan localmente en el navegador/dispositivo; no se sincronizan entre dispositivos. Exporta respaldos periódicamente. Si borras los datos del navegador o desinstalas la PWA podrías perderlos.

La versión 1.0 guarda tu preferencia de hora y texto para recordatorios, pero no envía notificaciones automáticas con la app cerrada. Eso requiere configurar un servicio adicional.

Archivos: `index.html`, `manifest.webmanifest`, `service-worker.js`, `icons/`.
