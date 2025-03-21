<div class="github-widget" data-repo="n2cholas/awesome-jax"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!--lint ignore double-link-->

<!--lint ignore double-link-->
[JAX](https://github.com/google/jax) brings automatic differentiation and the [XLA compiler](https://www.tensorflow.org/xla) together through a [NumPy](https://numpy.org/)-like API for high performance machine learning research on accelerators like GPUs and TPUs.
<!--lint enable double-link-->

This is a curated list of awesome JAX libraries, projects, and other resources. Contributions are welcome!



<a name="libraries" />

## Libraries

- Neural Network Libraries
    - [Flax](https://raw.githubusercontent.com/google/flax) - Centered on flexibility and clarity. <img src="https://img.shields.io/github/stars/google/flax?style=social" align="center">
    - [Haiku](https://raw.githubusercontent.com/deepmind/dm-haiku) - Focused on simplicity, created by the authors of Sonnet at DeepMind. <img src="https://img.shields.io/github/stars/deepmind/dm-haiku?style=social" align="center">
    - [Objax](https://raw.githubusercontent.com/google/objax) - Has an object oriented design similar to PyTorch. <img src="https://img.shields.io/github/stars/google/objax?style=social" align="center">
    - [Elegy](https://poets-ai.github.io/elegy/) - A framework-agnostic Trainer interface for the Jax ecosystem. Supports Flax, Haiku, and Optax. <img src="https://img.shields.io/github/stars/poets-ai/elegy?style=social" align="center">
    - [Trax](https://raw.githubusercontent.com/google/trax) - "Batteries included" deep learning library focused on providing solutions for common workloads. <img src="https://img.shields.io/github/stars/google/trax?style=social" align="center">
    - [Jraph](https://raw.githubusercontent.com/deepmind/jraph) - Lightweight graph neural network library. <img src="https://img.shields.io/github/stars/deepmind/jraph?style=social" align="center">
    - [Neural Tangents](https://raw.githubusercontent.com/google/neural-tangents) - High-level API for specifying neural networks of both finite and _infinite_ width. <img src="https://img.shields.io/github/stars/google/neural-tangents?style=social" align="center">
    - [HuggingFace](https://raw.githubusercontent.com/huggingface/transformers) - Ecosystem of pretrained Transformers for a wide range of natural language tasks (Flax). <img src="https://img.shields.io/github/stars/huggingface/transformers?style=social" align="center">
    - [Equinox](https://raw.githubusercontent.com/patrick-kidger/equinox) - Callable PyTrees and filtered JIT/grad transformations => neural networks in JAX. <img src="https://img.shields.io/github/stars/patrick-kidger/equinox?style=social" align="center">
- [NumPyro](https://raw.githubusercontent.com/pyro-ppl/numpyro) - Probabilistic programming based on the Pyro library. <img src="https://img.shields.io/github/stars/pyro-ppl/numpyro?style=social" align="center">
- [Chex](https://raw.githubusercontent.com/deepmind/chex) - Utilities to write and test reliable JAX code. <img src="https://img.shields.io/github/stars/deepmind/chex?style=social" align="center">
- [Optax](https://raw.githubusercontent.com/deepmind/optax) - Gradient processing and optimization library. <img src="https://img.shields.io/github/stars/deepmind/optax?style=social" align="center">
- [RLax](https://raw.githubusercontent.com/deepmind/rlax) - Library for implementing reinforcement learning agents. <img src="https://img.shields.io/github/stars/deepmind/rlax?style=social" align="center">
- [JAX, M.D.](https://raw.githubusercontent.com/google/jax-md) - Accelerated, differential molecular dynamics. <img src="https://img.shields.io/github/stars/google/jax-md?style=social" align="center">
- [Coax](https://raw.githubusercontent.com/coax-dev/coax) - Turn RL papers into code, the easy way. <img src="https://img.shields.io/github/stars/coax-dev/coax?style=social" align="center">
- [SymJAX](https://raw.githubusercontent.com/SymJAX/SymJAX) - Symbolic CPU/GPU/TPU programming. <img src="https://img.shields.io/github/stars/SymJAX/SymJAX?style=social" align="center">
- [mcx](https://raw.githubusercontent.com/rlouf/mcx) - Express & compile probabilistic programs for performant inference. <img src="https://img.shields.io/github/stars/rlouf/mcx?style=social" align="center">
- [Distrax](https://raw.githubusercontent.com/deepmind/distrax) - Reimplementation of TensorFlow Probability, containing probability distributions and bijectors. <img src="https://img.shields.io/github/stars/deepmind/distrax?style=social" align="center">
- [cvxpylayers](https://raw.githubusercontent.com/cvxgrp/cvxpylayers) - Construct differentiable convex optimization layers. <img src="https://img.shields.io/github/stars/cvxgrp/cvxpylayers?style=social" align="center">
- [TensorLy](https://raw.githubusercontent.com/tensorly/tensorly) - Tensor learning made simple. <img src="https://img.shields.io/github/stars/tensorly/tensorly?style=social" align="center">
- [NetKet](https://raw.githubusercontent.com/netket/netket) - Machine Learning toolbox for Quantum Physics. <img src="https://img.shields.io/github/stars/netket/netket?style=social" align="center">

<a name="new-libraries" />

### New Libraries

This section contains libraries that are well-made and useful, but have not necessarily been battle-tested by a large userbase yet.

- Neural Network Libraries
    - [FedJAX](https://raw.githubusercontent.com/google/fedjax) - Federated learning in JAX, built on Optax and Haiku. <img src="https://img.shields.io/github/stars/google/fedjax?style=social" align="center">
    - [Equivariant MLP](https://raw.githubusercontent.com/mfinzi/equivariant-MLP) - Construct equivariant neural network layers. <img src="https://img.shields.io/github/stars/mfinzi/equivariant-MLP?style=social" align="center">
    - [jax-resnet](https://raw.githubusercontent.com/n2cholas/jax-resnet/) - Implementations and checkpoints for ResNet variants in Flax. <img src="https://img.shields.io/github/stars/n2cholas/jax-resnet?style=social" align="center">
- [jax-unirep](https://raw.githubusercontent.com/ElArkk/jax-unirep) - Library implementing the [UniRep model](https://www.nature.com/articles/s41592-019-0598-1) for protein machine learning applications. <img src="https://img.shields.io/github/stars/ElArkk/jax-unirep?style=social" align="center">
- [jax-flows](https://raw.githubusercontent.com/ChrisWaites/jax-flows) - Normalizing flows in JAX. <img src="https://img.shields.io/github/stars/ChrisWaites/jax-flows?style=social" align="center">
- [sklearn-jax-kernels](https://raw.githubusercontent.com/ExpectationMax/sklearn-jax-kernels) - `scikit-learn` kernel matrices using JAX. <img src="https://img.shields.io/github/stars/ExpectationMax/sklearn-jax-kernels?style=social" align="center">
- [jax-cosmo](https://raw.githubusercontent.com/DifferentiableUniverseInitiative/jax_cosmo) - Differentiable cosmology library. <img src="https://img.shields.io/github/stars/DifferentiableUniverseInitiative/jax_cosmo?style=social" align="center">
- [efax](https://raw.githubusercontent.com/NeilGirdhar/efax) - Exponential Families in JAX. <img src="https://img.shields.io/github/stars/NeilGirdhar/efax?style=social" align="center">
- [mpi4jax](https://raw.githubusercontent.com/PhilipVinc/mpi4jax) - Combine MPI operations with your Jax code on CPUs and GPUs. <img src="https://img.shields.io/github/stars/PhilipVinc/mpi4jax?style=social" align="center">
- [imax](https://raw.githubusercontent.com/4rtemi5/imax) - Image augmentations and transformations. <img src="https://img.shields.io/github/stars/4rtemi5/imax?style=social" align="center">
- [FlaxVision](https://raw.githubusercontent.com/rolandgvc/flaxvision) - Flax version of TorchVision. <img src="https://img.shields.io/github/stars/rolandgvc/flaxvision?style=social" align="center">
- [Oryx](https://github.com/tensorflow/probability/tree/master/spinoffs/oryx) - Probabilistic programming language based on program transformations.
- [Optimal Transport Tools](https://github.com/google-research/ott) - Toolbox that bundles utilities to solve optimal transport problems.
- [delta PV](https://raw.githubusercontent.com/romanodev/deltapv) - A photovoltaic simulator with automatic differentation. <img src="https://img.shields.io/github/stars/romanodev/deltapv?style=social" align="center">
- [jaxlie](https://raw.githubusercontent.com/brentyi/jaxlie) - Lie theory library for rigid body transformations and optimization. <img src="https://img.shields.io/github/stars/brentyi/jaxlie?style=social" align="center">
- [BRAX](https://raw.githubusercontent.com/google/brax) - Differentiable physics engine to simulate environments along with learning algorithms to train agents for these environments. <img src="https://img.shields.io/github/stars/google/brax?style=social" align="center">
- [flaxmodels](https://raw.githubusercontent.com/matthias-wright/flaxmodels) - Pretrained models for Jax/Flax. <img src="https://img.shields.io/github/stars/matthias-wright/flaxmodels?style=social" align="center">
- [CR.Sparse](https://raw.githubusercontent.com/carnotresearch/cr-sparse) - XLA accelerated algorithms for sparse representations and compressive sensing. <img src="https://img.shields.io/github/stars/carnotresearch/cr-sparse?style=social" align="center">
- [exojax](https://raw.githubusercontent.com/HajimeKawahara/exojax) - Automatic differentiable spectrum modeling of exoplanets/brown dwarfs compatible to JAX. <img src="https://img.shields.io/github/stars/HajimeKawahara/exojax?style=social" align="center">
- [JAXopt](https://raw.githubusercontent.com/google/jaxopt) - Hardware accelerated (GPU/TPU), batchable and differentiable optimizers in JAX. <img src="https://img.shields.io/github/stars/google/jaxopt?style=social" align="center">
- [PIX](https://raw.githubusercontent.com/deepmind/dm_pix) - PIX is an image processing library in JAX, for JAX. <img src="https://img.shields.io/github/stars/deepmind/dm_pix?style=social" align="center">

<a name="models-and-projects" />

## Models and Projects

### JAX

- [Fourier Feature Networks](https://github.com/tancik/fourier-feature-networks) - Official implementation of [_Fourier Features Let Networks Learn High Frequency Functions in Low Dimensional Domains_](https://people.eecs.berkeley.edu/~bmild/fourfeat).
- [kalman-jax](https://github.com/AaltoML/kalman-jax) - Approximate inference for Markov (i.e., temporal) Gaussian processes using iterated Kalman filtering and smoothing.
- [GPJax](https://github.com/thomaspinder/GPJax) - Gaussian processes in JAX.
- [jaxns](https://github.com/Joshuaalbert/jaxns) - Nested sampling in JAX.
- [Amortized Bayesian Optimization](https://github.com/google-research/google-research/tree/master/amortized_bo) - Code related to [_Amortized Bayesian Optimization over Discrete Spaces_](http://www.auai.org/uai2020/proceedings/329_main_paper.pdf).
- [Accurate Quantized Training](https://github.com/google-research/google-research/tree/master/aqt) - Tools and libraries for running and analyzing neural network quantization experiments in JAX and Flax.
- [BNN-HMC](https://github.com/google-research/google-research/tree/master/bnn_hmc) - Implementation for the paper [_What Are Bayesian Neural Network Posteriors Really Like?_](https://arxiv.org/abs/2104.14421).
- [JAX-DFT](https://github.com/google-research/google-research/tree/master/jax_dft) - One-dimensional density functional theory (DFT) in JAX, with implementation of [_Kohn-Sham equations as regularizer: building prior knowledge into machine-learned physics_](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.126.036401).
- [Robust Loss](https://github.com/google-research/google-research/tree/master/robust_loss_jax) - Reference code for the paper [_A General and Adaptive Robust Loss Function_](https://arxiv.org/abs/1701.03077).

### Flax

- [Performer](https://github.com/google-research/google-research/tree/master/performer/fast_attention/jax) - Flax implementation of the Performer (linear transformer via FAVOR+) architecture.
- [JaxNeRF](https://github.com/google-research/google-research/tree/master/jaxnerf) - Implementation of [_NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis_](http://www.matthewtancik.com/nerf) with multi-device GPU/TPU support.
- [Big Transfer (BiT)](https://github.com/google-research/big_transfer) - Implementation of [_Big Transfer (BiT): General Visual Representation Learning_](https://arxiv.org/abs/1912.11370).
- [JAX RL](https://github.com/ikostrikov/jax-rl) - Implementations of reinforcement learning algorithms.
- [gMLP](https://github.com/SauravMaheshkar/gMLP) - Implementation of [_Pay Attention to MLPs_](https://arxiv.org/abs/2105.08050).
- [MLP Mixer](https://github.com/SauravMaheshkar/MLP-Mixer) - Minimal implementation of [_MLP-Mixer: An all-MLP Architecture for Vision_](https://arxiv.org/abs/2105.01601).
- [Distributed Shampoo](https://github.com/google-research/google-research/tree/master/scalable_shampoo) - Implementation of [_Second Order Optimization Made Practical_](https://arxiv.org/abs/2002.09018).
- [NesT](https://github.com/google-research/nested-transformer) - Official implementation of [_Aggregating Nested Transformers_](https://arxiv.org/abs/2105.12723).
- [XMC-GAN](https://github.com/google-research/xmcgan_image_generation) - Official implementation of [_Cross-Modal Contrastive Learning for Text-to-Image Generation_](https://arxiv.org/abs/2101.04702).
- [FNet](https://github.com/google-research/google-research/tree/master/f_net) - Official implementation of [_FNet: Mixing Tokens with Fourier Transforms_](https://arxiv.org/abs/2105.03824).
- [GFSA](https://github.com/google-research/google-research/tree/master/gfsa) - Official implementation of [_Learning Graph Structure With A Finite-State Automaton Layer_](https://arxiv.org/abs/2007.04929).
- [IPA-GNN](https://github.com/google-research/google-research/tree/master/ipagnn) - Official implementation of [_Learning to Execute Programs with Instruction Pointer Attention Graph Neural Networks_](https://arxiv.org/abs/2010.12621).
- [Flax Models](https://github.com/google-research/google-research/tree/master/flax_models) - Collection of models and methods implemented in Flax.
- [Protein LM](https://github.com/google-research/google-research/tree/master/protein_lm) - Implements BERT and autoregressive models for proteins, as described in [_Biological Structure and Function Emerge from Scaling Unsupervised Learning to 250 Million Protein Sequences_](https://www.biorxiv.org/content/10.1101/622803v1.full) and [_ProGen: Language Modeling for Protein Generation_](https://www.biorxiv.org/content/10.1101/2020.03.07.982272v2).
- [Slot Attention](https://github.com/google-research/google-research/tree/master/ptopk_patch_selection) - Reference implementation for [_Differentiable Patch Selection for Image Recognition_](https://arxiv.org/abs/2104.03059).
- [Vision Transformer](https://github.com/google-research/vision_transformer) - Official implementation of [_An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale_](https://arxiv.org/abs/2010.11929).
- [FID computation](https://github.com/matthias-wright/jax-fid) - Port of [mseitzer/pytorch-fid](https://github.com/mseitzer/pytorch-fid) to Flax.

### Haiku

- [AlphaFold](https://github.com/deepmind/alphafold) - Implementation of the inference pipeline of AlphaFold v2.0, presented in [_Highly accurate protein structure prediction with AlphaFold_](https://www.nature.com/articles/s41586-021-03819-2).
- [Adversarial Robustness](https://github.com/deepmind/deepmind-research/tree/master/adversarial_robustness) - Reference code for [_Uncovering the Limits of Adversarial Training against Norm-Bounded Adversarial Examples_](https://arxiv.org/abs/2010.03593) and [_Fixing Data Augmentation to Improve Adversarial Robustness_](https://arxiv.org/abs/2103.01946).
- [Bootstrap Your Own Latent](https://github.com/deepmind/deepmind-research/tree/master/byol) - Implementation for the paper [_Bootstrap your own latent: A new approach to self-supervised Learning_](https://arxiv.org/abs/2006.07733).
- [Gated Linear Networks](https://github.com/deepmind/deepmind-research/tree/master/gated_linear_networks) - GLNs are a family of backpropagation-free neural networks.
- [Glassy Dynamics](https://github.com/deepmind/deepmind-research/tree/master/glassy_dynamics) - Open source implementation of the paper [_Unveiling the predictive power of static structure in glassy systems_](https://www.nature.com/articles/s41567-020-0842-8).
- [MMV](https://github.com/deepmind/deepmind-research/tree/master/mmv) - Code for the models in [_Self-Supervised MultiModal Versatile Networks_](https://arxiv.org/abs/2006.16228).
- [Normalizer-Free Networks](https://github.com/deepmind/deepmind-research/tree/master/nfnets) - Official Haiku implementation of [_NFNets_](https://arxiv.org/abs/2102.06171).
- [NuX](https://github.com/Information-Fusion-Lab-Umass/NuX) - Normalizing flows with JAX.
- [OGB-LSC](https://github.com/deepmind/deepmind-research/tree/master/ogb_lsc) - This repository contains DeepMind's entry to the [PCQM4M-LSC](https://ogb.stanford.edu/kddcup2021/pcqm4m/) (quantum chemistry) and [MAG240M-LSC](https://ogb.stanford.edu/kddcup2021/mag240m/) (academic graph)
tracks of the [OGB Large-Scale Challenge](https://ogb.stanford.edu/kddcup2021/) (OGB-LSC).
- [Persistent Evolution Strategies](https://github.com/google-research/google-research/tree/master/persistent_es) - Code used for the paper [_Unbiased Gradient Estimation in Unrolled Computation Graphs with Persistent Evolution Strategies_](http://proceedings.mlr.press/v139/vicol21a.html).
- [WikiGraphs](https://github.com/deepmind/deepmind-research/tree/master/wikigraphs) - Baseline code to reproduce results in [_WikiGraphs: A Wikipedia Text - Knowledge Graph Paired Datase_](https://aclanthology.org/2021.textgraphs-1.7).

### Trax

- [Reformer](https://github.com/google/trax/tree/master/trax/models/reformer) - Implementation of the Reformer (efficient transformer) architecture.


<a name="videos" />

## Videos

- [NeurIPS 2020: JAX Ecosystem Meetup](https://www.youtube.com/watch?v=iDxJxIyzSiM) - JAX, its use at DeepMind, and discussion between engineers, scientists, and JAX core team.
- [Introduction to JAX](https://youtu.be/0mVmRHMaOJ4) - Simple neural network from scratch in JAX.
- [JAX: Accelerated Machine Learning Research | SciPy 2020 | VanderPlas](https://youtu.be/z-WSrQDXkuM) - JAX's core design, how it's powering new research, and how you can start using it.
- [Bayesian Programming with JAX + NumPyro — Andy Kitchen](https://youtu.be/CecuWGpoztw) - Introduction to Bayesian modelling using NumPyro.
- [JAX: Accelerated machine-learning research via composable function transformations in Python | NeurIPS 2019 | Skye Wanderman-Milne](https://slideslive.com/38923687/jax-accelerated-machinelearning-research-via-composable-function-transformations-in-python) - JAX intro presentation in [_Program Transformations for Machine Learning_](https://program-transformations.github.io) workshop.
- [JAX on Cloud TPUs | NeurIPS 2020 | Skye Wanderman-Milne and James Bradbury](https://drive.google.com/file/d/1jKxefZT1xJDUxMman6qrQVed7vWI0MIn/edit) - Presentation of TPU host access with demo.
- [Deep Implicit Layers - Neural ODEs, Deep Equilibirum Models, and Beyond | NeurIPS 2020](https://slideslive.com/38935810/deep-implicit-layers-neural-odes-equilibrium-models-and-beyond) - Tutorial created by Zico Kolter, David Duvenaud, and Matt Johnson with Colab notebooks avaliable in [_Deep Implicit Layers_](http://implicit-layers-tutorial.org).
- [Solving y=mx+b with Jax on a TPU Pod slice - Mat Kelcey](http://matpalm.com/blog/ymxb_pod_slice/) - A four part YouTube tutorial series with Colab notebooks that starts with Jax fundamentals and moves up to training with a data parallel approach on a v3-32 TPU Pod slice.
- [JAX, Flax & Transformers 🤗](https://github.com/huggingface/transformers/blob/9160d81c98854df44b1d543ce5d65a6aa28444a2/examples/research_projects/jax-projects/README.md#talks) - 3 days of talks around JAX / Flax, Transformers, large-scale language modeling and other great topics.

<a name="papers" />

## Papers

This section contains papers focused on JAX (e.g. JAX-based library whitepapers, research on JAX, etc). Papers implemented in JAX are listed in the [Models/Projects](#projects) section.

<!--lint ignore awesome-list-item-->
- [__Compiling machine learning programs via high-level tracing__. Roy Frostig, Matthew James Johnson, Chris Leary. _MLSys 2018_.](https://mlsys.org/Conferences/doc/2018/146.pdf) - White paper describing an early version of JAX, detailing how computation is traced and compiled.
- [__JAX, M.D.: A Framework for Differentiable Physics__. Samuel S. Schoenholz, Ekin D. Cubuk. _NeurIPS 2020_.](https://arxiv.org/abs/1912.04232) - Introduces JAX, M.D., a differentiable physics library which includes simulation environments, interaction potentials, neural networks, and more.
- [__Enabling Fast Differentially Private SGD via Just-in-Time Compilation and Vectorization__. Pranav Subramani, Nicholas Vadivelu, Gautam Kamath. _arXiv 2020_.](https://arxiv.org/abs/2010.09063) - Uses JAX's JIT and VMAP to achieve faster differentially private than existing libraries.
<!--lint enable awesome-list-item-->

<a name="tutorials-and-blog-posts" />

## Tutorials and Blog Posts

- [Using JAX to accelerate our research by David Budden and Matteo Hessel](https://deepmind.com/blog/article/using-jax-to-accelerate-our-research) - Describes the state of JAX and the JAX ecosystem at DeepMind.
- [Getting started with JAX (MLPs, CNNs & RNNs) by Robert Lange](https://roberttlange.github.io/posts/2020/03/blog-post-10/) - Neural network building blocks from scratch with the basic JAX operators.
- [Tutorial: image classification with JAX and Flax Linen by 8bitmp3](https://github.com/8bitmp3/JAX-Flax-Tutorial-Image-Classification-with-Linen) - Learn how to create a simple convolutional network with the Linen API by Flax and train it to recognize handwritten digits.
- [Plugging Into JAX by Nick Doiron](https://medium.com/swlh/plugging-into-jax-16c120ec3302) - Compares Flax, Haiku, and Objax on the Kaggle flower classification challenge.
- [Meta-Learning in 50 Lines of JAX by Eric Jang](https://blog.evjang.com/2019/02/maml-jax.html) - Introduction to both JAX and Meta-Learning.
- [Normalizing Flows in 100 Lines of JAX by Eric Jang](https://blog.evjang.com/2019/07/nf-jax.html) - Concise implementation of [RealNVP](https://arxiv.org/abs/1605.08803).
- [Differentiable Path Tracing on the GPU/TPU by Eric Jang](https://blog.evjang.com/2019/11/jaxpt.html) - Tutorial on implementing path tracing.
- [Ensemble networks by Mat Kelcey](http://matpalm.com/blog/ensemble_nets) - Ensemble nets are a method of representing an ensemble of models as one single logical model.
- [Out of distribution (OOD) detection by Mat Kelcey](http://matpalm.com/blog/ood_using_focal_loss) - Implements different methods for OOD detection.
- [Understanding Autodiff with JAX by Srihari Radhakrishna](https://www.radx.in/jax.html) - Understand how autodiff works using JAX.
- [From PyTorch to JAX: towards neural net frameworks that purify stateful code by Sabrina J. Mielke](https://sjmielke.com/jax-purify.htm) - Showcases how to go from a PyTorch-like style of coding to a more Functional-style of coding.
- [Extending JAX with custom C++ and CUDA code by Dan Foreman-Mackey](https://github.com/dfm/extending-jax) - Tutorial demonstrating the infrastructure required to provide custom ops in JAX.
- [Evolving Neural Networks in JAX by Robert Tjarko Lange](https://roberttlange.github.io/posts/2021/02/cma-es-jax/) - Explores how JAX can power the next generation of scalable neuroevolution algorithms.
- [Exploring hyperparameter meta-loss landscapes with JAX by Luke Metz](http://lukemetz.com/exploring-hyperparameter-meta-loss-landscapes-with-jax/) - Demonstrates how to use JAX to perform inner-loss optimization with SGD and Momentum, outer-loss optimization with gradients, and outer-loss optimization using evolutionary strategies.
- [Deterministic ADVI in JAX by Martin Ingram](https://martiningram.github.io/deterministic-advi/) - Walk through of implementing automatic differentiation variational inference (ADVI) easily and cleanly with JAX.
- [Evolved channel selection by Mat Kelcey](http://matpalm.com/blog/evolved_channel_selection/) - Trains a classification model robust to different combinations of input channels at different resolutions, then uses a genetic algorithm to decide the best combination for a particular loss.
- [Introduction to JAX by Kevin Murphy](https://colab.research.google.com/github/probml/pyprobml/blob/master/notebooks/jax_intro.ipynb) - Colab that introduces various aspects of the language and applies them to simple ML problems.
- [Writing an MCMC sampler in JAX by Jeremie Coullon](https://www.jeremiecoullon.com/2020/11/10/mcmcjax3ways/) - Tutorial on the different ways to write an MCMC sampler in JAX along with speed benchmarks.
- [How to add a progress bar to JAX scans and loops by Jeremie Coullon](https://www.jeremiecoullon.com/2021/01/29/jax_progress_bar/) - Tutorial on how to add a progress bar to compiled loops in JAX using the `host_callback` module.

<a name="community" />

## Community

- [JAX GitHub Discussions](https://github.com/google/jax/discussions)
- [Reddit](https://www.reddit.com/r/JAX/)

## Contributing

Contributions welcome! Read the [contribution guidelines](https://github.com/n2cholas/awesome-jax/blob/master/contributing.md) first.