---
title: 'Smart pixel sensor filtering with deep learning'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Jieun Yoo
- Jennet Dickinson
- Morris Swartz
- Giuseppe Di Guglielmo
- Alice Bean
- Douglas Berry
- Manuel. B. Valentin
- Karri DiPetrillo
- Farah Fahim
- Lindsey Gray
- James Hirschauer
- Shruti R. Kulkarni
- Ron Lipton
- Petar Maksimovic
- Corrinne Mills
- me
- Benjamin Parpillon
- Gauri Pradhan
- Chinar Syal
- Nhan Tran
- Dahai Wen
- Aaron Young

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-08-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-01-05T06:40:05.398679Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Mach. Learn. Sci. Tech.*'
publication_short: ''

ids:
  doi: '10.1088/2632-2153/ad6a00'

links:
  - name: DOI
    url: "https://iopscience.iop.org/article/10.1088/2632-2153/ad6a00"
  - name: arXiv
    url: "https://arxiv.org/abs/2310.02474"
  - name: pdf
    url: "https://iopscience.iop.org/article/10.1088/2632-2153/ad6a00/pdf"
    
abstract: 'Highly granular pixel detectors allow for increasingly precise measurements of charged particle tracks. Next-generation detectors require that pixel sizes will be further reduced, leading to unprecedented data rates exceeding those foreseen at the High- Luminosity Large Hadron Collider. Signal processing that handles data incoming at a rate of O(40 MHz) and intelligently reduces the data within the pixelated region of the detector at rate will enhance physics performance at high luminosity and enable physics analyses that are not currently possible. Using the shape of charge clusters deposited in an array of small pixels, the physical properties of the traversing particle can be extracted with locally customized neural networks. In this first demonstration, we present a neural network that can be embedded into the on-sensor readout and filter out hits from low momentum tracks, reducing the detector’s data volume by 57.1%–75.7%. The network is designed and simulated as a custom readout integrated circuit with 28 nm CMOS technology and is expected to operate at less than 300 µW with an area of less than 0.2 mm2. The temporal development of charge clusters is investigated to demonstrate possible future performance gains, and there is also a discussion of future algorithmic and technological improvements that could enhance efficiency, data reduction, and power per area.'

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
This open-access paper explores the use of deep learning for **on-sensor data reduction** in highly granular silicon pixel detectors intended for future high-luminosity colliders.

## Key points

- Next-generation pixel detectors will produce data rates far exceeding those expected at the High-Luminosity LHC, necessitating intelligent filtering close to the sensor.
- The authors develop a neural network that uses the shape of charge clusters deposited in small pixel arrays to extract properties of the traversing charged particle and filter out hits from low-momentum tracks.
- In this first demonstration, the network reduces detector data volume by **57.1%–75.7%**.
- The algorithm is designed and simulated as a custom readout integrated circuit in 28 nm CMOS technology, expected to operate at less than 300 μW with an area of less than 0.2 mm².
- The temporal development of charge clusters is also investigated as a path to further performance gains, along with discussion of future algorithmic and technological improvements.

Published 14 August 2024 in *Machine Learning: Science and Technology*.