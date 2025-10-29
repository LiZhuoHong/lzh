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

I am a postdoctoral researcher at Duke University (the Nicholas School of Environment), working with Prof. [Tong Qiu](https://scholar.google.com/citations?user=4JCY7mIAAAAJ&hl=en&oi=ao). My current working location is in the Levine Science Research Center (LSRC), Durham, North Carolina, USA. 
I received my B.S. degree of communication engineering from Wuhan University (2020) and received my Ph. D. degree (2025) from the State Key Laboratory of Information Engineering in Surveying, Mapping, and Remote Sensing (LIESMARS), Wuhan University, worked with Prof. [Hongyan Zhang](https://scholar.google.com/citations?user=fq7Uqx0AAAAJ&hl=en&oi=ao), Prof. [Wei He](https://prowdiy.github.io/weihe.github.io/), and Prof. [Liangpei Zhang](https://scholar.google.com/citations?user=vzj2hcYAAAAJ&hl=en&oi=ao).

My research interests include weakly-supervised semantic segmentation, land cover mapping, and large-scale Earth observation applications. 

Email: **zhuohong.li@duke.edu**

Google scholar: [**Zhuohong Li**](https://scholar.google.com/citations?user=cZt0JA4AAAAJ&hl=en&oi=ao)
# 📖 Academic Service
- **Guest Editor**: Guest Editor of *Remote Sensing*, leading the special issue "Advances in Multispectral Image Processing for Land Use and Land Cover Mapping" with co-editors I invited from the University of Tokyo, the University of Hong Kong, and Wuhan University; And co-Guest Editor of the special issue "Remote Sensing Intelligent Interpretation in the Era of Large Models and Intelligent Agents", working with Dr. Yongqiang Mao from Tsinghua University
- **Reviewer**: Served as a reviewer of <**CVPR**>，<**NeurIPS**>, <**IEEE TPAMI**>, <**ISPRS P&RS**>, <**IEEE TGRS**>, <**IEEE JSTARS**>, <Journal of Remote Sensing (**JRS**)>

# 🔥 News
- *2025.Sep.*: &nbsp;🎉 Two papers have been accepted by ISPRS P&RS (IF=12.2)[**Paper**](https://www.sciencedirect.com/science/article/pii/S0924271625002540) and IEEE TGRS (8.6)[**Paper**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11124258).
- *2025.Feb.*: &nbsp;🎉 My stories during PhD studies were published in a magazine of the China Ministry of Education. [**Check here**](https://ersp.lib.whu.edu.cn/s/net/cnki/kns/G.https/kcms2/article/abstract?v=d24vdHNzaZj3AJ4BwzkIi-WAlZGNfoUsbXPlOYK_gFd6ZV8EfLaUoseBF0AZHTxBpJHywq1FjCOnOiFqHScflj2IEHMDudShU0YuxHFrt4Q2jjX-laKlBmwniZrnE9HEWum_ewuBEltnuF4O12_y51PXFSt-iOOf0ZrjjGnR5M3TcjyZmzKHw0LV5_PYyMPt&uniplatform=NZKPT&language=CHS).
- *2024.Dec.*: &nbsp;🎉 I received the "Wang Zhizhuo Innovation Talent Award" (王之卓创新人才奖). The greatest honor at Wuhan University.
- *2024.Dec.*: &nbsp;🎉 I won the 2024 National Scholarship for Graduate Student (博士研究生国家奖学金), ranking FIRST in LIESMARS.
- *2024.Dec.*: &nbsp;🎉 A research has been posted on AGU 2024 (Washington, DC, USA). 
- *2024.Nov.*: &nbsp;🎉 Two papers have been accepted by ISPRS P&RS (IF=12.2). 
- *2024.Oct.*: &nbsp;🎉 I received the Postdoc offer from Duke University. 
- *2024.Apr.*: &nbsp;🎉 We won first place in the CVPR 2024 OpenEarthMap Land Cover Mapping challenge. 
- *2024.Apr.*: &nbsp;🎉 The CVPR 2024 L3D-LIV Workshop has accepted the SegLand.
- *2024.Apr.*: &nbsp;🎉 The Paraformer has been posted as **Highlight** in CVPR 2024.
- *2024.Feb.*: &nbsp;🎉 The Paraformer has been accepted by CVPR 2024 with a score of 5/5/4. 
- *2023.June*: &nbsp;🎉 The SinoLC-1 has been downloaded over 100,000 times. 
- *2023.Mar.*: &nbsp;🎉 SinoLC-1: The first 1-meter resolution national-scale land-cover map of China has been open-accessed.

# 📝 Selected Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/CVPR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Learning Without Exact Guidance: Updating Large-scale High-resolution Land Cover Maps from Low-resolution Historical Labels **(Highlight)**](https://arxiv.org/abs/2403.02746)
  
[**Code and data**](https://github.com/LiZhuoHong/Paraformer/) - score:5/5/4.
**Zhuohong Li**, Wei He, Jiepan Li, Fangxiao Lu, Hongyan Zhang
</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IGARSS 2024</div><img src='images/Motivation_v3.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
[Identifying every building's function in large-scale urban areas with multi-modality remote-sensing data](https://ieeexplore.ieee.org/document/10641437)
  
[**Data**](https://github.com/LiZhuoHong/BuildingMap/?tab=readme-ov-file) 

**Zhuohong Li**, Wei He, Jiepan Li, Fangxiao Lu, Hongyan Zhang
</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPRW 2024</div><img src='images/CVPRW_Paper.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Generalized Few-Shot Meets Remote Sensing: Discovering Novel Classes in Land Cover Mapping via Hybrid Semantic Segmentation Framework]([https://arxiv.org/pdf/2404.12721])

[**Code and data**](https://github.com/LiZhuoHong/SegLand/)

**Zhuohong Li**, Wei He, Jiepan Li, Hongyan Zhang
</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ESSD 2023</div><img src='images/SinoLC-1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[SinoLC-1: the first 1-meter resolution national-scale land-cover map of China created with the deep learning framework and open-access data **(SCI Q1 TOP, IF=11.4)**](https://essd.copernicus.org/preprints/essd-2023-87/)
  
[**Data download**](https://zenodo.org/record/8105314) - 102,080 Download.

**Zhuohong Li**, Wei He, Mofan Cheng, Jingxin Hu, Guangyi Yang, Hongyan Zhang
</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISPRS 2022</div><img src='images/L2HNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Breaking the resolution barrier: A low-to-high network for large-scale high-resolution land-cover mapping using low-resolution labels **(SCI Q1 TOP, IF=12.7)**](https://www.sciencedirect.com/science/article/abs/pii/S0924271622002180)
  
**Zhuohong Li**, Hongyan Zhang, Fangxiao Lu, Ruoyao Xue, Guangyi Yang, Liangpei Zhang

</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JSTARS 2021</div><img src='images/JSTARS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[The Outcome of the 2021 IEEE GRSS Data Fusion Contest—Track MSD: Multitemporal Semantic Change Detection **(SCI Q2, IF=5.5)**](https://ieeexplore.ieee.org/document/9690575)

**Zhuohong Li**, Fangxiao Lu, Hongyan Zhang, ..., Naoto Yokoya
</div>
</div>
- [Cross-scenario damaged building extraction network: Methodology, application, and efficiency using single-temporal HRRS imagery](https://www.sciencedirect.com/science/article/pii/S0924271625002540), **ISPRS P&RS 2025**
- [C2FNet: Cross-Probabilistic Weak Supervision Learning for High-Resolution Land Cover Enhancement](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11124258), **IEEE TGRS 2025**
- [Determining spatially variable peat depths of an alpine peatland in the Qinghai‐Tibet Plateau](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2024JG008713), **JGR Biogeosciences 2025**
- [Overcoming the uncertainty challenges in detecting building changes from remote sensing images](https://www.sciencedirect.com/science/article/pii/S092427162400426X), **ISPRS P&RS 2024**
- [Harmony in diversity: Content cleansing change detection framework for very-high-resolution remote-sensing images](https://www.sciencedirect.com/science/article/pii/S092427162400340X), **ISPRS P&RS 2024**
- [Cross-City Semantic Segmentation (C2Seg) in Multimodal Remote Sensing: Outcome of the 2023 IEEE WHISPERS C2Seg Challenge](https://ieeexplore.ieee.org/abstract/document/10517985), **IEEE JSTARS 2024**
- [Simultaneous Update of High-Resolution Land-Cover Mapping Attempt: Wuhan and the Surrounding Satellite Cities Cartography Using L2HNet](https://arxiv.org/pdf/2303.05305.pdf), **IEEE JSTARS 2023**
- [Multimodal unsupervised domain adaptation for remote sensing image segmentation]([https://ieeexplore.ieee.org/abstract/document/9553120](https://ieeexplore.ieee.org/abstract/document/10431324)), **2023 13th Workshop on Hyperspectral Imaging and Signal Processing: Evolution in Remote Sensing (WHISPERS) 2023**
- [Multi-stage pseudo-label iteration framework for semi-supervised land-cover mapping](https://ieeexplore.ieee.org/abstract/document/9884345), **IGRASS 2021**
- [Change Cross-Detection Based on Label Improvements and Multi-Model Fusion for Multi-Temporal Remote Sensing Images](https://ieeexplore.ieee.org/abstract/document/9553120), **IGRASS 2020**

# 🎖 Honors and Awards
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">First place</div><img src='images/CVPR-1st.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[First place: 2024 CVPR OpenEarthMap Land Cover Mapping Challenge](https://codalab.lisn.upsaclay.fr/competitions/17568#participate)
  

**Zhuohong Li**, Fangxiao Lu, Jiaqi Zou, Lei Hu, Hongyan Zhang
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">First place</div><img src='images/2021DFC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[First place: 2021 IEEE GRSS Data Fusion Contest—Track MSD: Multitemporal Semantic Change Detection](https://ieeexplore.ieee.org/abstract/document/9553120)
  

**Zhuohong Li**, Fangxiao Lu, Hongyan Zhang, ..., Liangpei Zhang
</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Second place</div><img src='images/DFC2022.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Second place: 2022 IEEE GRSS Data Fusion Contest—Track SLM: Semi-supervised Learning for Land Cover Classification](https://ieeexplore.ieee.org/abstract/document/9884345)
  

**Zhuohong Li**, Jiaqi Zou, Fangxiao Lu, Hongyan Zhang

</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Second place</div><img src='images/whisper.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Second place: 2023 Cross-city Multimodal Semantic Segmentation Challenge of WHISPER


Jiaqi Zou，**Zhuohong Li**, Fangxiao Lu, Wei He, Hongyan Zhang
</div>
</div>

- *2020* Third place: 2020 Gaofen challenge—Track: Remote-sensing image semantic segmentation 
- *2019* The first prize: China National Undergraduate Electronics Design Contest. 
- *2018* The second prize: China National Undergraduate Embedded Chip and System Design Competition. 
- *2023* The second prize: China National University Opt-Sci-Tech Competition. 

# 💬 Conference oral presentation
- *2024*, The IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2024, Seattle, USA.
- *2023*, IEEE 11th International Conference on Agro-Geoinformatics, Wuhan, China.
- *2022*, IEEE International Geoscience and Remote Sensing Symposium (IGRASS), Kuala Lumpur, Malaysia.
- *2021*, IEEE International Geoscience and Remote Sensing Symposium (IGRASS), Brussels, Belgium.

# 📖 Sport
I was the Captain of the LIESMARS soccer team and served as a national athlete (Goalkeeper).  
I joined the soccer team at Duke University.

<!-- 三张图水平紧密排列 -->
<div class="paper-box-container" style="display: flex; flex-direction: row; justify-content: flex-start; align-items: flex-start; gap: 5px; margin-top: 10px;">

  <!-- Card 1 -->
  <div class="paper-box" style="position: relative; width: 33%; min-width: 200px;">
    <div class="paper-box-image" style="position: relative; width: 200%; aspect-ratio: 16/9;">
      <div class="badge" style="position: absolute; top: 5px; left: 5px; background:#4CAF50; color:white; padding:2px 6px; border-radius:4px; font-size:12px;">Teamwork</div>
      <img src='images/s2.jpg' alt="Teamwork" style="width:200%; height:200%; object-fit: cover; border-radius:6px;">
    </div>
  </div>

  <!-- Card 2 -->
  <div class="paper-box" style="position: relative; width: 33%; min-width: 200px;">
    <div class="paper-box-image" style="position: relative; width: 200%; aspect-ratio: 16/9;">
      <div class="badge" style="position: absolute; top: 5px; left: 5px; background:#2196F3; color:white; padding:2px 6px; border-radius:4px; font-size:12px;">Long pass</div>
      <img src='images/s1.jpg' alt="Long pass" style="width:200%; height:200%; object-fit: cover; border-radius:6px;">
    </div>
  </div>

  <!-- Card 3 -->
  <div class="paper-box" style="position: relative; width: 33%; min-width: 200px;">
    <div class="paper-box-image" style="position: relative; width: 200%; aspect-ratio: 16/9;">
      <div class="badge" style="position: absolute; top: 5px; left: 5px; background:#FF5722; color:white; padding:2px 6px; border-radius:4px; font-size:12px;">Goalkeeper</div>
      <img src='images/soccor.jpg' alt="Goalkeeper" style="width:200%; height:200%; object-fit: cover; border-radius:6px;">
    </div>
  </div>

</div>

<!-- ==================== Page Visitor Section ==================== -->
# 💬 Page Visitor

<div class="visitor-section" style="display: flex; flex-direction: column; align-items: flex-start; gap: 10px; margin-top: 15px;">

  <!-- 顶部访客徽章 -->
  <img src="https://visitor-badge.laobi.icu/badge?page_id=page.id" alt="visitor badge" style="margin-bottom: 5px;">
  <script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=ffffff&w=a&t=tt&d=smikl9b7K_TA2OTYCETb4Sio2_EgFyVb88-4mhp1UAA&ct=000000'></script>
  <!-- 三个访客统计图水平紧密排列 -->
  <div style="display: flex; flex-direction: row; justify-content: flex-start; align-items: flex-start; gap: 5px;">

    <!-- World map flag counter -->
    <a href="https://info.flagcounter.com/Gupv">
    <!--     <img src="https://s01.flagcounter.com/map/Gupv/size_s/txt_000000/border_CCCCCC/pageviews_0/viewers_0/flags_0/" 
           alt="Flag Counter" border="0" style="border-radius:6px;">-->
    </a>

    <!-- Total flag counter 1 -->
    <a href="https://info.flagcounter.com/GvHh">
   <!--    <img src="https://s01.flagcounter.com/count2/GvHh/bg_FFFFFF/txt_000000/border_CCCCCC/columns_2/maxflags_12/viewers_0/labels_0/pageviews_0/flags_0/percent_0/" 
           alt="Flag Counter" border="0" style="border-radius:6px;">-->
    </a>

    <!-- Total flag counter 2 -->
    <a href="https://info.flagcounter.com/NkeR">
   <img src="https://s05.flagcounter.com/count2_US/NkeR/bg_FFFFFF/txt_000000/border_CCCCCC/columns_2/maxflags_12/viewers_0/labels_0/pageviews_0/flags_0/percent_0/" 
           alt="Flag Counter" border="0" style="border-radius:6px;">
    </a>

  </div>
</div>
