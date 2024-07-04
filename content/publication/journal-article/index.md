---
title: "A deep learning approach to predict significant wave height using long short-term memory"
authors:
- admin
- Leandro Farina
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-01-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.ocemod.2022.102151"

# Schedule page publish date (NOT publication's date).
publishDate: "2023"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Ocean Modelling, "
publication_short: ""

abstract: We present a new deep learning training framework for forecasting significant wave height on the Southwestern Atlantic Ocean. We use the long short-term memory algorithm (LSTM), trained with the ERA5 dataset and also with buoy data. The forecasts are made for seven different locations in the Brazilian coast, where buoy data are available. We consider four different lead times, e.g., 6, 12, 18 and 24 h. Experiments are conducted using exclusively historical series at the selected locations. The influence of other variables as inputs for training is investigated. Results of the LSTM forecast show that a data-driven methodology can be used as a surrogate to the computational expensive physical models and also as an alternative to the reanalysis data. Accuracy of the forecasted significant wave height is close to 87% when compared to real buoy data.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
# featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/abs/2201.00356
url_code: 'https://github.com/felipeminuzzi/lstm-ocean'
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