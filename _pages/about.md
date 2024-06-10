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

I received my Ph.D. from Aerospace Information Research Institute, Chinese Academy of Sciences, Beijing, China, in June 2024, advised by Prof. [Qingyan Meng](https://aircas.cas.cn/sourcedb/cn/expert/yjy/201811/t20181106_5165284.html). From 2021 to 2023, I was a Visiting Ph.D. Student at [RSlab](https://rslab.disi.unitn.it/), University of Trento, Trento, Italy, advised by Prof. [Lorenzo Bruzzone](https://rslab.disi.unitn.it/people/#LorenzoBruzzone).
My research interests include remote sensing image analysis, deep learning, and urban remote sensing.
<!--
My research interest includes neural machine translation and computer vision. 
I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->


# 🔥 News
- *2022.04*: &nbsp;🎉 One co-authored paper has been accepted by JAG ([link](https://www.sciencedirect.com/science/article/pii/S1569843224001523))!
- *2022.04*: &nbsp;🎉 One co-authored paper has been accepted by TGRS ([link](https://ieeexplore.ieee.org/abstract/document/10496710))!
- *2022.03*: &nbsp;🎉 One paper has been accepted by RSE ([link](https://www.sciencedirect.com/science/article/abs/pii/S0034425724001238))!
- *2022.03*: &nbsp;🎉 One paper has been accepted by TGRS ([link](https://ieeexplore.ieee.org/abstract/document/10476394))!
- *2022.02*: &nbsp;🎉 One co-authored paper has been accepted by JAG ([link](https://www.sciencedirect.com/science/article/pii/S1569843224000505))!

# 📝 Publications 
## Selected 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RSE 2024</div><img src='images/rse2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards robust classification of multi-view remote sensing images with partial data availability](https://www.sciencedirect.com/science/article/pii/S0034425724001238?via%3Dihub)

**Maofan Zhao**, Qingyan Meng, Lifeng Wang, Linlin Zhang, Xinli Hu, Wenxu Shi

[**Paper**](https://www.sciencedirect.com/science/article/pii/S0034425724001238?via%3Dihub) | [**Code**](https://github.com/mfzhao1998/multi_view_incomplete_learning) 
- Propose a unified model to handle both complete views and missing view 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TGRS 2024</div><img src='images/tgrs2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Beyond Pixel-Level Annotation: Exploring Self-Supervised Learning for Change Detection With Image-Level Supervision](https://ieeexplore.ieee.org/abstract/document/10476394)

**Maofan Zhao**, Xinli Hu, Linlin Zhang, Qingyan Meng, Yuxing Chen, Lorenzo Bruzzone

[**Paper**](https://ieeexplore.ieee.org/abstract/document/10476394) | [**Code**](https://github.com/mfzhao1998/WSLCD)
- Construct a weakly supervised learning (WSL) framework based on image-level labels for general change detection 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TGRS 2023</div><img src='images/tgrs2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Local and Long-Range Collaborative Learning for Remote Sensing Scene Classification](https://ieeexplore.ieee.org/document/10093899)

**Maofan Zhao**, Qingyan Meng, Linlin Zhang, Xinli Hu, Lorenzo Bruzzone

[**Paper**](https://ieeexplore.ieee.org/document/10093899)  
- Propose a local and long-range collaborative framework (L2RCF) for remote sensing scene classification that can fully collaborates CNNs and vision transformers 
</div>
</div>

## 2024 
- [Towards robust classification of multi-view remote sensing images with partial data availability](https://www.sciencedirect.com/science/article/pii/S0034425724001238?via%3Dihub),  **Maofan Zhao**, Qingyan Meng, Lifeng Wang, Linlin Zhang, Xinli Hu, Wenxu Shi, *Remote Sensing of Environment (RSE)*, 2024

- [Beyond Pixel-Level Annotation: Exploring Self-Supervised Learning for Change Detection With Image-Level Supervision](https://ieeexplore.ieee.org/document/10476394), **Maofan Zhao**,  Xinli Hu, Linlin Zhang, Qingyan Meng, Yuxing Chen, Lorenzo Bruzzone, *IEEE Transactions on Geoscience and Remote Sensing (TGRS)*, 2024
  
- [A deep learning framework for 3D vegetation extraction in complex urban environments](https://www.sciencedirect.com/science/article/pii/S1569843224001523?via%3Dihub), Jiahao Wu, Qingyan Meng, Liang Gao, Linlin Zhang, **Maofan Zhao**, Chen Su, *International Journal of Applied Earth Observation and Geoinformation (JAG)*, 2024
  
- [A Novel Approach to Incomplete Multimodal Learning for Remote Sensing Data Fusion](https://ieeexplore.ieee.org/document/10496710), Yuxing Chen, **Maofan Zhao**, Lorenzo Bruzzone, *IEEE Transactions on Geoscience and Remote Sensing (TGRS)*, 2024

- [A multimodal fusion framework for urban scene understanding and functional identification using geospatial data](https://www.sciencedirect.com/science/article/pii/S1569843224000505?via%3Dihub), Chen Su, Xinli Hu, Qingyan Meng, Linlin Zhang, Wenxu Shi, **Maofan Zhao**, *International Journal of Applied Earth Observation and Geoinformation (JAG)*, 2024

## 2023 
- [Local and Long-Range Collaborative Learning for Remote Sensing Scene Classification](https://ieeexplore.ieee.org/document/10093899), **Maofan Zhao**, Qingyan Meng, Linlin Zhang, Xinli Hu, Lorenzo Bruzzone, *IEEE Transactions on Geoscience and Remote Sensing (TGRS)*, 2023

## 2022 
- [Multilayer Feature Fusion Network With Spatial Attention and Gated Mechanism for Remote Sensing Scene Classification](https://ieeexplore.ieee.org/document/9770786),  Qingyan Meng, **Maofan Zhao#**, Linlin Zhang, Wenxu Shi, Chen Su, Lorenzo Bruzzone, *IEEE Geoscience and Remote Sensing Letters (GRSL)*, 2022
  
- [DSANet: A Deep Supervision-Based Simple Attention Network for Efficient Semantic Segmentation in Remote Sensing Imagery](https://www.mdpi.com/2072-4292/14/21/5399), Wenxu Shi, Qingyan Meng, Linlin Zhang, **Maofan Zhao**, Chen Su, Tamás Jancsó, *Remote Sensing (RS)*, 2022
  
- [How do urban morphological blocks shape spatial patterns of land surface temperature over different seasons? A multifactorial driving analysis of Beijing, China](https://www.sciencedirect.com/science/article/pii/S030324342100355X?via%3Dihub), Die Hu, Qingyan Meng, Uwe Schlink, Daniel Hertel, Wenxiu Liu, **Maofan Zhao**, Fengxiang Guo, *International Journal of Applied Earth Observation and Geoinformation (JAG)*, 2022

## 2021 
- [Developing a Method to Extract Building 3D Information from GF-7 Data](https://www.mdpi.com/2072-4292/13/22/4532), Jingyuan Wang, Xinli Hu, Qingyan Meng, Linlin Zhang, Chengyi Wang, Xiangchen Liu, **Maofan Zhao**, *Remote Sensing (RS)*, 2021

- [Land Cover and Crop Classification Based on Red Edge Indices Features of GF-6 WFV Time Series Data](https://www.mdpi.com/2072-4292/13/22/4522), Yupeng Kang, Xinli Hu, Qingyan Meng, Youfeng Zou, Linlin Zhang, Maio Liu, **Maofan Zhao**, *Remote Sensing (RS)*, 2021

## 2020 
- [A Fast and Effective Method for Unsupervised Segmentation Evaluation of Remote Sensing Images](https://www.mdpi.com/2072-4292/12/18/3005), **Maofan Zhao**, Qingyan Meng, Linlin Zhang,  Die Hu, Ying Zhang, Mona Allam, *Remote Sensing (RS)*, 2020


# 🎖 Honors and Awards
- *2024* Outstanding Graduates of Beijing, Beijing Education Committee.
- *2024* Excellent Prize of CAS President Scholarship, Chinese Academy of Sciences. 
- *2018* Special Prize of National Geomatics Contest in Programming, The State Bureau of Surveying and Mapping. 

# 📖 Educations
- *2019.09 - 2024.06*, Ph.D., Aerospace Information Research Institute, Chinese Academy of Sciences, Beijing, China. 
- *2021.12 - 2023.11*, Visiting Student, University of Trento, Trento, Italy. 

# 💻 Visitors
<div width='50%'>
<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=300&t=tt&d=O4Okz4olc3roRJQ93m9GBkRren5m0vPndwfEGGemj4E'></script>
</div>





