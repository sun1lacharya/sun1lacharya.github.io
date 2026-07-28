---
title: 'Solving the Capacity Mismatch Problem: Self-Knowledge Distillation for Ultra-Lightweight Networks'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'


date: '2025-11-08T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-07-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "International Conference on Machine Learning and Data Engineering - Procedia Computer Science (2026)"
  short_name: "ICMLDE"

peer_reviewed: true
open_access: true
license: CC-BY-4.0

# Awards, honors, and recognitions. Surfaced as badges on the page and in listings.
# awards:
#   - name: "Best Paper Award"
#     level: winner
#     note: "Top 5 of 8000 submissions"
#   - name: "Oral Presentation"
#     level: selected

# Funders and grants. Required by many funders for compliance reporting.
# funding:
#   - funder: "National Science Foundation"
#     grant: "NSF-2401234"
#   - funder: "European Research Council"
#     grant: "ERC-StG-101234"

abstract: "Deep neural networks achieve state-of-the-art performance across vision tasks, yet their deployment on edge devices remains challenging due to high computational and memory requirements. Knowledge Distillation (KD) shows promise for model compression, yet its effectiveness in the ultra-lightweight regime (models with fewer than one million parameters) remains underexplored. This paper systematically evaluates multiple KD paradigms, including traditional teacher-student approaches, online methods, and self-distillation techniques, on compact convolutional architectures designed for resource-constrained environments. We find that conventional teacher-student KD consistently degrades performance in ultra-lightweight models due to a capacity mismatch between large teachers and small students. We introduce the capacity mismatch hypothesis, which posits that optimization conflicts arise when students cannot accurately approximate teacher distributions. In contrast, self distillation methods, specifically Classwise Self Knowledge Distillation (CSKD) and Teacher Free Self Training (TFST), consistently deliver superior results by eliminating capacity mismatch. Results on CIFAR-10 and Fashion-MNIST demonstrate remarkable efficiency gains: our 600K-parameter model with TFST achieves 94.14% accuracy on Fashion-MNIST, approaching the 96.70% benchmark achieved by an 8.9M-parameter baseline. This represents a 15-fold parameter reduction while maintaining competitive performance. On CIFAR-10, the same model reaches 91.98% accuracy, rivalling much larger architectures. These findings validate that self-distillation consistently outperforms traditional KD across model sizes and datasets, with improvements ranging from 3% to 4% over baseline. Our research provides theoretical insights into KD behavior under resource constraints and practical guidelines for efficient design, demonstrating that combining architectural efficiency with self-distillation enables high-performance AI deployment on edge devices."

# Summary. An optional shortened abstract.
summary: "Solving the Capacity Mismatch Problem: Self-Knowledge Distillation for Ultra-Lightweight Networks"

tags:
  - Deep Learning
  - Edge AI
  - Knowledge distillation
  - Ultra light-weight Neural Networks

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1016/j.procs.2026.06.301

# Custom links
links:
  - type: pdf
    url: "https://doi.org/10.1016/j.procs.2026.06.301"
  - type: code
    url: "https://github.com/sun1lach/kd-custom-architectures"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/projects/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---

<!-- <!-- > [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software. -->

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.
