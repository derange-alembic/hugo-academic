---
title: "KAPLA: Scalable NN Accelerator Dataflow Design Space Structuring and Fast Exploring"
authors:
- Zhiyao Li
- Mingyu Gao
date: "2023-06-15T00:00:00Z"
doi: "https://doi.org/10.1145/3658617.3697549"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 30th Asia and South Pacific Design Automation Conference*
publication_short: "Appeared in *ASPDAC 2025*"

abstract: Dataflow scheduling is of vital importance to neural network (NN) accelerators. Recent scalable NN accelerators support a rich set of advanced dataflow techniques. The problems of comprehensively representing and quickly finding optimized dataflow schemes thus become significantly more complicated and challenging. In this work, we first propose comprehensive and pragmatic dataflow representations for temporal and spatial scheduling on scalable multi-node NN architectures. An informal hierarchical taxonomy highlights the tight coupling across different levels of the dataflow space as the major difficulty for fast design exploration. A set of formal tensor-centric directives accurately express various inter-layer and intra-layer schemes, and allow for quickly determining their validity and efficiency. We then build a generic, optimized, and fast dataflow solver, KAPLA. It makes use of the pragmatic directives to explore the design space with effective validity check and efficiency estimation. KAPLA decouples the upper inter-layer level for fast pruning, and solves the lower intra-layer schemes with a novel bottom-up cost descending method. KAPLA achieves within only 2.2% and 7.7% energy overheads on the result dataflow for training and inference, respectively, compared to the exhaustively searched optimal schemes. It also outperforms random and machine-learning-based approaches, with more optimized results and orders of magnitude faster search speed. 

# Summary. An optional shortened abstract.
# summary: 

tags: []
featured: false

url_pdf: https://dl.acm.org/doi/pdf/10.1145/3658617.3697549
url_code: https://github.com/tsinghua-ideal/kapla

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
