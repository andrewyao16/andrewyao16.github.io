---
layout: page
permalink: /blog/
title: ideas
nav: true
nav_order: 3
description: Exploring emerging concepts and their potential applications in atmospheric science.
---

## Kolmogorov-Arnold Networks (KAN) in Atmospheric Science

I've been exploring the potential applications of [Kolmogorov-Arnold Networks (KAN)](https://doi.org/10.48550/arXiv.2404.19756) in atmospheric science. KAN offers a promising alternative to traditional Multi-Layer Perceptrons (MLPs) by using learnable activation functions on edges rather than fixed activation functions on nodes.

#### KAN vs MLP Architecture

<div class="row justify-content-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/kan_mlp_comparison.svg" title="KAN vs MLP Architecture" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Comparison of MLP (left) and KAN (right) architectures. MLPs use fixed activation functions (σ) on nodes with linear weights on edges. KANs use learnable spline functions (φ) on edges with simple summation on nodes.
</div>

#### Why KAN for Atmospheric Science?

Traditional neural networks have been increasingly used in atmospheric modeling, but they often suffer from:
- Poor interpretability
- Difficulty capturing complex nonlinear relationships
- Limited ability to discover underlying physical laws

KAN addresses these challenges by:
- **Improved interpretability:** The network structure can reveal underlying mathematical relationships
- **Higher accuracy with smaller networks:** KAN can achieve comparable or better accuracy with fewer parameters
- **Scientific discovery potential:** KAN can help identify governing equations from data

#### Potential Applications

1. **Aerosol-cloud interactions:** Modeling complex relationships between aerosol properties and cloud formation
2. **Chemical mechanism discovery:** Identifying reaction pathways from observational data
3. **Parameterization development:** Creating more accurate and interpretable parameterizations for Earth system models
4. **Emission source attribution:** Discovering relationships between emissions and atmospheric composition

#### Future Directions

I plan to explore how KAN can be integrated into atmospheric chemistry models like CESM to improve both accuracy and interpretability of aerosol and chemistry parameterizations.

---

*This is an evolving research interest. More updates coming soon.*
