---
layout: paper
title: "Microscopic Simulations of Charge Transport in Disordered Organic Semiconductors"
year: "2011"
shortref: "Rühle et al., JCTC 7, 3335 (2011)"
nickname: "microscopic-simulations"
journal: "J. Chem. Theory Comput."
volume: 7
issue: 10
pages: 3335 
authors: "Victor Rühle, Alexander Lukyanov, Falk May, Manuel Schrader, Thorsten Vehoff, James Kirkpatrick, Björn Baumeier, and Denis Andrienko"
image: /assets/images/papers/microscopic-simulations.svg
redirect_from: 
fulltext: https://pubs.acs.org/doi/10.1021/ct200388s
pdflink: /assets/pdfs/ct200388s.pdf
github: 
pmid: 
pmcid: 
f1000: 
doi: "10.1021/ct200388s"
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

Charge carrier dynamics in an organic semiconductor can often be described in terms of charge hopping between localized states. The hopping rates depend on electronic coupling elements, reorganization energies, and driving forces, which vary as a function of position and orientation of the molecules. The exact evaluation of these contributions in a molecular assembly is computationally prohibitive. Various, often semiempirical, approximations are employed instead. In this work, we review some of these approaches and introduce a software toolkit which implements them. The purpose of the toolkit is to simplify the workflow for charge transport simulations, provide a uniform error control for the methods and a flexible platform for their development, and eventually allow in silico prescreening of organic semiconductors for specific applications. All implemented methods are illustrated by studying charge transport in amorphous films of tris-(8-hydroxyquinoline)aluminum, a common organic semiconductor.