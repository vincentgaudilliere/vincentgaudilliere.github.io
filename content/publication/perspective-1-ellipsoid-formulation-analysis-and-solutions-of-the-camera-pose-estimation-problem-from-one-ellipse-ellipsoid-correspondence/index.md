---
title: "Perspective-1-Ellipsoid: Formulation, Analysis and Solutions of the
  Camera Pose Estimation Problem from one Ellipse-Ellipsoid Correspondence"
publication_types:
  - "2"
authors:
  - Vincent Gaudillière
  - Gilles Simon
  - Marie-Odile Berger
doi: 10.1007/s11263-023-01794-x
publication: International Journal of Computer Vision
publication_short: IJCV
abstract: In computer vision, camera pose estimation from correspondences between 3D geometric entities and their projections into the image has been a widely investigated problem. Although most state-of-the-art methods exploit low-level primitives such as points or lines, the emergence of very effective CNN-based object detectors in the recent years has paved the way to the use of higher-level features carrying semantically meaningful information. Pioneering works in that direction have shown that modelling 3D objects by ellipsoids and 2D detections by ellipses offers a convenient manner to link 2D and 3D data. However, the mathematical formalism most often used in the related litterature does not enable to easily distinguish ellipsoids and ellipses from other quadrics and conics, leading to a loss of specificity potentially detrimental in some developments. Moreover, the linearization process of the projection equation creates an over-representation of the camera parameters, also possibly causing an efficiency loss. In this paper, we therefore introduce an ellipsoid-specific theoretical framework and demonstrate its beneficial properties in the context of pose estimation. More precisely, we first show that the proposed formalism enables to reduce the pose estimation problem to a position or orientation-only estimation problem in which the remaining unknowns can be derived in closed-form. Then, we demonstrate that it can be further reduced to a 1 Degree-of-Freedom (1DoF) problem and provide the analytical derivations of the pose as a function of that unique scalar unknown. We illustrate our theoretical considerations by visual examples and include a discussion on the practical aspects. Finally, we release this paper along with the corresponding source code in order to contribute towards more efficient resolutions of ellipsoid-related pose estimation problems.
draft: false
featured: true
image:
  filename: "IJCV2023.png"
  focal_point: Center
  preview_only: false
links:
- name: ArXiv
  url: https://arxiv.org/abs/2208.12513
- name: Springer
  url: https://link.springer.com/article/10.1007/s11263-023-01794-x
url_pdf: https://arxiv.org/pdf/2208.12513.pdf
url_code: 'https://gitlab.inria.fr/vgaudill/p1e'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://members.loria.fr/moberger/Documents/P1E.mp4'
date: 2023-04-07T12:00:00.000Z
---
