---
title: "Distributed Estimation and Control for LTI systems under Finite-Time Agreement"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Camilla Fioravanti
- admin
- Gabriele Oliva
- Maria Vrakopoulou
- Themistoklis Charalambous

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2024-02-28T00:00:00Z"
doi: "https://arxiv.org/abs/2402.17466"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv Preprint*
#publication_short: In *ETFA*

abstract: "This paper considers a strongly connected network of agents, each capable of partially observing and controlling a discrete-time linear time-invariant (LTI) system that is jointly observable and controllable. Additionally, agents collaborate to achieve a shared estimated state, computed as the average of their local state estimates. Recent studies suggest that increasing the number of average consensus steps between state estimation updates allows agents to choose from a wider range of state feedback controllers, thereby potentially enhancing control performance. However, such approaches require that agents know the input matrices of all other nodes, and the selection of control gains is, in general, centralized. Motivated by the limitations of such approaches, we propose a new technique where: (i) estimation and control gain design is fully distributed and finite-time, and (ii) agent coordination involves a finite-time exact average consensus subroutine, allowing arbitrary selection of the convergence rate of the overall asymptotic estimation process despite the estimator’s distributed nature. We verify our methodology’s effectiveness using illustrative numerical simulations."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Distributed Estimation, Distributed Control, Distributed Gain Design, LTI Systems, Finite-time Agreement.]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2402.17466'
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
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
