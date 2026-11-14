# Noosfera TAO — Descargas

Instaladores oficiales de Noosfera TAO. Este repositorio solo contiene las
**releases**; el código fuente es privado.

➡️ **[Última versión](https://github.com/Raulcadiz/noosfera-descargas/releases/latest)**

| Archivo | Para qué |
|---|---|
| `Noosfera-TAO-Setup-<versión>.exe` | App de escritorio para Windows: chat con modelos locales, red y nodo. Se actualiza sola desde aquí. |
| `noosfera-android-<versión>.apk` | Nodo ligero para Android (red; sin chat ni cosecha). |
| `noosfera-nodo-<fecha>.zip` | Núcleo del nodo (Python) para cosechar brotes en otro PC. Descomprimir y ejecutar `INSTALAR.bat`. |

## Antes de instalar

- **Comprueba la huella.** Cada release lista el SHA-256 de cada archivo. En
  PowerShell: `Get-FileHash .\archivo -Algorithm SHA256`. Si no coincide, no lo
  instales.
- **Windows SmartScreen** puede avisar de que el instalador no está firmado:
  todavía no tiene certificado de firma de código.
- **El APK** se instala fuera de Google Play: Android pedirá permiso para
  instalar aplicaciones de origen desconocido.
- **Modelos:** la app no incluye modelos GGUF. Colócalos en
  `%USERPROFILE%\.noosfera\models`.

## Qué no es

La red y las recompensas están en desarrollo. Hoy no se paga nada y nada de
este proyecto es una inversión ni una promesa de ganancia.

## Licencia

Business Source License 1.1 (ver el archivo LICENSE que acompaña a la app).
