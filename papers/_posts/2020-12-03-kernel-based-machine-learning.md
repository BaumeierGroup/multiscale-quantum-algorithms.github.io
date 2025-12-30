---
layout: paper
title: "A Kernel based Machine Learning Approach to Computing Quasiparticle Energies within Many-Body Green’s Functions Theory"
year: "2020"
shortref: "Tirimbo, Caylak, Baumeier, NNeurIPS Workshop ML4MOL (2020)"
nickname: "kernel-based-machine-learning"
journal: "NeurIPS Workshop Machine Learning for Molecules"
volume: 
issue: 
pages:  
authors: "Gianluca Tirimbo, Onur Caylak, Bjoern Baumeier"
image: /assets/images/papers/kernel-based-machine-learning.svg
redirect_from: 
fulltext: https://ml4molecules.github.io/papers2020/ML4Molecules_2020_paper_40.pdf
pdflink: /assets/pdfs/tirimbo-caylak-baumeier-kernel-based-machine-learning-2020.pdf
github: 
pmid: 
pmcid: 
f1000: 
doi: "10.48550/arXiv.2012.01787"
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
tags: [machine learning, quantum machine learning, GW-BSE, quasiparticles, Green Functions]
---
{% include JB/setup %}

# Abstract 

We present a Kernel Ridge Regression (KRR) based supervised learning method combined with Genetic Algorithms (GAs) for the calculation of quasiparticle ener- gies within Many-Body Green’s Functions Theory. These energies representing electronic excitations of a material are solutions to a set of non-linear equations, containing the electron self-energy (SE) in the GW approximation. Due to the frequency-dependence of this SE, standard approaches are computationally ex- pensive and may yield non-physical solutions, in particular for larger systems. In our proposed model, we use KRR as a self-adaptive surrogate model which reduces the number of explicit calculations of the SE. Transforming the standard fixed-point problem of finding quasiparticle energies into a global optimization problem with a suitably defined fitness function, application of the GA yields uniquely the physically relevant solution. We demonstrate the applicability of our method for a set of molecules from the GW 100 dataset, which are known to exhibit a particularly problematic structure of the SE. Results of the KRR-GA model agree within less than 0.01 eV with the reference standard implementation, while reducing the number of required SE evaluations roughly by a factor of ten.