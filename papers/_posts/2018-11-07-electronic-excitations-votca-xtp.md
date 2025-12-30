---
layout: paper
title: "Electronic Excitations in Complex Molecular Environments: Many-Body Green’s Functions Theory in VOTCA-XTP"
year: "2018"
shortref: "Wehner et al., JCTC 14, 6253 (2018)"
nickname: "electronic-excitations-votca-xtp"
journal: "J. Chem. Theory Comput."
volume: 14
issue: 12
pages: 6253 
authors: "Jens Wehner, Lothar Brombacher, Joshua Brown, Christoph Junghans, Onur Çaylak, Yuriy Khalak, Pranav Madhikar, Gianluca Tirimbò, and Björn Baumeier"
image: /assets/images/papers/wehner-electronic-excitations-votca-xtp.svg
redirect_from: 
fulltext: https://pubs.acs.org/doi/10.1021/acs.jctc.8b00617
pdflink: assets/pdfs/wehner-electronic-excitations-votca-xtp.pdf
github: 
pmid: 
pmcid: 
f1000: 
doi: "10.1021/acs.jctc.8b00617"
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
tags: [GW-BSE, QMMM]
---
{% include JB/setup %}

# Abstract 

Many-body Green’s functions theory within the GW approximation and the Bethe-Salpeter Equation (BSE) is implemented in the open-source VOTCA-XTP software, aiming at the calculation of electronically excited states in complex molecular environments. Based on Gaussian-type atomic orbitals and making use of resolution of identity techniques, the code is designed specifically for nonperiodic systems. Application to a small molecule reference set successfully validates the methodology and its implementation for a variety of excitation types covering an energy range from 2 to 8 eV in single molecules. Further, embedding each GW-BSE calculation into an atomistically resolved surrounding, typically obtained from Molecular Dynamics, accounts for effects originating from local fields and polarization. Using aqueous DNA as a prototypical system, different levels of electrostatic coupling between the regions in this GW-BSE/MM setup are demonstrated. Particular attention is paid to charge-transfer (CT) excitations in adenine base pairs. It is found that their energy is extremely sensitive to the specific environment and to polarization effects. The calculated redshift of the CT excitation energy compared to a nucelobase dimer treated in vacuum is of the order of 1 eV, which matches expectations from experimental data. Predicted lowest CT energies are below that of a single nucleobase excitation, indicating the possibility of an initial (fast) decay of such an UV excited state into a binucleobase CT exciton. The results show that VOTCA-XTP’s GW-BSE/MM is a powerful tool to study a wide range of types of electronic excitations in complex molecular environments.
