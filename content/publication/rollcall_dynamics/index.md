---
title: "Analytic Models of Roll Call Voting Dynamics"

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

date: "2019-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "In *IEEE Transactions on Computational Social Systems*"
publication_short: "In *IEEE TCSS*"

abstract: "Roll call modeling is an essential component of analyzing a political system. Current models focus on individual decision-making, and most of them do not take advantage of voting dynamics. Some political systems, such as Ukraine's Verkhovna Rada, are inherently dynamic and should be modeled as such. Therefore, a roll call model is developed from a linear second-order homogeneous differential equation. This model equation is fit to Verkhovna Rada votes from the seventh and eighth convocations. The model determines whether or not bills will reach the passing threshold with 77% and 85% accuracy for the seventh and eighth convocations, respectively. It is shown that the dynamic legislative model is slightly less accurate than a neural network, but it is significantly more interpretable. This interpretability is vitally important, as it is what makes models meaningful beyond their predictive power. It is found that bills sponsored by the president show quantitatively different behavior than ordinary bills and the ordinary bills are largely decided in the first two votes. Furthermore, our models have intuitive theoretical implications, some of which are back by prior work. The models suggest that MPs are less willing to change their vote on bills as iterations increase and they are more sensitive to change the public opinion if the bill is sponsored by the president. While the majority of bills are modeled well, about 25% of votes have greater than 10% error. Investigation of these votes indicates that some votes may be impossible to predict without a more complex model which incorporates contextual information. Finally, the information from a bill's first two votes is also leveraged through a vote switching network. This directed network gives insight into who sends the most powerful signals and who follows them. An ensemble of centrality members is then used to identify the legislator's most influential members."

# Summary. An optional shortened abstract.
summary: "We show that sequential voting on bills in Ukraine's legislature can be well modeled with a simple ODE. Our results imply that the first two votes are crucial for a bill's success. We also find that bills sponsored by the President exhibit quantitatively different behavior in that they are more sensitive to change between votes."

tags:
- Voting Networks
- Network Dynamics

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Full Paper
  url: https://ieeexplore.ieee.org/abstract/document/8693796

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
  caption: 'Phase space representation of roll call dynamics in Convocation 8.'
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
