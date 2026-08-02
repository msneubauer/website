---
title: A detailed study of interpretability of deep neural network based top taggers
short_title: Explainability of Deep Neural Networks in top quark tagging

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- me
- Ayush Khot
- Avik Roy

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-01-05T06:40:05.408978Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Mach. Learn. Sci. Tech.*'
publication_short: ''

ids:
  doi: 10.1088/2632-2153/ace0a1

links:
- name: DOI
  url: "https://iopscience.iop.org/article/10.1088/2632-2153/ace0a1"
- name: arXiv
  url: https://arxiv.org/abs/2210.04371
- name: pdf
  url: https://iopscience.iop.org/article/10.1088/2632-2153/ace0a1/pdf

abstract: 'Recent developments in the methods of explainable AI (XAI) allow researchers to explore the inner workings of deep neural networks (DNNs), revealing crucial information about input-output relationships and realizing how data connects with machine learning models. In this paper we explore interpretability of DNN models designed to identify jets coming from top quark decay in high energy proton-proton collisions at the Large Hadron Collider (LHC). We review a subset of existing top tagger models and explore different quantitative methods to identify which features play the most important roles in identifying the top jets. We also investigate how and why feature importance varies across different XAI metrics, how correlations among features impact their explainability, and how latent space representations encode information as well as correlate with physically meaningful quantities. Our studies uncover some major pitfalls of existing XAI methods and illustrate how they can be overcome to obtain consistent and meaningful interpretation of these models. We additionally illustrate the activity of hidden layers as Neural Activation Pattern (NAP) diagrams and demonstrate how they can be used to understand how DNNs relay information across the layers and how this understanding can help to make such models significantly simpler by allowing effective model reoptimization and hyperparameter tuning. These studies not only facilitate a methodological approach to interpreting models but also unveil new insights about what these models learn. Incorporating these  observations into augmented model design, we propose the Particle Flow Interaction Network (PFIN) model and demonstrate how interpretability-inspired model augmentation can improve top tagging performance.'

# Summary. An optional shortened abstract.
summary: ''

tags:
  - Artificial Intelligence

# Display this page in a list of Featured pages?
featured: true

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

---

This open-access paper presents a systematic study of the **interpretability** of deep neural network (DNN) models used for top-quark jet tagging in high-energy proton–proton collisions at the LHC.

## Key points

- The authors review a subset of existing top-tagger models (primarily MLP-based) and apply multiple quantitative explainable AI (XAI) methods to identify which input features contribute most to classifying jets originating from top-quark decays versus QCD background.
- They examine how feature importance varies across different XAI metrics, the impact of feature correlations on explainability, and how information is encoded in the models’ latent-space representations (including correlations with physically meaningful quantities).
- Major pitfalls of existing XAI techniques are identified, along with ways to obtain consistent and meaningful interpretations.
- Neural activation pattern diagrams are used to visualize information flow through hidden layers, enabling model simplification, re-optimization, and hyperparameter tuning.
- Building on these interpretability insights, the authors propose the **Particle Flow Interaction Network (PFIN)** model and demonstrate that interpretability-inspired architectural improvements can enhance top-tagging performance.

Published 11 July 2023 in *Machine Learning: Science and Technology*. This work laid the groundwork for the later evidential deep learning studies by the same group.