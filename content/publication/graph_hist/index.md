---
title: "Graph-Hist: Graph Classification from Latent Feature Histograms with Application to Bot Detection"
authors:
- admin
- David Beskow
- Kathleen M. Carley
author_notes:
- ""
- ""
date: "2020-02-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*AAAI 2020*"
publication_short: ""

abstract: "Neural networks are increasingly used for graph classification in a variety of contexts. Social media is a critical application area in this space, however the characteristics of social media graphs differ from those seen in most popular benchmark datasets. Social networks tend to be large and sparse, while benchmarks are small and dense. Classically, large and sparse networks are analyzed by studying the distribution of local properties. Inspired by this, we introduce Graph-Hist: an end-to-end architecture that extracts a graph's latent local features, bins nodes together along 1-D cross sections of the feature space, and classifies the graph based on this multi-channel histogram. We show that Graph-Hist improves state of the art performance on true social media benchmark datasets, while still performing well on other benchmarks. Finally, we demonstrate Graph-Hist's performance by conducting bot detection in social media. While sophisticated bot and cyborg accounts increasingly evade traditional detection methods, they leave artificial artifacts in their conversational graph that are detected through graph classification. We apply Graph-Hist to classify these conversational graphs. In the process, we confirm that social media graphs are different than most baselines and that Graph-Hist outperforms existing bot-detection models."

# Summary. An optional shortened abstract.
summary: "The deep learning approach to graph classification is to embed nodes in a latent space, typically graph convolutions, and then to use these embeddings to make a single classification. The number of nodes may differ from one training example to the next, which poses a problem. We demonstrate that the node embedding distribution can be approximated using differentiable histograms. After the histograms are created, traditional convolutional layers can be used to classify the graph. This procedure leverages all available information, regardless of how the size of graphs vary. We demonstrate that this architecture gives incremental improvement for various benchmark datasets. We use this approach to classify bots on Twitter based on their communication graph. We find this classification technique generalizes better than previous methods, however sacrifices some precision."

tags:
- Machine Learning on Networks
- Social Cybersecurity
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/1910.01180.pdf
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
  caption: 'The Graph-Hist Architecture'
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
