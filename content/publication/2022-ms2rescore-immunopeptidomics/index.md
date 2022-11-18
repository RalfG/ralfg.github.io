---
title: "MS²Rescore: Data-driven rescoring dramatically boosts immunopeptide identification rates"
date: 2022-08-16
publishDate: 2022-08-16
authors: ["Arthur Declercq", "Robbin Bouwmeester", "Aurélie Degroeve", "Hirschler", "Christine Carapito", "Sven", "Lennart Martens", "Ralf Gabriels"]
publication_types: ["2"]
abstract: "Immunopeptidomics aims to identify major histocompatibility complex (MHC)-presented peptides on almost all cells that can be used in anti-cancer vaccine development. However, existing immunopeptidomics data analysis pipelines suffer from the nontryptic nature of immunopeptides, complicating their identification. Previously, peak intensity predictions by MS2PIP and retention time predictions by DeepLC have been shown to improve tryptic peptide identifications when rescoring peptide-spectrum matches with Percolator. However, as MS2PIP was tailored toward tryptic peptides, we have here retrained MS2PIP to include nontryptic peptides. Interestingly, the new models not only greatly improve predictions for immunopeptides but also yield further improvements for tryptic peptides. We show that the integration of new MS2PIP models, DeepLC, and Percolator in one software package, MS2Rescore, increases spectrum identification rate and unique identified peptides with 46% and 36% compared to standard Percolator rescoring at 1% FDR. Moreover, MS2Rescore also outperforms the current state-of-the-art in immunopeptide-specific identification approaches. Altogether, MS2Rescore thus allows substantially improved identification of novel epitopes from existing immunopeptidomics workflows."
featured: true
publication: "*Molecular & Cellular Proteomics*"
tags: ["bioinformatics", "immunopeptidomics", "machine learning", "proteomics", "mass spectrometry", "peptide identification"]
doi: "10.1016/j.mcpro.2022.100266"
url_pdf: "https://biblio.ugent.be/publication/8766058/file/8766059.pdf"
url_project: "https://github.com/compomics/ms2rescore"
url_code: "https://github.com/compomics/ms2rescore"
---
