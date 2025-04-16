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

## Brief Intro.

Zheng Dong is currently a research fellow (特聘研究员) at Zhejiang Sci-Tech University. He received his Ph.D. Degree in computer vision and graphics from the State Key Laboratory of CAD&CG, Zhejiang University, under the supervision of Prof. [Weiwei Xu](http://www.cad.zju.edu.cn/home/weiweixu/weiweixu_en.htm) (Zhejiang University) and Prof. [Rynson W.H. Lau](https://www.cs.cityu.edu.hk/~rynson/) (City University of Hong Kong). His research interests lie in **human-centric 3D/4D vision** and **2D image processing**, with a focus on image-based 3D human reconstruction, dynamic human-scene modeling, and reflection/flare removal in 2D images, among others.

**E-mail**: zhengdong AT zstu.edu.cn / zju.edu.cn

**WeChat**: -zhengdong-

**Resume**: [[resume.pdf]](./files/resume.pdf)

<span class='anchor' id='academic-service'></span>

## Academic Service

**Reviewer**: SIGGRAPH, CVPR, ICCV, NeurIPS, IJCV, TVCG, CAVW, etc

<span class='anchor' id='background' style="padding-top:10px"></span>

## Background

<img align="left" width="86" height="86" src="./images/zstu-logo.png" style="padding-right:20px; padding-top:0px"/>

**Researcher | Apr. 2025 - Present**<br>
[School of Artificial Intelligence](https://scst.zstu.edu.cn/)<br>
[Zhejiang Sci-Tech University (浙江理工大学)](https://www.zstu.edu.cn/)<br>

---

<img align="left" width="90" height="90" src="./images/zju-logo.png" style="padding-right:20px; padding-top:0px"/>

**Ph.D. Degree in Computer Vision and Graphics | Sep. 2019 - Mar. 2025**<br>
[State Key Laboratory of CAD&CG](http://www.cad.zju.edu.cn/index.html)<br>
[Zhejiang University (浙江大学)](http://www.zju.edu.cn)<br>

---

<img align="left" width="90" height="90" src="./images/csu-logo.png" style="padding-right:20px; padding-top:0px"/>

**Bachelor of Computer Science | Sep. 2015 - Jun. 2019**<br>
[School of Computer Science and Engineering](https://cse.csu.edu.cn/index.htm)<br>
[Central South University (中南大学)](https://www.csu.edu.cn/)<br>

<span class='anchor' id='publications' style="padding-top:5px"></span>

## Publications 

<img align="left" width="280" height="140" src="./images/papers/siga24.png" style="padding-right:20px; padding-top:0px"/>

<b>Gaussian Surfel Splatting for Live Human Performance Capture</b><br>
<b>Zheng Dong</b>, Ke Xu, Yaoan Gao, Hujun Bao, Weiwei Xu, Rynson W.H. Lau<br>
ACM Trans. on Graphics, 43(6), (Proc. ACM <b>SIGGRAPH Asia</b> 2024)<br>
[<i class="fas fa-fw fa-globe"></i>Project](https://zdlarry.github.io/projects/GSSHuman) /
[<i class="fas fa-fw fa-file-pdf"></i>Paper](./files/papers/gsshuman.pdf) /
[<i class="fas fa-fw fa-video"></i>Video](https://www.youtube.com/watch?v=MGIlBT_JZNk) /
<i class="fab fa-fw fa-github"></i>Github<br>
*We propose a novel regressed-surface-point-based method, to leverage Gaussian surfel splatting and blending-based appearance enhancement, for human live free-view rendering from 4 RGBD sensors.*

---

<img align="left" width="280" height="140" src="./images/papers/siga23-sailor.png" style="padding-right:20px; padding-top:0px"/>

<b>SAILOR: Synergizing Radiance and Occupancy Fields for Live Human Performance Capture</b><br>
<b>Zheng Dong</b>, Ke Xu, Yaoan Gao, Qilin Sun, Hujun Bao, Weiwei Xu, Rynson W.H. Lau<br>
ACM Trans. on Graphics, 42(6), (Proc. ACM <b>SIGGRAPH Asia</b> 2023)<br>
[<i class="fas fa-fw fa-globe"></i>Project](https://zdlarry.github.io/projects/SAILOR) /
[<i class="fas fa-fw fa-file-pdf"></i>Paper](./files/papers/sailor.pdf) /
[<i class="fas fa-fw fa-video"></i>Video](https://www.youtube.com/watch?v=88tX22Z0Dz0) /
[<i class="fab fa-fw fa-github"></i>Github](https://github.com/zdlarr/SAILOR)<br>
*SAILOR is a generalizable method for human free-view rendering and reconstruction from very sparse (*e.g.*, 4) RGBD streams, achieving near real-time performance under acceleration.*

---

<img align="left" width="280" height="140" src="./images/papers/nips22-gtpifu.png" style="padding-right:20px; padding-top:5px"/>

<b>Geometry-aware Two-scale PIFu Representation for Human Reconstruction</b><br>
<b>Zheng Dong</b>, Ke Xu, Ziheng Duan, Hujun Bao, Weiwei Xu, Rynson W.H. Lau<br>
Annual Conference on Neural Information Processing Systems (**NeurIPS**) 2022 (<font color="#dd0000"><b>Spotlight</b></font>)<br>
[<i class="fas fa-fw fa-globe"></i>Project](https://sites.google.com/view/twoscale) /
[<i class="fas fa-fw fa-file-pdf"></i>Paper](./files/papers/gtpifu.pdf) /
[<i class="fas fa-fw fa-video"></i>Video](https://www.youtube.com/watch?v=K6Dx6-jJ-S4&t=6s) /
[<i class="fas fa-fw fa-file-pdf"></i>OpenReview](https://openreview.net/forum?id=yqVWRZ3gfmg)<br>
*The geometry-aware two-scale PIFu is a method to address the problem of PIFu-based approaches that reconstruct flat facial and geometry-fallible bodies in a sparse capture setting.*

---

<img align="left" width="280" height="140" src="./images/papers/iccv21-larr.png" style="padding-right:20px; padding-top:10px"/>

<b>Location-aware Single Image Reflection Removal</b><br>
<b>Zheng Dong</b>, Ke Xu, Yin Yang, Hujun Bao, Weiwei Xu, Rynson W.H. Lau<br>
International Conference on Computer Vision (**ICCV**) 2021<br>
[<i class="fas fa-fw fa-file-pdf"></i>Paper](./files/papers/larr.pdf) /
[<i class="fas fa-fw fa-file-pdf"></i>Supp.](./files/papers/larr_supp.pdf) /
[<i class="fas fa-fw fa-video"></i>Video](https://www.youtube.com/watch?v=O5F20FLRrsw) /
[<i class="fab fa-fw fa-github"></i>Github](https://github.com/zdlarr/Location-aware-SIRR)<br>
*LARR leverages the Laplacian features to regress probabilistic reflection conﬁdence maps, and incorporates a recurrent network to refine reflection removal results at each iteration.*

<span class='anchor' id='distinctions'></span>

## Distinctions

Outstanding Graduate Student，Zhejiang University (**2025**)，浙江大学优秀毕业生

Excellent Postgraduate Student Award, Zhejiang University (**2020, 2022-2023**)，浙江大学优秀研究生

Outstanding Graduate Student, Central South University (**2019**)，中南大学优秀毕业生

National Scholarship, Central South University (**2016**)，国家奖学金

<br />

