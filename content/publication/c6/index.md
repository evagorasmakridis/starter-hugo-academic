---
title: "Harnessing HARQ Retransmissions for Fast Average Consensus over Unreliable Communication Channels"

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

date: "2023-10-23T00:00:00Z"
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

abstract: "In this work, we introduce a new consensus mechanism by incorporating a Hybrid Repeat reQuest (HARQ) error control protocol into the Ratio Consensus (RC) algorithm to achieve fast discrete-time asymptotic average consensus in the presence of packet retransmissions (information delays), and packet-dropping  links (information loss) over directed networks. Using this consensus mechanism (hereinafter referred to as HARQ-RC), each transmitting node decides whether to retransmit packets (containing values of consensus variables) to its out-neighbors by utilizing their HARQ feedback signals. Under this protocol, each receiving node may detect the corrupted part of the received packet, and by combining successfully received information from previous retransmission trials, it may recover the information of the packet. This mechanism leads in a lower number of retransmission trials compared to standard ARQ mechanism, and hence the consensus iterations converge faster to the average consensus value. By introducing the weighted adjacency matrix that models the HARQ-based information exchange between nodes, we show that the nodes are guaranteed to reach asymptotic average consensus using the HARQ-RC mechanism despite the information delays and losses. The effectiveness of the HARQ-RC over bad communication links, with respect to achieving faster convergence to the average consensus value, is demonstrated under different simulation scenarios."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [average consensus,ratio consensus,unreliable wireless networks,transmission delays,packet drops,HARQ.]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
#- name: Demo Video
#  url: https://www.youtube.com/watch?v=pEBHR3MTPuA

url_pdf: 'https://www.evagoras.org/publication/c6/example.pdf'
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
