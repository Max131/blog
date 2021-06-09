---
layout: post
title: Cómo redimiensionar y cortar imágenes con Imagemagick
categories: [imagenes, optimizar, cortar, redimiensionar, imagemagick]
tags: [imagenes, optimizar, cortar, redimiensionar, imagemagick]
---
## Cómo redimiensionar y cortar imágenes con diferentes medidas  con Imagemagick

Si necesitas redimiensionar y cortar imágenes con diferentes medidas, tranquilo, se soluciona de forma sencilla con `mogrify`, que está dentro del paquete de Imagemagick.


```bash
mogrify -resize "300x200^" -gravity center -extent "300x200" *
```
Este comando cambiará el tamaño y cortará todas las imágenes del directorio actual, el tamaño será de "300x200" pixeles y cortará el excedente en caso de que lo haya, puesto que el redimensionamiento se hará a partir del centro de la imagen para tomar adecuadamente las medidas dadas. 
- `resize`, la opción que redimensiona la imagen.
- `gravity` toma el centro de la imagen como referencia para cortar la imagen.
- `extent` corta el excedente en caso de que lo haya.
