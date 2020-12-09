# Causal Reinforcement Learning
This repository serves as a resource compilation and note-taking avenue for my research in causal reinforcement learning (CRL).

## CRL Papers
* Rezende, Danilo J., et al. "Causally Correct Partial Models for Reinforcement Learning." ([2020](https://arxiv.org/abs/2002.02836v1))
  * Partial models, which are generative models whose predictions are only conditioned on initial agent internal state, partial views (functions of past observations and actions), and actions, are causally incorrect because the previous states are not included in the model. Proposed is to choose a partial view to be used as a backdoor adjustment variable to be modelled.
* Genewein, Tim, et al. "Algorithms for Causal Reasoning in Probability Trees." ([2020](https://arxiv.org/abs/2010.12237))
* Lee, Sanghack, and Elias Bareinboim. "Structural causal bandits: where to intervene?." ([2018](https://proceedings.neurips.cc/paper/2018/file/c0a271bc0ecb776a094786474322cb82-Paper.pdf))
* Bengio, Yoshua, et al. "A meta-transfer objective for learning to disentangle causal mechanisms." ([2019](https://arxiv.org/abs/1901.10912))
* Gershman, Samuel J. "Reinforcement learning and causal models." ([2015](http://gershmanlab.webfactional.com/pubs/RL_causal.pdf))
  * Reinforcement learning rely on a representation of state relevant for obtaining rewards that is often not the representation produced in early sensory processing. RL models must discover hidden states underlying observations, or latent structure learning, which can be modelled using latent cause models in partially observable domains.
* Zhu, Shengyu et al. "Causal Discovery with Reinforcement Learning." ([2020](https://arxiv.org/pdf/1906.04477.pdf))
* Gershman, Samuel J. et al. "Discovering latent causes in reinforcement learning." ([2015](http://compmemweb.princeton.edu/wp/wp-content/uploads/2016/11/discovering-latent-causes-in-reinforcement-learning.pdf))

# Causal Learning Papers
* Silva, Ricardo. "Motivation and Background." ([2014](http://www.homepages.ucl.ac.uk/~ucgtrbd/papers/causality.pdf)).
  * The learning task is to discover an equivalence class of graphs instead of a particular graph.
* Spirtes, Peter, et al. Causation, prediction, and search. MIT press, [2000](http://www.cs.cmu.edu/afs/cs.cmu.edu/project/learn-43/lib/photoz/.g/web/.g/scottd/fullbook.pdf).
* Schölkopf, Bernhard. "Causality for machine learning." arXiv preprint arXiv:1911.10500 (2019).
  * Causal modelling can lead to more invariant/robust models, applicable to transfer learning across different problems. Algorithmic information theory provides a natural framework for structural causal models because two conditionals are independent if knowing one does not help to achieve a shorter compression (Kolmogorov complexity) of the other.

## RL Papers
* Ha, David, and Jürgen Schmidhuber. "World models." ([2018](https://arxiv.org/abs/1803.10122)).
  * World models is a model-based reinforcement learning (MBRL) unsupervised pre-training method to compress spatial and temporal representations of the environment using a variational autoencoder (VAE) and mixture density network-recurrent neural network (MDN-RNN) respectively, and uses covariance matrix adaptation-evolutionary strategy (CMA-ES) to optimize the action-selector model, or "controller".

## Tutorials
* Causal Reinforcement Learning, [ICML2020](https://crl.causalai.net/)
  * Elias Barenboim introduces the motivation behind integrating causal inference with reinforcement learning (Part 1) and categories 6 tasks in CRL: Generalized Policy Learning, When and Where to Intervene, Counterfactual Decision-Making, Generalizability & Robustness of Causal Claims, Learning Causal Models and Causal Imitation Learning (Part 2).

## Books
* Causal Inference: What If ([Miguel Hernan, Jamie Robins](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/))
  * Chapters 19-21 address time-varying treatments, confounders, feedbacks and adjustments, generalising assumptions to their sequential counterparts, such as sequential exchangeability, and generalising adjustment methods to time-varying treatments.
* Sutton, Richard S., and Andrew G. Barto. Reinforcement learning: An introduction. MIT press, ([2018](http://www.incompleteideas.net/book/the-book-2nd.html)).
  * Reinforcement Learning Specialization on [Coursera](https://www.coursera.org/specializations/reinforcement-learning) by University of Alberta heavily references book chapters 1-8 with practical coding tutorials in Python.
* Pearl, Judea. Causality. Cambridge university press, ([2009](http://bayes.cs.ucla.edu/BOOK-2K/)).
  * Have not read but heard it is the "bible" (apologies for loose usage) of causal inference.

## Courses
* Introduction to Causal Inference ([Brady Neal](https://www.bradyneal.com/causal-inference-course))
  * In my opinion having watched to Week 7, he explains causal inference concepts with exceptional clarity. 
* Causal Inference, Columbia University on Coursera ([Michael E. Sobel](https://www.coursera.org/learn/causal-inference))
* A Crash Course in Causality: Inferring Causal Effects from Observational Data, University of Penssylvania on Coursera ([Jason A. Roy](https://www.coursera.org/learn/crash-course-in-causality))

Disclaimer: There may contain unintended misconceptions or misunderstanding of content. In such cases, I will be so grateful if you would raise an issue to ask a question or address any inaccuracies in this repository.
