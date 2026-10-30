# Almacén de contenido de @tallerito.pe
Imágenes, videos e historias que se publican en Instagram (Instagram necesita una URL pública para cada archivo).
- `media/`: archivos listos para publicar.
- `cola.json`: calendario de publicación. Cada elemento tiene `fecha_utc`, `tipo` (reel, carrusel, imagen, historia, historias), `urls`, `caption` y `estado` (pendiente → publicado).
Solo contiene contenido publicitario que ya es o será público; nunca datos de clientes ni secretos.
