---
layout: paper
title: "A General Framework for Consistent Estimation of Charge Transport Properties via Random Walks in Random Environments"
year: "2014"
shortref: "Stenzel et al., Multiscale Model. Simul. 12, 1108 (2014)"
nickname: "general-framework"
journal: "Multiscale Modeling & Simulation"
volume: 12
issue: 3
pages: 1108 
authors: "Ole Stenzel, Christian Hirsch, Tim Brereton, Bjoern Baumeier, Denis Andrienko, Dirk Kroese, and Volker Schmidt"
image: /assets/images/papers/general-framework.svg
redirect_from: 
fulltext: https://epubs.siam.org/doi/10.1137/130942504
pdflink: 
github: 
pmid: 
pmcid: 
f1000: 
doi: "10.1137/130942504"
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

A general framework is proposed for the study of the charge transport properties of materials via random walks in random environments (RWRE). The material of interest is modeled by a random environment, and the charge carrier is modeled by a random walker. The framework combines a model for the fast generation of random environments that realistically mimic materials morphology with an algorithm for efficient estimation of key properties of the resulting random walk. The model of the environment makes use of tools from spatial statistics and the theory of random geometric graphs. More precisely, the disordered medium is represented by a random spatial graph with directed edge weights, where the edge weights represent the transition rates of a Markov jump process (MJP) modeling the motion of the random walker. This MJP is a multiscale stochastic process. In the long term, it explores all vertices of the random graph model. In the short term, however, it becomes trapped in small subsets of the state space and makes many transitions in these small regions. This behavior makes efficient estimation of velocity by Monte Carlo simulations a challenging task. Therefore, we use aggregate Monte Carlo (AMC), introduced in [T. Brereton et al., Methodol. Comput. Appl. Probab., 16 (2014), pp. 465--484], for estimating the velocity of a random walker as it passes through a realization of the random environment. In this paper, we prove the strong consistency of the AMC velocity estimator and use this result to conduct a detailed case study, in which we describe the motion of holes in an amorphous mesophase of an organic semiconductor, dicyanovinyl-substituted oligothiophene (DCV4T). In particular, we analyze the effect of system size (i.e., number of molecules) on the velocity of single charge carriers.