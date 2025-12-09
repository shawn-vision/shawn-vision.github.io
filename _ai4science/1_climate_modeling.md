---
layout: page
title: Probabilistic Data Assimilation
img: assets/img/climate-da.png
importance: 1
---

<img src="/assets/img/climate-da.png" alt="Probabilistic Data Assimilation" style="max-width: 50%; display:block; margin:auto; padding: 20px 0;" />

Traditional data assimilation in weather and climate science focuses on improving **short-term state estimation** — for example, updating a model's trajectory using daily temperature observations. While effective for forecasting, this approach does not directly address a deeper challenge in **climate modeling**: we are rarely interested in the exact state of one day far into the future. Instead, we aim to understand how **probability distributions evolve** — especially the tails that govern extreme events.

Our work introduces a new **distribution-aware data assimilation framework**, shifting emphasis from pointwise corrections to **learning and updating full statistical distributions** of climate variables. Built upon a **Bayesian generative-modeling formulation**, it enables uncertainty-aware **parameter inference**, improved projection stability, and better characterization of **extreme-event behavior**.

This methodology supports:

- Probabilistic estimation of long-range climate states  
- Quantile-based risk analysis and rare-event statistics  
- More reliable projections under limited or noisy observations  

### 📄 Read More  

**1.** **Li, S**., Zheng, T., Farchi, A., Bocquet, M., & Gentine, P. (2025).  
**Projections with generative machine learning: a Lorenz ’96 proof-of-concept.**  
*Geophysical Research Letters*, 52(12), e2024GL112523.  
🔗 [Read the paper](https://doi.org/10.1029/2024GL112523)

**2.** Qu, Y., Nathaniel, J., **Li, S.**, & Gentine, P. (2024).  
**Deep generative data assimilation in multimodal setting.**  
*Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2024).*  
🔗 [PDF on CVF OpenAccess](https://openaccess.thecvf.com/content/CVPR2024/papers/Qu_Deep_Generative_Data_Assimilation_in_Multimodal_Setting_CVPR_2024_paper.pdf)

---



