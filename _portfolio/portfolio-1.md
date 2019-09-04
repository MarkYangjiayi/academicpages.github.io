---
title: "Large Kernel Spatial Pyramid Pooling for Image Segmentation"
excerpt: "Short description of portfolio item number 1<br/><img src='/images/500x300.png'>"
collection: portfolio
---

<p>Semantic Segmentation has been one of the core techniques of remote sensing image application. Through pixel-wise segmentation, we can have a whole idea of the objects contained in the remote sensing images, and provide foundation of further object detection, and high level segmentation extraction. Early semantic segmentations choose to use traditional machine learning algorithms, but with the development of neural networks and fully convoluted networks(FCN), using deep learning often have much better results than traditional methods.</p>
<p>Compared with natural image processing, remote sensing image segmentation has the following problems:</p>
<ul><li><p>Remote sensing Images often has large size with abundant information. This brings the problem of cropping and regeneration of images.</p></li></ul>
<ul><li><p>Remote Sensing Images often has more channels compared to 3 channels in original images</p></li></ul>
<ul><li><p>The complexity brought by the earth components, properties and distribution may result in different object with similar appearance and same object with different appearance</p></li></ul>
<p>Based on these properties of remote sensing images, we designed a new network component based on google’s Atrous Spatial Pyramid Pooling, which we name it as Large Kernel Spatial Pyramid Pooling. The idea of this component is to use “Large Kernel” component to extract precise feature to avoid the grid effect brought by Atrous Convolution. At the same time, Spatial Pyramid Pooling can extract multi-scale features.</p>
<br>
<a href="https://news.bupt.edu.cn/info/1014/18997.htm">News Page</a>
