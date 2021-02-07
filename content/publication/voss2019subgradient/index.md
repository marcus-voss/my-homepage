---
title: "Subgradient Methods for Averaging Household Load Profiles under Local Permutations"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Brijnesh Jain
- Sahin Albayrak

# Author notes (optional)
author_notes: []

date: "2019-08-26T00:00:00Z"
doi: "https://doi.org/10.1109/PTC.2019.8810783"

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

abstract: The sample mean is one of the most fundamental concepts in statistics with far-reaching implications for data mining and pattern recognition. Household load profiles are compared to the aggregated levels more intermittent and a specific error measure based on local permutations has been proposed to cope with this when comparing profiles. We formally describe a distance based on this error, the local permutation invariant (LPI) distance, and introduce the sample mean problem in the LPI space. An existing exact solution has exponential complexity and is only tractable for very few profiles. We propose three subgradient-based approximation algorithms and compare them empirically on 100 households of the CER dataset. We find that stochastic subgradient descent can approximate the mean best, while the majorize-minimize mean is a good compromise for applications as no hyperparameter-tuning is needed. We show how the algorithms can be used in forecasting and clustering to achieve more appropriate results than by using the arithmetic mean.

# Summary. An optional shortened abstract.
summary: "This paper introduces an approximation of the permutation invariant (LPI) sample mean to average smart meter load profiles, with applications in load forecasting and clustering."

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.researchgate.net/profile/Marcus_Voss/publication/332370098_Subgradient_Methods_for_Averaging_Household_Load_Profiles_under_Local_Permutations/links/5d304680458515c11c3975da/Subgradient-Methods-for-Averaging-Household-Load-Profiles-under-Local-Permutations.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://www.windnode.de/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Simplified depiction of the Fréchet function F of the LPI sample mean.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- windnode

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---