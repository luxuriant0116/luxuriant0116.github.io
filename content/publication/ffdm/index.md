---
title: "Fundus-Enhanced Disease-Aware Distillation Model for Retinal Disease Classification from OCT Images"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Weihang Dai
- Mei Jin
- Chubin Ou
- Xiaomeng Li

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
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: The 26th International Conference on Medical Image Computing and Computer Assisted Intervention
publication_short: MICCAI 2023

abstract: Optical Coherence Tomography (OCT) is a novel and effective screening tool for ophthalmic examination. Since collecting OCT images is relatively more expensive than fundus photographs, existing methods use multi-modal learning to complement limited OCT data with additional context from fundus images. However, the multi-modal framework requires eye-paired datasets of both modalities, which is impractical for clinical use. To address this problem, we propose a novel fundus-enhanced disease-aware distillation model (FDDM), for retinal disease classification from OCT images. Our framework enhances the OCT model during training by utilizing unpaired fundus images and does not require the use of fundus images during testing, which greatly improves the practicality and efficiency of our method for clinical use. Specifically, we propose a novel class prototype matching to distill disease-related information from the fundus model to the OCT model and a novel class similarity alignment to enforce consistency between disease distribution of both modalities. Experimental results show that our proposed approach outperforms single-modal, multi-modal, and state-of-the-art distillation methods for retinal disease classification.

# Summary. An optional shortened abstract.
summary: We propose a novel fundus-enhanced disease-aware distillation model (FDDM), for retinal disease classification from OCT images.
tags: 
- featured

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2308.00291'
url_code: 'https://github.com/xmed-lab/FDDM'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://drive.google.com/file/d/1uPY_M13LFliaKX4bsQSv-my6r0MA9Zdf/view?usp=drive_link'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Overview Framework of FFDM'
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

<div class=ml-3>
    {{ $image := .Resources.Get "featured.jpg".Resize "200x" }}
</div>

