# Awesome Differential Privacy [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Differential privacy is a mathematical framework for sharing statistical insights about a dataset while provably limiting what can be learned about any individual in it.

## Contents

- [Code and Projects](#code-and-projects)
- [Learn](#learn)
- [Read](#read)
- [Industry Articles](#industry-articles)
- [YouTube](#youtube)

## Code and Projects

- [OpenDP](https://opendp.org/) - Community effort to build trustworthy, open source tools for differential privacy.
- [Google's Differential Privacy Library](https://github.com/google/differential-privacy) - C++, Go and Java libraries for computing differentially private statistics.
- [Opacus](https://github.com/meta-pytorch/opacus) - Train PyTorch models with differential privacy.
- [TensorFlow Privacy](https://github.com/tensorflow/privacy) - Train TensorFlow models with differential privacy.
- [Diffprivlib](https://github.com/IBM/differential-privacy-library) - IBM's general-purpose library of differential privacy mechanisms and machine learning models.
- [JAX-Privacy](https://github.com/google-deepmind/jax_privacy) - Algorithms for privacy-preserving machine learning in JAX.
- [Harvard University Privacy Tools Project](https://privacytools.seas.harvard.edu/) - Research project developing tools and policies for sharing sensitive research data.
- [Tumult Analytics](https://docs.tmlt.dev/analytics/latest/index.html) - Platform for computing differentially private aggregate statistics on large datasets.
- [PyDP](https://github.com/OpenMined/PyDP) - Python wrapper for Google's differential privacy library.
- [PipelineDP](https://github.com/OpenMined/PipelineDP) - Framework for applying differential privacy to large datasets, aimed at non-experts.
- [Private Multiplicative Weights](https://github.com/mrtzh/PrivateMultiplicativeWeights.jl) - Julia implementation of the MWEM algorithm for differentially private synthetic data.
- [diffpriv](https://github.com/brubinstein/diffpriv) - R package for easy differential privacy.
- [ARX](https://github.com/arx-deidentifier/arx) - Data anonymization tool supporting differential privacy, k-anonymity and other privacy models.
- [DP-XGBoost](https://github.com/sarus-tech/dp-xgboost) - Differentially private gradient boosted trees at scale, built on XGBoost.
- [Qrlew](https://qrlew.github.io/) - SQL-to-SQL rewriting layer that makes queries differentially private.
- [SynthLeak](https://amanpriyanshu.github.io/SynthLeak/) - Experiments on breaking privacy in real-world differentially private synthetic data.
- [Fast Differential Privacy](https://github.com/awslabs/fast-differential-privacy) - Faster differentially private training of PyTorch models.

## Learn

- [The Algorithmic Foundations of Differential Privacy](https://www.cis.upenn.edu/~aaroth/Papers/privacybook.pdf) - Foundational textbook by Cynthia Dwork and Aaron Roth.
- [A Course in Differential Privacy](https://www.youtube.com/playlist?list=PLmd_zeMNzSvRRNpoEWkVo6QY_6rR3SHjp) - Video lectures by Gautam Kamath.
- [BIU Winter School on Differential Privacy](https://www.youtube.com/playlist?list=PL8Vt-7cSFnw1li73YXZdTaiAeXFkmWWRh) - Lectures from the Bar-Ilan University school "Differential Privacy: From Theory to Practice".
- [CS 860 - Algorithms for Private Data Analysis](https://www.gautamkamath.com/CS860-fa2020.html) - Graduate course by Gautam Kamath, with lecture notes and videos.
- [Secure and Private AI](https://www.udacity.com/course/secure-and-private-ai--ud185) - Udacity course on differential privacy, federated learning and encrypted computation in deep learning.
- [A Friendly, Non-Technical Introduction to Differential Privacy](https://desfontain.es/blog/friendly-intro-to-differential-privacy.html) - Blog post series by Damien Desfontaines.
- [Programming Differential Privacy](https://programming-dp.com/) - Online book about differential privacy, for programmers.
- [Differential Privacy in Deep Learning](https://towardsdatascience.com/differential-privacy-in-deep-learning-cf9cc3591d28/) - Introduction to applying differential privacy to deep learning.

## Read

- [Wikipedia](https://en.wikipedia.org/wiki/Differential_privacy) - Encyclopedic overview of differential privacy.
- [A Primer for a Non-Technical Audience](https://privacytools.seas.harvard.edu/files/privacytools/files/pedagogical-document-dp_0.pdf) - Introduction to differential privacy for lawyers and policymakers.
- [Differential Privacy for Dummies](https://github.com/frankmcsherry/blog/blob/master/posts/2016-02-03.md) - Informal introduction by Frank McSherry.
- [Introducing TensorFlow Privacy](https://blog.tensorflow.org/2019/03/introducing-tensorflow-privacy-learning.html) - Announcement of the TensorFlow Privacy library.
- [Introducing Opacus](https://ai.meta.com/blog/introducing-opacus-a-high-speed-library-for-training-pytorch-models-with-differential-privacy/) - Announcement of the Opacus library.
- [An Illustrated Primer](https://github.com/frankmcsherry/blog/blob/master/posts/2016-02-06.md) - Worked examples of differential privacy by Frank McSherry.
- [Win-Vector Blog](https://win-vector.com/2015/11/01/our-differential-privacy-mini-series/) - Mini-series on differential privacy and reusable holdout sets.
- [The Promise of Differential Privacy](https://www.microsoft.com/en-us/research/wp-content/uploads/2011/10/PID2016981.pdf) - Tutorial on algorithmic techniques by Cynthia Dwork.
- [Visualizing the Accuracy-Privacy Trade-Off](https://priyakalot.github.io/ViP-demo/) - Interactive demo.
- [Laplacian Noisy Counting Mechanism Illustration](https://georgianpartners.shinyapps.io/interactive_counting/) - Interactive illustration of the Laplace mechanism.

## Industry Articles

- [Apple - Learning with Privacy at Scale](https://machinelearning.apple.com/research/learning-with-privacy-at-scale) - How Apple uses local differential privacy to learn from user data.
- [Apple - Differential Privacy Overview](https://www.apple.com/privacy/docs/Differential_Privacy_Overview.pdf) - Apple's overview of its use of differential privacy.
- [Google - Deep Learning with Differential Privacy](https://arxiv.org/abs/1607.00133) - Paper introducing differentially private stochastic gradient descent.
- [Microsoft - How Cynthia Dwork Is Making Data Analysis Better](https://blogs.microsoft.com/ai/privacy-and-accuracy-how-cynthia-dwork-is-making-data-analysis-better/) - Profile of the co-inventor of differential privacy.
- [Microsoft - Collecting Telemetry Data Privately](https://www.microsoft.com/en-us/research/blog/collecting-telemetry-data-privately/) - How Microsoft collects telemetry with local differential privacy.
- [How One of Apple's Key Privacy Safeguards Falls Short](https://www.wired.com/story/apple-differential-privacy-shortcomings/) - Critique of the privacy parameters used by Apple.
- [Google's Differential Privacy May Be Better Than Apple's](https://www.macobserver.com/columns-opinions/google-apple-differential-privacy/) - Comparison of the two companies' approaches.
- [Privacy and Machine Learning: Two Unexpected Allies?](https://cleverhans.io/privacy/2018/04/29/privacy-and-machine-learning.html) - How differential privacy and machine learning can benefit each other.

## YouTube

- [The Definition of Differential Privacy](https://www.youtube.com/watch?v=lg-VhHlztqo) - Talk by Cynthia Dwork at the Institute for Advanced Study.
- [Tutorial on Differential Privacy](https://www.youtube.com/watch?v=ekIL65D0R3o) - Tutorial from the Simons Institute for the Theory of Computing.
- [A Practical Beginners' Guide to Differential Privacy](https://www.youtube.com/watch?v=Gx13lgEudtU) - CERIAS security seminar at Purdue University.
- [Accessing Data While Preserving Privacy](https://www.youtube.com/watch?v=GBw07xJyc0c&t=20s) - Talk at the Institut Henri Poincaré.
- [Protecting Privacy with MATH](https://www.youtube.com/watch?v=pT19VwBAqKA) - Minutephysics video made in collaboration with the US Census Bureau.

## Footnotes

<a href="https://star-history.com/#menisadi/awesome-differential-privacy&Date">
  <img src="https://api.star-history.com/svg?repos=menisadi/awesome-differential-privacy&type=Date" width="600" />
</a>
