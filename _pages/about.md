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

<div style="max-width: 900px; margin: auto; line-height: 1.6; font-size: 16px;">

<!-- ==================== About Me ==================== -->
<p>I am a postdoctoral researcher at Duke University (the Nicholas School of Environment), working with Prof. <a href="https://scholar.google.com/citations?user=4JCY7mIAAAAJ&hl=en&oi=ao">Tong Qiu</a>. My current working location is in the Levine Science Research Center (LSRC), Durham, North Carolina, USA. 
I received my B.S. degree of communication engineering from Wuhan University (2020) and received my Ph.D. degree (2025) from the State Key Laboratory of Information Engineering in Surveying, Mapping, and Remote Sensing (LIESMARS), Wuhan University, worked with Prof. <a href="https://scholar.google.com/citations?user=fq7Uqx0AAAAJ&hl=en&oi=ao">Hongyan Zhang</a>, Prof. <a href="https://prowdiy.github.io/weihe.github.io/">Wei He</a>, and Prof. <a href="https://scholar.google.com/citations?user=vzj2hcYAAAAJ&hl=en&oi=ao">Liangpei Zhang</a>.</p>

<p>My research interests include weakly-supervised semantic segmentation, land cover mapping, and large-scale Earth observation applications.</p>

<p>Email: <strong>zhuohong.li@duke.edu</strong><br>
Google scholar: <a href="https://scholar.google.com/citations?user=cZt0JA4AAAAJ&hl=en&oi=ao"><strong>Zhuohong Li</strong></a></p>

<!-- ==================== Academic Service ==================== -->
# 📖 Academic Service
<div style="margin-left: 15px;">
<ul>
<li><strong>Guest Editor</strong>: Guest Editor of <em>Remote Sensing</em>, leading the special issue of "Advances in Multispectral Image Processing for Land Use and Land Cover Mapping" with co-editors from University of Tokyo, University of Hong Kong, and Wuhan University. Co-Guest Editor of "Remote Sensing Intelligent Interpretation in the Era of Large Models and Intelligent Agents", working with Dr. Yongqiang Mao from Tsinghua University.</li>
<li><strong>Reviewer</strong>: Served as a reviewer of NeurIPS, IEEE TPAMI, IEEE TGRS, IEEE JSTARS, Journal of Remote Sensing (JRS).</li>
</ul>
</div>

<!-- ==================== News ==================== -->
# 🔥 News
<div style="margin-left: 15px;">
<ul>
<li><strong>2025.Sep.</strong> 🎉 Two papers accepted by ISPRS P&RS (IF=12.2) <a href="https://www.sciencedirect.com/science/article/pii/S0924271625002540">Paper</a> and IEEE TGRS (8.6) <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11124258">Paper</a>.</li>
<li><strong>2025.Feb.</strong> 🎉 Stories during PhD published in the magazine of China Ministry of Education. <a href="https://ersp.lib.whu.edu.cn/s/net/cnki/kns/G.https/kcms2/article/abstract?v=d24vdHNzaZj3AJ4BwzkIi-WAlZGNfoUsbXPlOYK_gFd6ZV8EfLaUoseBF0AZHTxBpJHywq1FjCOnOiFqHScflj2IEHMDudShU0YuxHFrt4Q2jjX-laKlBmwniZrnE9HEWum_ewuBEltnuF4O12_y51PXFSt-iOOf0ZrjjGnR5M3TcjyZmzKHw0LV5_PYyMPt&uniplatform=NZKPT&language=CHS">Check here</a>.</li>
<li><strong>2024.Dec.</strong> 🎉 Received "Wang Zhizhuo Innovation Talent Award".</li>
<li><strong>2024.Dec.</strong> 🎉 Won 2024 National Scholarship for Graduate Student, ranking FIRST among all LIESMARS students.</li>
<li><strong>2024.Dec.</strong> 🎉 Research posted on AGU 2024 (Washington, DC, USA).</li>
<li><strong>2024.Nov.</strong> 🎉 Two papers accepted by ISPRS P&RS (IF=12.2).</li>
<li><strong>2024.Oct.</strong> 🎉 Postdoc offer from Duke University.</li>
<li><strong>2024.Apr.</strong> 🎉 First place in CVPR 2024 OpenEarthMap Land Cover Mapping challenge.</li>
<li><strong>2024.Apr.</strong> 🎉 SegLand accepted by CVPR 2024 L3D-LIV Workshop.</li>
<li><strong>2024.Apr.</strong> 🎉 Paraformer highlighted in CVPR 2024.</li>
<li><strong>2024.Feb.</strong> 🎉 Paraformer accepted by CVPR 2024 with score 5/5/4.</li>
<li><strong>2023.June</strong> 🎉 SinoLC-1 downloaded >100,000 times.</li>
<li><strong>2023.Mar</strong> 🎉 SinoLC-1 open-accessed.</li>
</ul>
</div>

<!-- ==================== Selected Publications ==================== -->
# 📝 Selected Publications
<div style="display: flex; flex-direction: column; gap: 15px;">

<!-- Example publication card -->
<div class="paper-box" style="display: flex; flex-direction: row; gap: 15px; border: 1px solid #ddd; border-radius: 12px; padding: 10px; box-shadow: 2px 2px 8px rgba(0,0,0,0.1);">
  <div class="paper-box-image" style="flex-shrink: 0; width: 120px; position: relative;">
    <div class="badge" style="position: absolute; top: 5px; left: 5px; background:#4CAF50; color:white; padding:2px 6px; border-radius:4px; font-size:12px;">CVPR 2024</div>
    <img src='images/CVPR.png' alt="CVPR 2024" style="width:100%; border-radius:6px;">
  </div>
  <div class="paper-box-text" style="flex-grow:1;">
    <a href="https://arxiv.org/abs/2403.02746"><strong>Learning Without Exact Guidance: Updating Large-scale High-resolution Land Cover Maps from Low-resolution Historical Labels (Highlight)</strong></a><br>
    <a href="https://github.com/LiZhuoHong/Paraformer/">Code and data</a><br>
    <strong>Zhuohong Li</strong>, Wei He, Jiepan Li, Fangxiao Lu, Hongyan Zhang
  </div>
</div>

<!-- 其他 publication card 可以按同样样式复制 -->

</div>

<!-- ==================== Honors and Awards ==================== -->
# 🎖 Honors and Awards
<div style="display: flex; flex-direction: column; gap: 15px;">
  <div class="paper-box" style="display: flex; flex-direction: row; gap: 15px; border: 1px solid #ddd; border-radius: 12px; padding: 10px; box-shadow: 2px 2px 8px rgba(0,0,0,0.1);">
    <div class="paper-box-image" style="flex-shrink:0; width: 120px; position: relative;">
      <div class="badge" style="position:absolute; top:5px; left:5px; background:#FFD700; color:black; padding:2px 6px; border-radius:4px; font-size:12px;">First place</div>
      <img src='images/CVPR-1st.png' alt="First place" style="width:100%; border-radius:6px;">
    </div>
    <div class="paper-box-text" style="flex-grow:1;">
      <a href="https://codalab.lisn.upsaclay.fr/competitions/17568#participate"><strong>2024 CVPR OpenEarthMap Land Cover Mapping Challenge</strong></a><br>
      <strong>Zhuohong Li</strong>, Fangxiao Lu, Jiaqi Zou, Lei Hu, Hongyan Zhang
    </div>
  </div>
</div>

<!-- ==================== Conference Oral Presentation ==================== -->
# 💬 Conference Oral Presentation
<div style="margin-left: 15px;">
<ul>
<li><strong>2024</strong>, IEEE/CVF CVPR 2024, Seattle, USA</li>
<li><strong>2023</strong>, IEEE 11th International Conference on Agro-Geoinformatics, Wuhan, China</li>
<li><strong>2022</strong>, IEEE IGRASS, Kuala Lumpur, Malaysia</li>
<li><strong>2022</strong>, Geography of China Information Science Theory and Method Annual Conference, Hangzhou, China</li>
<li><strong>2021</strong>, IEEE IGRASS, Brussels, Belgium</li>
<li><strong>2020</strong>, China High-Resolution Earth Observation Conference, Changsha, China</li>
</ul>
</div>

</div> <!-- end max-width container -->
<!-- ==================== Sport Section ==================== -->
# 📖 Sport
I was the Captain of the LIESMARS soccer team and served as a national athlete (Goalkeeper).

<div class="paper-box-container" style="display: flex; flex-direction: row; gap: 10px; align-items: stretch; margin-top: 10px;">
  <!-- Card 1 -->
  <div class="paper-box" style="flex: 1; max-width: 200px; position: relative;">
    <div class="paper-box-image" style="position: relative; height: 150px;">
      <div class="badge" style="position: absolute; top: 5px; left: 5px; background:#4CAF50; color:white; padding:2px 6px; border-radius:4px; font-size:12px;">Teamwork</div>
      <img src='images/s2.jpg' alt="Teamwork" style="width:100%; height:100%; object-fit: cover; border-radius:6px;">
    </div>
  </div>

  <!-- Card 2 -->
  <div class="paper-box" style="flex: 1; max-width: 200px; position: relative;">
    <div class="paper-box-image" style="position: relative; height: 150px;">
      <div class="badge" style="position: absolute; top: 5px; left: 5px; background:#2196F3; color:white; padding:2px 6px; border-radius:4px; font-size:12px;">Long pass</div>
      <img src='images/s1.jpg' alt="Long pass" style="width:100%; height:100%; object-fit: cover; border-radius:6px;">
    </div>
  </div>

  <!-- Card 3 -->
  <div class="paper-box" style="flex: 1; max-width: 200px; position: relative;">
    <div class="paper-box-image" style="position: relative; height: 150px;">
      <div class="badge" style="position: absolute; top: 5px; left: 5px; background:#FF5722; color:white; padding:2px 6px; border-radius:4px; font-size:12px;">Goalkeeper</div>
      <img src='images/soccor.jpg' alt="Goalkeeper" style="width:100%; height:100%; object-fit: cover; border-radius:6px;">
    </div>
  </div>
</div>

<!-- ==================== Page Visitor Section ==================== -->
# 💬 Page visitor

<div class="visitor-section" style="display: flex; flex-direction: column; align-items: flex-start; gap: 10px; margin-top: 15px;">
  <!-- Visitor badge 在上方 -->
  <img src="https://visitor-badge.laobi.icu/badge?page_id=page.id" alt="visitor badge">

  <!-- 下方水平排列 World map 和 Total flag counter -->
  <div style="display: flex; gap: 10px;">
    <!-- World map flag counter -->
    <a href="https://info.flagcounter.com/Gupv">
      <img src="https://s01.flagcounter.com/map/Gupv/size_s/txt_000000/border_CCCCCC/pageviews_0/viewers_0/flags_0/" alt="Flag Counter" border="0">
    </a>
    <!-- Total flag counter -->
    <a href="https://info.flagcounter.com/GvHh">
      <img src="https://s01.flagcounter.com/count2/GvHh/bg_FFFFFF/txt_000000/border_CCCCCC/columns_2/maxflags_12/viewers_0/labels_0/pageviews_0/flags_0/percent_0/" alt="Flag Counter" border="0">
    </a>
  </div>
</div>
