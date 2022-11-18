---
title: 'RTVS: A Lightweight Differentiable MPC Framework for Real-Time Visual Servoing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2021-05-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-05-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In International Conference on Intelligent Robots and Systems (IRoS 2021) 
publication_short: In *IRoS 2021*

abstract: Recent data-driven approaches to visual servoing have shown improved performances over classical methods due to precise feature matching and depth estimation. Some recent servoing approaches use a model predictive control (MPC) framework which generalise well to novel environments and are capable of incorporating dynamic constraints, but are computationally intractable in real-time, making it difficult to deploy in real-world scenarios. On the contrary, single-step methods optimise greedily and achieve high servoing rates, but lack the benefits of the MPC multi-step ahead formulation. In this paper, we make the best of both worlds and propose a lightweight visual servoing MPC framework which generates optimal control near real-time at a frequency of 10.52 Hz. This work utilises the differential cross-entropy sampling method for quick and effective control generation along with a lightweight neural network, significantly improving the servoing frequency. We also propose a flow depth normalisation layer which ameliorates the issue of inferior predictions of two view depth from the flow network. We conduct extensive experimentation on the Habitat simulator and show a notable decrease in servoing time in comparison with other approaches that optimise over a time horizon. We achieve the right balance between time and performance for visual servoing in six degrees of freedom (6DoF), while retaining the advantageous MPC formulation. Our code and dataset are publicly available.

# Summary. An optional shortened abstract.
summary: We present a lightweight MPC framework for Visual Servoing based on differential cross-entropy sampling to generate optimal control in real-time.

tags: ["Visual Servoing", "Sequence Networks"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://drive.google.com/file/d/1vRdxj9BZXNdiQmYgPiu7Ov8zt5NNOmh2/view?usp=sharing'
#url_code: 'https://github.com/pushkalkatara/DeepMPCVS'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---