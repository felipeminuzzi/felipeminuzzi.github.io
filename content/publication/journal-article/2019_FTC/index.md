---
title: "Simulation of methane/air non-premixed turbulent flames based on REDIM simplified chemistry"
authors:
- admin
- Chunkan Yu
- Ulrich Maas
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2019-01-01T00:00:00Z"
doi: "https://doi.org/10.1007/s10494-019-00059-3"

# Schedule page publish date (NOT publication's date).
publishDate: "2019T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Flow, Turbulence and Combustion, v. 103, p. 963-984"
publication_short: ""

abstract: Combustion simulations involve the modeling of chemical kinetics, and due to the complexity of detailed mechanisms, chemistry reduction techniques are necessary. One model reduction strategy is the reaction-diffusion manifold (REDIM) method, and to obtain the REDIM, an evolution equation must be solved till its stationary solution and a gradient estimation is needed, provided e.g. from flamelet solutions with detailed chemistry. In this work, the REDIM technique is applied to simulate methane/air turbulent flames based on a simplified gradient estimation. This strategy uses less information in constructing the REDIM, increasing computational efficiency while reducing computational costs. Validation is performed for non-premixed laminar flames. A RANS/transported-PDF framework for the simulation of turbulent reacting flows is presented and used to validate the proposed model. Results show that the simplified gradient estimation is enough to simulate turbulent flames at moderate Reynolds number, which demonstrates the suitability of REDIM as reduced kinetic model in reactive flows.

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