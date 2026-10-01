# Vozi — versión 1

PWA estática para practicar pronunciación, entonación, fluidez y vocabulario.

## Qué debes subir a Hostinger

Sube estos **cinco archivos** dentro de `public_html/`:

- `index.html` — estructura de la aplicación y menú inferior.
- `styles.css` — colores, diseño móvil, tipografías y animaciones.
- `app.js` — rutina de 10 pasos, actividades, rachas y progreso.
- `manifest.json` — permite instalar Vozi como aplicación.
- `service-worker.js` — guarda recursos para funcionar sin conexión.

`README.md` es solo documentación: puedes subirlo o dejarlo fuera.

## Cómo publicarla

1. Entra a **hPanel → Administrador de archivos**.
2. Abre la carpeta `public_html` (o la carpeta del dominio).
3. Sube los cinco archivos indicados.
4. Si existe otro `index.html`, reemplázalo únicamente si corresponde a este sitio.
5. Abre tu dominio usando `https://`.
6. En el teléfono, usa “Añadir a pantalla de inicio” para instalarla.

## Datos y privacidad

La versión 1 no usa base de datos ni cuentas. El progreso y la racha se guardan en `localStorage`, dentro del navegador y dispositivo donde uses Vozi. Si borras los datos del navegador, se pierde ese progreso.

## Cómo está organizada la rutina

`app.js` contiene diez pasos y un banco de ejercicios rotativo para 20 sesiones. El contenido se puede editar buscando `const seeds`.

## Próximas versiones posibles

- V2: más actividades y calendario mensual.
- V3: grabación real de voz con `MediaRecorder`.
- V4: PHP/MySQL para sincronizar varios dispositivos.
