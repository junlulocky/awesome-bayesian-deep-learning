## [Perturbative Black Box Variational Inference](https://arxiv.org/abs/1709.07433)] 

The drawback of KL divergence is that: suppose the *q(w|.)* is the variational distribution and *p(w|.)* is the posterior distribution we want to use. The KL divergence will penalise *q(w)* for placing mass where *p(w|.)* has no or small mass and penalise less for not placing mass where *p(w|.)* has large mass [[See another note](/notes/alpha-divergence.md)]. The authors constructed a new variational bound which is tighter than the KL bound and **more mass covering**. Compared to alpha-divergences, its reparameterization gradients have a lower variance. In short, the authors chose a lower bound lies in the general version of evidence lower bound (ELBO) - f-ELBO, that is a biased estimator with smaller variance which induces careful bias-variance trade-off.

Note: it also contains a good review how ELBO can be derived from the marginal distribution of data.
