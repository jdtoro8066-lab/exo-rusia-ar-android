# EXO – Rusia AR: APK sin Android Studio

Este proyecto abre https://jdtoro8066-lab.github.io/rusia-ar/ en el navegador del teléfono y utiliza tu ícono EXO.

## Crear el APK con GitHub Actions

1. En GitHub crea un repositorio nuevo, preferiblemente privado, por ejemplo `exo-rusia-ar-android`.
2. Sube **el contenido de esta carpeta** a la raíz del repositorio (incluyendo la carpeta oculta `.github`). No subas la carpeta contenedora por encima.
3. Abre la pestaña **Actions** de ese repositorio.
4. Elige **Crear APK EXO Rusia AR** y presiona **Run workflow** si no se ejecutó automáticamente.
5. Espera a que el trabajo termine en verde. Abre la ejecución y, en **Artifacts**, descarga **EXO-Rusia-AR-APK**.
6. Descomprime ese archivo para obtener `app-debug.apk` e instálalo en el Android.

**Importante:** este ZIP es el proyecto, no un APK ya compilado. La compilación se realiza en GitHub. Para instalar APK descargados fuera de Google Play, Android podría pedir habilitar permisos de instalación. La experiencia AR depende de un navegador compatible, conexión a Internet y permisos que solicite la web.
