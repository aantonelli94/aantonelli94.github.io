---
title: 'A Fisher matrix for gravitational-wave population inference'
date: 2022-05-18
permalink: /posts/2022/05/PopFisher/
excerpt_separator: <!--more-->
toc: true
tags:
  - paper
---


Population analyses with gravitational-wave (GW) data are hard and computationally expensive, but absolutely crucial for the future of GW astrophysics in the blogger's humble opinion.

In our [paper](https://arxiv.org/pdf/2205.07893.pdf) with Jon Gair and Riccardo Barbieri, we have taken a step back and thought about alternative ways to estimate the precision on distribution parameters that would better lend themselves to quick and dirty forecast estimates. In purely Jon's style, we ended up within a Fisher-matrix formalism. 

We find that a formalism can be developed for arbitrary population models, and including selection effects and uncertainties in individual events' measurements. In its full glory the final equation (last in Sec.2) is admittedly brutal, but there are ways to make it more tractable. Tip: the first term is what you mostly care about!

We applied the formalism to a toy model and a more GW-like example in which we estimate the spectral index of the mass spectrum of supermassive black holes. In the process we reproduce results in the literature, but without the large computational overhead that Jon tells me was needed for [his previous paper](https://arxiv.org/pdf/1004.1921.pdf).

We find that, mostly, the results can be reproduced with an expression that can be written down very easily (Eq. 51). That's how useful our formalism could be!

If you have the interest (and stamina), you could also read some of the notes and comments I've written in the [public codes](https://github.com/aantonelli94/PopFisher), which I hope could be useful for anyone interested in reproducing the results or use the formalism for their own research.