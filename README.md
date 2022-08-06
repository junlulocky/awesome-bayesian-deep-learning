# bayesian-deep-learning-notes
> One-phrase-summary for Bayesian deep learning papers.
> We here organize these papers in the following categories. But some of them might have overlap.

## (1). Uncertainty in deep learning
> Model uncertainty in deep learning via Bayesian modelling by variational inference etc.

- [1705]. Concrete Dropout - [[arxiv](https://arxiv.org/abs/1705.07832)] [[Note](/notes/concrete-dropout.md)]
- [1703]. Dropout Inference in Bayesian Neural Networks with Alpha-divergences - [[arxiv](https://arxiv.org/abs/1703.02914)] [[Note](/notes/alpha-divergence.md)]
- [1703]. What Uncertainties Do We Need in Bayesian Deep Learning for Computer Vision? - [[arxiv](https://arxiv.org/abs/1703.04977)] [[Note](/notes/)]
- [2016]. Uncertainty in Deep Learning - [[PDF](https://pdfs.semanticscholar.org/a6af/62389c6655770c624e2fa3f3ad6dc26bf77e.pdf)] [[Blog](http://mlg.eng.cam.ac.uk/yarin/blog_2248.html)] [[Note](/notes/uncertainty-deep-learning.md)]
- [1505]. Weight Uncertainty in Neural Networks - [[arxiv](https://arxiv.org/abs/1505.05424)] [[Note](/notes/bbb.md)]
- [2015]. On Modern Deep Learning and Variational Inference - [[NIPS](http://www.approximateinference.org/accepted/GalGhahramani2015.pdf)] [[Note](/notes/modern-vi.md)]
- [1995]. Bayesian learning for neural networks - [[PDF](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.446.9306&rep=rep1&type=pdf)]

## (2). Probabilistic deep models
> Use probabilistic model to imitate deep neural networks.

- [1711]. Deep Gaussian Mixture Models - [[arxiv](https://arxiv.org/abs/1711.06929)]
- [1411]. Deep Exponential Families - [[arxiv](https://arxiv.org/pdf/1411.2581.pdf)] [[Note](/notes/deep-expo-families.md)]

## (3). Probabilistic neural networks
> Use probabilistic methods to do the inference in neural networks.

- [1611]. Natural-Parameter Networks: A Class of Probabilistic Neural Networks - [[arxiv](https://arxiv.org/abs/1611.00448)] [[Note](/notes/npn.md)]

## (4). Approximate inference
> Approximate inference or variational inference mostly is the building block for Bayesian deep learning. 
> Variational inference: the main idea behind variational inference is to pick a family of distributions over the latent variables with its own parameters which is called *variational parameters*.

### (4.1) General
- [1712]. Vprop: Variational Inference using RMSprop - [[arxiv](https://arxiv.org/abs/1712.01038)] [[Note](/notes/vprop.md)]
- [1709]. Perturbative Black Box Variational Inference - [[arxiv](https://arxiv.org/abs/1709.07433)] [[Note](/notes/perturbative-vi.md)]
- [1703]. Conjugate-Computation Variational Inference : Converting Variational Inference in Non-Conjugate Models to Inferences in Conjugate Models - [[arxiv](https://arxiv.org/abs/1703.04265)] [[Note](/notes/cvi.md)]
- [1611]. Variational Inference via χ-Upper Bound Minimization - [[arxiv](https://arxiv.org/abs/1611.00328)]
- [1601]. Variational Inference: A Review for Statisticians - [[arxiv](https://arxiv.org/abs/1601.00670)]
- [1401]. Black Box Variational Inference - [[arxiv](https://arxiv.org/abs/1401.0118)] [[Note](/notes/blackbox-vi.md)]
- [2014]. Smoothed Gradients for Stochastic Variational Inference - [[NIPS](http://papers.nips.cc/paper/5557-smoothed-gradients-for-stochastic-variational-inference.pdf)] [[Note](/notes/smooth-svi.md)]
- [1206]. Stochastic Variational Inference - [[arxiv](https://arxiv.org/abs/1206.7051)] [[Note](/notes/svi.md)]
- [2011]. Practical Variational Inference for Neural Networks - [[NIPS](https://papers.nips.cc/paper/4329-practical-variational-inference-for-neural-networks)]
- [1999]. An Introduction to Variational Methods for Graphical Models - [[PDF](https://people.eecs.berkeley.edu/~jordan/papers/variational-intro.pdf)]

### (4.2) Reparametrization trick in variational inference
- [1506]. Variational Dropout and the Local Reparameterization Trick - [[arxiv](https://arxiv.org/abs/1506.02557)]
- [1401]. Stochastic Backpropagation and Approximate Inference in Deep Generative Models - [[arxiv](https://arxiv.org/abs/1401.4082)]
- [1312]. Auto-Encoding Variational Bayes - [[arxiv](https://arxiv.org/abs/1312.6114)] [[Note](/notes/aevb.md)]

### (4.3) Others
- [NA]. [A roadmap to research on EP](https://tminka.github.io/papers/ep/roadmap.html)
- [1608]. Stein Variational Gradient Descent: A General Purpose Bayesian Inference Algorithm - [[arxiv](https://arxiv.org/abs/1608.04471)] [[Note](/notes/stein-var.md)]

## (5) Continuous relaxation
> Use continuous distribution to approximate discrete random variables, e.g. concrete distribution is a continuous distribution used to approximate discrete random variables.

- [1611]. The Concrete Distribution: A Continuous Relaxation of Discrete Random Variables - [[arxiv](https://arxiv.org/abs/1611.00712)]
- [1611]. Categorical Reparameterization with Gumbel-Softmax - [[arxiv](https://arxiv.org/abs/1611.01144)]

## (6) Bayesian neural network pruning
> Sparse prior can be used to induce sparse weight or neuron in neural networks, thus favor smaller network structure for mobile devices etc. 

- [1711]. Interpreting Convolutional Neural Networks Through Compression - [[arXiv](https://arxiv.org/abs/1711.02329)] [[Note](/notes/interpret-cnn-compress.md)]
- [1705]. Structural compression of convolutional neural networks based on greedy filter pruning - [[arXiv](https://arxiv.org/abs/1705.07356)] [[Note](/notes/interpret-cnn-compress.md)]
- [1705]. Structured Bayesian Pruning via Log-Normal Multiplicative Noise - [[arxiv](https://arxiv.org/abs/1705.07283)]
- [1705]. Bayesian Compression for Deep Learning - [[arxiv](https://arxiv.org/abs/1705.08665)] [[Note](/notes/bayesian-compress.md)]
- [1701]. Variational Dropout Sparsifies Deep Neural Networks - [[arxiv](https://arxiv.org/abs/1701.05369)]


## Contribution
Any contribution is welcome. But notice that we need '*one phrase summary*' to give an overview guidance to the readers RATHER THAN a list of papers. And please add yourself into the contributor list!

## Contributors
- [Jun Lu](https://github.com/junlulocky)
- [Christine Chai](https://github.com/star1327p)
