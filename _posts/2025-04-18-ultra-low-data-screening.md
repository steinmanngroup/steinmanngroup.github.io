---
layout: post
author: Casper Steinmann
title: "Finding Drug Candidate Hits With a Hundred Samples: Ultra-low Data Screening With Active Learning"
---

A new preprint from our collaboration with the Jensen group is now available on [ChemRxiv](https://chemrxiv.org/doi/full/10.26434/chemrxiv-2025-jlml5).

Virtual screening of large compound libraries typically requires extensive affinity evaluations — a bottleneck for academic labs with limited experimental capacity. In this work, Nielsen, Rasmussen, Steinmann, Ree, Gajhede, Stenvang and Jensen ask how few evaluations are actually needed to reliably identify top hits from a large library.

Using an active learning framework applied to the NCI Developmental Therapeutics Program (DTP) compound library, we show that as few as **110 affinity evaluations** are sufficient to identify drug candidate hits with high confidence. The key is choosing the right combination of molecular representation and model: continuous and data-driven descriptors (CDDD) paired with a multi-layer perceptron (MLP), augmented with pairwise difference regression (PADRE) for data augmentation, emerged as the best-performing strategy.

With this setup, the active learning loop achieves a **97% probability of recovering at least five top-1% hits** from the full library — a result that makes high-throughput screening tractable even under severe data constraints.

The work directly addresses a persistent gap in computational drug discovery: the assumption that large labeled datasets are a prerequisite for useful predictions. By demonstrating reliable hit discovery in the ultra-low data regime, this opens up active learning as a practical tool for resource-limited screening campaigns.
