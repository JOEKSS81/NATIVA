# Volta Board

App para Onewheel, pensada para el **V1 original** con el BMS sin comunicar:
porcentaje de batería estimado por el voltaje, aviso por voz y vibración cada 10 %,
alarma de voltaje bajo, autonomía según tu gasto real e informe mensual de la batería.

- **Web**: carpeta `web/`, publicada en Vercel.
- **APK**: carpeta `android/` (Trusted Web Activity). GitHub Actions lo compila en cada cambio
  y lo deja en **Releases** → [descargar el último APK](../../releases/latest/download/VoltaBoard.apk).

## Instalar en Android
1. Descarga `VoltaBoard.apk` desde Releases con el móvil.
2. Ábrelo y permite instalar apps de origen desconocido.
3. Debe estar instalado Google Chrome (la app usa su Bluetooth y su voz).
4. Si la voz suena en otro idioma: Ajustes › Sistema › Idiomas › Salida de texto a voz ›
   Google › Instalar datos de voz › Español (España), y elige la voz en Ajustes de la app.
