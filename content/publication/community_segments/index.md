---
title: "Community-based time segmentation from network snapshots"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Kathleen M. Carley

# Author notes (optional)
author_notes:
- ""
- ""

date: "2019-05-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "In *Applied Network Science*"
publication_short: ""

abstract: "Community detection has proved to be extremely successful in a variety of domains. However, most of the algorithms used in practice assume networks are unchanging in time. This assumption is violated for many datasets, resulting in incorrect or misleading communities. Many different algorithms to rectify this problem have been proposed. Most of them, however, focus on community evolution rather than abrupt changes. The problem of change detection is easier than that of community evolution, and is often sufficient. Here, we propose an algorithm for determining community-based change points from network snapshots. Networks can then be aggregated between change points, and analyzed without violating assumptions. There are three network types that we have defined our algorithm for, each having a case study: static nodesets, semi-static nodesets, and dynamic nodesets. The case studies for these network types are: the Ukrainian Legislature, the Enron email network, and Twitter data from Ukraine. We empirically verify our algorithm in each case study, and compare results to two popular alternatives: Generalized Louvain and GraphScope. We show the impracticality of Generalized Louvain and that our method is less sensitive than GraphScope. Lastly, we use our first two  case studies to determine optimal parameters for an anomaly-detection-based streaming method. We then demonstrate that the streaming method was capable of determining events both from data collection errors and from internal network disruptions."

# Summary. An optional shortened abstract.
summary: "We develop a procedure for finding time-segments of community stability in dynamic networks. This also functions as a community-based event detector. Applying this to the legislative voting network in Ukraine's 8th convocation, we identify the Euromaidan Revolution as a major event, and show that the network structure is vastly different before and after."

tags:
- Community Detection
- Network Dynamics
- Voting Networks

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Full Paper
  url: https://link.springer.com/article/10.1007/s41109-019-0136-1

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
image:
  caption: 'The voting network before and after our detected event, colored by Louvain grouping.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

