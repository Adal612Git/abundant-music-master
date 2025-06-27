# Guía de instalación y uso

## Instalación
1. Clona este repositorio.
2. Instala las dependencias ejecutando `npm install` en la raíz del proyecto.
3. Inicia la aplicación con `npm start` y abre `http://localhost:3000` en tu navegador.

## Primeros pasos
- El directorio `tutorials` incluye varios archivos HTML que explican cómo utilizar la herramienta. Puedes comenzar con [tutorials/index.html](tutorials/index.html) para ver el índice completo.
- Para conocer las opciones de exportación a audio revisa [tutorials/render_and_play_songs.html](tutorials/render_and_play_songs.html), que describe cómo generar archivos Midi, Mp3 u Ogg.
- Si deseas profundizar en el cambio de instrumentos y otros parámetros abre [tutorials/details.html](tutorials/details.html) y [tutorials/sub_seeds.html](tutorials/sub_seeds.html).

## Cambiar instrumentos
1. Abre la ventana **Song Settings** desde la interfaz de Abundant Music.
2. Dirígete a la pestaña **Details** para seleccionar instrumentos específicos para la melodía, bajo, percusión y voces internas.
3. También puedes modificar las "seeds" relacionadas con los instrumentos en la pestaña **Sub Seeds**, como se explica en `tutorials/sub_seeds.html`.

## Exportar audio
1. Selecciona la opción **Export** en la aplicación.
2. Elige el formato deseado (Mp3, Ogg o Midi) y presiona el botón correspondiente, tal como se muestra en `tutorials/render_and_play_songs.html`.
3. Cuando aparezca el enlace de resultado, guárdalo para conservar el archivo generado.
