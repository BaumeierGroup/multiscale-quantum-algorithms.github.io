---
layout: paper
title: "Excited-State Geometry Optimization of Small Molecules with Many-Body Green’s Functions Theory"
year: "2021"
shortref: "Caylak and Baumeier, JCTC 17, 879 (2021)"
nickname: "excited-state-geometry-optimization"
journal: "J. Chem. Theory Comput."
volume: 17
issue: 2
pages: 879 
authors: "Onur Caylak, Bjoern Baumeier"
image: /assets/images/papers/excited-state-geometry-optimization.svg
redirect_from: 
fulltext: https://pubs.acs.org/doi/10.1021/acs.jctc.0c01099
pdflink: /assets/pdfs/caylak-baumeier-excited-state-geometry-optimization-2021.pdf
github: 
pmid: 
pmcid: 
f1000: 
doi: "10.1021/acs.jctc.0c01099"
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
tags: [excited state, GW-BSE, geometry optimization]
---
{% include JB/setup %}

# Abstract 

We present a benchmark study of gas phase geometry optimizations in the excited states of carbon monoxide, acetone, acrolein, and methylenecyclopropene using many-body Green’s functions theory within the GW approximation and the Bethe–Salpeter equation (BSE) employing numerical gradients. We scrutinize the influence of several typical approximations in the GW-BSE framework; we used one-shot G0W0 or eigenvalue self-consistent evGW, employing a fully analytic approach or plasmon-pole model for the frequency dependence of the electron self-energy, or performing the BSE step within the Tamm–Dancoff approximation. The obtained geometries are compared to reference results from multireference perturbation theory (CASPT2), variational Monte Carlo (VMC) method, second-order approximate coupled cluster (CC2) method, and time-dependent density-functional theory (TDDFT). We find overall a good agreement of the structural parameters optimized with the GW-BSE calculations with CASPT2, with an average relative error of around 1% for the G0W0 and 1.5% for the evGW variants based on a PBE0 ground state, respectively, while the other approximations have negligible influence. The relative errors are also smaller than those for CC2 and TDDFT with different functionals and only larger than VMC, indicating that the GW-BSE method does not only yield excitation energies but also geometries in good agreement with established higher-order wave function methods.