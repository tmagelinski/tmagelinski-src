---
title: "Measuring Node Contribution to Community Structure with Modularity Vitality"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Mihovil Bartulovic
- Kathleen M. Carley

# Author notes (optional)
author_notes:
- ""
- ""

date: "2020-12-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-31T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "In *IEEE Transactions on Network Science and Engineering*"
publication_short: "In *IEEE TNSE*"

abstract: "Community-aware centrality is an emerging research area in network science concerned with the importance of nodes in relation to community structure. Measures are a function of a network's structure and a given partition. Previous approaches extend classical centrality measures to account for community structure with little connection to community detection theory. In contrast, we propose cluster-quality vitality measures, i.e., modularity vitality, a community-aware measure which is well-grounded in both centrality and community detection theory. Modularity vitality quantifies positive and negative contributions to community structure, which indicate a node's role as a community bridge or hub. We derive a computationally efficient method of calculating modularity vitality for all nodes in O(M + NC) time, where C is the number of communities. We systematically fragment networks by removing central nodes, and find that modularity vitality consistently outperforms existing community-aware centrality measures. Modularity vitality is over 8 times more effective than the next-best method on a million-node infrastructure network. This result does not generalize to social media communication networks, which exhibit extreme robustness to all community-aware centrality attacks. This robustness suggests that user-based interventions to mitigate misinformation diffusion will be ineffective. Finally, we demonstrate that modularity vitality provides a new approach to community-deception."

# Summary. An optional shortened abstract.
summary: "We show that modularity vitality, or the difference between the modularity of a graph with and without a node, can be used to measure that node's contribution to community structure. We also derive a scalable way of computing this for all nodes. We then show that this measure identifies nodes which are more important to network integrity than existing measures can. This method fragmentes the PA Road network over 8 times more effectively than previous methods."

tags:
- Community Detection

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Full Paper
  url: https://ieeexplore.ieee.org/document/9314244

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
  caption: 'Fragmentation of the PA Road Network. Our measures overlap, clearly fragmenting the network fastest.'
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
