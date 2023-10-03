---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

## About Me

Hi, this is Zheng Dong. I am a 5th-year (2019~) Ph.D. student in the State Key Laboratory of CAD&CG, Zhejiang University, advised by Prof. [Weiwei Xu](http://www.cad.zju.edu.cn/home/weiweixu/weiweixu_en.htm). My research focuses on **human-centric 3D vision** and **2D image processing**, including image-based 3D human reconstruction, human volumetric capture, 2D image reflection removal, etc.

**E-mail**: zhengdong AT zju.edu.cn

**Resume**: [[resume.pdf]](./files/resume.pdf)

<span class='anchor' id='background' style="padding-top:10px"></span>

## Background

<img align="left" width="90" height="90" src="./images/zju-logo.png" style="padding-right:20px; padding-top:0px"/>

**Ph.D. Student. Sep. 2019 - Jun. 2024 (Expected)**<br>
[State Key Laboratory of CAD&CG](http://www.cad.zju.edu.cn/index.html)<br>
[Zhejiang University](http://www.zju.edu.cn)<br>

---

<img align="left" width="90" height="90" src="./images/csu-logo.png" style="padding-right:20px; padding-top:0px"/>

**Bachelor of Computer Science. Sep. 2015 - Jun. 2019**<br>
[School of Computer Science and Engineering](https://cse.csu.edu.cn/index.htm)<br>
[Central South University](https://www.csu.edu.cn/)<br>

<span class='anchor' id='publications' style="padding-top:5px"></span>

## Publications 

<img align="left" width="280" height="140" src="./images/papers/siga23-sailor.png" style="padding-right:20px; padding-top:0px"/>

<b>SAILOR: Synergizing Radiance and Occupancy Fields for Live Human Performance Capture</b><br>
<b>Zheng Dong</b>, Ke Xu, Yaoan Gao, Qilin Sun, Hujun Bao, Weiwei Xu, Rynson W.H. Lau<br>
ACM Trans. on Graphics, 42(6), (Proc. ACM **SIGGRAPH Asia** 2023)<br>
[<i class="fas fa-fw fa-globe"></i>Project]() /
[<i class="fas fa-fw fa-file-pdf"></i>Paper](./files/papers/sailor.pdf) /
[<i class="fas fa-fw fa-video"></i>Video](https://www.youtube.com/watch?v=88tX22Z0Dz0) /
[<i class="fab fa-fw fa-github"></i>Github](https://github.com/zdlarr/SAILOR)<br>
*SAILOR is a generalizable method for human free-view rendering and reconstruction from very sparse (*e.g.*, 4) RGBD streams, achieving near real-time performance under acceleration.*

---

<img align="left" width="280" height="140" src="./images/papers/nips22-gtpifu.png" style="padding-right:20px; padding-top:0px"/>

<b>Geometry-aware Two-scale PIFu Representation for Human Reconstruction</b><br>
<b>Zheng Dong</b>, Ke Xu, Ziheng Duan, Hujun Bao, Weiwei Xu, Rynson W.H. Lau<br>
Annual Conference on Neural Information Processing Systems (**NeurIPS**) 2022 (<b>Spotlight</b>)<br>
[<i class="fas fa-fw fa-globe"></i>Project](https://sites.google.com/view/twoscale) /
[<i class="fas fa-fw fa-file-pdf"></i>Paper](./files/papers/gtpifu.pdf) /
[<i class="fas fa-fw fa-video"></i>Video](https://www.youtube.com/watch?v=K6Dx6-jJ-S4&t=6s) /
[<i class="fas fa-fw fa-file-pdf"></i>OpenReview](https://openreview.net/forum?id=yqVWRZ3gfmg)<br>
*The geometry-aware two-scale PIFu is a method to address the problem of PIFu-based approaches that reconstruct flat facial and geometry-fallible bodies in a sparse capture setting.*

---

<img align="left" width="280" height="140" src="./images/papers/iccv21-larr.png" style="padding-right:20px; padding-top:0px"/>

<b>Location-aware Single Image Reflection Removal</b><br>
<b>Zheng Dong</b>, Ke Xu, Yin Yang, Hujun Bao, Weiwei Xu, Rynson W.H. Lau<br>
International Conference on Computer Vision (**ICCV**) 2021 <br>
[<i class="fas fa-fw fa-file-pdf"></i>Paper](./files/papers/larr.pdf) /
[<i class="fas fa-fw fa-video"></i>Video](https://www.youtube.com/watch?v=O5F20FLRrsw) /
[<i class="fab fa-fw fa-github"></i>Github](https://github.com/zdlarr/Location-aware-SIRR)<br>
*LARR leverages the Laplacian kernel to emphasize the boundaries of strong reflections, and incorporates a recurrent network to refine reflection removal results at each iteration.*

<span class='anchor' id='distinctions'></span>

## Distinctions

Excellent Postgraduate Student Award, Zhejiang University (**2020, 2022-2023**)

Outstanding Graduate Student, Central South University (**2019**)

National Scholarship, Central South University (**2016**)

<span class='anchor' id='academic-service'></span>

## Academic Service

**Reviewer**: IJCV, CVPR, CAVW, etc

