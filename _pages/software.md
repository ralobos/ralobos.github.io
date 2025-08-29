---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

{% include base_path %}

<b>PISCO 2.0</b>
======

<br>[GitHub Repository](https://github.com/ralobos/PISCO.git)<br>

We’re pleased to announce the release of PISCO v2.0, a computational tool designed for efficient and accurate sensitivity map estimation in multichannel MRI applications.

Sensitivity map estimation is critical in many advanced MRI techniques. While subspace-based methods like ESPIRiT deliver great results, they often suffer from high computational costs. A few years ago, we introduced a theoretical framework equivalent to ESPIRiT but grounded in structured low-rank modeling and linear predictability principles [1]. Alongside this, we developed a suite of computational techniques—collectively known as PISCO—that dramatically improved computational efficiency. Our initial open-source release focused on 2D sensitivity map estimation.

What’s new in PISCO v2.0?

Full 3D Support: All original PISCO techniques are now extended to 3D sensitivity map estimation.

Enhanced Performance: We’ve integrated a recently proposed sketched SVD technique [2], further optimizing computation times.

Notable Efficiency: On a MacBook Pro M2, 2D map estimation (32 channels) can be completed in approximately 0.4 seconds, while 3D estimation takes around 12 seconds. Both examples are available in the GitHub repository.

References

[1] Lobos RA, Chan CC, Haldar JP. New theory and faster computations for subspace-based sensitivity map estimation in multichannel MRI. IEEE Transactions on Medical Imaging. 2023 Jul 21; 43(1):286-96.
 
[2] Lobos RA, Wang X, Fung RT, He Y, Frey D, Gupta D, Liu Z, Fessler JA, Noll DC. Spatiotemporal Maps for Dynamic MRI Reconstruction. arXiv preprint arXiv:2507.14429, 2025 Jul 19.

We’re excited to contribute to the MRI research community and look forward to your feedback!

