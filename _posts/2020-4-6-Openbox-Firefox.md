---
layout: post
title: Openbox & Firefox windows
categories : [firefox, openbox]
tags: [firefox, openbox]
---

# Cómo mostrar los botones de ventana de Firefox en Openbox



Para mostrar los botones de Firefox sin la  barra de título en Openbox, sólo hay que agregar la siguiente línea de código en el archivo indicado:

_.config/openbox/environment_

```bash
export XDG_CURRENT_DESKTOP=openbox
```