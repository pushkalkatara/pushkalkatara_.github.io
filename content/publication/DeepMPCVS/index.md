---
title: 'DeepMPCVS: Deep-Model Predictive Control for Visual Servoing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2020-11-17T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-11-17T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In Conference on Robot Learning (CoRL 2020)
publication_short: In *CoRL 2020*

abstract: The simplicity of the visual servoing approach makes it an attractive option for tasks dealing with vision-based control of robots in many real-world applications. However, attaining precise alignment for unseen environments pose a challenge to existing visual servoing approaches. While classical approaches assume a perfect world, the recent data-driven approaches face issues when generalizing to novel environments. In this paper, we aim to combine the best of both worlds. We present a deep model predictive visual servoing framework that can achieve precise alignment with optimal trajectories and can generalize to novel environments. Our framework consists of a deep network for optical flow predictions, which are used along with a predictive model to forecast future optical flow. For generating an optimal set of velocities we present a control network that can be trained on-the-fly without any supervision. Through extensive simulations on photo-realistic indoor settings of the popular Habitat framework, we show significant performance gain due to the proposed formulation vis-a-vis recent state of the art methods. Specifically, we show vastly improved performance in trajectory length and faster convergence over recent approaches.

# Summary. An optional shortened abstract.
summary: We present a deep model predictive visual servoing framework that can achieve precise alignment with optimal trajectories and can generalize to novel environments.

tags: ["Visual Servoing", "Self-Supervised Learning", "Sequence Networks"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2105.00788'
url_code: 'https://github.com/pushkalkatara/DeepMPCVS'
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