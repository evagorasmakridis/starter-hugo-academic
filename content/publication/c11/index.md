---
title: "Distributed Gradient-Tracking Optimization with Packet-Error Resilience in Unreliable Networks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Sindri Magnusson
- Themistoklis Charalambous

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2025-10-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Conference on Decision and Control (CDC)*

abstract: "In this paper, we address the distributed optimization problem over unreliable error-prone directed networks. We propose a distributed gradient-tracking optimization algorithm (referred to as ARQ-OPT), which exploits packet retransmissions via an Automatic Repeat reQuest (ARQ) error control protocol. Nodes utilize acknowledgement messages transmitted over one-bit error-free channels to trigger retransmissions of packets that were previously received in error. This ensures reliable propagation of information throughout the network, even in the presence of packet errors. We analyze the convergence properties of the proposed algorithm, by augmenting the consensus matrices to align with the retransmission mechanism. Subsequently, we show that by appropriately choosing the maximum number of retransmission attempts, ARQ-OPT can achieve B-step consensus contractivity which allow us to establish asymptotic convergence to the unique optimal solution with probability one. Numerical simulations conducted under various channel conditions validate our ﬁndings."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [distributed optimization, directed graphs, ARQ, time-varying delays, packet-errors, gradient tracking.]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
#- name: Demo Video
#  url: https://www.youtube.com/watch?v=pEBHR3MTPuA

url_pdf: 'https://www.evagoras.org/publication/c11/example.pdf'
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
