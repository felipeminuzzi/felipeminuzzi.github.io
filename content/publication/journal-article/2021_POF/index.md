---
title: "A novel model for incorporation of differential diffusion effects in PDF simulations of non-premixed turbulent flames based on reaction-diffusion manifolds (REDIM)"
authors:
- Chunkan Yu
- Paola Breda
- admin
- Michael Pfitzner
- Ulrich Maas
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021-01-01T00:00:00Z"
doi: "https://doi.org/10.1063/5.0039160"

# Schedule page publish date (NOT publication's date).
publishDate: "2021T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: " Physics of Fluids, v. 33, n. 2"
publication_short: ""

abstract: In this work, reaction-diffusion manifold (REDIM) reduced chemistry is used in the simulation of turbulent non-premixed flames based on a transported-probability density function model. Differential molecular diffusion is applied in the generation of the manifolds. This is the first work to consider the gradients of the reduced variables as additional parameters in the REDIM model, and one-directional gradients are utilized to generate the REDIM reduced chemistry. Hereby, the influence of turbulence on differential molecular diffusion is automatically considered in terms of reduced variable gradients, and the physical transport properties (e.g., diffusion coefficients) are used in a detailed way, without any additional modeling (e.g., unity-Lewis number assumption). Although the scalar gradients appear as multi-directional in a general turbulent reacting flow, previous direct numerical simulation analysis reveals that REDIMs generated from one-directional gradients can accurately describe the system featuring multi-directional gradients, if this one-directional gradient has a major effect on the chemistry. Here, it is proposed to obtain such gradients under the hypothesis that the flame structure is locally one-dimensional at each spatial position. In order to retrieve the gradients of the reduced variables for the interpolation of the thermo-kinetic states from the REDIM table, the sub-grid gradient is evaluated here from the particle fields. The well-known Sandia series of flames is selected to validate the proposed algorithm. The results show that the new algorithm can reproduce the thermo-kinetic quantities with high accuracy for all investigated flames.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
# \\- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---