---
title: 3D-Aware Object Localization using Gaussian Implicit Occupancy Function
publication_types:
  - "1"
authors:
  - Vincent Gaudillière
  - Leo Pauly
  - Arunkumar Rathinam
  - Albert Garcia Sanchez
  - Mohamed Adel Musallam
  - Djamila Aouada
publication: IROS 2023 - 2023 IEEE/RSJ International Conference on Intelligent
  Robots and Systems, Oct 2023, Detroit, USA.
publication_short: IROS 2023
abstract: To automatically localize a target object in an image is crucial for many computer vision applications. To represent the 2D object, ellipse labels have recently been identified as a promising alternative to axis-aligned bounding boxes. This paper further considers 3D-aware ellipse labels, i.e., ellipses which are projections of a 3D ellipsoidal approximation of the object, for 2D target localization. Indeed, projected ellipses carry more geometric information about the object geometry and pose (3D awareness) than traditional 3D-agnostic bounding box labels. Moreover, such a generic 3D ellipsoidal model allows for approximating known to coarsely known targets. We then propose to have a new look at ellipse regression and replace the discontinuous geometric ellipse parameters with the parameters of an implicit Gaussian distribution encoding object occupancy in the image. The models are trained to regress the values of this bivariate Gaussian distribution over the image pixels using a statistical loss function. We introduce a novel non-trainable differentiable layer, E-DSNT, to extract the distribution parameters. Also, we describe how to readily generate consistent 3D-aware Gaussian occupancy parameters using only coarse dimensions of the target and relative pose labels. We extend three existing spacecraft pose estimation datasets with 3D-aware Gaussian occupancy labels to validate our hypothesis.
draft: false
featured: true
image:
  filename: "IROS2023"
  focal_point: Smart
  preview_only: false
links:
- name: ArXiv
  url: https://arxiv.org/abs/2303.02058
url_pdf: https://arxiv.org/pdf/2303.02058.pdf
url_code: 'https://gitlab.uni.lu/cvi2/space/3d-aware-obj-loc'
url_dataset: 'https://gitlab.uni.lu/cvi2/space/3d-aware-obj-loc'
url_poster: ''
url_project: 'https://cvi2.uni.lu/3d-aware-obj-loc/'
url_slides: ''
url_source: 'https://gitlab.uni.lu/cvi2/space/3d-aware-obj-loc'
url_video: ''
date: 2023-06-21T12:00:00.000Z
---
