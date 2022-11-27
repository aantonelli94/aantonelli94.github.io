---
permalink: /research_areas/statistics
title: "Statistical analysis"
---


A large portion of statistical analyses of GW sources is dedicated to estimating the parameters that best describe the signals we expect in the data.

Current parameter estimation (PE) studies employ Bayesian statistics. This is most apt for GW analyses, since we do have *one* experiment (signal coming) which we cannot really replicate it the way a frequentist statistician would. 

The bread and butter of Bayesian statistics are Monte Carlo analyses, in which one estimates the posteriors for the parameters of interest in a numerical way. However it is also possible to think of certain frequentist concepts in a Bayesian way.  This is the case for  the *Fisher matrix*, which can be seen as the covariance matrix for the Whittle likelihood when the signals are expanded in a high signal-to-noise expansion. The advantage of using Fisher approaches is that they are cheaper to evaluate, and thus more apt for forecast studies. 

>*In my work, I have developed and leveraged Fisher matrix formalisms for the parameter estimation of distribution and source parameters of GW events, often speeding up runs by a factor of 100.*


We have reached a point in GW inference in which we are confronted with many sources. This is great, because it means that we can treat sets of observations *as a whole*. This is the goal of population studies, which are reaching into astrophysical and cosmological inference. With future detectors, having many signals in the data may be problematic for the inference of the parameters of a source we are interested in. It is currently not yet known how to fully deal with such problematics, and only nowadays people are trying to attack the problem.

>*In my work, I have developed novel A/B hypothesis testing methods to gauge when parameter estimation runs of near-future detectors will be biased.*

-------------------------

# Projects


> I have exploited the Fisher matrix to devise A/B testing metrics aimed at assessing when the presence of an unmodelled foreground is problematic in PE studies of future detectors. The same metrics can be used to assess confusion-noise biases from the removal of ill-fitted sources. The metrics we devise compare very well against Monte Carlo analyses, with errors <1$\%$.

 [Software](/portfolio_projects/popfisher){: .btn--research} [Paper I](https://arxiv.org/pdf/2104.01897.pdf){: .btn--research} [Paper II](https://arxiv.org/pdf/2209.13452.pdf){: .btn--research} [Code](https://github.com/aantonelli94/GWOP){: .btn--research}

> I have co-developed a Fisher-matrix formalism for gravitational-wave (GW) population inference. Our approach lends itself to several simplifications that may make the life of GW population analysts easier, especially in the context of forecasts for future detectors. In the process, we also reproduce [previous results](https://arxiv.org/pdf/1004.1921.pdf) in the literature regarding how well we can measure the mass distribution of supermassive black holes with future LISA observations. Our approach takes seconds to run on a laptop, while previous runs required weeks. 

 [Software](/portfolio_projects/noisy_neighbours){: .btn--research} [Paper](https://arxiv.org/pdf/2205.07893.pdf){: .btn--research} [Code](https://github.com/aantonelli94/PopFisher){: .btn--research}