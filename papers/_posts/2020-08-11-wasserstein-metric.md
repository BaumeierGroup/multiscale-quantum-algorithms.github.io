---
layout: paper
title: "Wasserstein metric for improved quantum machine learning with adjacency matrix representations"
year: "2020"
shortref: "Caylak, Baumeier, von Lilienfeld, MLST 1, 03LT01 (2020)"
nickname: "wasserstein-metric"
journal: "Mach. Learn.: Sci. Technol."
volume: 1
issue: 3
pages: 03LT01 
authors: "Onur Caylak, Bjoern Baumeier, O. Anatole von Lilienfeld"
image: /assets/images/papers/wasserstein-metric.svg
redirect_from: 
fulltext: https://iopscience.iop.org/article/10.1088/2632-2153/aba048
pdflink: /assets/pdfs/caylak-baumeier-lilienfeld-wasserstein-metric-2020.pdf
github: 
pmid: 
pmcid: 
f1000: 
doi: "10.1088/2632-2153/aba048"
dryad_doi: 
figshare_doi: 
altmetric_id: 
category: paper
# Note: 'published' is a Jekyll keyword and does not refer to whether the paper is published, but rather to whether this Markdown should be part of the rendered site.
published: true
preprint: false
embargo: false	
peerreview: true
review: true
tags: [machine learning, quantum machine learning, molecular represenations, Wasserstein]
---
{% include JB/setup %}

# Abstract 

We study the Wasserstein metric to measure distances between molecules represented by the atom index dependent adjacency ‘Coulomb’ matrix, used in kernel ridge regression based supervised learning. Resulting machine learning models of quantum properties, a.k.a. quantum machine learning models exhibit improved training efficiency and result in smoother predictions of energies related to molecular distortions. We first illustrate smoothness for the continuous extraction of an atom from some organic molecule. Learning curves, quantifying the decay of the atomization energy’s prediction error as a function of training set size, have been obtained for tens of thousands of organic molecules drawn from the QM9 data set. In comparison to conventionally used metrics (L1 and L2 norm), our numerical results indicate systematic improvement in terms of learning curve off-set for random as well as sorted (by norms of row) atom indexing in Coulomb matrices. Our findings suggest that this metric corresponds to a favorable similarity measure which introduces index-invariance in any kernel based model relying on adjacency matrix representations.