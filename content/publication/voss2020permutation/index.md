---
title: "An example conference paper"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
author_notes: []

date: "2020-06"
doi: "https://doi.org/10.1145/3396851.3397731"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-31T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In e-Energy '20 Proceedings of the Eleventh ACM International Conference on Future Energy Systems
publication_short: In ACM e-Energy '20

abstract: What makes a household-level short-term load forecast "good"? Individual household load profiles are intermittent, as distinct peaks correspond to specific activities in the household. Using traditional point-wise error metrics to assess household-level forecasts may lead to, for instance, double-digit mean absolute percentage errors. One reason is a double penalty incurred if a peak is forecasted correctly in amplitude, but with a small delay in time. An adjusted forecast error measure based on local permutations was proposed to assess household-level forecasts by optimally aligning the peaks bounded by a displacement limit. This work shows how the choice of this parameter leads to different "best" forecasts in terms of specific applications, namely the optimization objectives of an energy management system. For that, different parameterizations of the Local Permutation Invariant (LPI) distance are compared within k-Nearest Neighbors as a forecasting model for three different optimization objectives. A simulation study on 100 households of the CER dataset shows that the optimal parameterization can decrease the peak load on average by over 22.5% compared to the Euclidean distance. However, for increasing self-sufficiency and minimizing costs, no significant improvements can be achieved. This implies that household-level forecasts should generally be evaluated in terms of their application, as traditional metrics as a proxy may not express its "goodness" adequately.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.researchgate.net/publication/342291882_Permutation-Based_Residential_Short-term_Load_Forecasting_in_the_Context_of_Energy_Management_Optimization_Objectives'
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
  caption: ''
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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
