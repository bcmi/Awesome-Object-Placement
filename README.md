# Awesome Object Placement [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources including papers, datasets, and relevant links pertaining to object placement, which aims to learn plausible **spatial transformation** (e.g., shifting, scaling, affine transformation, perspective transformation) for the inserted foreground object in a composite image considering geometric and semantic information. The simplest case is finding reasonable **location and scale** for the foreground object. 

## Contributing

Contributions are welcome.  If you wish to contribute, feel free to send a pull request. If you have suggestions for new sections to be included, please raise an issue and discuss before sending a pull request.

## Table of Contents
+ [Papers](#Papers)
+ [Datasets](#Datasets)
+ [Other Resources](#Other-resources)


## Papers

#### 1. Instance-specific: predict transformation parameters given a pair of foreground and background

##### 1.1 Generative Methods

+ Siyuan Zhou, Liu Liu, Li Niu, Liqing Zhang: "*Learning Object Placement via Dual-path Graph Completion.*" ECCV (2022)

+ Lingzhi Zhang, Tarmily Wen, Jie Min, Jiancong Wang, David Han, Jianbo Shi: "*Learning Object Placement by Inpainting for Compositional Data Augmentation.*" ECCV (2020) [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580562.pdf)

+ Shashank Tripathi, Siddhartha Chandra, Amit Agrawal, Ambrish Tyagi, James M. Rehg, Visesh Chari: "*Learning to Generate Synthetic Data via Compositing.*" CVPR (2019) [[arXiv]](https://arxiv.org/pdf/1904.05475.pdf)

+ Chen-Hsuan Lin, Ersin Yumer, Oliver Wang, Eli Shechtman, Simon Lucey: "*ST-GAN: Spatial Transformer Generative Adversarial Networks for Image Compositing.*" CVPR (2018) [[arXiv]](https://arxiv.org/pdf/1803.01837.pdf) [[code]](https://github.com/chenhsuanlin/spatial-transformer-GAN)

##### 1.2 Discriminative Methods

+ Liu Liu, Zhenchen Liu, Bo Zhang, Jiangtong Li, Li Niu, Qingyang Liu, Liqing Zhang: "*OPA: Object Placement Assessment Dataset.*" arXiv preprint arXiv:2107.01889 [[arXiv]](https://arxiv.org/pdf/2107.01889.pdf)[[code]](https://github.com/bcmi/Object-Placement-Assessment-Dataset-OPA)

#### 2. Category-specific: predict bounding boxes for certain categories given a background

##### 2.1 Generative Methods

+ Anna Volokitin, Igor Susmelj, Eirikur Agustsson, Luc Van Gool, Radu Timofte: "*Efficiently Detecting Plausible Locations for Object Placement Using Masked Convolutions.*" ECCV workshop (2020) [[pdf]](https://link.springer.com/chapter/10.1007/978-3-030-66823-5_15)

+ Song-Hai Zhang, Zhengping Zhou, Bin Liu, Xi Dong, Peter Hall: "*What and Where: A Context-based Recommendation System for Object Insertion.*" Computational Visual Media (2020) [[arXiv]](https://arxiv.org/pdf/1811.09783.pdf)

+ Donghoon Lee, Sifei Liu, Jinwei Gu, Ming-Yu Liu, Ming-Hsuan Yang, Jan Kautz: "*Context-Aware Synthesis and Placement of Object Instances.*" NeurIPS (2018) [[pdf]](https://proceedings.neurips.cc/paper/2018/file/c6969ae30d99f73951cb976b88a457af-Paper.pdf)

+ Fuwen Tan, Crispin Bernier, Benjamin Cohen, Vicente Ordonez, Connelly Barnes: "*Where and Who? Automatic Semantic-Aware Person Composition.*" WACV (2018) [[arXiv]](https://arxiv.org/pdf/1706.01021.pdf)[[code]](https://github.com/fwtan/who_where)


## Datasets

+ **OPA**: it contains 62,074 training images and 11,396 test images, in which the foregrounds/backgrounds in training set and test set have no overlap. The training (resp., test) set contains 21,376 (resp.,3,588) positive samples and 40,698 (resp., 7,808) negative samples. Besides, the training (resp., test) set contains 2,701 (resp., 1,436) unrepeated foreground objects and1,236 (resp., 153) unrepeated background images. [[pdf]](https://arxiv.org/pdf/2107.01889.pdf) [[link]](https://github.com/bcmi/Object-Placement-Assessment-Dataset-OPA)
 
## Other Resources

+ [Awesome-Image-Composition](https://github.com/bcmi/Awesome-Image-Composition)

