---
title: "A comprehensive evaluation of consensus spectrum generation methods in proteomics"
date: 2022-05-13
publishDate: 2022-05-13
authors: ["Xiyang Luo", "Wout Bittremieux", "Johannes Griss", "Eric W. Deutsch", "Timo Sachsenberg", "Lev I. Levitsky", "Mark V. Ivanov", "Julia A. Bubis", "Ralf Gabriels", "Henry Webel", "Aniel Sanchez", "Mingze Bai", "Lukas Käll*", "and Yasset Perez-Riverol*"]
publication_types: ["Publication"]
abstract: "Spectrum clustering is a powerful strategy to minimize redundant mass spectra by grouping them based on similarity, with the aim of forming groups of mass spectra from the same repeatedly measured analytes. Each such group of near-identical spectra can be represented by its so-called consensus spectrum for downstream processing. Although several algorithms for spectrum clustering have been adequately benchmarked and tested, the influence of the consensus spectrum generation step is rarely evaluated. Here, we present an implementation and benchmark of common consensus spectrum algorithms, including spectrum averaging, spectrum binning, the most similar spectrum, and the best-identified spectrum. We have analyzed diverse public data sets using two different clustering algorithms (spectra-cluster and MaRaCluster) to evaluate how the consensus spectrum generation procedure influences downstream peptide identification. The BEST and BIN methods were found the most reliable methods for consensus spectrum generation, including for data sets with post-translational modifications (PTM) such as phosphorylation. All source code and data of the present study are freely available on GitHub at https://github.com/statisticalbiotechnology/representative-spectra-benchmark."
featured: false
publication: "*Journal of Proteome Research*"
tags: ["Consensus spectrum", "Comparison", "Spectral libraries", "Proteomics", "Mass spectrometry", "Benchmark"]
doi: "10.1021/acs.jproteome.2c00069"
---
