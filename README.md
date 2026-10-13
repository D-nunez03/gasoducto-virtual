Gasoducto Virtual Canalete - sitio web estático

Publicar: subir la carpeta completa tal cual (index.html + imágenes + carpeta t/ + edificios.json)
a cualquier hosting estático con HTTPS. Abrir la URL de la carpeta (carga index.html).

Embeber en ArcGIS StoryMaps: bloque "Insertar" (Embed) -> pegar la URL https -> mostrar como "Interactivo"/"Incrustado".
Recomendado: bloque a ancho completo o dentro de un "Sidecar"/"Immersive" a pantalla completa.

Nota: la página necesita internet para cargar la librería 3D (cdnjs.cloudflare.com) y las fuentes (Google Fonts).
No se puede abrir con doble clic desde el disco: el navegador bloquea la carga de imágenes desde file://.
Para probar en local: en la carpeta, ejecutar  python -m http.server 8000  y abrir http://localhost:8000
