---
layout: default
---

### About Me
* * *


I am a Faculty Fellow / Assistant Professor at the Center for Data Science at NYU.
I obtained my PhD in Computer Science from the Courant Institute, NYU, where I was fortunate to be advised by [Prof. Rajesh Ranganath](https://cims.nyu.edu/~rajeshr/).

My research centers on **adaptation**: building AI systems that generalize beyond their training distribution, reason about the mechanisms that transfer across environments, and reveal what they rely on. I develop the representations and algorithms that make adaptation reliable, working toward the broader goal of reliable world models.

**Representations and mechanisms.** Generalization and shortcut learning — [NuRD](https://arxiv.org/abs/2107.00520) for out-of-distribution generalization with optimality guarantees, [semantic corruptions](https://arxiv.org/abs/2210.01302) for adjusting away unknown nuisances, and [margin control](https://arxiv.org/abs/2308.12553) for the shortcut learning that arises from gradient-based training with cross entropy. I also work on [faithfulness and encoding in explanations](https://arxiv.org/abs/2411.02664), [causal estimation with functional confounders](https://papers.nips.cc/paper/2020/hash/36dcd524971019336af02550264b8a08-Abstract.html), [black-box causal estimation via meta-learning](https://arxiv.org/abs/2503.05985), and [multimodal representation alignment](https://arxiv.org/abs/2411.01053).

**Modeling and architectures.** [Long-context modeling](https://arxiv.org/abs/2511.05313), [transformer dynamics and retrieval](https://aclanthology.org/2025.findings-emnlp.1260/), and [flow maps](https://openreview.net/forum?id=C1bkDPqvDW).

**Impact on science.** Equal learning for transportable clinical risk models, [LODE](https://papers.nips.cc/paper/2020/hash/36dcd524971019336af02550264b8a08-Abstract.html) for genome-wide association studies, and [NuRD for new-particle detection](https://iopscience.iop.org/article/10.1088/2632-2153/ad780c/meta) on LHC data.

I'm eternally excited about new ideas and finding good applications for my work! Shoot me an email if you want to chat!

### Selected Work
* * *

**[Explanations that Reveal All through the Definition of Encoding](https://arxiv.org/abs/2411.02664)** — NeurIPS 2024.
Defines *encoding* in explanations and gives STRIPE-X, a scalable way to detect it.

**[Don't Blame Dataset Shift! Shortcut Learning due to Gradients and Cross Entropy](https://arxiv.org/abs/2308.12553)** — NeurIPS 2023.
Shortcut learning comes from the training objective, not just the data; margin control mitigates it.

**[OOD Generalization in the Presence of Nuisance-Induced Spurious Correlations](https://arxiv.org/abs/2107.00520)** — ICLR 2022.
NuRD, with optimality guarantees for generalizing across populations.

**[Attention and Compression is all you need for Controllably Efficient Language Models](https://arxiv.org/abs/2511.05313)** — In submission, 2026.
CAT matches ten efficient alternatives from a single trained model, at higher throughput than a dense transformer.

**[Learning Is Not A Race: Improving Retrieval in Language Models via Equal Learning](https://aclanthology.org/2025.findings-emnlp.1260/)** — EMNLP 2025.
Equal learning improves retrieval by fixing how fast different features get learned.

**[Black Box Causal Inference: Effect Estimation via Meta Prediction](https://arxiv.org/abs/2503.05985)** — 2025.
Learns whole estimation algorithms by framing causal estimation as dataset-level prediction.

[Full publication list →](./publications.html)

### News
* * *
  1. **May 2026**: Gave talks at UCLA, UC Irvine, and UC Riverside on *Making the most of your data for Reliable AI*.

  1. **Apr 2026**: Gave a talk at Fermilab on *The Spectre of Spurious Correlations in OOD Generalization and Interpretability*.

  1. **Mar 2026**: Gave the same talk at the [DBMI Seminar](https://www.dbmi.columbia.edu/) at Columbia.

  1. **Mar 2026**: [Extracting Representations in LLMs Robust to Distribution Shifts](https://openreview.net/forum?id=KzH1cLVU1R) at the UCRL workshop at ICLR, about improved probing for high-level concepts in LLM representations.

  1. **Jan 2026**: New paper [Flow Map Learning Via Non-Gradient Vector Flow](https://openreview.net/forum?id=C1bkDPqvDW) accepted at ICLR 2026, led by Mark Goldstein.

  1. **2025**: My dissertation was awarded the Janet Fabri Prize, given to NYU CS's most outstanding dissertation.

  1. **Nov 2025**: Two papers at ML4H — [Let the Experts Speak: Improving Survival Prediction & Calibration via Mixture-of-Experts Heads](https://arxiv.org/abs/2511.09567), led by Todd Morrill, and [New-Onset Diabetes Assessment Using Artificial Intelligence-Enhanced Electrocardiography](https://arxiv.org/abs/2205.02900), led by Hao Zhang.

  1. **Nov 2025**: New paper [Attention and Compression is all you need for Controllably Efficient Language Models](https://arxiv.org/abs/2511.05313) on building controllably efficient sequence models with attention primitives.

  1. **Nov 2025**: New paper [Learning Is Not A Race: Improving Retrieval in Language Models via Equal Learning](https://aclanthology.org/2025.findings-emnlp.1260/) at EMNLP Findings, improves feature learning in Transformers via a simple class of losses called E-losses.

  1. **Jan 2025**: [Black-box Causal Inference](https://arxiv.org/abs/2503.05985) shows how to learn entire estimation algorithms by framing causal estimation as a meta-learning dataset-level prediction problem.

  1. **Dec 2024**: Gave a [tutorial at NeurIPS 2024](https://neurips.cc/virtual/2024/tutorial/99523) on *Out-of-Distribution Generalization: Shortcuts, Spuriousness, and Stability*, with Maggie Makar and Yoav Wald.

  1. **Oct 2024**: Two papers at NeurIPS 2024, [Explanations that reveal all through the definition of Encoding](https://arxiv.org/abs/2411.02664) lead by Nhi and I, [Multi-modal contrastive learning with SYMILE](https://arxiv.org/abs/2411.01053) led by Adriel Saporta.

  1. **Aug 2024**: Defended my PhD!

  1. **June 2024**: Nuisances via Negativa accepted by TMLR; [link](https://arxiv.org/abs/2210.01302).

  1. **Oct 2023**: Gave a talk about OOD generalization in health at INFORMS.

  1. **Sept 2023**: New paper accepted at NeurIPS 2023; [link](https://arxiv.org/abs/2308.12553).

  1. **July 2023**: The second SCIS workshop was a success at ICML 2023; [link](https://sites.google.com/view/scis-workshop-23)

  1. **April 2023**: DIET was published at AISTATS; [link](https://arxiv.org/abs/2208.08579).

  1. **July 2022**: Organized the SCIS workshop at ICML 2022; [website](https://sites.google.com/view/scis-workshop/home).

  1. **March 2022, Very happy to be a recipient of the Apple Scholars in AI/ML PhD Fellowship!** [announcement](https://machinelearning.apple.com/updates/apple-scholars-aiml-2022)

  1. **March 2022, Updated version of NuRD on arxiv with code and improved results!** [link](https://arxiv.org/abs/2107.00520)

  1. **January 2022, NuRD published at ICLR 2022 and work led by Mark Goldstein published at CLeaR 2022;** [link](https://arxiv.org/abs/2112.00881).

  1. **Oct' 21, Named Rising Star by the Trustworthy ML initiative**

  1. **June' 21, New work on arxiv:** What sort of predictive models come with performance guarantees under spurious correlations induced by a relationship between the label and some nuisance variables that are correlated on the covariates? [Out-of-distribution Generalization in the Presence of Nuisance-Induced Spurious Correlations](https://arxiv.org/abs/2107.00520)

  1. **Apr' 21, Link to work at AISTATS, 2021; Led by Mukund Sudarshan**: A new contrarian test statistic to use in CRTs to improve robustness to mis-specified covariate distributions. [CONTRA: Contrarian statistics for controlled variable selection](http://proceedings.mlr.press/v130/sudarshan21a.html)

  1. **Nov' 20. Links to my work at NeurIPS 2020 along with punchlines (shoot me an email if these interest you!)**:
      - *General method for causal estimation from instrumental variables using only treatment process assumptions*: [General Control Functions for Causal Estimation from IVs](https://papers.nips.cc/paper/2020/hash/604f2c31e67034642b288d76a8df11d5-Abstract.html)
      - *Fundamental nonparametric assumptions for causal estimation using functional confounders which violate positivity*: [Causal Estimation with Functional Confounders](https://papers.nips.cc/paper/2020/hash/36dcd524971019336af02550264b8a08-Abstract.html)
      - *Add-on differentiable loss to improve calibration of survival models allowing explicit trade-off with predictive quality*: [X-CAL: Explicit Calibration for Survival Analysis](https://papers.nips.cc/paper/2020/hash/d4a93297083a23cc099f7bd6a8621131-Abstract.html)

### Olds

* * *

I was an intern in the summer of 2019 in Adobe Research, San Jose working on bayesian attribution models for ad targeting. Previously, I worked as a Software Developer at [DBMI, Columbia University](https://www.dbmi.columbia.edu/). In 2017, I completed my MS in CS, also at NYU. I was introduced to causal inference in the [Clinical Machine Learning group](http://clinicalml.org), where I worked with two amazing mentors, [Prof. Uri Shalit](https://web.iem.technion.ac.il/en/people/userprofile/urishalit.html) and [Prof. David Sontag](https://people.csail.mit.edu/dsontag/). My fateful but fun undergrad was from [IIT Madras](https://www.iitm.ac.in), where I was enrolled in the EE department.
