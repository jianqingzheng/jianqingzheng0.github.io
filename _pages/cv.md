---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* <i>Imperial College London</i>, 2017-2018
  * <b>M.Res. in Medical Robotics & Image Guide Intervention</b>
  * Distinction, GPA: 77%
* <i>University of Liverpool</i>, 2015-2017
  * <b>B.Eng. (Hons) in Electrical and Eletctronic Engineering</b>
  * 1st Class Honours, GPA: 78%
* <i>Xi'an Jiaotong-Liverpool University</i>, 2013-2015
  * <b>B.Eng. in Telecommunication Engineering</b>

Awards
======
* <b>£6000 Bursary</b>, <i>The Hamlyn Centre for Robotic Surgery, Imperical College London</i>, 2017
* <b>Honourable Mention</b>, Interdisciplinary Contests in Modelling, <i>COMAP</i>, 2015
* <b>Outstanding Student</b>, <i>Xi'an Jiaotong-Liverpool University</i>, 2015
* <b>Second Prize Winner</b>, Mathematical Contest in Modelling, <i>Xi'an Jiaotong-Liverpool University</i>, 2014
* <b>Accomplished Competitor</b>, University Physics Competition, <i>American Physical Society</i>, 2014
* <b>Excellent Student</b>, <i>Xi'an Jiaotong-Liverpool University</i>, 2013

Research and Thesis
======
* 2018 <b>Real-time 3D Path Planning from a Single Fluoroscopic Image for Robot Assisted Fenestrated Endovascular Aortic Repair (FEVAR)</b>
  * Segmented Abdominal Aortic Aneurysm (AAA) using U-Net with data augmentation of gray value variation instead of rotation and mirroring to avoid overfitting caused by relatively small intra-subject variation of intensity and translation. Extracted the largest connected area from the segmented volume and reconstruct the 3D AAA shape using marching cube. Extracted the centrelines of AAA from CTA and fluoroscopy image. Establish the correspondence between the 3D preoperative and 2D intra-operative AAA skeletons using a proposed graph matching method. Deformed the 3D skeletons using thin plate spline with regularization in respect to skeleton length and smoothness to implement the deformable 2D/3D registration. Validate the proposed framework on simulation, phantom and patient AAA data sets, achieving 3D distance error of 2mm in the phantom setup. Obtained also performance advantages in terms of accuracy, robustness and time-efficiency.
  
* 2018 <b>High-resolution Feature Map Propagation in Deep Convolutional Neural Network</b>
  * Theoretically analysed the receptive field (RF) with dilated (atrous) rate setting and the truncation effect. Obtained and proved a general solution of atrous rate setting for a uniform distributed RF while large and fully covered RF guaranteed. Proposed a novel network, Atrous Convolutional Neural Network (ACNN) with skip connections and multi-scale consideration as an example for semantic segmentation. Validated ACNN on three bio-medical datasets with high-resolution feature map propagation and reasonable segmentation results, reducing the number of variables by 99.75%, and achieving a reasonable DSC of 0.6~0.7.

* 2017 <b>Brain-Computer Interface Framework for NAO Robot</b>
  * Removed the artefacts caused by electromyography and electrooculography from electroencephalograph (EEG) signals using Wavelet Analysis. Extracted the features of the EEG signals using Common Spatial Pattern filter. Used Linear Discriminant Analysis, Support Vector Machine, Convolutional Neural Network and RNN to classified two (and three) kinds of imaginary motion. Transmitted classified data to the second computer with SSH protocol by Python-Socket for real-time control of one NAO robot out of a maze. Implemented colourized boundary distance measurement using histogram equalization to enhance contrast, a Laplacian filter to detect edge and a homogeneous transformation to reconstruct the 3-D coordinates.

* 2016 <b>Load Frequency Control of a Smart Grid</b>
  * Built a model of Load Frequency Control and Direct Load Control in a multi-area power system. Decoupled frequency of each area by solving an equivalent optimization problem of minimizing flow network. Utilized direct controlled load to improve the efficiency and stability of the power system.

* 2016 <b>Smartphone Download-Management System</b>
  * Built a model of Wi-Fi and 3G data transmissions using MATLAB. Simulated a process of file generation and downloads to optimize the downloading process. Designed strategies for priority ranking, and optimized loss functions. Implemented the data dynamic visualization of download values and download size for different strategies. Quantified the performance of each strategy according to the size and value of downloaded documents, tested the simulation in multiple internet environments, and selected the optimal strategies for most cases.

* 2015 <b>Image Mosaic of Unmanned Aerial Vehicle</b>
  * Implemented noise reduction using a Wiener filter. Utilized the random sample consensus algorithm to registry images based on feature points extracted by the Scale-Invariant Feature Transform in MATLAB. Applied weighted averaging to image fusion. Completed a MATLAB program that implemented an automatic image mosaic for given photos.

Work experience
======
* 2018 <b>Research Assistant</b>, <i>Imperial College London</i>
  * Studying on the shape instantiation of partially-deployed stent-graft and the prediction of fully- deployed stent-graft from a fluoroscopy for navigation in robot-assisted Fenestrated Endovascular Aortic Repair (FEVAR).

* 2017 <b>Technical Development and Algorithm Design Intern</b>, <i>AlgoLib Ltd</i>.
  * Designed a recursive enumeration algorithm and combined it with dynamic programming to find the products’ prices using the longest increasing period. Obtained step matrices using dynamic programming to search the longest common subarray of increasing natural numbers in the issue-date array of the sorted prices. Cut processing time down from 8 hours using the company’s original traversing algorithm to 30 minutes with the designed algorithm. Additionally, applied ARIMA and ARFIMA and Recurrent Neural Network (RNN) to fit previous prices and predict future prices in Python.
  
Skills
======
* <b>Languages</b>
  * Mandarin (Native), English (Fluent)
* <b>Computer</b>
  * MATLAB, Python, C, C++, AHDL

Publications
======
## <i>Conference</i>
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
## <i>Patent</i>
  <ul>{% for post in site.patent %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
