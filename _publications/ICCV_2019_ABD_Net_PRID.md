---
title: "ABD-Net: Attentive but Diverse Person Re-Identification"
collection: publications
permalink: /publication/ICCV2019_ABD_Net
date: 2019-10-27
venue: "ICCV"
paperurl: "https://arxiv.org/abs/1908.01114"
citation: "Tianlong Chen et al. (2019). &quot;ABD-Net: Attentive but Diverse Person Re-Identification.&quot; <i>ICCV 2019</i>. ..."
excerpt: 'We advocate the complementary powers of attention and diversity for Re-ID, by proposing an Attentive but Diverse Network (ABD-Net). ABD-Net seamlessly integrates attention modules and diversity regularizations throughout the entire network to learn features that are representative, robust, and more discriminative'


---
## Author(s)
Tianlong Chen, Shaojin Ding, Jingyi Xie, Ye Yuan, Wuyang Chen, Yang Yang, Zhou Ren, Zhangyang Wang

## Abstract
Attention mechanisms have been found effective for person re-identification (Re-ID). However, the learned “attentive” features are often not naturally uncorrelated or “diverse”, which compromises the retrieval performance based on the Euclidean distance. We advocate the complementary powers of attention and diversity for Re-ID, by proposing an Attentive but Diverse Network (ABD-Net). ABD-Net seamlessly integrates attention modules and diversity regularizations throughout the entire network to learn features that are representative, robust, and more discriminative. Specifically, we introduce a pair of complementary attention modules, focusing on channel aggregation and position awareness, respectively. Then, we plug in a novel orthogonality constraint that efficiently enforces diversity on both hidden activations and weights. Through an extensive set of ablation study, we verify that the attentive and diverse terms each contributes to the performance boosts of ABD-Net. It consistently outperforms existing state-of-the-art methods on there popular person Re-ID benchmarks.

[Download paper here](https://arxiv.org/pdf/1908.01114.pdf)

## Citation
@misc{chen2019abdnet,
    title={ABD-Net: Attentive but Diverse Person Re-Identification},
    author={Tianlong Chen and Shaojin Ding and Jingyi Xie and Ye Yuan and Wuyang Chen and Yang Yang and Zhou Ren and Zhangyang Wang},
    year={2019},
    eprint={1908.01114},
    archivePrefix={arXiv},
    primaryClass={cs.CV}
}