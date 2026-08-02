---
title: Graph Neural Networks for Particle Tracking on FPGAs

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Abdelrahman Elabd
- Vesal Razavimaleki
- Shi-Yu Huang
- Javier Duarte
- Markus Atkinson
- Gage DeZoort
- Peter Elmer
- Scott Hauck
- Jin-Xuan Hu
- Shih-Chieh Hsu
- Bo-Cheng Lai
- me
- Isobel Ojalvo
- Savannah Thais
- Matthew Trahms

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-01-05T06:40:05.451307Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Front. Big Data*'
publication_short: ''

ids:
  doi: '10.3389/fdata.2022.828666'

links:
  - name: DOI
    url: "https://doi.org/10.3389/fdata.2022.828666"
  - name: arXiv
    url: "https://arxiv.org/abs/2112.02048"
  - name: pdf
    url: "https://public-pages-files-2025.frontiersin.org/journals/big-data/articles/10.3389/fdata.2022.828666/pdf"

abstract: 'The determination of charged particle trajectories in collisions at the CERN Large Hadron Collider (LHC) is an important but challenging problem, especially in the high interaction density conditions expected during the future high-luminosity phase of the LHC (HL-LHC). Graph neural networks (GNNs) are a type of geometric deep learning algorithm that has successfully been applied to this task by embedding tracker data as a graph -- nodes represent hits, while edges represent possible track segments -- and classifying the edges as true or fake track segments. However, their study in hardware- or software-based trigger applications has been limited due to their large computational cost. In this paper, we introduce an automated translation workflow, integrated into a broader tool called 𝚑𝚕𝚜𝟺𝚖𝚕, for converting GNNs into firmware for field-programmable gate arrays (FPGAs). We use this translation tool to implement GNNs for charged particle tracking, trained using the TrackML challenge dataset, on FPGAs with designs targeting different graph sizes, task complexites, and latency/throughput requirements. This work could enable the inclusion of charged particle tracking GNNs at the trigger level for HL-LHC experiments.'

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
This original research article presents an automated workflow for deploying **graph neural networks (GNNs)** for charged particle tracking onto field-programmable gate arrays (FPGAs).

## Key points

- Charged particle tracking at the LHC (especially under high-luminosity conditions) is computationally challenging. GNNs have shown promise by encoding tracker hits as graphs (nodes = hits, edges = possible track segments) and classifying edges as true or fake.
- The authors integrate an automated translation tool into the **hls4ml** framework to convert Interaction Network–based GNNs into FPGA firmware.
- Models are trained on the TrackML challenge dataset and implemented targeting different graph sizes, task complexities, and latency/throughput requirements.
- The work demonstrates feasible FPGA designs and aims to enable GNN-based tracking at the trigger level for HL-LHC experiments, where strict sub-microsecond latency constraints apply.

Published 23 March 2022 in *Frontiers in Big Data* (section: Big Data and AI in High Energy Physics).