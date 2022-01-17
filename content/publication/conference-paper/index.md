---
title: "Continual Learning for Anomaly based Network Intrusion Detection"
authors:
- admin
- Reethu Vinta
- Suresh Kumar Amalapuram
- Sumohana S. Channappayya
- Bheemarjuna Reddy Tamma
date: "2013-07-01T00:00:00Z"
doi: "10.1109/COMSNETS53615.2022.9668482"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In 2022 14th International Conference on COMmunication Systems & NETworkS (COMSNETS)
publication_short: In *COMSNETS*

abstract: To defend computing systems against ever-growing cyber attacks, Anomaly-based Network Intrusion Detection Systems (A-NIDS) have to evolve continuously. This requirement renders classical machine learning algorithms ineffective since they do not handle sequentially evolving tasks gracefully. Specifically, neural networks (NNs) are prone to catastrophic forgetting (CF) when trained on sequential data. Recent advances in addressing this drawback of NNs have resulted in a paradigm called Continual Learning (CL) which mitigates CF by introducing suitable constraints during the sequential training of these NNs. CL has been shown to be very effective in improving the performance of NNs on computer vision tasks. However, its application to the design of A-NIDS has not been explored. In this work, we evaluate the suitability of CL to address the challenges posed in A-NIDS design. Unlike computer vision datasets, network datasets suffer from the Class Imbalance (CI) problem, which makes the direct application of CL algorithms challenging. To evaluate the suitability of CL algorithms on network datasets, we study the impact of class imbalance on task ordering and its effect on the design of CL- based A-NIDS in the Class Incremental (CIL) and Domain Incremental (DIL) learning settings. Towards this end, we apply two popular CL algorithms viz. Elastic Weight Consolidation (EWC) and Gradient Episodic Memory (GEM) on two datasets viz., CICIDS and KDD Cup'99, and evaluate their performance. We found that CI affects task order sensitivity to a greater extent in the CIL setting when compared to the DIL setting. The performance of DIL setting can be further enhanced by incorporating experience forgetting aware memory population techniques, and we recommend this as a practical approach to building CL-based A-NIDS.

# Summary. An optional shortened abstract.
summary: Studied the impact of class imbalance on task ordering and its effect on the design of CL- based Anomaly-based Network Intrusion Detection Systems(A-NIDS) in the Class Incremental (CIL) and Domain Incremental (DIL) learning settings.

tags:
- Source Themes
featured: true

links:
- name: Paper link
  url: 'https://ieeexplore.ieee.org/document/9668482'
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9668482'
url_code: 'https://github.com/ReethuVinta/AnomalyDetection'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Proposed A-NIDS Design using Continual Learning'
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
