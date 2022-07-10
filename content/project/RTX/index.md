---
title: Ray Tracing Renderer
summary: A simple C++ implementation of ray tracing rendering, based on Monte Carlo path tracing.
tags:
- Others
date: "2020-01-10T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 'A rendered bunny in a colorful room.'
  focal_point: Right

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides= "ray_tracing"
---



This renderer supports Monte Carlo path tracing with reflection and refraction. Simple geometries (cubes, spheres, circles, cylinders, etc.) can be loaded in from .txt files, while complicated triangular meshes with uv textures and normal vector interpolation can be loaded from .obj files. Area lights are supported to create soft shadows. Moreover, we support depth of fields effects and achieve anti-aliasing by super-sampling. For more details, please click the button and redirect to the main slide.

