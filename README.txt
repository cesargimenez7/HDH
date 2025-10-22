Instrucciones - Proyecto LibroAR

Contenido:
 - index.html         -> archivo de la escena AR (usa marker.patt por defecto)
 - portadalibro.jpg  -> la portada que querés usar como marcador
 - marker.patt        -> archivo patrón (placeholder). Tenés que generar el .patt real.
 - diablo.glb         -> tu modelo 3D (ya incluido)

Importante:
Para que la portada funcione como marcador, necesitás convertir 'portadalibro.jpg' en un archivo de patrón 'marker.patt'.

Recomendación rápida (online):
 - Abrí el generador de marcadores de AR.js: https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html
 - Subí 'portadalibro.jpg' y descargá el archivo .patt generado.
 - Reemplazá el archivo 'marker.patt' en esta carpeta por el que descargues.

Cómo probar localmente:
 1) Abrí una terminal en esta carpeta.
 2) Ejecutá: python -m http.server 8000
 3) Abrí en el navegador: http://localhost:8000
 4) Permití acceso a la cámara y apuntá la cámara a la portada impresa.

Ajustes si el modelo no aparece:
 - Cambiá el valor de 'scale' en index.html.
 - Probá diferentes rotaciones (rotation="-90 0 0" ó "0 0 0").
 - Aumentá la intensidad de las luces.

Si querés, yo puedo intentar generar el marker.patt por vos si me confirmás que está bien usar la portada completa y me permitís usar una herramienta online (necesitaría acceso a internet), o te lo dejo para que lo generes localmente con las instrucciones.

Hecho por ChatGPT - Proyecto LibroAR
