# Ejercicio 01 — Tarjeta de Perfil

Descripción:

- Se creó una tarjeta de perfil centrada usando HTML semántico y CSS.

Archivos creados/actualizados:

- [index.html](index.html): Estructura semántica con `header`, `main`, `section` (tarjeta) y `footer`. Incluye avatar, `h1` con nombre, biografía, lista de habilidades y enlaces sociales.
- [styles.css](styles.css): Estilos generales, importación de Google Fonts, y reglas clave:
	- `.profile-card { max-width: 380px; margin: 40px auto; padding: 24px; border-radius: 12px; }`
	- `.avatar { width: 120px; height: 120px; border-radius: 50%; object-fit: cover; }`
- [script.js](script.js): Pequeña interacción (alerta desde botón demo) y log de carga.

Cómo probar:

1. Abrir la carpeta `ejercicio-01` en el explorador de archivos.
2. Abrir [index.html](index.html) en el navegador (doble clic) o desde terminal con:

```bash
# desde la carpeta ejercicio-01 en Windows
start index.html
```

Aceptación (verificación visual):

- Al cargar la página se debe ver una tarjeta centrada con foto circular, nombre en `h1`, biografía corta, lista de habilidades y enlaces sociales estilizados.

Si quieres, puedo:

- Añadir una imagen `avatar.jpg` local en la carpeta en lugar de usar el placeholder.
- Hacer el commit de los cambios y preparar un breve CSS alternativo para modo oscuro.
