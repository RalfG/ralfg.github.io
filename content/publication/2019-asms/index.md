---
title: "MS²PIP : fast and accurate MS² peak intensity prediction for multiple fragmentation methods, instruments and labeling techniques"
date: 2019-06-01
publishDate: 2020-02-16T11:34:26.299121Z
authors: ["Ralf Gabriels", "Lennart Martens", "Sven Degroeve"]
publication_types: ["1"]
abstract: "An important step in high-throughput mass spectrometry-based proteomics is the correct identification of peptide MS² fragmentation spectra. Due to incomplete understanding of the fragmentation process and unpredictable machine noise, matching MS² spectra with the correct peptide is far from trivial. We therefore developed, in 2013, MS²PIP: MS² Peak Intensity Prediction, a data-driven tool that accurately predicts the expected MS² spectrum for a given peptide. Nevertheless, specific fragmentation techniques, instruments and isobaric labels influence the peak intensities in such a way, that the general MS²PIP models underperform when predicting for these special cases. Because MS²PIP is a purely data-driven approach, we can make use of the vast quantities of publicly available proteomics data and train specific MS²PIP models on relevant datasets.


To train and evaluate specific MS²PIP models for CID and HCD fragmentation, for TripleTOF 5600+ instruments and for TMT and iTRAQ-labeled peptides, we downloaded and parsed a multitude of publicly available spectral libraries and experimental datasets. The size of the train-test datasets ranged from 129 000 to 1.6 million unique peptide spectra. We can evaluate the models’ performance by predicting MS² spectra present in the external evaluation datasets and comparing these predictions to their corresponding empirical spectra. This comparison is done by calculating the Pearson correlation coefficient of the two spectra, each normalized to their total-ion-current. 


The median Pearson correlations are consistently and substantially higher when we apply the specific models to the corresponding specific evaluation dataset (e.g. TMT model to TMT dataset), then when we apply the specific models to mismatched evaluation datasets (e.g. TMT model to CID dataset). This confirms that there are indeed strong differences in fragmentation pattern between the specific cases, and emphasizes the need for specific MS²PIP models. 


Predictions from the specific models yield median Pearson correlations higher then 0.90, except for the TripleTOF 5600+ and the iTRAQ phospho models, which have median Pearson correlations of 0.74 and 0.84, respectively. It is also noteworthy that models for labeling techniques perform similarly on all datasets, indicating that TMT and iTRAQ labels affect the fragmentation pattern in a comparable fashion.


MS²PIP has already been used for creating proteome-wide spectral libraries for search engines (including Data Independent Acquisition), for selecting discriminative transitions for targeted proteomics and for validating interesting peptide identifications (e.g. biomarkers). These new models extend the applicability of MS²PIP even further, allowing it to be applied when specific fragmentation methods, instruments, or labeling techniques are employed.


All MS²PIP models are available on the user-friendly MS²PIP web server (https://iomics.ugent.be/ms2pip). Users can upload up to 100.000 peptide sequences simultaneously, for which MS²PIP predicts MS² spectra in just a few seconds. The resulting spectra can be inspected through interactive plots and can be downloaded in both CSV and MGF file formats.


With these specific models, MS²PIP is the first MS² peak intensity predictor for specific instruments, fragmentation methods and labeling techniques."
featured: false
publication: "*ASMS 67th conference, Abstracts*"
tags: ["MS²PIP", "Proteomics", "Machine Learning", "Bioinformatics"]
url_pdf: "https://biblio.ugent.be/publication/8641638/file/8641656.pdf"
url_project: "https://iomics.ugent.be/ms2pip"
url_code: "https://github.com/compomics/ms2pip_c"
doi: "10.13140/RG.2.2.34973.97761"
---


