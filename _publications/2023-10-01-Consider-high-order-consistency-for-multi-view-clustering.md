---
title: "Consider high-order consistency for multi-view clustering"
collection: publications
permalink: /publication/2023-10-01-Consider-high-order-consistency-for-multi-view-clustering
date: 2023-10-01
venue: 'Neural Computing and Applications'
authors: 
  - 'Xiaojian You'
  - 'Haoran Li'
  - 'Jiali You'
  - 'Zhenwen Ren'
---
Tensor-based multi-view clustering has attracted intensive attention due to the effectiveness of exploiting multi-view data information. However, most existing methods purely aim to explore the consistency of different views while neglecting the inherent difference between views, which may lead to incomplete modeling and affect the final clustering performance. To handle this problem, in this paper, we unify the consistency and specificity to model the multi-view data in a tensor manner. Specifically, we learn multiple candidate graphs corresponding to all views through self-expressiveness learning. Then these candidate graphs are decomposed into two sets of graphs, i.e., consistent graphs and specific graphs, respectively. After that, these consistent graphs are stacked into a tensor to exploit the high-order structure information while the specific graphs are used to capture the inherent difference in each view, such that a refined consensus affinity graph can be obtained for spectral clustering. The established model is dubbed Consider High-Order Consistency for Multi-View Clustering (CHOC-MVC), and its optimal problem can be efficiently solved by the alternating direction method of multipliers (ADMM). The experimental results demonstrate the effectiveness of our proposed method. The source code is available at https://github.com/haoranli50/CHOC-MVSC.
Use [Google Scholar](https://scholar.google.com/scholar?q=Consider+high+order+consistency+for+multi+view+clustering){:target="_blank"} for full citation
