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
* Imperial College London, 2017-2018
  * M.Res. in Medical Robotics & Image Guide Intervention
  * Distinction, GPA: 77%
* University of Liverpool, 2015-2017
  * B.Eng. (Hons) in Electrical and Eletctronic Engineering
  * 1st Class Honours, GPA: 78%
* Xi'an Jiaotong-Liverpool University, 2013-2015
  * B.Eng. in Telecommunication Engineering

Awards
======
* £6000 Bursary, The Hamlyn Centre for Robotic Surgery, Imperical College London, 2017
* Honourable Mention, Interdisciplinary Contests in Modelling, COMAP, 2015
* Outstanding Student (Top 3%), Xi'an Jiaotong-Liverpool University, 2015
* Second Prize Winner, Mathematical Contest in Modelling, Xi'an Jiaotong-Liverpool University, 2014
* Accomplished Competitor, University Physics Competition, American Physical Society, 2014
* Excellent Student, Xi'an Jiaotong-Liverpool University, 2013

Research and Thesis
======
*Real-time 3D Path Planning from a Single Fluoroscopic Image for Robot Assisted Fenestrated Endovascular Aortic Repair (FEVAR)
  *Segmented Abdominal Aortic Aneurysm (AAA) using U-Net with data augmentation of gray value variation instead of rotation and mirroring to avoid overfitting caused by relatively small intra-subject variation of intensity and translation. Extracted the largest connected area from the segmented volume and reconstruct the 3D AAA shape using marching cube. Extracted the centrelines of AAA from CTA and fluoroscopy image. Establish the correspondence between the 3D preoperative and 2D intra-operative AAA skeletons using a proposed graph matching method. Deformed the 3D skeletons using thin plate spline with regularization in respect to skeleton length and smoothness to implement the deformable 2D/3D registration. Validate the proposed framework on simulation, phantom and patient AAA data sets, achieving 3D distance error of 2mm in the phantom setup. Obtained also performance advantages in terms of accuracy, robustness and time-efficiency.

Work experience
======
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
