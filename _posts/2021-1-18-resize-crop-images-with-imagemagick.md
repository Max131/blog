---
layout: post
title: How to resize and crop images with different sizes with imagemagick
---
## How to resize and crop images with different sizes with imagemagick

If you need to resize and crop images with different sizes, don't panic, solve it with `mogrify` content in Imagemagick


```bash
mogrify -resize "300x200^" -gravity center -extent "300x200" *
```
This command will resize and crop all images in the current directory, the size will be "300x200" pixels, it will crop the excedent
- `resize`, the option that resize the image
- `gravity` resize and take the center as reference to crop excedent
- `extent` crop the image excedent
