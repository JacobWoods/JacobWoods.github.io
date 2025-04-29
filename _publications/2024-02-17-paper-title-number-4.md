---
title: "Moment Methods for Advection on Networks and an Application to Forest Pest Life Cycle Models"
collection: publications
category: preprint
permalink:
excerpt: 'This paper develops low-dimensional moment methods for advective problems
on networks of domains with applications to the invasive Spotted Lanternfly.'
date: 2023-08-14
paperurl: 'https://arxiv.org/pdf/2308.06940'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

This paper develops low-dimensional moment methods for advective problems
on networks of domains. The evolution of a density function is described by a linear
advection-diffusion-reaction equation on each domain, combined via advective flux coupling
across domains in the network graph. The PDEs’ coefficients vary in time and across domains
but they are fixed along each domain. As a result, the solution on each domain is frequently
close to a Gaussian that moves, decays, and widens. For that reason, this work studies moment methods that track only three degrees of freedom per domain—in contrast to traditional
PDE discretization methods that tend to require many more variables per domain. A simple
ODE-based moment method is developed, as well as an asymptotic-preserving scheme. We
apply the methodology to an application that models the life cycle of forest pests that undergo
different life stages and developmental pathways. The model is calibrated for the spotted
lanternfly, an invasive species present in the Eastern USA. We showcase that the moment
method, despite its significant low-dimensionality, can successfully reproduce the prediction
of the pest’s establishment potential, compared to much higher-dimensional computational
approaches
