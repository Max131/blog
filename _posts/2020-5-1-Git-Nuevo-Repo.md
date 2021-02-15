---
layout: post
title: Agregar nuevo repo en consola
categories: [git]
---

# Cómo agregar un nuevo repositorio en la consola después de haberlo creado en Github


Después de creado el repositorio en Github, hacer esto en consola:

```bash
echo "# blog" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Max131/blog.git
git push -u origin master
```