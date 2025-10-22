---
title: "Remote Estimation over Packet-Dropping Wireless Channels with Partial State Information"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Ioannis Tzortzis
- admin
- Charalambos D. Charalambous
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
publication: In *European Control Conference (ECC)*

abstract: "In this paper, we address the problem of designing an optimal transmission policy for remote state estimation over packet-dropping wireless channels with imperfect channel
state information. We consider a setup where a smart sensor performs state estimation of a linear time-invariant (LTI) dynamical system using a Kalman filter. The resulting state
estimate obtained by the smart sensor at each discrete-time step, is transmitted over the wireless channel to a remote estimator. To balance the trade-off between information freshness and
reliability, we employ a Hybrid Automatic Repeat reQuest (HARQ) protocol at the smart sensor which has imperfect channel state information in the form of acknowledgment feedback
signal received by the remote estimator after its attempt to decode the information packets. We formulate this problem as a finite horizon Partially Observable Markov Decision Process
(POMDP) with an augmented state-space that incorporates both the Age of Information (AoI) and the unknown channel state. By defining an information state that serves as a sufficient
statistic for optimal decision-making by the smart sensor, we derive the dynamic programming equations for evaluating the optimal policy. This policy is computed numerically using the
point-based value iteration algorithm."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [remote state estimation, HARQ, POMDP, partial channel state information.]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
#- name: Demo Video
#  url: https://www.youtube.com/watch?v=pEBHR3MTPuA

url_pdf: 'https://www.evagoras.org/publication/c12/example.pdf'
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
