---
layout: post
title: Agregar texto a imagenes con convert 
categories: [convert, imagemagick, imagenes]
---
Para agregar texto a imagenes con convert se puede usar el siguiente comando

```bash
convert imagen.jpg -gravity South -pointsize 10 -fill white -font Helvetica -annotate +0+10 'Mi texto en imagen' imagen2.jpg
```
Dónde: 

- gravity South es el punto a insertar el text, North, South, East, West (arriba, abajo...a)
- pointsize el tamaño de la fuente
- fill el color
- font el tipo de letra
- annotate la distancia en pixeles desde el punto referido en gravity (+0 pixeles en X +10 pixeles en Y)

