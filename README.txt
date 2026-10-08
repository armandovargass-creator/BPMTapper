BPM TAPPER
==========

Esta carpeta contiene una app Android independiente basada en la calculadora BPM original.
No requiere internet para funcionar y no solicita permisos de red.

OPCION SIN ANDROID STUDIO
-------------------------
El proyecto incluye un workflow de GitHub Actions en:
.github/workflows/build-apk.yml

Sube esta carpeta a un repositorio de GitHub, entra a Actions, selecciona
"Build BPM Tapper APK" y pulsa "Run workflow". Al terminar podrás descargar
el APK desde Artifacts.

OPCION ANDROID STUDIO
---------------------
Abre la carpeta BPMTapper como proyecto Gradle y ejecuta assembleDebug.

El APK generado será:
app/build/outputs/apk/debug/app-debug.apk
