---
layout: post
title: Optimizar imágenes jpg para la web
categories: [imagenes, optimizar]
---

# Cómo optimizar imágenes `jpg`



En GNU/Linux usar jpegoptim.


```bash
jpegoptim -f -m 80 -s --all-progressive *jpg
```
-f Forzar optimización
-m 80 para 80% de calidad
-s borrar metadatos
--all-progresive para imágenes progresivas