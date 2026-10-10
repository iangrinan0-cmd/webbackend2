# App Android — Mente Detective

El proyecto Android empaqueta la interfaz web dentro de una WebView y funciona sin conexión. El progreso se guarda en el almacenamiento local de la aplicación.

## Obtener el APK
1. En GitHub, abre **Actions → Build Android APK**.
2. Ejecuta **Run workflow** si no hay una ejecución reciente.
3. Abre la ejecución terminada y descarga el artefacto **mente-detective-android**.
4. Extrae el ZIP e instala `app-debug.apk` en tu Android. Android puede pedir autorización para instalar desde esa fuente.

El APK generado por Actions es una compilación debug, adecuada para pruebas personales, no una versión firmada para publicar en Play Store.
