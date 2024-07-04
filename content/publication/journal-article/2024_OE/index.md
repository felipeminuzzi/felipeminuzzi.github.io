---
title: "Artificial neural networks ensemble methodology to predict significant wave height"
authors:
- admin
- Leandro Farina
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2024"
doi: "https://doi.org/10.1016/j.oceaneng.2024.117479"

# Schedule page publish date (NOT publication's date).
publishDate: "2023"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Ocean Engineering, 300, 117479"
publication_short: ""

abstract: The forecast of wave variables are important for several applications that depend on a better description of the ocean state. Due to the chaotic behaviour of the differential equations which model this problem, a well know strategy to overcome the difficulties is basically to run several simulations, by for instance, varying the initial condition, and averaging the result of each of these, creating an ensemble. Moreover, in the last few years, considering the amount of available data and the computational power increase, machine learning algorithms have been applied as surrogate to traditional numerical models, yielding comparative or better results. In this work, we present a methodology to create an ensemble of different artificial neural networks architectures, namely, MLP, RNN, LSTM, CNN and a hybrid CNN–LSTM, which aims to predict significant wave height on six different locations in the Brazilian coast. The networks are trained using NOAA’s numerical reforecast data and target the residual between observational data and the numerical model output. A new strategy to create the training and target datasets is demonstrated. Results show that our framework is capable of producing high efficient forecast, with an average accuracy of 80%, that can achieve up to 88% in the best case scenario, which means 5% reduction in error metrics if compared to NOAA’s numerical model, and a increasingly reduction of computational cost.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: 'https://github.com/felipeminuzzi/ensemble-wave-prediction'
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