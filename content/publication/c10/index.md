---
title: "HARQ-based Quantized Average Consensus over Unreliable Directed Network Topologies"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Neofytos Charalambous
- admin
- Apostolos I. Rikos
- Themistoklis Charalambous

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2024-06-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *European Control Conference (ECC)*

abstract: "In this paper, we propose a distributed algorithm (herein called HARQ-QAC) that enables nodes to calculate the average of their initial states by exchanging quantized messages over a directed communication network. In our setting, we assume that our communication network consists of unreliable communication links i.e., links suffering from packet drops). 
For countering link unreliability our algorithm leverages narrowband error-free feedback channels for acknowledging whether a packet transmission between nodes was successful. Additionally, we show that the feedback channels play a crucial role in enabling our algorithm to exhibit finite-time convergence. We analyze our algorithm and demonstrate its operation via an example, where we illustrate its operational advantages. Finally, simulations corroborate that our proposed algorithm converges to the average of the initial quantized values in a finite number of steps, despite the packet losses. This is the first quantized consensus algorithm in the literature that can handle packet losses and converge to the average. Additionally, the use of the retransmission mechanism allows for accelerating the convergence."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [distributed coordination, average consensus, quantized communication, ARQ feedback, packet drops.]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
#- name: Demo Video
#  url: https://www.youtube.com/watch?v=pEBHR3MTPuA

url_pdf: 'https://www.evagoras.org/publication/c10/example.pdf'
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
