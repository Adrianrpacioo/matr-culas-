REGISTRO DE VEHÍCULOS — PWA

Contenido:
- index.html: aplicación
- manifest.webmanifest: configuración instalable
- sw.js: caché offline
- icon.svg: icono

Instalación en iPhone:
1. Sube estos archivos a un alojamiento HTTPS estático (por ejemplo, un repositorio GitHub Pages privado/público según tus preferencias, o un hosting propio con HTTPS).
2. Abre la URL en Safari en el iPhone.
3. Toca Compartir > Añadir a pantalla de inicio.
4. Abre la app instalada una vez con conexión para que se almacenen los recursos offline.

Los registros y marcas se guardan en IndexedDB del navegador/dispositivo; no se envían a un servidor.
Exporta JSON periódicamente desde Historial para realizar copias de seguridad. La importación combina registros por ID.
Para mantener la app actualizada, reemplaza los archivos del hosting y vuelve a abrir la PWA.

Aviso:
La app no es un sistema oficial ni está integrada con bases policiales. Protege el dispositivo y usa los datos conforme a la normativa, protocolos y autorizaciones aplicables. No almacena identidad del conductor ni datos personales adicionales.
