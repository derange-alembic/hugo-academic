---
title: 'Spada: Accelerating Sparse Matrix Multiplication with Adaptive Dataflow'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhiyao Li
  - Jiaxiang Li
  - Taijie Chen
  - Dimin Niu
  - Hongzhong Zheng
  - Yuan Xie
  - Mingyu Gao

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-01-30T00:00:00Z'
doi: 'https://doi.org/10.1145/3575693.3575706'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 28th ACM International Conference on Architectural Support for Programming Languages and Operating Systems*
publication_short: In *ASPLOS 2023*

abstract: Sparse matrix-matrix multiplication (SpGEMM) is widely used in many scientific and deep learning applications. The highly irregular structures of SpGEMM limit its performance and efficiency on conventional computation platforms, and thus motivate a large body of specialized hardware designs. Existing SpGEMM accelerators only support specific types of rigid execution dataflow such as inner/output-product or row-based schemes. Each dataflow is only optimized for certain sparse patterns and fails to generalize with robust performance to the widely diverse SpGEMM workloads across various domains. We propose Spada, a combination of three novel techniques for SpGEMM accelerators to efficiently adapt to various sparse patterns. First, we describe a window-based adaptive dataflow that can be flexibly adapted to different modes to best match the data distributions and realize different reuse benefits. Then, our hardware architecture efficiently supports this dataflow template, with flexible, fast, and low-cost reconfigurability and effective load balancing features. Finally, we use a profiling-guided approach to detect the sparse pattern and determine the optimized dataflow mode to use, based on the key observations of sparse pattern similarity in nearby matrix regions. Our evaluation results demonstrate that Spada is able to match or exceed the best among three state-of-the-art SpGEMM accelerators, and avoid the performance degradation of the others if data distribution and dataflow mismatch. It achieves an average 1.44× speedup across a wide range of sparse matrices and compressed neural network models.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3575693.3575706'
url_code: 'https://github.com/tsinghua-ideal/spada-sim'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=0JgyN3Xps7M'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
