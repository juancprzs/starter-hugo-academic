---
title: Gabor Layers Enhance Network Robustness
date: '2020-01-01'
draft: true
publishDate: '2022-01-24T12:51:35.519584Z'
authors:
- Juan C. Pérez
- Motasem Alfarra
- Guillaume Jeanneret
- Adel Bibi
- Ali Thabet
- Bernard Ghanem
- Pablo Arbeláez
publication_types:
- '1'
abstract: We revisit the benefits of merging classical vision concepts with deep learning
  models. In particular, we explore the effect of replacing the first layers of various
  deep architectures with Gabor layers (i.e. convolutional layers with filters that
  are based on learnable Gabor parameters) on robustness against adversarial attacks.
  We observe that architectures with Gabor layers gain a consistent boost in robustness
  over regular models and maintain high generalizing test performance. We then exploit
  the analytical expression of Gabor filters to derive a compact expression for a
  Lipschitz constant of such filters, and harness this theoretical result to develop
  a regularizer we use during training to further enhance network robustness. We conduct
  extensive experiments with various architectures (LeNet, AlexNet, VGG16, and WideResNet)
  on several datasets (MNIST, SVHN, CIFAR10 and CIFAR100) and demonstrate large empirical
  robustness gains. Furthermore, we experimentally show how our regularizer provides
  consistent robustness improvements.
featured: false
publication: '*Proceedings of the European Conference on Computer Vision (ECCV)*'
---

