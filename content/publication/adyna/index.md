---
title: "Adyna: Accelerating Dynamic Neural Networks with Adaptive Scheduling"
authors:
- Zhiyao Li
- Bohan Yang
- Jiaxiang Li
- Taijie Chen
- Xintong Li
- Mingyu Gao

date: "2025-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 31st Symposium on High Performance Computer Architecture*
publication_short: Appeared in *the Symposium on High Performance Computer Architecture (HPCA) 2025*

abstract: Dynamic architecture neural networks (DynNNs) are an emerging type of deep learning models that can leverage different processing difficulties of data samples to dynamically reduce computation demands at runtime. However, current GPUs and specialized accelerators lack the necessary architecture and dataflow support to achieve the promised theoretical efficiency improvements due to the high dynamism in DynNN execution. We propose Adyna, a novel hardware-software co-design solution to efficiently support DynNN inference. Adyna uses a unified representation to capture most existing DynNNs to enable a general design. It features a dynamism-aware, multi-kernel selection paradigm, in which the dataflow scheduler makes resource allocation decisions according to the distribution of dynamic size values, and the hardware architecture keeps multiple precompiled kernels and selects the best matching one to process each specific data sample according to its dynamic size. Adyna further uses an effective kernel sampling algorithm to carefully choose the set of kernels to load onto the hardware. Evaluated on various DynNN models, Adyna can outperform state-of-the-art multi-tile and multi-tenant accelerators by 1.70× and 1.57× on average, and up to 2.32× and 2.01×.
# Summary. An optional shortened abstract.
# summary: 

tags: []
featured: false

url_pdf: 'https://people.iiis.tsinghua.edu.cn/~gaomy/pubs/adyna.hpca25.pdf'

projects: []

slides: ""
---
