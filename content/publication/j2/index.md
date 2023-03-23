---
title: "ARQ-based Average Consensus over Unreliable Directed Network Topologies"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Themistoklis Charalambous
- Christoforos N. Hadjicostis

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2022-12-15T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2209.14699"

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

abstract: "In this paper, we address the problem of discrete-time average consensus, where agents (nodes) exchange information over unreliable communication links. We enhance the Robustified Ratio Consensus algorithm by exploiting features of the Automatic Repeat ReQuest (ARQ) protocol used for error control of data transmissions, in order to allow the agents to reach asymptotic average consensus even when operating within unreliable directed networks. This strategy, apart from handling time-varying delays induced by retransmissions of erroneous packets (which can be captured by the Robustified Ratio Consensus as well), can also handle packet drops that occur when exceeding a predefined packet retransmission limit imposed by the ARQ protocol. Invoking the ARQ protocol allows nodes to: (a) exploit the incoming error-free acknowledgement feedback signals to initially acquire or later update their out-degree, (b) know whether a packet has arrived or not, and (c) determine a local upper-bound on the delays which is imposed by the retransmission limit. By augmenting the network's corresponding weighted adjacency matrix, to handle time-varying (yet bounded) delays and possible packet drops, we show that nodes can make use of the proposed algorithm, herein called the ARQ-based Ratio Consensus algorithm, to reach asymptotic average consensus, while maintaining low running sum values, despite the fact that the communication links are unreliable."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Average consensus, digraphs, ratio consensus, ARQ feedback, heterogeneous time-varying delays, packet drops]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2209.14699.pdf'
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
