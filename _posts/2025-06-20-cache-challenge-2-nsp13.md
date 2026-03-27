---
layout: post
author: Casper Steinmann
title: "CACHE Challenge #2: Targeting the RNA-Binding Site of SARS-CoV-2 Nsp13 Helicase"
---

Results from the second [CACHE challenge](https://cache-challenge.org/) are now published in the [*Journal of Chemical Information and Modeling*](https://doi.org/10.1021/acs.jcim.5c00535). I was again a contributing computational team.

This challenge targeted the RNA-binding site of the SARS-CoV-2 Nsp13 helicase — a highly conserved COVID-19 target. Twenty-three teams used protein structure and fragment-screening data, combined with computational and machine learning methods, to each predict up to 100 inhibitory ligands. In total, 1957 compounds were procured and tested.

The overall hit rate was **0.7%** by SPR, reflecting the difficulty of the site. The six best-performing workflows employed fragment growing, active learning, or conventional virtual screening augmented with deep-learning scoring functions. Follow-up functional assays identified **two compound scaffolds** with K_d values below 10 μM that also inhibited in vitro helicase activity.

A clear pattern is emerging across the first two CACHE challenges: workflows that link or grow docked/crystallized fragments, or that use docking of small diverse libraries to train ultrafast machine-learning surrogates, are recurrently among the top performers. CACHE #2 demonstrates that crowd-sourced, critically assessed benchmarking can yield genuinely novel lead matter even for challenging viral targets.
