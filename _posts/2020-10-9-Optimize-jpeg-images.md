---
layout: post
title: Optimize jpeg images for the web
---

# How to optimize jpef images



In GNU/Linux just use jpegoptim


```bash
jpegoptim -f -m 80 -s --all-progressive *jpg
```
-f Force optimization
-m 80 for 80% of quality
-s strip metadata
--all-progresive self explained