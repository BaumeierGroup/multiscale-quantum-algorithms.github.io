---
layout: paper
title: "Efficient Simulation of Markov Chains Using Segmentation"
year: "2014"
shortref: "Brereton et al., Methodology and Computing in Applied Probability 16, 465 (2014)"
nickname: "efficient-simulation"
journal: "Methodology and Computing in Applied Probability "
volume: 16
issue: 2
pages: 465 
authors: "Tim Brereton, Ole Stenzel, Björn Baumeier, Denis Andrienko, Volker Schmidt & Dirk Kroese "
image: /assets/images/papers/efficient-simulation.svg
redirect_from: 
fulltext: https://link.springer.com/article/10.1007/s11009-013-9327-x
pdflink: 
github: 
pmid: 
pmcid: 
f1000: 
doi: "10.1007/s11009-013-9327-x"
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

A methodology is proposed that is suitable for efficient simulation of continuous-time Markov chains that are nearly-completely decomposable. For such Markov chains the effort to adequately explore the state space via Crude Monte Carlo (CMC) simulation can be extremely large. The purpose of this paper is to provide a fast alternative to the standard CMC algorithm, which we call Aggregate Monte Carlo (AMC). The idea of the AMC algorithm is to reduce the jumping back and forth of the Markov chain in small subregions of the state space. We accomplish this by aggregating such problem regions into single states. We discuss two methods to identify collections of states where the Markov chain may become ‘trapped’: the stochastic watershed segmentation from image analysis, and a graph-theoretic decomposition method. As a motivating application, we consider the problem of estimating the charge carrier mobility of disordered organic semiconductors, which contain low-energy regions in which the charge carrier can quickly become stuck. It is shown that the AMC estimator for the charge carrier mobility reduces computational costs by several orders of magnitude compared to the CMC estimator.