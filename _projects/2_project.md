---
layout: page
title: Image Segmentation
description: Image segmentation using initialization techniques + K-means clustering algorithm
img: assets/img/p1_1.jpg
importance: 1
category: work
giscus_comments: true
---

Image segmentation is the classification of an image into different groups. Here we have use k-means clustering algorithm for image segmentation.K -means clustering algorithm is an unsupervised algorithm and it is used to segment the interest area from the background. But before applying K -means algorithm, first partial stretching enhancement is applied to the image to improve the quality of the image. Next, Initialization techniques like subtractive clustering, kmeans++, random initialization is used to generate the initial centers and these centers are used in k-means algorithm for the segmentation of image. Then finally medial filter is applied to the segmented image to remove any unwanted region from the image.
 
Our main idea is to segment the image using kmeans from scratch.This project can further be used in many areas like medical analysis , image detection , image extraction,etc.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/P1_1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Image segmentation
</div>


