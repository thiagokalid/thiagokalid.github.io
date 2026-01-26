---
title: Inverse-based ultrasound imaging through linear programming
date: 2025-02-08
summary: Ultrasound imaging casted as an inverse problem solved through linear programming.
links:
  - type: code
    url: https://github.com/thiagokalid/milp_image_reconstruction

  - type: pdf
    url: Inverse_based_ultrasound_imaging_through_linear_programming.pdf
tags:
  - Ultrasound imaging
  - Inverse problems
  - Simulation
  
status: published
---

**Abstract**

Ultrasound image reconstruction is typically performed through delay-and-sum: they are linear and computationally efficient algorithms. However, images produced by this family of methods contain oscillation that limits the imaging resolution–a phenomenon especially problematic when imaging very close point-like reflectors. Inverse-based methods have been proven to enhance imaging resolution by reducing high-frequency oscillations. They incorporate specific prior information and reduce oscillations by proper regularization. Although the regularization reduces oscillations, it also attenuates the signal of interest. We are proposing an inverse-based method without regularization. It is a linear programming-based approach: the inverse-problem is modeled as the minimization of the $\ell_1$ norm of a residue, which is solved through linear programming. We compared our methods to delay-and-sum and inverse-based imaging algorithms by simulating a steel specimen with point-like reflectors. Our method outperforms classical algorithms regarding SNR and resolution but at a higher computational cost.
