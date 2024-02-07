---
title: "Reinforcement Learning for Link Adaptation in 5G-NR Networks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-02-15T00:00:00Z"
doi: "https://www.diva-portal.org/smash/record.jsf?pid=diva2:1527910"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: In *TRITA-EECS-EX ; 2020:909*
#publication_short: In *ETFA*

abstract: The Adaptive Modulation and Coding (AMC) scheme in the link adaptation is a core feature in the current cellular networks. In particular, based on Channel Quality Indicator (CQI) measurements that are computed from the Signal-to-Interference-plus-Noise Ratio (SINR) level of User Equipment (UE), the base station (e.g., Next Generation NodeB (gNB)) selects a Modulation and Coding Scheme (MCS) to be used for the next downlink transmission. However, communication channels are inherently variant due to changes in traffic load, user mobility, and transmission delays and thus the estimation of the SINR levels at the transmitter side usually deviates from the actual value. The Outer-Loop Link Adaptation (OLLA) technique was proposed to improve the channel quality estimation by adjusting the value of SINR by an offset dependent on whether previous transmissions were decoded successfully or not captured by Hybrid Automatic Repeat Request (HARQ) feedback. Although this technique indeed improves the user throughput, it typically takes several Transmission Time Intervals (TTIs) to converge to a certain SINR value that fulfills a predefined target Block Error Rate (BLER). As a result, the slow convergence speed of the OLLA mechanism causes inaccurate MCS selection specially for users with bursty traffic, while it needs to be a priori tuned with a fixed BLER target. These factors lead to degraded network performance, in terms of throughput and spectral efficiency. To cope with these challenges, in this project we propose a reinforcement learning (RL) framework where an agent takes observations from the environment (e.g., from UEs and the network) and learns proper policies that adjust the estimated SINR, such that a reward function (i.e., the UE normalized throughput) is maximized. This framework was designed and developed in a radio network system-level simulator, while for the agents using RL (hereafter called RL agents), Deep Q-Network (DQN) and Proximal Policy Optimization (PPO) models were trained accordingly. Both models showed significant increment of about 1.6% - 2.5% and 10% - 17% on the average throughput for mid-cell and cell-edge users respectively, over the current state-of-the-art OLLA mechanism. Finally, setting a priori a fixed BLER target is not needed, and hence the RL-based link adaptation performs well in diverse radio conditions. 

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudincondimentum.

tags: [Reinforcement Learning, Link Adaptation, 5G Networks, DQN, PPO, Optimization]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'example.pdf'
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
