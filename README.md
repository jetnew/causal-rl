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

## Causal Learning Papers
* Silva, Ricardo. "Motivation and Background." ([2014](http://www.homepages.ucl.ac.uk/~ucgtrbd/papers/causality.pdf)).
  * The learning task is to discover an equivalence class of graphs instead of a particular graph.
* Spirtes, Peter, et al. Causation, prediction, and search. MIT press, [2000](http://www.cs.cmu.edu/afs/cs.cmu.edu/project/learn-43/lib/photoz/.g/web/.g/scottd/fullbook.pdf).
* Schölkopf, Bernhard. "Causality for machine learning." arXiv preprint arXiv:1911.10500 (2019).
  * Causal modelling can lead to more invariant/robust models, applicable to transfer learning across different problems. Algorithmic information theory provides a natural framework for structural causal models because two conditionals are independent if knowing one does not help to achieve a shorter compression (Kolmogorov complexity) of the other.

## RL Papers
* Ha, David, and Jürgen Schmidhuber. "World models." ([2018](https://arxiv.org/abs/1803.10122)).
  * World models is a model-based reinforcement learning (MBRL) unsupervised pre-training method to compress spatial and temporal representations of the environment using a variational autoencoder (VAE) and mixture density network-recurrent neural network (MDN-RNN) respectively, and uses covariance matrix adaptation-evolutionary strategy (CMA-ES) to optimize the action-selector model, or "controller".
  
## NeurIPS 2020 Causal Papers
* Algorithmic recourse under imperfect causal knowledge: a probabilistic approach Amir-Hossein Karimi, Bodo Julius von Kügelgen, Bernhard Schölkopf, Isabel Valera
* A Causal View on Robustness of Neural Networks Cheng Zhang, Kun Zhang, Yingzhen Li
* Causal Intervention for Weakly-Supervised Semantic Segmentation Dong Zhang, Hanwang Zhang, Jinhui Tang, Xian-Sheng Hua, Qianru Sun
* Deep Structural Causal Models for Tractable Counterfactual Inference Nick Pawlowski, Daniel Coelho de Castro, Ben Glocker
* Asymmetric Shapley values: incorporating causal knowledge into model-agnostic explainability Christopher Frye, Colin Rowat, Ilya Feige
* Learning to search efficiently for causally near-optimal treatments Samuel Håkansson, Viktor Lindblom, Omer Gottesman, Fredrik D. Johansson
* A causal view of compositional zero-shot recognition Yuval Atzmon, Felix Kreuk, Uri Shalit, Gal Chechik
* CASTLE: Regularization via Auxiliary Causal Graph Discovery Trent Kyono, Yao Zhang, Mihaela van der Schaar
* Long-Tailed Classification by Keeping the Good and Removing the Bad Momentum Causal Effect Kaihua Tang, Jianqiang Huang, Hanwang Zhang
* Causal analysis of Covid-19 Spread in Germany Atalanti Mastakouri, Bernhard Schölkopf
* Causal Shapley Values: Exploiting Causal Knowledge to Explain Individual Predictions of Complex Models Tom Heskes, Evi Sijben, Ioan Gabriel Bucur, Tom Claassen
* Causal Estimation with Functional Confounders Aahlad Puli, Adler Perotte , Rajesh Ranganath
* Generative causal explanations of black-box classifiers Matthew O'Shaughnessy, Gregory Canal, Marissa Connor, Christopher Rozell, Mark Davenport
* Towards practical differentially private causal graph discovery Lun Wang, Qi Pang, Dawn Song
* Bayesian Causal Structural Learning with Zero-Inflated Poisson Bayesian Networks Junsouk Choi, Robert Chapkin, Yang Ni
* Multi-task Causal Learning with Gaussian Processes Virginia Aglietti, Theodoros Damoulas, Mauricio Álvarez, Javier Gonzalez
* Towards Scalable Bayesian Learning of Causal DAGs Jussi Viinikka, Antti Hyttinen, Johan Pensar, Mikko Koivisto
* General Control Functions for Causal Effect Estimation from IVs Aahlad Puli, Rajesh Ranganath
* COT-GAN: Generating Sequential Data via Causal Optimal Transport Tianlin Xu, Li Kevin Wenliang, Michael Munn, Beatrice Acciaio
* Causal Discovery in Physical Systems from Videos Yunzhu Li, Antonio Torralba, Anima Anandkumar, Dieter Fox, Animesh Garg
* Causal Discovery from Soft Interventions with Unknown Targets: Characterization and Learning Amin Jaber, Murat Kocaoglu, Karthikeyan Shanmugam, Elias Bareinboim
* A polynomial-time algorithm for learning nonparametric causal graphs Ming Gao, Yi Ding, Bryon Aragam
* Identifying Causal-Effect Inference Failure with Uncertainty-Aware Models Andrew Jesson, Sören Mindermann, Uri Shalit, Yarin Gal
* Causal Imitation Learning With Unobserved Confounders Junzhe Zhang, Daniel Kumor, Elias Bareinboim
* Investigating Gender Bias in Language Models Using Causal Mediation Analysis Jesse Vig, Sebastian Gehrmann, Yonatan Belinkov, Sharon Qian, Daniel Nevo, Yaron Singer, Stuart Shieber
* High-recall causal discovery for autocorrelated time series with latent confounders Andreas Gerhardus, Jakob Runge
* Learning Causal Effects via Weighted Empirical Risk Minimization Yonghan Jung, Jin Tian, Elias Bareinboim
* Entropic Causal Inference: Identifiability and Finite Sample Results Spencer Compton, Murat Kocaoglu, Kristjan Greenewald, Dmitriy Katz
* Generalized Independent Noise Condition for Estimating Latent Variable Causal Graphs Feng Xie, Ruichu Cai, Biwei Huang, Clark Glymour, Zhifeng Hao, Kun Zhang
* Active Invariant Causal Prediction: Experiment Selection through Stability Juan Gamella, Christina Heinze-Deml
* Applications of Common Entropy for Causal Inference Murat Kocaoglu, Sanjay Shakkottai, Alexandros G. Dimakis, Constantine Caramanis, Sriram Vishwanath
* Active Structure Learning of Causal DAGs via Directed Clique Trees Chandler Squires, Sara Magliacane, Kristjan Greenewald, Dmitriy Katz, Murat Kocaoglu, Karthikeyan Shanmugam
* Differentiable Causal Discovery from Interventional Data Philippe Brouillard, Sébastien Lachapelle, Alexandre Lacoste, Simon Lacoste-Julien, Alexandre Drouin

## NeurIPS 2020 Reinforcement Papers
* Reinforcement Learning with Combinatorial Actions: An Application to Vehicle Routing Arthur Delarue, Ross Anderson, Christian Tjandraatmadja
* Towards Playing Full MOBA Games with Deep Reinforcement Learning Deheng Ye, Guibin Chen, Wen Zhang, Sheng Chen, Bo Yuan, Bo Liu, Jia Chen, Zhao Liu, Fuhao Qiu, Hongsheng Yu, Yinyuting Yin, Bei Shi, Liang Wang, Tengfei Shi, Qiang Fu, Wei Yang, Lanxiao Huang, Wei Liu
* Stochastic Latent Actor-Critic: Deep Reinforcement Learning with a Latent Variable Model Alex Lee, Anusha Nagabandi, Pieter Abbeel, Sergey Levine
* Discovering Reinforcement Learning Algorithms Junhyuk Oh, Matteo Hessel, Wojciech M. Czarnecki, Zhongwen Xu, Hado P. van Hasselt, Satinder Singh, David Silver
* Conservative Q-Learning for Offline Reinforcement Learning Aviral Kumar, Aurick Zhou, George Tucker, Sergey Levine
* Provably Good Batch Off-Policy Reinforcement Learning Without Great Exploration Yao Liu, Adith Swaminathan, Alekh Agarwal, Emma Brunskill
* A Unifying View of Optimism in Episodic Reinforcement Learning Gergely Neu, Ciara Pike-Burke
* Learning to Dispatch for Job Shop Scheduling via Deep Reinforcement Learning Cong Zhang, Wen Song, Zhiguang Cao, Jie Zhang, Puay Siew Tan, Xu Chi
* Scalable Multi-Agent Reinforcement Learning for Networked Systems with Average Reward Guannan Qu, Yiheng Lin, Adam Wierman, Na Li
* Near-Optimal Reinforcement Learning with Self-Play Yu Bai, Chi Jin, Tiancheng Yu
* Inverse Reinforcement Learning from a Gradient-based Learner Giorgia Ramponi, Gianluca Drappo, Marcello Restelli
* Weakly-Supervised Reinforcement Learning for Controllable Behavior Lisa Lee, Ben Eysenbach, Russ R. Salakhutdinov, Shixiang (Shane) Gu, Chelsea Finn
* Reinforcement Learning for Control with Multiple Frequencies Jongmin Lee, ByungJun Lee, Kee-Eung Kim
* Deep Reinforcement and InfoMax Learning Bogdan Mazoure, Remi Tachet des Combes, Thang Long DOAN, Philip Bachman, R Devon Hjelm
* Adaptive Discretization for Model-Based Reinforcement Learning Sean Sinclair, Tianyu Wang, Gauri Jain, Siddhartha Banerjee, Christina Yu
* AttendLight: Universal Attention-Based Reinforcement Learning Model for Traffic Signal Control Afshin Oroojlooy, Mohammadreza Nazari, Davood Hajinezhad, Jorge Silva
* Efficient Exploration of Reward Functions in Inverse Reinforcement Learning via Bayesian Optimization Sreejith Balakrishnan, Quoc Phong Nguyen, Bryan Kian Hsiang Low, Harold Soh
* MDP Homomorphic Networks: Group Symmetries in Reinforcement Learning Elise van der Pol, Daniel Worrall, Herke van Hoof, Frans Oliehoek, Max Welling
* Munchausen Reinforcement Learning Nino Vieillard, Olivier Pietquin, Matthieu Geist
* Variational Policy Gradient Method for Reinforcement Learning with General Utilities Junyu Zhang, Alec Koppel, Amrit Singh Bedi, Csaba Szepesvari, Mengdi Wang
* Multi-Task Reinforcement Learning with Soft Modularization Ruihan Yang, Huazhe Xu, YI WU, Xiaolong Wang
* Independent Policy Gradient Methods for Competitive Reinforcement Learning Constantinos Daskalakis, Dylan J. Foster, Noah Golowich
* The Value Equivalence Principle for Model-Based Reinforcement Learning Christopher Grimm, Andre Barreto, Satinder Singh, David Silver
* Is Plug-in Solver Sample-Efficient for Feature-based Reinforcement Learning? Qiwen Cui, Lin Yang
* Reinforcement Learning with General Value Function Approximation: Provably Efficient Approach via Bounded Eluder Dimension Ruosong Wang, Russ R. Salakhutdinov, Lin Yang
* Neurosymbolic Reinforcement Learning with Formally Verified Exploration Greg Anderson, Abhinav Verma, Isil Dillig, Swarat Chaudhuri
* Multi-task Batch Reinforcement Learning with Metric Learning Jiachen Li, Quan Vuong, Shuang Liu, Minghua Liu, Kamil Ciosek, Henrik Christensen, Hao Su
* Task-Agnostic Online Reinforcement Learning with an Infinite Mixture of Gaussian Processes Mengdi Xu, Wenhao Ding, Jiacheng Zhu, ZUXIN LIU, Baiming Chen, Ding Zhao
* The LoCA Regret: A Consistent Metric to Evaluate Model-Based Behavior in Reinforcement Learning Harm Van Seijen, Hadi Nekoei, Evan Racah, Sarath Chandar
* On Efficiency in Hierarchical Reinforcement Learning Zheng Wen, Doina Precup, Morteza Ibrahimi, Andre Barreto, Benjamin Van Roy, Satinder Singh
* Implicit Distributional Reinforcement Learning Yuguang Yue, Zhendong Wang, Mingyuan Zhou
* RL Unplugged: A Collection of Benchmarks for Offline Reinforcement Learning Caglar Gulcehre, Ziyu Wang, Alexander Novikov, Thomas Paine, Sergio Gómez, Konrad Zolna, Rishabh Agarwal, Josh S. Merel, Daniel J. Mankowitz, Cosmin Paduraru, Gabriel Dulac-Arnold, Jerry Li, Mohammad Norouzi, Matthew Hoffman, Nicolas Heess, Nando de Freitas
* Generalized Hindsight for Reinforcement Learning Alexander Li, Lerrel Pinto, Pieter Abbeel
* Improving Generalization in Reinforcement Learning with Mixture Regularization KAIXIN WANG, Bingyi Kang, Jie Shao, Jiashi Feng
* Robust Reinforcement Learning via Adversarial training with Langevin Dynamics Parameswaran Kamalaruban, Yu-Ting Huang, Ya-Ping Hsieh, Paul Rolland, Cheng Shi, Volkan Cevher
* Security Analysis of Safe and Seldonian Reinforcement Learning Algorithms Pinar Ozisik, Philip S. Thomas
* Bridging Imagination and Reality for Model-Based Deep Reinforcement Learning Guangxiang Zhu, Minghao Zhang, Honglak Lee, Chongjie Zhang
* Self-Paced Deep Reinforcement Learning Pascal Klink, Carlo D'Eramo, Jan R. Peters, Joni Pajarinen
* Steady State Analysis of Episodic Reinforcement Learning Huang Bojun
* A Boolean Task Algebra for Reinforcement Learning Geraud Nangue Tasse, Steven James, Benjamin Rosman
* Provably adaptive reinforcement learning in metric spaces Tongyi Cao, Akshay Krishnamurthy
* A game-theoretic analysis of networked system control for common-pool resource management using multi-agent reinforcement learning Arnu Pretorius, Scott Cameron, Elan van Biljon, Thomas Makkink, Shahil Mawjee, Jeremy du Plessis, Jonathan Shock, Alexandre Laterre, Karim Beguir
* Model-based Adversarial Meta-Reinforcement Learning Zichuan Lin, Garrett Thomas, Guangwen Yang, Tengyu Ma
* Weighted QMIX: Expanding Monotonic Value Function Factorisation for Deep Multi-Agent Reinforcement Learning Tabish Rashid, Gregory Farquhar, Bei Peng, Shimon Whiteson
* Robust Multi-Agent Reinforcement Learning with Model Uncertainty Kaiqing Zhang, TAO SUN, Yunzhe Tao, Sahika Genc, Sunil Mallya, Tamer Basar
* Shared Experience Actor-Critic for Multi-Agent Reinforcement Learning Filippos Christianos, Lukas Schäfer, Stefano Albrecht
* Instance-based Generalization in Reinforcement Learning Martin Bertran, Natalia Martinez, Mariano Phielipp, Guillermo Sapiro
* Task-agnostic Exploration in Reinforcement Learning Xuezhou Zhang, Yuzhe Ma, Adish Singla
* Online Decision Based Visual Tracking via Reinforcement Learning ke Song, Wei Zhang, Ran Song, Yibin Li
* Learning Implicit Credit Assignment for Cooperative Multi-Agent Reinforcement Learning Meng Zhou, Ziyu Liu, Pengwei Sui, Yixuan Li, Yuk Ying Chung
* Sample Efficient Reinforcement Learning via Low-Rank Matrix Estimation Devavrat Shah, Dogyoon Song, Zhi Xu, Yuzhe Yang
* Safe Reinforcement Learning via Curriculum Induction Matteo Turchetta, Andrey Kolobov, Shital Shah, Andreas Krause, Alekh Agarwal
* Leverage the Average: an Analysis of KL Regularization in Reinforcement Learning Nino Vieillard, Tadashi Kozuno, Bruno Scherrer, Olivier Pietquin, Remi Munos, Matthieu Geist
* Breaking the Sample Size Barrier in Model-Based Reinforcement Learning with a Generative Model Gen Li, Yuting Wei, Yuejie Chi, Yuantao Gu, Yuxin Chen
* Trajectory-wise Multiple Choice Learning for Dynamics Generalization in Reinforcement Learning Younggyo Seo, Kimin Lee, Ignasi Clavera Gilaberte, Thanard Kurutach, Jinwoo Shin, Pieter Abbeel
* Interferobot: aligning an optical interferometer by a reinforcement learning agent Dmitry Sorokin, Alexander Ulanov, Ekaterina Sazhina, Alexander Lvovsky
* A Local Temporal Difference Code for Distributional Reinforcement Learning Pablo Tano, Peter Dayan, Alexandre Pouget
* Provably Efficient Reinforcement Learning with Kernel and Neural Function Approximations Zhuoran Yang, Chi Jin, Zhaoran Wang, Mengdi Wang, Michael Jordan
* Efficient Model-Based Reinforcement Learning through Optimistic Policy Search and Planning Sebastian Curi, Felix Berkenkamp, Andreas Krause
* Storage Efficient and Dynamic Flexible Runtime Channel Pruning via Deep Reinforcement Learning Jianda Chen, Shangyu Chen, Sinno Jialin Pan
* Knowledge Transfer in Multi-Task Deep Reinforcement Learning for Continuous Control Zhiyuan Xu, Kun Wu, Zhengping Che, Jian Tang, Jieping Ye
* Almost Optimal Model-Free Reinforcement Learningvia Reference-Advantage Decomposition Zihan Zhang, Yuan Zhou, Xiangyang Ji
* Meta-Gradient Reinforcement Learning with an Objective Discovered Online Zhongwen Xu, Hado P. van Hasselt, Matteo Hessel, Junhyuk Oh, Satinder Singh, David Silver
* Upper Confidence Primal-Dual Reinforcement Learning for CMDP with Adversarial Loss Shuang Qiu, Xiaohan Wei, Zhuoran Yang, Jieping Ye, Zhaoran Wang
* Promoting Coordination through Policy Regularization in Multi-Agent Deep Reinforcement Learning Julien Roy, Paul Barde, Félix Harvey, Derek Nowrouzezahrai, Chris Pal
* Non-Crossing Quantile Regression for Distributional Reinforcement Learning Fan Zhou, Jianing Wang, Xingdong Feng
* Constrained episodic reinforcement learning in concave-convex and knapsack settings Kianté Brantley, Miro Dudik, Thodoris Lykouris, Sobhan Miryoosefi, Max Simchowitz, Aleksandrs Slivkins, Wen Sun
* Deep Reinforcement Learning with Stacked Hierarchical Attention for Text-based Games Yunqiu Xu, Meng Fang, Ling Chen, Yali Du, Joey Tianyi Zhou, Chengqi Zhang
* Reinforcement Learning with Feedback Graphs Christoph Dann, Yishay Mansour, Mehryar Mohri, Ayush Sekhari, Karthik Sridharan
* Dynamic allocation of limited memory resources in reinforcement learning Nisheet Patel, Luigi Acerbi, Alexandre Pouget
* Combining Deep Reinforcement Learning and Search for Imperfect-Information Games Noam Brown, Anton Bakhtin, Adam Lerer, Qucheng Gong
* Cooperative Heterogeneous Deep Reinforcement Learning Han Zheng, Pengfei Wei, Jing Jiang, Guodong Long, Qinghua Lu, Chengqi Zhang
* On Reward-Free Reinforcement Learning with Linear Function Approximation Ruosong Wang, Simon S. Du, Lin Yang, Russ R. Salakhutdinov
* Effective Diversity in Population Based Reinforcement Learning Jack Parker-Holder, Aldo Pacchiano, Krzysztof M. Choromanski, Stephen J. Roberts
* Reinforcement Learning in Factored MDPs: Oracle-Efficient Algorithms and Tighter Regret Bounds for the Non-Episodic Setting Ziping Xu, Ambuj Tewari
* BAIL: Best-Action Imitation Learning for Batch Deep Reinforcement Learning Xinyue Chen, Zijian Zhou, Zheng Wang, Che Wang, Yanqiu Wu, Keith Ross
* Sample-Efficient Reinforcement Learning of Undercomplete POMDPs Chi Jin, Sham Kakade, Akshay Krishnamurthy, Qinghua Liu
* DisCor: Corrective Feedback in Reinforcement Learning via Distribution Correction Aviral Kumar, Abhishek Gupta, Sergey Levine
* Preference-based Reinforcement Learning with Finite-Time Guarantees Yichong Xu, Ruosong Wang, Lin Yang, Aarti Singh, Artur Dubrawski
* Expert-Supervised Reinforcement Learning for Offline Policy Learning and Evaluation Aaron Sonabend, Junwei Lu, Leo Anthony Celi, Tianxi Cai, Peter Szolovits
* Accelerating Reinforcement Learning through GPU Atari Emulation Steven Dalton, iuri frosio
* Model-based Reinforcement Learning for Semi-Markov Decision Processes with Neural ODEs Jianzhun Du, Joseph Futoma, Finale Doshi-Velez
* Reinforcement Learning with Augmented Data Misha Laskin, Kimin Lee, Adam Stooke, Lerrel Pinto, Pieter Abbeel, Aravind Srinivas
* Towards Minimax Optimal Reinforcement Learning in Factored Markov Decision Processes Yi Tian, Jian Qian, Suvrit Sra
* Learning Retrospective Knowledge with Reverse Reinforcement Learning Shangtong Zhang, Vivek Veeriah, Shimon Whiteson
* TorsionNet: A Reinforcement Learning Approach to Sequential Conformer Search Tarun Gogineni, Ziping Xu, Exequiel Punzalan, Runxuan Jiang, Joshua Kammeraad, Ambuj Tewari, Paul Zimmerman
* Information-theoretic Task Selection for Meta-Reinforcement Learning Ricardo Luna Gutierrez, Matteo Leonetti
* Robust Deep Reinforcement Learning against Adversarial Perturbations on State Observations Huan Zhang, Hongge Chen, Chaowei Xiao, Bo Li, mingyan liu, Duane Boning, Cho-Jui Hsieh
* POMO: Policy Optimization with Multiple Optima for Reinforcement Learning Yeong-Dae Kwon, Jinho Choo, Byoungjip Kim, Iljoo Yoon, Youngjune Gwon, Seungjai Min
* Generating Adjacency-Constrained Subgoals in Hierarchical Reinforcement Learning Tianren Zhang, Shangqi Guo, Tian Tan, Xiaolin Hu, Feng Chen
* MOReL: Model-Based Offline Reinforcement Learning Rahul Kidambi, Aravind Rajeswaran, Praneeth Netrapalli, Thorsten Joachims
* On the Stability and Convergence of Robust Adversarial Reinforcement Learning: A Case Study on Linear Quadratic Systems Kaiqing Zhang, Bin Hu, Tamer Basar
* Confounding-Robust Policy Evaluation in Infinite-Horizon Reinforcement Learning Nathan Kallus, Angela Zhou
* Risk-Sensitive Reinforcement Learning: Near-Optimal Risk-Sample Tradeoff in Regret Yingjie Fei, Zhuoran Yang, Yudong Chen, Zhaoran Wang, Qiaomin Xie
* Learning to Decode: Reinforcement Learning for Decoding of Sparse Graph-Based Channel Codes Salman Habib, Allison Beemer, Joerg Kliewer
* Provably Efficient Exploration for Reinforcement Learning Using Unsupervised Learning Fei Feng, Ruosong Wang, Wotao Yin, Simon S. Du, Lin Yang

## NeurIPS 2020 Planning Papers
* Planning in Markov Decision Processes with Gap-Dependent Sample Complexity Anders Jonsson, Emilie Kaufmann, Pierre Menard, Omar Darwiche Domingues, Edouard Leurent, Michal Valko
* Marginal Utility for Planning in Continuous or Large Discrete Action Spaces Zaheen Ahmad, Levi Lelis, Michael Bowling
* A Novel Automated Curriculum Strategy to Solve Hard Sokoban Planning Instances Dieqiao Feng, Carla P. Gomes, Bart Selman
* Influence-Augmented Online Planning for Complex Environments Jinke He, Miguel Suau de Castro, Frans Oliehoek
* POLY-HOOT: Monte-Carlo Planning in Continuous Space MDPs with Non-Asymptotic Analysis Weichao Mao, Kaiqing Zhang, Qiaomin Xie, Tamer Basar
* Sparse Graphical Memory for Robust Planning Scott Emmons, Ajay Jain, Misha Laskin, Thanard Kurutach, Pieter Abbeel, Deepak Pathak
* PlanGAN: Model-based Planning With Sparse Rewards and Multiple Goals Henry Charlesworth, Giovanni Montana
* Online Planning with Lookahead Policies Yonathan Efroni, Mohammad Ghavamzadeh, Shie Mannor
* Efficient Model-Based Reinforcement Learning through Optimistic Policy Search and Planning Sebastian Curi, Felix Berkenkamp, Andreas Krause
* Planning with General Objective Functions: Going Beyond Total Rewards Ruosong Wang, Peilin Zhong, Simon S. Du, Russ R. Salakhutdinov, Lin Yang
* Long-Horizon Visual Planning with Goal-Conditioned Hierarchical Predictors Karl Pertsch, Oleh Rybkin, Frederik Ebert, Shenghao Zhou, Dinesh Jayaraman, Chelsea Finn, Sergey Levine
* Efficient Planning in Large MDPs with Weak Linear Function Approximation Roshan Shariff, Csaba Szepesvari
* Online Bayesian Goal Inference for Boundedly Rational Planning Agents Tan Zhi-Xuan, Jordyn Mann, Tom Silver, Josh Tenenbaum, Vikash Mansinghka
* Evolving Graphical Planner: Contextual Global Planning for Vision-and-Language Navigation Zhiwei Deng, Karthik Narasimhan, Olga Russakovsky

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
