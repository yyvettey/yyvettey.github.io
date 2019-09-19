---
title: "Quantification of Amyloid Burden from Florbetapir PET Images without Using Target and Reference Regions: Preliminary Findings Based on the Deep Learning 3D Convolutional Neural Network Approach"
collection: publications
permalink: /publication/Quantification_Amyloid_Burden_Florbetapir_PET
date: 2018-07-01
venue: "Alzheimer's & Dementia: The Journal of the Alzheimer's Association"
paperurl: "https://www.alzheimersanddementia.com/article/S1552-5260(18)32262-3/fulltext"
citation: "Ye Yuan et al. (2018). &quot;Quantification of Amyloid Burden from Florbetapir PET Images without Using Target and Reference Regions: Preliminary Findings Based on the Deep Learning 3D Convolutional Neural Network Approach.&quot; <i>Alzheimer's & Dementia: The Journal of the Alzheimer's Association</i>. Volume 14, Issue 7, P31."
excerpt: ''

---
## Author(s)
Ye Yuan, Zhangyang Wang, Wendy Lee, Paul VanGilder, Yinghua Chen, Eric M. Reiman, Kewei Chen

## Background
Beta-amyloid (Aβ) is widely viewed as a major hallmark of Alzheimer’s disease (AD) pathology. Standard uptake value ratio (SUVr) between a pre-specified target mean-cortical region and the cerebellum (or another) reference region is the most commonly used measurement to quantify Aβ burden for amyloid positron emission tomography (PET) technique. By utilizing a 3D convolutional neural network (3D-CNN), we examined the feasibility of estimating SUVr and determining Aβ positivity from florbetapir PET images directly without defining the target and reference regions and without extracting data from them.

## Methods
Florbetapir PET data from 1072 subjects (178 AD patients, 525 MCI patients and 369 cognitively unimpaired [CU] individuals) from Alzheimer’s Disease Neuroimage Initiative (ADNI) were used for this analysis. Florbetapir PET data were first spatially normalized to MNI template space. We designed the Deep Learning 3D-CNN, consisting of two convolutional layers (each followed by a max pooling layer), and two fully connected layers with the mean-square-error (MSE) loss on top. To overcome data limitations (small size and noisy quality), we employ (1) a denoising auto-encoder to pre-train the 3D-CNN layer-wise; and (2) batch normalization to stabilize training. The estimated SUVr values from the 3D-CNN were subsequently used to define amyloid positivity using a previously defined threshold (Fleisher, et al., 2011).

## Results
For florbetapir PET-based SUVr estimation, we achieve a mean absolute difference of 0.035, the correlation between original SUVr vs 3D-CNN estimated SUVr is 0.97 (p=2.2e-16). Using the traditional method as the current standard of truth, the deep learning method distinguished between positive and negative amyloid scans (i.e., florbetapir SUVr greater than or equal to 1.18) with 92% sensitivity, 98% specificity and 95% accuracy.

## Conclusions
Although preliminary, our deep-learning 3D-CNN based results point out the potential to produce highly accurately SUVr from entire PET images directly without extracting data from mean-cortical and the cerebellar reference region. Additional studies are being undertaken to improve SUVr estimates and explore the feasibility of directly using native space imaging data.

[Download paper here](https://doi.org/10.1016/j.jalz.2018.06.2090)

## Citation
@article {Yuan-PET,
	author = {Ye Yuan, Zhangyang Wang, Wendy Lee, Paul VanGilder, Yinghua Chen, Eric M. Reiman and Kewei Chen.},
	title = {Quantification of Amyloid Burden from Florbetapir PET Images without Using Target and Reference Regions: Preliminary Findings Based on the Deep Learning 3D Convolutional Neural Network Approach},
	volume = {14},
	number = {7},
	page = {P30 - P31},
	year = {2018},
	doi = {10.1016/j.jalz.2018.06.2090},
	publisher = {Elsevier},
	journal = {Alzheimer's & Dementia: The Journal of the Alzheimer's Association}
}