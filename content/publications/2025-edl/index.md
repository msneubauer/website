---
title: Evidential deep learning for uncertainty quantification and out-of-distribution detection in jet identification using deep neural networks
short_title: Evidential DL for Uncertainties and Anomaly Detection

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- me
- Ayush Khot
- Xuwei Wang
- Avik Roy
- Vladimir Kindratenko

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-07-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-01-05T06:40:05.386417Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Mach. Learn. Sci. Tech.*'
publication_short: 

ids:
  doi: 10.1088/2632-2153/ade51b

links:
  - name: DOI
    url: "https://doi.org/10.1088/2632-2153/ade51b"
  - name: arXiv
    url: "https://arxiv.org/abs/2501.05656"
  - name: pdf
    url: "https://iopscience.iop.org/article/10.1088/2632-2153/ade51b/pdf"

abstract: 'Current methods commonly used for uncertainty quantification (UQ) in deep learning (DL) models utilize Bayesian methods which are computationally expensive and time-consuming. In this paper, we provide a detailed study of UQ based on evidential DL (EDL) for deep neural network models designed to identify jets in high energy proton–proton collisions at the Large Hadron Collider and explore its utility in anomaly detection (AD). EDL is a DL approach that treats learning as an evidence acquisition process designed to provide confidence (or epistemic uncertainty) about test data. Using publicly available datasets for jet classification benchmarking, we explore hyperparameter optimizations for EDL applied to the challenge of UQ for jet identification. We also investigate how the uncertainty is distributed for each jet class, how this method can be implemented for the detection of anomalies, how the uncertainty compares with Bayesian ensemble methods, and how the uncertainty maps onto latent spaces for the models. Our studies uncover some pitfalls of EDL applied to AD and a more effective way to quantify uncertainty from EDL as compared with the foundational EDL setup. These studies illustrate a methodological approach to interpreting EDL in jet classification models, providing new insights on how EDL quantifies uncertainty and detects out-of-distribution data which may lead to improved EDL methods for DL models applied to classification tasks.'

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
This is the peer-reviewed, published version of the work previously available as arXiv:2501.05656. It presents a detailed study of **evidential deep learning (EDL)** for uncertainty quantification (UQ) and out-of-distribution (OOD)/anomaly detection in deep neural networks used for jet identification (tagging) at the LHC.

## Key points

- Bayesian and ensemble methods for UQ are computationally costly. EDL provides a lighter alternative by treating learning as an *evidence-acquisition* process and modeling epistemic uncertainty via a Dirichlet distribution over class probabilities.
- The authors integrate EDL with the Particle Flow Interaction Network (PFIN) and evaluate it on public jet-classification benchmark datasets.
- They study hyperparameter optimization, per-class uncertainty distributions, comparisons with Bayesian ensembles, mapping of uncertainty onto latent spaces, and the application of EDL to anomaly detection.
- The work identifies limitations of the standard EDL formulation for anomaly detection and proposes a more effective way to extract uncertainty from EDL.
- Overall, it offers a methodological framework for interpreting EDL in jet-tagging models and insights that may improve EDL-based UQ for classification tasks in high-energy physics.

Published 8 July 2025 in the “Focus on Explainable Machine Learning in Sciences” collection of *Machine Learning: Science and Technology* (Open Access).
