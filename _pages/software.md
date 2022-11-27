---
layout: archive
title: ""
permalink: /software/
author_profile: true
---


## The elusive origin of black holes in binaries




[<center> <img src='/images/software/RF_predictions.png' alt =  ''> </center>](/portfolio_projects/BH_classification)



[Post](/posts/2022/11/BHClassifier/){: .btn--research}
[GitHub](https://github.com/aantonelli94/TheBHClassifier){: .btn--research}


<details open> 
    <summary> 
       <b>
      The question
       </b>
    </summary>
      <em>
      Can we establish the origin of black holes detected in binaries?
      </em>
</details>


<details open> 
    <summary> 
      <b>
      The strategy
      </b>
    </summary>
      <em>
      I wrangle a large dataset  from a suit of simulations for dynamically-formed black-hole binaries. I use the set to train a machine-learning classification model. I cross-validate the model and apply it to messy data from interferometers.
      </em>
</details>


<details open> 
    <summary> 
       <b>
      The final product
       </b>
    </summary>
     <em>
      A model that predicts the binary's formation path and how many dynamical interactions were undertaken by the black holes with 85 and 99 percent accuracy, respectively.
      </em>
</details>






## A polynomial regression model for the loudness of massive black-hole binaries



[ <center> <img  height = "600" width = "600" src='/images/software/SNRfit_validation.png' > </center>  ](/posts/2022/11/SNRFits)



[Post](/posts/2022/11/SNRFits){: .btn--research}
[GitHub](https://github.com/aantonelli94/SNR_fits){: .btn--research}
 


<details open> 
    <summary> 
       <b>
      The question
       </b>
    </summary>
      <em>
      Can we detect large black holes with future gravitational-wave experiments?
      </em>
</details>


<details open> 
    <summary> 
      <b>
      The strategy
      </b>
    </summary>
      <em>
     I create and wrangle a dataset from a large suite of simulations of the signal-to-noise ratio (SNR) of intermediate mass black holes, using  dedicated software and parallel computing. I train a polynomial regression model to predict the SNR using a variety of detector configurations. I validate the model on both test data and dedicated mock simulations.
      </em>
</details>


<details open> 
    <summary> 
       <b>
      The final product
       </b>
    </summary>
     <em>
      A regression model that, given a detector network, predicts whether an intermediate-mass black hole will be observed with 99 percent accuracy.
      </em>
</details>






##  PopFisher: gravitational-wave hyperparameter estimation made easy!




[<img  width="1000" height="1000" src='/images/software/hyperpar.png' alt =  ''>](/posts/2022/05/PopFisher/)


[Post](/posts/2022/05/PopFisher/){: .btn--research}
[GitHub](https://github.com/aantonelli94/PopFisher){: .btn--research}
[Paper](https://arxiv.org/pdf/2205.07893.pdf){: .btn--research}


<details open> 
    <summary> 
       <b>
      The question
       </b>
    </summary>
      <em>
      Can we quickly and effectively estimate the parameters that describe distributions of supermassive black holes?
      </em>
</details>


<details open> 
    <summary> 
      <b>
      The strategy
      </b>
    </summary>
      <em>
     I used Monte Carlo analysis through Python's $\texttt{emcee}$ and a Fisher-matrix formalism to quickly and reliably estimate the index of the power law usually used to model the distribution of supermassive black holes.
      </em>
</details>


<details open> 
    <summary> 
       <b>
      The final product
       </b>
    </summary>
     <em>
      A code that can estimate the hyperparameters of distributions of supermassive black holes in a matter of seconds.
     </em>
</details>




## An A/B test for biased gravitational-wave signals



[<img src='/images/software/TD_waveform.png' alt =  ''>](/posts/2022/09/NoisyNeighbours)



[Post](/posts/2022/09/NoisyNeighbours){: .btn--research}
[GitHub](https://github.com/aantonelli94/GWOP){: .btn--research}
[Paper I](https://arxiv.org/pdf/2104.01897.pdf){: .btn--research}
[Paper II](https://arxiv.org/pdf/2209.13452.pdf){: .btn--research}


<details open> 
    <summary> 
       <b>
      The question
       </b>
    </summary>
      <em>
      Can we reliably estimate the parameters describing binary black holes, when their signals are buried in other loud signals?
      </em>
</details>


<details open> 
    <summary> 
      <b>
      The strategy
      </b>
    </summary>
      <em>
     I create a mock dataset of both resolved and unresolved binary black hole time-series signals. I set up a Markov-Chain Monte Carlo infrastructure to estimate the parameters of an individual signal in the presence of the mock data.
      </em>
</details>


<details open> 
    <summary> 
       <b>
      The final product
       </b>
    </summary>
     <em>
       A (semi-)analytical A/B testing infrastructure that reliably detects anomalies (biases) in the parameter estimation of time-series signals in the presence of an unmodelled or poorly-modelled background. 
      </em>
</details>








{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

