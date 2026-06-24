---
title: "Benchmarking of AlphaFold Results for Structural Protein Variants"
date: 2024-07-05
tags: ["project", "thesis"]
---

# Overview

Computational structural analysis of protein (serpin) variants to evaluate the ability of AI-based structure prediction and molecular dynamics simulations to capture mutation-induced conformational changes associated with disease phenotypes.

# Problem

Serpins are highly conserved but conformationally flexible proteins, where pathogenic mutations can induce large-scale structural transitions leading to loss of function. However, predicting these conformational effects computationally remains challenging. Despite advances in protein structure predicion (e.g. AlphaFold), it is unclear whether these methods can accurately capture mutation-driven conformational shifts in serpins.

# Solution

Integrated clinically and experimentally validated mutation datasets with computational structural modeling approaches. Generated wild-type and mutant serpin structures using AlphaFold and performed long-timescale molecular dynamics simulations under conditions designed to induce conformational transitions. Compared predicted structural stability and conformational behavior across variants.

# Stack

Python · AlphaFold · Molecular Dynamics (Maestro Desmond) · Linux · HPC

# Impact

* Evaluated the limitations of state-of-the-art, AI-based protein structure prediction methods.
* Demonstrated that AlphaFold converge toward native-like conformations even for experimentally validated destabilizing mutations.
* Provided evidence highlighting the need for improved computational strategies for flexible protein systems such as serpins.
* Contributed to peer-reviewed research in structural biology and computational biophysics.

# Related Publications

`Garrido-Rodríguez, P., Carmena-Bargueño, M., de la Morena-Barrio, M. E., Bravo-Pérez, C., de la Morena-Barrio, B., Cifuentes-Riquelme, R., Lozano, ML., Pérez-Sánchez, H. & Corral, J. (2024). Analysis of AlphaFold and molecular dynamics structure predictions of mutations in serpins. Plos one, 19(7), e0304451.`

DOi: [10.1371/journal.pone.0304451](https://doi.org/10.1371/journal.pone.0304451)
