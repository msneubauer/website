---
title: Robustness of the smartpixels classifier for different simulated sensor geometries
  and non-ideal detector conditions

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Danush Shekar
- Ben Weiss
- Morris Swartz
- Corrinne Mills
- Jennet Dickinson
- Lindsey Gray
- David Jiang
- Mohammad Abrar Wadud
- Daniel Abadjiev
- Anthony Badea
- Douglas Berry
- Alec Cauper
- Arghya Ranjan Das
- Karri Folan DiPetrillo
- Farah Fahim
- Rachel Kovach Fuentes
- Abhijith Gandrakota
- Giuseppe Di Guglielmo
- Eliza Howard
- Shiqi Kuang
- Carissa Kumar
- Mia Liu
- Petar Maksimovic
- Nick Manganelli
- me
- Aidan Nicholas
- Emily Pan
- Benjamin Parpillon
- Jannicke Pearkes
- Ricardo Silvestre
- Chinar Syal
- Amit Trivedi
- Keith Ulmer
- Jieun Yoo
- Eric You

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2026-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-08-03T22:28:13.238487Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Nuclear Instruments and Methods in Physics Research Section A: Accelerators,
  Spectrometers, Detectors and Associated Equipment*'
publication_short: ''

abstract: Pixel tracking detectors at upcoming collider experiments will see unprecedented
  charged-particle densities. Real-time data reduction on the detector will enable
  higher granularity and faster readout, possibly enabling the use of the pixel detector
  in high-rate online event selection, such as the ATLAS or CMS first-level trigger
  systems. This data reduction can be accomplished with a neural network (NN) in the
  readout chip bonded with the sensor that recognizes and rejects tracks with low
  transverse momentum (pT) based on the geometrical shape of the charge deposition
  (“cluster”). To design viable detectors for deployment, the dependence of the NN
  as a function of the sensor geometry, external magnetic field, irradiation, and
  noise must be understood. In this paper, we present first studies of the efficiency
  and data reduction for planar pixel sensors exploring these parameters. For the
  CMS HL-LHC sensor geometry, we obtain a signal efficiency of (91.9 ± 0.7)% and a
  data reduction of (29.7 ± 1.0)%. A smaller sensor pitch in the bending direction
  improves the pT discrimination, but a larger pitch can be partially compensated
  with detector thickness. Any accumulated radiation damage also changes the cluster
  shape, reducing the signal efficiency compared to the baseline by approximately
  30–60% in absolute terms, but nearly all of the performance can be recovered through
  retraining of the network and updating the weights. Finally, the impact of noise
  was investigated, and retraining the network on noise-injected datasets was found
  to maintain performance within 6% of the baseline network trained and evaluated
  on noiseless data.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Edge computing
- On-chip networks
- Smart detectors
- Data-reduction
- Detector simulation

# Display this page in a list of Featured pages?
featured: false

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

links:
  - name: DOI
    url: "https://doi.org/10.1016/j.nima.2026.171897"
  - name: arXiv
    url: "https://arxiv.org/abs/2510.06588v1"
  - name: pdf
    url: "https://arxiv.org/pdf/2510.06588v1"
---

This paper studies the co-design of planar pixel sensors and on-sensor neural networks for real-time data reduction in future high-granularity pixel tracking detectors.

## Key points

- Neural networks embedded in the readout chip can reject low-\(p_T\) tracks based on the geometric shape of charge clusters, enabling higher granularity and possible use of pixel data in the first-level trigger.
- The authors systematically explore how NN efficiency and data-reduction performance depend on:
  - Sensor geometry (pitch and depth)
  - External magnetic field (Lorentz drift)
  - Radiation damage
  - Noise
- Smaller pitch in the bending direction improves \(p_T\) discrimination; larger pitch can be partially compensated by greater sensor depth.
- A magnetic field parallel to the sensor plane broadens clusters via Lorentz drift and improves network performance; its absence degrades background rejection by \(\mathcal{O}(10\%)\).
- Radiation damage alters cluster shapes and reduces signal efficiency by \(\sim 30\)–\(60\%\), but nearly full performance is recovered by retraining the network.
- Noise effects are largely mitigated by retraining on noise-injected data (performance remains within \(6\%\) of the noiseless baseline).

The work provides essential guidance for designing viable “smart pixel” detectors for upcoming collider experiments.