---
layout: archive
title: "Research and Thesis"
collection: research
author_profile: true
permalink: /research/ 
---

---

## Individual Project

2018### <rm>2018</rm> <b>Real-time 3D Path Planning from a Single Fluoroscopic Image for Robot Assisted Fenestrated Endovascular Aortic Repair (FEVAR)</b>
* Imperial College London, London, UK
* Segmented Abdominal Aortic Aneurysm (AAA) using U-Net with data augmentation of gray value variation instead of rotation and mirroring to avoid overfitting caused by relatively small intra-subject variation of intensity and translation. Extracted the largest connected area from the segmented volume and reconstruct the 3D AAA shape using marching cube. Extracted the centrelines of AAA from CTA and fluoroscopy image. Establish the correspondence between the 3D preoperative and 2D intra-operative AAA skeletons using a proposed graph matching method. Deformed the 3D skeletons using thin plate spline with regularization in respect to skeleton length and smoothness to implement the deformable 2D/3D registration. Validate the proposed framework on simulation, phantom and patient AAA data sets, achieving 3D distance error of 2mm in the phantom setup. Obtained also performance advantages in terms of accuracy, robustness and time-efficiency.


### <rm>2016</rm> <b>Load Frequency Control of a Smart Grid</b>
* University of Liverpool, Liverpool, UK
* Built a model of Load Frequency Control and Direct Load Control in a multi-area power system. Decoupled frequency of each area by solving an equivalent optimization problem of minimizing flow network. Utilized direct controlled load to improve the efficiency and stability of the power system.



* 2015 <b>Image Mosaic of Unmanned Aerial Vehicle</b>
  * Implemented noise reduction using a Wiener filter. Utilized the random sample consensus algorithm to registry images based on feature points extracted by the Scale-Invariant Feature Transform in MATLAB. Applied weighted averaging to image fusion. Completed a MATLAB program that implemented an automatic image mosaic for given photos.

---

## Collaborated Project

### 2018 <b>High-resolution Feature Map Propagation in Deep Convolutional Neural Network</b>
* Imperial College London, London, UK
* Theoretically analysed the receptive field (RF) with dilated (atrous) rate setting and the truncation effect. Obtained and proved a general solution of atrous rate setting for a uniform distributed RF while large and fully covered RF guaranteed. Proposed a novel network, Atrous Convolutional Neural Network (ACNN) with skip connections and multi-scale consideration as an example for semantic segmentation. Validated ACNN on three bio-medical datasets with high-resolution feature map propagation and reasonable segmentation results, reducing the number of variables by 99.75%, and achieving a reasonable DSC of 0.6~0.7.
* Contribution: Theoretical analysed and simulated the effect of atrous rate on the receptive field, and the truncation effect. Processed data and evaluated segmentation results.

### 2017 <b>Brain-Computer Interface Framework for NAO Robot</b>
* Imperial College London, London, UK
* Removed the artefacts caused by electromyography and electrooculography from electroencephalograph (EEG) signals using Wavelet Analysis. Extracted the features of the EEG signals using Common Spatial Pattern filter. Used Linear Discriminant Analysis, Support Vector Machine, Convolutional Neural Network and RNN to classified two (and three) kinds of imaginary motion. Transmitted classified data to the second computer with SSH protocol by Python-Socket for real-time control of one NAO robot out of a maze. Implemented colourized boundary distance measurement using histogram equalization to enhance contrast, a Laplacian filter to detect edge and a homogeneous transformation to reconstruct the 3-D coordinates.
  
### 2016 <b>Smartphone Download-Management System</b>
* University of Liverpool, Liverpool, UK
* Built a model of Wi-Fi and 3G data transmissions using MATLAB. Simulated a process of file generation and downloads to optimize the downloading process. Designed strategies for priority ranking, and optimized loss functions. Implemented the data dynamic visualization of download values and download size for different strategies. Quantified the performance of each strategy according to the size and value of downloaded documents, tested the simulation in multiple internet environments, and selected the optimal strategies for most cases.
* Contribution: Leaded the group. Designed the framework and downloading strategies. Implemented the file generation and data visualization.
