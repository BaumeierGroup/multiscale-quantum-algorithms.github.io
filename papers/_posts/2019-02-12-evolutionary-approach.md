---
layout: paper
title: "Evolutionary Approach to Constructing a Deep Feedforward Neural Network for Prediction of Electronic Coupling Elements in Molecular Materials"
year: "2019"
shortref: "Caylak, Yaman, Baumeier, JCTC 15, 1777 (2019)"
nickname: "evolutionary-approach"
journal: "J. Chem. Theory Comput."
volume: 15
issue: 3
pages: 1777 
authors: "Onur Caylak, Anil Yaman*, and Björn Baumeier"
image: /assets/images/papers/caylak-evolutionary-approach.svg
redirect_from: 
fulltext: https://pubs.acs.org/doi/full/10.1021/acs.jctc.8b01285
pdflink: /assets/pdfs/caylak-evolutionary-approach.pdf
github: 
pmid: 
pmcid: 
f1000: 
doi: "10.1021/acs.jctc.8b01285"
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
tags: [polymers, persistence length]
---
{% include JB/setup %}

# Abstract 

We present a general framework for the construction of a deep feedforward neural network (FFNN) to predict distance and orientation dependent electronic coupling elements in disordered molecular materials. An evolutionary algorithm automatizes the selection of an optimal architecture of the artificial neural network within a predefined search space. Systematic guidance, beyond minimizing the model error with stochastic gradient descent based backpropagation, is provided by simultaneous maximization of a model fitness that takes into account additional physical properties, such as the field-dependent carrier mobility. As a prototypical system, we consider hole transport in amorphous tris(8-hydroxyquinolinato)aluminum. Reference data for training and validation is obtained from multiscale ab initio simulations, in which coupling elements are evaluated using density-functional theory, for a system containing 4096 molecules. The Coulomb matrix representation is chosen to encode the explicit molecular pair coordinates into a rotation and translation invariant feature set for the FFNN. The final optimized deep feedforward neural network is tested for transport models without and with energetic disorder. It predicts electronic coupling elements and mobilities in excellent agreement with the reference data. Such a FFNN is readily applicable to much larger systems at negligible computational cost, providing a powerful surrogate model to overcome the size limitations of the ab initio approach.