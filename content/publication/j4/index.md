---
title: "A Fully Distributed LTI Estimation Scheme over Directed Graph Topologies"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Camilla Fioravanti
- Gabriele Oliva
- Maria Vrakopoulou
- Themistoklis Charalambous

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2024-05-16T00:00:00Z"
doi: "10.1109/LCSYS.2024.3402111"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Control Systems Letters (L-CSS)*
#publication_short: In *ETFA*

abstract: "This paper introduces a distributed state estimation scheme for linear time-invariant (LTI) discrete-time systems, where observers, with partial observation of the system, communicate with each other over a directed and strongly connected (but not necessarily balanced) graph topology and execute a predefined number of average consensus steps in-between estimation steps. Our methodology departs from previous works in the literature in that it does not require any degree of centralized design nor relies on procedures that might be prone to numerical instability. By leveraging ratio consensus and matrix perturbation theory, we establish a convergence-guaranteeing condition for the number of consensus iterations needed between the steps of the distributed estimation process. This condition becomes the blueprint for a distributed initialization procedure, which allows the agents to collectively select an adequate number of ratio consensus steps."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Distributed Estimation, Ratio Consensus, Ma- trix Perturbation Analysis, LTI Systems.]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

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
