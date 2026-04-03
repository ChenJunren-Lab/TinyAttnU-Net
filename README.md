# TinyAttnU-Net

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) ![Language](https://img.shields.io/static/v1?label=By&message=Pytorch&color=red)

<!-- Official implementation of the `MICCAI 2024` paper "[TinyU-Net: Lighter Yet Better U-Net with Cascaded Multi-receptive Fields](https://doi.org/10.1007/978-3-031-72114-4_60)". -->

In this paper, we extend [TinyU-Net](https://github.com/ChenJunren-Lab/TinyU-Net), which is a MICCAI 2024 conference paper and selected for `Oral` presentation (top 2.7%).

<!-- ## Poster
![Posterl Results](./assets/MICCAI2024-TinyU-Net-Poster.png "Poster")
 -->

## BibTex
```bibtex
@article{Chen_PLDet,
        title     = {PLDet: Intra-layer Multi-scale Perception and Local Space Attention for Pulmonary Lesion Detection in CT Images},
        author    = {Junren Chen and Wei Wang and Junlong Cheng and Gang Liang and Lei Zhang and Liangyin Chen},
        journal   = {Biomedical Signal Processing and Control},
        volume    = {120},
        pages     = {110087},
        year      = {2026},
        issn      = {1746-8094},
        doi       = {https://doi.org/10.1016/j.bspc.2026.110087},
        url       = {https://www.sciencedirect.com/science/article/pii/S1746809426006415},
}

@InProceedings{Chen_NSDA_NeurIPS2025Spotlight,
        title     = {Neighborhood Self-Dissimilarity Attention for Medical Image Segmentation},
        author    = {Chen, Junren and Chen, Rui and Wang, Wei and Cheng, Junlong and Liang, Gang and Zhang, Lei and Chen, Liangyin},
        year      = {2025},
        booktitle = {The Thirty-ninth Annual Conference on Neural Information Processing Systems}
        # todo: add publisher, volume, month, pages
}

@InProceedings{Chen_TinyUNet_MICCAI2024Oral,
        title     = {TinyU-Net: Lighter Yet Better U-Net with Cascaded Multi-receptive Fields},
        author    = {Chen, Junren and Chen, Rui and Wang, Wei and Cheng, Junlong and Zhang, Lei and Chen, Liangyin},
        booktitle = {Medical Image Computing and Computer Assisted Intervention -- MICCAI 2024},
        year      = {2024},
        publisher = {Springer Nature Switzerland},
        volume    = {LNCS 15009},
        month     = {October},
        pages     = {626--635}
}
```



## Data
- [ISIC2018](https://challenge.isic-archive.com/data/#2018). The ISIC2018 dataset consists of images with skin disease lesions (2594 training images, 100 validation images, and 1000 test images).
- [NCP](http://ncov-ai.big.ac.cn/download?lang=en). Lesion segmentation dataset of the CT slice images from the China Consortium of Chest CT Image Investigation (CC-CCII). A total of 750 CT slices from 150 COVID-19 patients were manually segmented into background, lung field, ground-glass opacity (GGO), and consolidation (CL).

<!-- ## Results
![Qualitative Experimental Results](./assets/Qualitative_experimental_results.png "Comparative qualitative results on ISIC2018 (top two rows) and NCP (bottom two rows) datasets.") -->
