---
permalink: /research_areas/statistics
title: "Statistical analyses"
---

-------------------------

# Glossary


A large portion of statistical analyses of GW sources is dedicated to estimating the parameters that best describe the signals we expect in the data.

Current parameter estimation (PE) studies employ Bayesian statistics. This is most apt for GW analyses, since we do have *one* experiment (signal coming) which we cannot really replicate it the way of a hardcore frequentist would. 

The bread and butter of Bayesian statistics are Monte Carlo analyses, in which one estimates the posteriors for the parameters of interest in a numerical way. However it is also possible to think of certain frequentist concepts in a Bayesian way.  This is the case for  the *Fisher matrix*, which can be seen as the covariance matrix for the Whittle likelihood when the signals are expanded in a high signal-to-noise expansion. The advantage of using Fisher approaches is that they are cheaper to evaluate, and thus more apt for forecast studies. In any case, when possible, results from both approaches should be compared for robust parameter inference.

We have reached a point in GW inference in which we are confronted with many sources. This is great, because it means that we can treat sets of observations *as a whole*. This is the goal of population studies, which are reaching into astrophysical and cosmological inference. 

With future detectors, having many signals in the data may be problematic for the inference of the parameters of a source we are interested in. It is currently not yet known how to fully deal with such problematics, and only nowadays people are trying to attack the problem.

-------------------------

# Projects


- Collaborators and I have exploited the Fisher matrix to devise metrics aimed at assessing when the presence of an unmodelled foreground is problematic in PE studies of future detectors. The same metrics can be used to assess confusion-noise biases from the removal of ill-fitted sources. The metrics we devise compare very well against Monte Carlo analyses. [Paper](https://arxiv.org/pdf/2104.01897.pdf){: .btn--research} [Code](https://github.com/aantonelli94/GWOP){: .btn--research}

- We have developed a Fisher-matrix formalism for gravitational-wave (GW) population inference. We propose several illustrations and compare the Fisher predictions against independent Monte Carlo analyses, finding very good agreement. Our approach lends itself to several simplifications that may make the life of GW population analysts easier, especially in the context of forecasts for future detectors. In the process, we also reproduce [previous results](https://arxiv.org/pdf/1004.1921.pdf) in the literature regarding how well we can measure the mass distribution of supermassive black holes with future LISA observations. [Paper](https://arxiv.org/pdf/2205.07893.pdf){: .btn--research} [Code](https://github.com/aantonelli94/PopFisher){: .btn--research}