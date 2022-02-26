---
title: "Speedup Robust Graph Structure Learning with Low-Rank Information"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Hui Xu
- Liyao Xiang
- Jiahao Yu
- Anqi Cao
- Xinbing Wang

date: "2021-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *CIKM21*
publication_short: In *CIKM21*

abstract: Recent studies have shown that graph neural networks (GNNs) are vulnerable to unnoticeable adversarial perturbations, which largely confines their deployment in many safety-critical domains. Robust graph structure learning has been proposed to improve the GNN performance in the face of adversarial attacks. In particular, the low-rank methods are utilized to purify the perturbed graphs. However, these methods are mostly computationally expensive with O(n3) time complexity and O(n2) space complexity. We propose LRGNN, a fast and robust graph structure learning framework, which exploits the low-rank property as prior knowledge to speed up optimization. To eliminate adversarial perturbation, LRGNN decouples the adjacency matrix into a low-rank component and a sparse one, and learns by minimizing the rank of the first part while suppressing the second part. Its sparse variant is formed to reduce the memory footprint further. Experimental results on various attack settings have shown LRGNN acquires comparable robustness with the state-of-the-art much more efficiently, boasting a significant advantage on large-scale graphs.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://dl.acm.org/doi/abs/10.1145/3459637.3482299

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.

---
