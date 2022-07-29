---
title: "About"
---

# About the workshop

Machine learning (ML) has established itself as the dominant and most successful paradigm for artificial intelligence (AI). A key strength of ML over earlier (symbolic, logic and rule-based) approaches to AI, is its ability to infer useful features or *representations* of often very high-dimensional observations in an automated, data-driven way. However, in doing so, it generally only leverages *statistical* information (e.g., correlations present in a training set) and consequently struggles at tasks such as knowledge transfer, systematic generalization, or planning, which are thought to require higher-order cognition.

Causal inference (CI), on the other hand, is concerned with going beyond the statistical level of description (“seeing”) and instead aims to reason about the effect of interventions or external manipulations to a system (“doing”) as well as about hypothetical counterfactual scenarios (“imagining”). Similar to classic approaches to AI, CI typically assumes that the causal variables of interest (i.e., an appropriate level of description of a given system) are given from the outset. However, real-world data often comprises high-dimensional, low-level observations and is thus usually not structured into such meaningful causal units. 

The emerging field of causal representation learning (CRL) aims to combine the strengths of ML and CI. Much like ML went beyond symbolic AI in not requiring that the symbols that algorithms manipulate be given a priori, in CRL low-dimensional, high-level variables *along with their causal relations* should be learned from raw, unstructured data, leading to representations that support notions such as intervention, reasoning, and planning. In this sense, CRL aligns with the general goal of modern ML to learn *meaningful* representations of data, where meaningful can also include *robust, explainable,* or *fair*.

One aim of this first workshop on CRL is to bring together researchers focusing mainly on either CI or representation learning, from both theoretical and applied perspectives. Moreover, the workshop aims at engaging the various communities interested in learning robust and transferable representations from different perspectives, in order to foster an exchange of ideas. Given that this is still a young, emerging line of research, another goal is to establish a common vocabulary and to identify useful frameworks for addressing CRL. 


## Selected References

The following is a non-exhaustive list of selected references related to the topics of the workshop, compiled before announcing the call for papers.

* Kosoy, E., Liu, A., Collins, J.L., Chan, D., Hamrick, J.B., Ke, N.R., Huang, S., Kaufmann, B., Canny, J. & Gopnik, A. Learning Causal Overhypotheses through Exploration in Children and Computational Models. Conference on Causal Learning and Reasoning, 2022.

* Ahuja, K., Hartford, J., & Bengio, Y. Properties from Mechanisms: An Equivariance Perspective on Identifiable Representation Learning. International Conference on Learning Representations, 2022.

* Lippe, P., Magliacane, S., Löwe, S., Asano, Y. M., Cohen, T., & Gavves, E. CITRIS: Causal Identifiability from Temporal Intervened Sequences. arXiv:2202.03169, 2022.

* Yao, W., Chen, G., & Zhang, K. Learning Latent Causal Dynamics. arXiv:2202.04828, 2022.

* Schölkopf, B., Locatello, F., Bauer, S., Ke, N. R., Kalchbrenner, N., Goyal, A., Bengio, Y. Toward Causal Representation Learning. Proceedings of the IEEE, 2021.

* Gresele, L., von Kügelgen, J., Stimper, V., Schölkopf, B., Besserve, M. Independent mechanisms analysis, a new concept? Advances in Neural Information Processing Systems 34, 2021.

* von Kügelgen, J., Sharma, Y., Gresele, L., Brendel, W., Schölkopf, B., Besserve, M., Locatello, F. Self-supervised learning with data augmentations provably isolates content from style. Advances in Neural Information Processing Systems 34, 2021.

* Wang, Y., & Jordan, M. I. Desiderata for representation learning: A causal perspective. arXiv preprint arXiv:2109.03795, 2021.

* Moran, G. E., Sridhar, D., Wang, Y., & Blei, D. M. Identifiable Variational Autoencoders via Sparse Decoding. arXiv preprint arXiv:2110.10804, 2021.

* Yang, M., Liu, F., Chen, Z., Shen, X., Hao, J., & Wang, J. CausalVAE: Disentangled representation learning via neural structural causal models.Computer Vision and Pattern Recognition, 2021.

* Didolkar, A., Goyal, A., Ke, N. R., Blundell, C., Beaudoin, P., Heess, N., Mozer, M. & Bengio, Y. Neural production systems. Advances in Neural Information Processing Systems 34, 2021.

* Ke, N.R., Didolkar, A.R., Mittal, S., Goyal, A., Lajoie, G., Bauer, S., Rezende, D.J., Bengio, Y., Pal, C. & Mozer, M.C. Systematic Evaluation of Causal Discovery in Visual Model Based Reinforcement Learning. Conference on Neural Information Processing Systems: Datasets and Benchmarks Track, 2021.

* Belyaeva, A., Cammarata, L., Radhakrishnan, A., Squires, C., Yang, K. D., Shivashankar, G. V., &  Uhler, C. Causal network models of SARS-CoV-2 expression and aging to identify candidates for drug repurposing. Nature Communications, 2021.

* Yang, K. D., Belyaeva, A., Venkatachalapathy, S., Damodaran, K., Katcoff, A., Radhakrishnan, A., Shivashankar, G. V. & Uhler, C. Multi-domain translation between single-cell imaging and sequencing data using autoencoders. Nature Communications, 2021.

* Rischel, E. F., & Weichwald, S. Compositional abstraction error and a category of causal models. Uncertainty in Artificial Intelligence, 2021.

* Wang, J.X., et al. Alchemy: A benchmark and analysis toolkit for meta-reinforcement learning agents. Conference on Neural Information Processing Systems: Datasets and Benchmarks Track, 2021.

* Geng, Y., Han, Z., Zhang, C., & Hu, Q. Uncertainty-Aware Multi-View Representation Learning. AAAI Conference on Artificial Intelligence, 2021.

* Besserve, M., Sun, R., Janzing, D., & Schölkopf, B. A Theory of Independent Mechanisms for Extrapolation in Generative Models. AAAI Conference on Artificial Intelligence, 2021.

* Kivva, B., Rajendran, G., Ravikumar, P., & Aragam, B. Learning latent causal graphs via mixture oracles. Advances in Neural Information Processing Systems 34, 2021.

* Adams, J., Hansen, N., & Zhang, K. Identification of partially observed linear causal models: Graphical conditions for the non-gaussian and heterogeneous cases. Advances in Neural Information Processing Systems 34, 2021.

* Keller, T., & Welling, M. Topographic VAEs learn equivariant capsules. Advances in Neural Information Processing Systems 34, 2021.

* Locatello, F., Weissenborn, D., Unterthiner, T., Mahendran, A., Heigold, G., Uszkoreit, J., Dosovitskiy, A. & Kipf, T. Object-centric learning with slot attention. Advances in Neural Information Processing Systems 33, 2020.

* Khemakhem, I., Monti, R., Kingma, D., & Hyvarinen, A. ICE-BeeM: Identifiable conditional energy-based deep models based on nonlinear ICA. Advances in Neural Information Processing Systems 33, 2020.

* Khemakhem, I., Kingma, D., Monti, R., & Hyvarinen, A. Variational autoencoders and nonlinear ICA: A unifying framework. International Conference on Artificial Intelligence and Statistics, 2020.

* Locatello, F., Poole, B., Rätsch, G., Schölkopf, B., Bachem, O., & Tschannen, M. Weakly-supervised disentanglement without compromises. International Conference on Machine Learning, 2020.

* Gresele, L., Rubenstein, P. K., Mehrjou, A., Locatello, F., & Schölkopf, B. The Incomplete Rosetta Stone problem: Identifiability results for multi-view nonlinear ICA. Uncertainty in Artificial Intelligence, 2020.

* Mitrovic, J., McWilliams, B., Walker, J. C., Buesing, L. H., & Blundell, C. Representation Learning via Invariant Causal Mechanisms. International Conference on Learning Representations, 2020.

* Goyal, A., Lamb, A., Hoffmann, J., Sodhani, S., Levine, S., Bengio, Y., & Schölkopf, B. Recurrent Independent Mechanisms. International Conference on Learning Representations, 2020.

* Beckers, S., Eberhardt, F., & Halpern, J. Y. Approximate causal abstractions. Uncertainty in Artificial Intelligence, 2020.

* Ke, N. R., Wang, J., Mitrovic, J., Szummer, M., & Rezende, D. J. Amortized learning of neural causal representations. arXiv preprint arXiv:2008.09301, 2020.

* Wu, M., & Goodman, N. A simple framework for uncertainty in contrastive learning. arXiv:2010.02038, 2020.

* Besserve, M. Merhjou, A., Sun, R., & Schölkopf, B. Counterfactuals uncover the modular structure of deep generative models. International Conference on Learning Representations, 2020.

* Xie, F., Cai, R., Huang, B., Glymour, C., Hao, Z., & Zhang, K. Generalized independent noise condition for estimating latent variable causal graphs. Advances in Neural Information Processing Systems 33, 2020.

* Bengio, Y., Deleu, T., Rahaman, N., Ke, N. R., Lachapelle, S., Bilaniuk, O., Goyal, A. & Pal, C. A Meta-Transfer Objective for Learning to Disentangle Causal Mechanisms. International Conference on Learning Representations, 2019.

* Kipf, T., van der Pol, E., & Welling, M. Contrastive Learning of Structured World Models. International Conference on Learning Representations, 2019.

* Beckers, S., & Halpern, J. Y. Abstracting causal models. AAAI Conference on Artificial Intelligence, 2019.

* Besserve, M., Shajarisales, N., Schölkopf, B. & Janzing, D. Group Invariance Principles for Causal Generative Models. International Conference on Artificial Intelligence and Statistics, 2018.

* Rubenstein, P., Weichwald, S., Bongers, S., Mooij, J., Janzing, D., Grosse-Wentrup, M., & Schölkopf, B. Causal Consistency of Structural Equation Models. Uncertainty in Artificial Intelligence, 2017.

* Chalupka, K., Eberhardt, F., & Perona, P. Multi-level cause-effect systems. International Conference on Artificial Intelligence and Statistics, 2016.

* Eberhardt, F. Green and grue causal variables. Synthese, 2016.

* Chalupka, K., Perona, P., & Eberhardt, F. Visual causal feature learning. Uncertainty in Artificial Intelligence, 2015.
