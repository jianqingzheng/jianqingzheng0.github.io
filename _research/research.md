---
layout: archive
title: "Research and Thesis"
collection: research
author_profile: true
permalink: /research/ 
---

---

## Individual Project

### <b>Real-time 3D Path Planning from a Single Fluoroscopic Image for Robot Assisted Fenestrated Endovascular Aortic Repair (FEVAR)</b>
* 2018, _Imperial College London, London, UK_
<h3><a href="javascript:void(0)" class="dsphead" onclick="dsp(this)"><span class="dspchar">+</span> Detail</a></h3>
<div class="dspcont" style='display:none;'>
  <fieldset>
  <ul>
    <li><b>Motivation</b>: To navigate robot-assisted fenestrated endovascular aortic repair.</li>
    <li><b>Pipeline</b>: Segmented Abdominal Aortic Aneurysm (AAA) using U-Net with data augmentation of grey value variation instead of rotation and mirroring to avoid overfitting caused by relatively small intra-subject variation of intensity and translation. Extracted the largest connected area from the segmented volume and reconstruct the 3D AAA shape using marching cube. Extracted the centrelines of AAA from CTA and fluoroscopy image. Establish the correspondence between the 3D preoperative and 2D intra-operative AAA skeletons using a proposed graph matching method. Deformed the 3D skeletons using thin plate spline with regularization in respect to skeleton length and smoothness to implement the deformable 2D/3D registration. Validate the proposed framework on simulation, phantom and patient AAA data sets, achieving 3D distance error of 2mm in the phantom setup. Obtained also performance advantages in terms of accuracy, robustness and time-efficiency.
</li>
    <li>[<u><a href="https://jianqingzheng.github.io/publication/HSMR2018-abdominal_zheng">publication</a></u>]</li>
  </ul>
  <br/>
  <img src='/images/aaaseg2d_2.gif' />
  <img src='/images/aaaseg3d.png' />
  </fieldset>
</div>

### <b>Load Frequency Control of a Smart Grid</b>
* 2016, _University of Liverpool, Liverpool, UK_
* __Motivation__: To investigate on the potential usage of direct load control in load frequency control of a smart grid.
* __Pipeline__: Built a mathematical model and the simulated one of Load Frequency Control and Direct Load Control in a multi-area power system. Decoupled frequency of each area by solving an equivalent optimization problem of minimizing flow network. Utilized direct controlled load to improve the efficiency and stability of the power system and validated the results with simulation.

### <b>Capacitive Touch Sensing Device</b>
* 2015, _Wuhan University, Wuhan, CN_
* __Motivation__: To design and develop a capacitive touch sensing module used in toys.
* __Pipeline__: Designed a printed circuit board and the coniguration of capacitance sensor and the sensing circuit. Analyzed electromagnetic coupling. Added an identification wire to each connected signal wire to compensate for current errors caused by the stray capacitances and parasitic capacitances between the connected wires and ground wire. Applied logic circuits to filter fake signals triggered by noise.

### <b>Image Mosaic of Unmanned Aerial Vehicle</b>
* 2015, _Xi’an Jiaotong-Liverpool University, Suzhou, CN_
* __Motivation__: To implement an automatic program for image mosaic for a unmanned aerial vehicle.
* __Pipeline__: Implemented noise reduction using a Wiener filter. Utilized the random sample consensus algorithm for image registration based on feature points extracted by the Scale-Invariant Feature Transform in MATLAB. Applied weighted averaging to image fusion. Completed a MATLAB program that implemented an automatic image mosaic for given photos.

---

## Collaborated Project

### <b>High-resolution Feature Map Propagation in Deep Convolutional Neural Network</b>
* 2018, _Imperial College London, London, UK_
* __Motivation__: To investigate on the effect of atrous rate on receptive field in a deep convolutional neural network and to improve the resolution of feature maps and the efficiency of the network.
* __Pipeline__: Theoretically analysed the receptive field (RF) with dilated (atrous) rate setting and the truncation effect. Obtained and proved a general solution of atrous rate setting for a uniform distributed RF while large and fully covered RF guaranteed. Proposed a novel network, Atrous Convolutional Neural Network (ACNN) with skip connections and multi-scale consideration as an example for semantic segmentation. Validated ACNN on three bio-medical datasets with high-resolution feature map propagation and reasonable segmentation results, reducing the number of variables by 99.75%, and achieving a reasonable DSC of 0.6~0.7.
* __Contribution__: Theoretical analysed and simulated the effect of atrous rate on the receptive field, and the truncation effect. Processed data and evaluated segmentation results.

### Estimation of Tissue Oxygen Saturation from RGB Images based on Pixel-level Image Translation
* 2018, _Imperial College London, London, UK_
* __Motivation__: To estimate tissue oxygen saturation directly from RGB images without hyperspectral images for a seamless integration of the proposed method into surgical and diagnostic workflows with standard endoscope systems.
* __Pipeline__: Simulated RGB images and calculated the oxygen saturation from given hyperspectral images. Augmented data by flipping and cropping with a slide-window. Fed the simulated RGB images and the calculated oxygen saturation to train a conditional Generative Adversarial Network (cGAN). Estimated tissue oxygen using pixel-level image-to-image translation by cGAN. Evaluated prediction results using with different batch size and weight coefficient.
* __Contribution__: Programed data processing and data augmentation.

### <b>Brain-Computer Interface Framework for NAO Robot</b>
* 2017, _Imperial College London, London, UK_
* __Motivation__: To build a brain-computer interface network with electroencephalograph signals for robot control.
* __Pipeline__: Removed the artefacts caused by electromyography and electrooculography from electroencephalograph (EEG) signals using Wavelet Analysis. Extracted the features of the EEG signals using Common Spatial Pattern (CSP) filter. Used Linear Discriminant Analysis (LDA), Support Vector Machine (SVM), Convolutional Neural Network (CNN) and Recurrent Neural Network (RNN) to classified two kinds of imaginary motion. Transmitted classified data to the second computer with SSH protocol by Python-Socket for real-time control of one NAO robot. Implemented colourized boundary distance measurement using histogram equalization to enhance contrast, a Laplacian filter to detect edge and a homogeneous transformation to reconstruct the 3-D coordinates. Controlled a NAO robot to walk out of a maze with EEG.
* __Contribution__: Optimized the algorithm of artefact removal. Extracted feature using CSP filter. Classified EEG signal using LDA in MATLAB and OpenVibe as well as kernel SVM in OpenVibe. Transmitted classified data with SSH. 

### <b>Smartphone Download-Management System</b>
* 2016, _University of Liverpool, Liverpool, UK_
* __Motivation__: To investigate on management strategies of file downloading in a smartphone.
* __Pipeline__: Built a model of Wi-Fi and 3G data transmissions using MATLAB. Simulated a process of file generation and downloads to optimize the downloading process. Designed strategies for priority ranking, and optimized loss functions. Implemented the data dynamic visualization of download values and download size for different strategies. Quantified the performance of each strategy according to the size and value of downloaded documents, tested the simulation in multiple internet environments, and selected the optimal strategies for most cases.
* __Contribution__: Leaded the group. Designed the framework and downloading strategies. Implemented the file generation and data visualization.

### Big Data Challenge, Interdisciplinary Contest in Modeling, COMAP
* 2015, _Xi’an Jiaotong-Liverpool University, Suzhou, CN_
* __Motivation__: To quantify and optimize the investment strategies to universities with a large dataset.
* __Pipeline__: Replaced outlier and missing data using linear interpolation and averaging. Reduced the dimensions of the feature space with principal component analysis. Fitted a characteristic curve of investment and performance indexes weighted according to the result of the PCA using a Back-Propagation Neural Network (BP-NN). Utilized the Stochastic Gradient Descent method to minimize the cost function based on the Euclidean distance with various, random initial points.
* __Contribution__: Programed data pre-processing including normalization, data cleaning, as well as dimension reduction. Implemented BP-NN and optimization using MATLAB toolbox.
