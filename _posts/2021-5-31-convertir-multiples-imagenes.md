---
layout: post
title: Agregar texto a imagenes con convert 
categories: [convert, imagemagick, imagenes]
tags: [convert, imagemagick, imagenes]
---

Para cambiar de formato varias imágenes con `convert` de ImageMagick se puede usar el siguiente script: 

```bash

for PHOTO in *.jpg
   do
        convert "$PHOTO" "$PHOTO.webp"
   done

```

