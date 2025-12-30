---
layout: paper
title: "Automatic identification of traps in molecular charge transport networks of organic semiconductors"
year: "2025"
shortref: "Chen, van der Hoorn, Baumeier, Phys. Rev. B (2025)"
nickname: "trap-identification"
journal: "Phys. Rev. B"
volume: 111
issue: 
pages:  224209
authors: "Zhongquan Chen, Pim van der Hoorn, Bjoern Baumeier"
image: /assets/images/papers/trap-identification.svg
redirect_from: 
fulltext: https://journals.aps.org/prb/abstract/10.1103/shyl-kcfp
pdflink: /assets/pdfs/chen-trap-identification-2024.pdf
github: 
pmid: 
pmcid: 
f1000: 
doi: 10.1103/shyl-kcfp
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
tags: [multiscale models, charge transport]
---
{% include JB/setup %}

# Abstract
 
This paper introduces a method to identify traps in molecular charge transport networks as obtained by multiscale modeling of organic semiconductors. Depending on the materials, traps can be defect-like single molecules or clusters of several neighboring ones, and can have a significant impact on the dynamics of charge carriers. Our proposed method builds on the random walk model of charge dynamics on a directed, weighted graph, the molecular transport network. It comprises an effective heuristic to determine the number of traps or trap clusters based on the eigenvalues and eigenvectors of the random walk Laplacian matrix and uses subsequent spectral clustering techniques to identify these traps. In contrast to currently available methods, ours enables identification of trap molecules in organic semiconductors without having to explicitly simulate the charge dynamics. As a prototypical system we study an amorphous morphology of bathocuproine, a material with known high energetic disorder and charge trapping. Based on a first-principle multiscale model, we first obtain a reference charge transport network and then modify its properties to represent different trap characteristics. In contrast to currently available methods, our approach successfully identifies both single trap, multiple distributed traps, and a combination of a single-molecule trap and trap regions on an equal footing. 
