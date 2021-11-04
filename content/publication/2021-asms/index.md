---
title: "MS²DIP: Highly accurate MS2 spectrum prediction for modified peptides & MS²Rescore: Data-driven rescoring dramatically boosts  immunopeptide identification rates"
date: 2021-11-03
publishDate: 2021-11-04
authors: ["Ralf Gabriels", "Arthur Declercq", "Robbin Bouwmeester", "Jasper Zuallaert", "Lennart Martens", "Sven Degroeve"]
publication_types: ["1"]
abstract: "Accurate MS2 spectrum predictions enable drastic improvements in peptide identification workflows. This identification improvement is particularly useful for challenging proteomics experiments where conventional identification software often falls short. Notable examples of such cases are proteogenomics, data independent acquisition, and open modification searches. The latter also implicitly requires models that can account for residue modifications, but current state-of-the-art MS2 spectrum predictors cannot take these into account. Instead, the corresponding mass shift is introduced, and peak intensities are simply presumed to remain the same for modified and unmodified forms. We here therefore introduce a novel peptide spectrum predictor, called MS²DIP, which can provide accurate predictions for peptides carrying residue modifications, including for modifications not seen during training.

Immunopeptidomics aims to identify immunopeptides, which are presented on major histocompatibility complexes. Existing mmunopeptidomics data analysis pipelines have some major hurdles to overcome, which complicates their identification. To enable MS²PIP-based rescoring of immunopeptide PSMs, we have retrained MS²PIP for non-tryptic peptides. Next, the new MS²PIP models, DeepLC, and Percolator were integrated into one software package, called MS²Rescore. Using this integration, we could identify 46% more spectra and 36% more unique peptides at 1% false discovery rate. The integration of the new immunopeptide MS²PIP models, DeepLC, and Percolator into MS²Rescore shows great promise to substantially improve the identification of novel neo- and xeno-epitopes in existing immunopeptidomics workflows."

featured: false
publication: "*ASMS 69th conference, Abstracts*"
tags: ["MS²DIP", "MS²Rescore", "Proteomics", "Immunopeptidomics", "Mass spectrometry", "Machine Learning", "Bioinformatics"]
url_pdf: "https://zenodo.org/record/5645168/files/2021-10-28%20ASMS%202021%20Poster.pdf?download=1"
doi: "https://doi.org/10.5281/zenodo.5645168"
---
