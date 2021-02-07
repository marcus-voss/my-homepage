---
title: "Residential short-term load forecasting using convolutional neural networks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Christian Bender-Saebelkampf
- Sahin Albayrak

# Author notes (optional)
author_notes: []

date: "2018-12-27T00:00:00Z"
doi: "https://doi.org/10.1109/SmartGridComm.2018.8587494"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-31T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2018 IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm)*
publication_short: In *2018 IEEE SmartGridComm*

abstract: "Low aggregations of electric load profiles are more fluctuating, relative forecast errors are comparatively high, and it has been shown that different forecast models and feature configurations may be best suitable for specific households or buildings. However, at low aggregations, the monetary incentive for manual feature engineering and model selection is low, as benefits from forecast improvements are small. Convolutional Neural Networks (CNN) have proven to achieve high accuracy in an end-to-end fashion with minimal effort for manual feature selection. WaveNet, a CNN-based approach, has been developed to handle noisy time-series data for speech recognition and synthesis. In this work we explore if WaveNet is suitable for short-term forecasts of lowly aggregated electric loads. We find that WaveNet performs similarly to, and slightly better than, typical benchmark models for individual households, at the cost of higher model complexity. Preliminary experiments show that transfer learning can further improve results and decrease training times for individual households, as a pattern such as the correlation between outside temperature and load can be learned as general features. For aggregations of 10-200 households WaveNet improves most over the benchmarks, e.g., 13% compared to vanilla Artificial Neural Networks at 200 households, making it possibly suitable for aggregated load forecasting."

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.researchgate.net/publication/329958886_Residential_Short-Term_Load_Forecasting_Using_Convolutional_Neural_Networks'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

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