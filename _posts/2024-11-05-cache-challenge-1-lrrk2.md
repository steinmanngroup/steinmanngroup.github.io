---
layout: post
author: Casper Steinmann
title: "CACHE Challenge #1: Targeting the WDR Domain of LRRK2"
---

The results of the first [CACHE (Critical Assessment of Computational Hit-Finding Experiments) challenge](https://cache-challenge.org/) have been published in the [*Journal of Chemical Information and Modeling*](https://doi.org/10.1021/acs.jcim.4c01267). I was one of the 23 participating computational teams.

CACHE is a prospective benchmarking series designed to evaluate the state of the art in computational hit-finding under realistic, blinded conditions. In this inaugural challenge, the target was the WDR domain of LRRK2 — a Parkinson's disease-associated protein with no known ligand and only an apo structure available in the PDB. The absence of prior binding data and the presumably low druggability of the site made this a deliberately difficult test case.

Each team selected up to 100 commercially available compounds predicted to bind the target. Of the 1955 molecules submitted in Round 1, **73 were confirmed binders** in an SPR assay (K_D < 150 μM). These hits were advanced to a Round 2 expansion phase, where teams selected analogs. Binding was confirmed in two orthogonal assays for **seven chemically diverse series**, with affinities ranging from 18 to 140 μM.

The seven successful workflows were strikingly diverse: three used molecular dynamics-derived conformational ensembles, three included fragment docking, three applied generative design, and five incorporated deep learning. Notably, machine learning-accelerated methods performed comparably to exhaustive docking — neither dominated. The overall hit rate was low, consistent with a challenging, cryptic binding site, and confirmed binders were weakly potent. CACHE #1 thus paints an honest picture of the current frontier: powerful but still insufficient for truly difficult targets.
