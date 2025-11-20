---
title: Integrating the Support for Machine Learning of Inter-Model Relations in Model
  Views
authors:
- James Miranda
- Hugo Bruneliere
- Massimo Tisi
- Gerson Sunyé
date: '2024-07-01'
publishDate: '2025-06-24T13:04:30.685146Z'
publication_types:
- article-journal
publication: '*The Journal of Object Technology*'
doi: 10.5381/jot.2024.23.3.a4
abstract: Model-driven engineering (MDE) supports the engineering of complex systems
  via multiple models representing various aspects of the system. These interrelated
  models are usually heterogeneous and specified using complementary modeling languages.
  Thus, model-view solutions can be employed to federate these models more transparently.
  Inter-model links in model views can sometimes be automatically computed via explicitly
  written matching rules. However, in some cases, matching rules would be too complex
  (or even impossible) to write, but inter-model links may be inferred by analyzing
  previous examples instead. In this paper, we propose a Machine Learning (ML)-backed
  approach for expressing and computing such model views. Notably, we aim at making
  the use of ML in this context as simple as possible. To this end, we refined and
  extended the ViewPoint Definition Language (VPDL) from the EMF Views model-view
  solution to integrate the use of dedicated Heterogeneous Graph Neural Networks (HGNNs).
  These view-specific HGNNs are trained with appropriate sets of contributing models
  before being used for inferring links to be added to the views. We validated our
  approach by implementing a prototype combining EMF Views with PyEcore and PyTorch
  Geometric. Our experiments show promising results regarding the ease-of-use of our
  approach and the relevance of the inferred inter-model links.

url_code: 'https://github.com/NaoMod/Support-ML-Relations-Model-Views'

---
