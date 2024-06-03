# Observable Propagation

This repository contains the code used to carry out the experiments in our paper on observable propagation.

The following is a guide to which notebooks contain code for which experiments in the paper:
* `ObsPropCode.ipynb`:
  * Section 4.1: feature vector norms versus path patching scores; cosine similarities and coupling coefficients; code for getting feature scores from the Pile
  * Section 4.2: code for getting `n_bias` and `n_subj` feature scores
  * Appendix E: experiments regarding the effect of LayerNorm on feature vectors
  * Appendix G: experiments regarding the use of feature vectors for debiasing
* `BestFitScores.ipynb`:
  * Section 4.1: Code for calculating the best fit slope and r^2 between `n_subj` and `n_obj` feature vector scores
  * Section 4.2: Code for calculating best fit between `n_subj` and `n_bias` scores
  * Appendix I: Maximum activating examples
* `OtherObservables.ipynb`:
  * Section 4.3: Experiments involving other observables (political party, C vs. Python) and comparisons to other methods
