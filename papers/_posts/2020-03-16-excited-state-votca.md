---
layout: paper
title: "Excited-state electronic structure of molecules using many-body Green’s functions: Quasiparticles and electron–hole excitations with VOTCA-XTP"
year: "2020"
shortref: "Tirimbo et al., JCP 152, 114103 (2020)"
nickname: "excited-state-votca"
journal: "J. Chem. Phys."
volume: 152
issue: 11
pages: 114103 
authors: "Gianluca Tirimbo, Vivek Sundaram, Onur Caylak, Wouter Scharpach, Javier Sijen, Christoph Junghans, Joshua Brown, Felipe Zapata Ruiz, Nicolas Renaud, Jens Wehner, Bjoern Baumeier"
image: /assets/images/papers/excited-state-votca.svg
redirect_from: 
fulltext: https://aip.scitation.org/doi/10.1063/1.5144277
pdflink: 
github: 
pmid: 
pmcid: 
f1000: 
doi: "10.1063/1.5144277"
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
tags: [electronic excitations, GW-BSE, excited states, quasiparticle energies]
---
{% include JB/setup %}

# Abstract 

We present the open-source VOTCA-XTP software for the calculation of the excited-state electronic structure of molecules using many-body Green’s function theory in the GW approximation with the Bethe–Salpeter equation (BSE). This work provides a summary of the underlying theory and discusses the details of its implementation based on Gaussian orbitals, including resolution-of-identity techniques and different approaches to the frequency integration of the self-energy or acceleration by offloading compute-intensive matrix operations using graphics processing units in a hybrid OpenMP/Cuda scheme. A distinctive feature of VOTCA–XTP is the capability to couple the calculation of electronic excitations to a classical polarizable environment on an atomistic level in a coupled quantum- and molecular-mechanics (QM/MM) scheme, where a complex morphology can be imported from Molecular Dynamics simulations. The capabilities and limitations of the GW–BSE implementation are illustrated with two examples. First, we study the dependence of optically active electron–hole excitations in a series of diketopyrrolopyrrole-based oligomers on molecular-architecture modifications and the number of repeat units. Second, we use the GW–BSE/MM setup to investigate the effect of polarization on localized and intermolecular charge-transfer excited states in morphologies of low-donor content rubrene–fullerene mixtures. These showcases demonstrate that our implementation currently allows us to treat systems with up to 2500 basis functions on regular shared-memory workstations, providing accurate descriptions of quasiparticle and coupled electron–hole excited states of various characters on an equal footing.