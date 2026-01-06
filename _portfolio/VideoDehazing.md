---
title: "Video Dehazing Demo"
excerpt: "we present a frequency-aware video dehazing framework built upon State Space Models (SSM)<br/><img src='/images/demo.gif'>"
collection: portfolio
---

In this work, we present a frequency-aware video dehazing framework built upon State Space Models (SSM), which leverage linear-time sequence modeling with recursive hidden states to establish implicit spatio-temporal dependencies, thereby avoiding costly motion estimation. To better separate haze degradation from structural details, we incorporate wavelet decomposition for frequency-domain decoupling: low-frequency components are restored with strong temporal modeling, while high-frequency components preserve fine textures and edges. 
<br/><img src='/images/demo.gif'>
<br/>This is the pipline:
<br/><img src='/images/video_dehaze_framework.png'>
