---
layout: project
type: project
image: images/cell_segmentation_card.jpg
title: Deep learning Segmentation
permalink: projects/cell-segmentation
# All dates must be YYYY-MM-DD format!
date: 2016-12-16
labels:
  - Deep Learning
  - Caffe
  - Python
summary: A project to segment cells in colon tissue images using deep convolutional neural network techniques. Whis was supported by the European Commission under the Erasmus+ programme at Budapest, Hungary.
---

<div class="ui small rounded images">
  <img class="ui image" src="https://raw.githubusercontent.com/matiaszilli/cellSegmentation/master/Results/Example%201/img.jpg">
  <img class="ui image" src="https://raw.githubusercontent.com/matiaszilli/cellSegmentation/master/Results/Example%201/prob.jpg">
  <img class="ui image" src="https://raw.githubusercontent.com/matiaszilli/cellSegmentation/master/Results/Example%201/result.jpg">
  <img class="ui image" src="https://raw.githubusercontent.com/matiaszilli/cellSegmentation/master/Newspaper.jpg">
</div>

In this work, I propose a supervised deep learning-based model for accurate automatic cell nuclei segmentation. Given a tissue image, it begins with a deep convolutional neural network model to generate a probability map. Next, a threshold and morphological operations are applied to distinguish the background and the cells.  

One of the significant benefits of the proposed method is that it can be applicable to different staining histopathology images taken of different patients. Due to the feature learning characteristic of deep convolutional neural network and the high level shape prior modeling, the proposed method is general enough to work properly across different image scenario like healthy, adenoma, hyperplasia.  

Finally, I validated the proposed algorithm on several histopathology images using a range of different tissue from various patients with differents diseases.  

This project was recognized in 2017 as one of the most important projects between Argentina and Hungary by FICH - Universidad Nacional del Litoral, and it allowed to start a collaboration between both countries. You can see the newspaper article [Here](https://raw.githubusercontent.com/matiaszilli/cellSegmentation/master/Newspaper.jpg) or get into the full newspaper [Here](https://www.unl.edu.ar/noticias/products/view/el_paraninfo_131_1).

Source and full text: <a href="https://github.com/matiaszilli/cellSegmentation"><i class="large github icon"></i>matiaszilli/cellSegmentation</a>



