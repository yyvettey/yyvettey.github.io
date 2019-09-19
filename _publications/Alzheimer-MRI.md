---
title: "Feasibility of Quantifying Amyloid Burden Using Volumetric MRI Data: Preliminary Findings Based on the Deep Learning 3D Convolutional Neural Network Approach"
collection: publications
permalink: /publication/Quantifying_Amyloid_Burden_Volumetric_MRI
date: 2018-07-01
venue: "Alzheimer's & Dementia: The Journal of the Alzheimer's Association"
paperurl: "https://www.alzheimersanddementia.com/article/S1552-5260(18)32261-1/fulltext"
citation: "Ye Yuan et al. (2018). &quot;Feasibility of Quantifying Amyloid Burden Using Volumetric MRI Data: Preliminary Findings Based on the Deep Learning 3D Convolutional Neural Network Approach.&quot; <i>Alzheimer's & Dementia: The Journal of the Alzheimer's Association</i>. Volume 14, Issue 7, P30 - P31."
excerpt: ''

---
## Author(s)
Ye Yuan, Zhangyang Wang, Wendy Lee, Pradeep Thiyyagura, Eric M. Reiman, Kewei Chen

## Background
Amyloid positron emission tomography (PET) technique has been used to image beta-amyloid (Aβ) for studies of AD. The standard uptake value ratio (SUVr) between a pre-specified mean-cortical target region and the cerebellum (or other) reference region over the amyloid PET image is routinely used as a measure of Aβ burden in the brain. On the other hand, the volumetric magnetic resonance imaging (vMRI) with information on the structural damage presumably caused by the Aβ accumulation could be potentially used to assess Aβ burden. This study examined the feasibility of using 3D convolutional neural network (3D-CNN) to estimate SUVr and to determine Aβ positivity based on only vMRI data.

## Methods
vMRI data from 1072 ADNI subjects (178 AD patients, 525 MCI patients and 369 cognitively unimpaired [CU] individuals) were used (sample size for training/validation/test were 863/99/110) together with the SUVr values obtained from florbetapir PET. vMRI data were first spatially normalized. We designed the 3D-CNN structure, consisting of two convolutional layers (each followed by a max pooling layer), and two fully connected layers with the mean-square-error loss on top. To overcome data limitations (small size and noisy quality), we employed (1) a denoising auto-encoder to pre-train the 3D-CNN layer-wise; and (2) batch normalization to stabilize training. The 3D-CNN estimated SUVr values were subsequently used to define amyloid positivity with a threshold previously defined (Fleisher, et al., 2011).

## Results
Between 3D-CNN estimated SUVr estimation and the original SUVr, we achieve a mean absolute difference of 0.166 (std=0.111). The correlation between original SUVr and 3D-CNN estimated SUVr is 0.44 (p=1.7e-6). Using the traditional method as the current standard of truth, the deep learning method distinguished between positive and negative amyloid scans (i.e., florbetapir SUVr greater than or equal to 1.18) with 75% sensitivity, 70% specificity and 73% accuracy.

## Conclusions
Treating our findings as preliminary, our deep-learning 3D-CNN based results pointed out the potential to provide reasonably accurate amyloid positivity from vMRI data. Additional studies are needed to improve the SUVr estimation from vMRI alone or via integrating other information into 3D-CNN and to explore the feasibility of directly using individual native-space vMRI data.

[Download paper here](https://doi.org/10.1016/j.jalz.2018.06.2089)

## Citation
@article {Yuan-MRI,
	author = {Ye Yuan, Zhangyang Wang, Wendy Lee, Pradeep Thiyyagura, Eric M. Reiman and Kewei Chen.},
	title = {Feasibility of Quantifying Amyloid Burden Using Volumetric MRI Data: Preliminary Findings Based on the Deep Learning 3D Convolutional Neural Network Approach},
	volume = {14},
	number = {7},
	page = {P30 - P31},
	year = {2018},
	doi = {10.1016/j.jalz.2018.06.2089},
	publisher = {Elsevier},
	journal = {Alzheimer's & Dementia: The Journal of the Alzheimer's Association}
}