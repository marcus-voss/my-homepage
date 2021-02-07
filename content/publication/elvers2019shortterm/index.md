---
title: "Short-term probabilistic load forecasting at low aggregation levels using convolutional neural networks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Alexander Elvers
- admin
- Sahin Albayrak

# Author notes (optional)
author_notes: []

date: "2019-08-26T00:00:00Z"
doi: "10.1109/PTC.2019.8810811"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-31T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2019 IEEE Milan PowerTech*
publication_short: In *PowerTech 2020*

abstract: "Lowly aggregated load profiles such as of individual households or buildings are more fluctuating and relative forecast errors are comparatively high. Therefore, the prevalent point forecasts are not sufficiently capable of optimally capturing uncertainty and hence lead to non-optimal decisions in different operational tasks. We propose an approach for short-term load quantile forecasting based on convolutional neural networks (STLQF-CNN). Historical load and temperature are encoded in a three-dimensional input to enforce locality of seasonal data. The model efficiently minimizes the pinball loss over all desired quantiles and the forecast horizon at once. We evaluate our approach for day-ahead and intra-day predictions on 222 house-holds and different aggregations from the Pecan Street dataset. The evaluation shows that our model consistently outperforms a naïve and an established linear quantile regression benchmark model, e.g., between 21 and 29 % better than the best benchmark on aggregations of 10, 20 and 50 households from Austin."

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.researchgate.net/publication/332370250_Short-Term_Probabilistic_Load_Forecasting_at_Low_Aggregation_Levels_Using_Convolutional_Neural_Networks'
url_code: 'https://github.com/AlexElvers/stplfcnn'
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