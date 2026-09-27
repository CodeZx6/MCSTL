## Mask- and Contrast-Enhanced Spatio-Temporal Learning for Urban Flow Prediction

[![DOI](https://img.shields.io/badge/DOI-10.1145%2F3583780.3614958-blue)](https://doi.org/10.1145/3583780.3614958)
[![Free to read](https://img.shields.io/badge/free%20to%20read-ACM%20DL-brightgreen)](https://doi.org/10.1145/3583780.3614958)
[![Paper page](https://img.shields.io/badge/paper-page-blue)](https://codezx6.github.io/papers/mcstl.html)

Official implementation of **MC-STL** (CIKM 2023): *Mask- and Contrast-Enhanced Spatio-Temporal Learning for Urban Flow Prediction*. The paper calls the method **MC-STL**; this repository is named MCSTL.

MC-STL pre-trains two encoders for urban flow prediction: a ViT encoder learns to reconstruct regions masked at different timestamps, and its attention weights also build a GCN adjacency matrix; a global-local cross-attention encoder learns a temporal-order contrastive task. It reaches RMSE 14.53 on full TaxiBJ.

📄 Paper: https://doi.org/10.1145/3583780.3614958 · 🌐 Paper page with quoted results, FAQ and BibTeX: https://codezx6.github.io/papers/mcstl.html


```bibtex
@inproceedings{zhang2023mcstl,
  title        = {Mask- and Contrast-Enhanced Spatio-Temporal Learning for Urban Flow Prediction},
  author       = {Zhang, Xu and Gong, Yongshun and Zhang, Xinxin and Wu, Xiaoming and Zhang, Chengqi and Dong, Xiangjun},
  booktitle    = {Proceedings of the 32nd ACM International Conference on Information and Knowledge Management (CIKM '23)},
  year         = {2023},
  pages        = {3298--3307},
  publisher    = {ACM},
  doi          = {10.1145/3583780.3614958},
  url          = {https://doi.org/10.1145/3583780.3614958}
}
```
