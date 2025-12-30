---
layout: paper
title: "Machine Learning of Quasiparticle Energies in Molecules and Clusters"
year: "2021"
shortref: "Caylak and Baumeier, JCTC 17, 4891 (2021)"
nickname: "machine-learning-quasiparticle"
journal: "J. Chem. Theory Comput."
volume: 17
issue: 8
pages: 4891 
authors: "Onur Caylak, Bjoern Baumeier"
image: /assets/images/papers/machine-learning-quasiparticle.svg
redirect_from: 
fulltext: https://pubs.acs.org/doi/full/10.1021/acs.jctc.1c00520
pdflink: /assets/pdfs/caylak-baumeier-machine-learning-quasiparticle-2021.pdf
github: 
pmid: 
pmcid: 
f1000: 
doi: "10.1021/acs.jctc.1c00520"
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
tags: [stress granules, biomolecular condensation, condensates, RNA]
---
{% include JB/setup %}

# Abstract 

We present a Δ-machine learning approach for the prediction of GW quasiparticle energies (ΔMLQP) and photoelectron spectra of molecules and clusters, using orbital-sensitive representations (OSRs) based on molecular Cartesian coordinates in kernel ridge regression-based supervised learning. Coulomb matrix, bag-of-bond, and bond-angle-torsion representations are made orbital-sensitive by augmenting them with atom-centered orbital charges and Kohn–Sham orbital energies, both of which are readily available from baseline calculations at the level of density functional theory (DFT). We first illustrate the effects of different constructions of the OSRs on the prediction of frontier orbital energies of 22k molecules of the QM8 data set and show that it is possible to predict the full photoelectron spectrum of molecules within the data set using a single model with a mean absolute error below 0.1 eV. We further demonstrate that the OSR-based ΔMLQP captures the effects of intra- and intermolecular conformations in application to water monomers and dimers. Finally, we show that the approach can be embedded in multiscale simulation workflows, by studying the solvatochromic shifts of quasiparticle and electron–hole excitation energies of solvated acetone in a setup combining molecular dynamics, DFT, the GW approximation, and the Bethe–Salpeter equation. Our findings suggest that the ΔMLQP model allows us to predict quasiparticle energies and photoelectron spectra of molecules and clusters with GW accuracy at DFT cost.