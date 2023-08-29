---
title: "Modularized Pre-training for End-to-end Task-oriented Dialogue"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Libo Qin
- Xiao Xu
- admin
- Yup Zhang
- Wanxiang Che

# Author notes (optional)
# author_notes:


date: "2023-06-24T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE/ACM Transactions on Audio, Speech, and Language Processing
publication_short: IEEE TASLP 2023

abstract: Pre-training for end-to-end task-oriented dialogue systems (EToDs) is a challenging task due to its unique knowledge base query (accuracy) need and lack of sufficient training data (fluency). In this paper, we try to mitigate the above challenges by introducing a modularized pre-training framework for EToDs, which achieves to effectively improve both accuracy and fluency of EToDs through a pre-training paradigm. The core insight is a modular design by decomposing EToDs into a generation (fluency) module and a knowledge-retriever (accuracy) module, which allows us to optimize each module by pre-training these two sub-modules with different well-designed pre-training tasks, respectively. In addition, such a modularized paradigm enables us to make full use of large amounts of KB-free dialogue corpus for the pre-training generation module, which can alleviate the insufficient training problem. Furthermore, we introduce a new consistency-guided data augmentation (CGDA) strategy to cope with the data scarcity problem to better pre-train the knowledge-retriever module. Finally, we fine-tune the pre-trained generation module and knowledge-retriever module jointly. Experimental results on three datasets show that our model achieve superior performance in terms of both fluency and accuracy. To our knowledge, this is the first work to explore modularized pre-training methods for EToDs.

# Summary. An optional shortened abstract.
summary: 
tags: 
  - other

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10043710'
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
  caption: ''
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
