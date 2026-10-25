# t-children 

Tarea "Del prototipo al código (I)" de Desarrollo de Interfaces, 2.º DAM.

En este proyecto he preparado una pantalla de mi app de ropa infantil para poder construirla después en Android Studio. La pantalla elegida es **Inicio de sesión**. Tiene el logo, una cabecera con título, dos cajas para escribir (correo y contraseña), un enlace para registrarse y un botón para entrar.

## Qué hay en el repositorio

- `app/`: el proyecto de Android Studio.
- `docs/`: la memoria en PDF (con el árbol de la pantalla, la ficha de medidas y colores, el inventario de imágenes, la captura de la app y mi reflexión).
- `.gitignore`: para no subir archivos que no hacen falta (`build`, `.gradle`, `.idea` y `local.properties`).

El enlace de mi diseño de Figma está en la primera página de la memoria.

## Cómo está creado el proyecto

- Tipo de proyecto: Empty Views Activity.
- Lenguaje: Java.
- Versión mínima de Android: API 28.
- ViewBinding: activado.
- La pantalla se llama `InicioSesionActivity` y su diseño es `activity_inicio_sesion.xml`.

## Qué he preparado

- **Colores, textos, estilos de letra y tema:** guardados en la carpeta `res/values`, con los datos de mi diseño.
- **Fuentes:** en la carpeta `res/font`.
- **Logo:** en formato WebP, en la carpeta `res/drawable-xxhdpi`, con el nombre `img_logo`.

## Cómo probarlo

1. Descargar el repositorio y abrirlo con Android Studio.
2. Esperar a que termine de cargar.
3. Elegir un móvil virtual (emulador) y pulsar el botón verde de Run.

La app todavía no tiene la pantalla construida, porque eso se hace en la siguiente tarea.
