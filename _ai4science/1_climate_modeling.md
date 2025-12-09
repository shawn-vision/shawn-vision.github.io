---
layout: page
title: Probabilistic Data Assimilation
img: assets/img/12.jpg
importance: 1
---

Traditional data assimilation in weather and climate science focuses on improving **short-term state estimation** — for example, updating a model's trajectory using daily temperature observations. While effective for forecasting, this approach does not directly address a deeper challenge in **climate modeling**: we are rarely interested in the exact state of one day far into the future. Instead, we aim to understand how **probability distributions evolve** — especially the tails that govern extreme events.

Our work introduces a new **distribution-aware data assimilation framework**, shifting emphasis from pointwise corrections to **learning and updating full statistical distributions** of climate variables. Built upon a **Bayesian generative-modeling formulation**, it enables uncertainty-aware **parameter inference**, improved projection stability, and better characterization of **extreme-event behavior**.

This methodology supports:

- Probabilistic estimation of long-range climate states  
- Quantile-based risk analysis and rare-event statistics  
- More reliable projections under limited or noisy observations  

---

### 📄 Publication  
Li, S., Zheng, T., Farchi, A., Bocquet, M., & Gentine, P. (2025).  
**Projections with generative machine learning: a Lorenz ’96 proof-of-concept.**  
*Geophysical Research Letters*, 52(12), e2024GL112523.  
🔗 [Read the paper](https://doi.org/10.1029/2024GL112523)
