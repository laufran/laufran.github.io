---
layout: page
title: Phylogenetic network inference accuracy
description: Testing the accuracy and robustness of hybridization inference methods through simulation
img: assets/img/publication_preview/complexity.png
importance: 1
category: research
related_publications: true
---

Accurately inferring reticulate evolutionary histories — networks of species that have exchanged genes through hybridization — is a central challenge in phylogenetics. In these projects, I used extensive simulations to investigate how well current hybridization inference methods perform, and under what conditions they break down.

**Rate variation biases summary tests of introgression.** Popular summary statistics for detecting introgression (e.g., D-statistics and related f-branch tests) assume a molecular clock. I simulated networks with varying degrees of substitution rate variation across lineages to test how robust these methods are when that assumption is violated. I found that most commonly used summary tests have high type-1 error in the face of lineage-rate variation — meaning they can mistake rate heterogeneity for a signal of hybridization. This work is described in {% cite frankel2023summary %}.

**Admixture graph inference accuracy drops with complexity.** Admixture graphs inferred from f-statistics are widely used to reconstruct complex histories of population and species mixture. I evaluated the accuracy of these inference methods on more complex graphs than have typically been tested, using extensive simulations. The results show that accuracy drops considerably as graph complexity increases, which has implications for how confidently these methods can be applied to real, complicated evolutionary histories. See {% cite frankel2026low %} for the full study.
