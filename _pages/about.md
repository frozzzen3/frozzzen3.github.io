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
I am a PhD student in [the Department of Electrical and Computer Engineering](https://ece.northeastern.edu/) at Northeastern University. My primary research interests include Augmented and Virtual Reality (AR/VR) Systems, Computer Networks, Wireless Sensing and Communications, Mobile and Wearable Computing. If you are seeking any form of **academic cooperation**, please feel free to email me at [chen.guod@northeastern.edu](mailto:chen.guod@northeastern.edu).

At Northeastern University, I'm fortunate to work as a member of Spatial Internet Research Group (SINRG) led by Professor [Mallesham Dasari](https://mallesham.com/). 

Click here to view my [CV](https://frozzzen3.github.io/files/Guodong_Chen_CV_2026_03_30.pdf).

 <!--Click here to view my [CV](https://frozzzen3.github.io/files/Guodong_Chen_CV_10_12.pdf). -->

# 🔥 News

{% include news-list.html homepage=true %}

<a href="{{ '/news/' | relative_url }}" target="_self">More news</a>

# 💡 Research

I am going to explore the future of immersive media and do something cool to shape the future of communication! Currently, I mainly focus on AR/VR, 3D Mesh/Point Cloud compression, and spatial/volumetric video streaming. I am also interested in AI-based 3D content compression and streaming technologies.

# 🌐 Open4D
{: #open4d}

<div class="paper-box open4d-box">
<div class="paper-box-image">
<a href="{{ '/images/open4d-ecosystem.png' | relative_url }}" aria-label="View the full Open4D ecosystem diagram">
<img src="{{ '/images/open4d-ecosystem.png' | relative_url }}" alt="Open4D ecosystem: shared infrastructure for time-varying 4D geometry, connecting reconstruction, mesh compression, XR, autonomous systems, interoperability, openness, reproducibility, and governance." width="1942" height="1400" loading="lazy">
</a>
</div>
<div class="paper-box-text" markdown="1">
<h2 class="open4d-title">Open4D: Open-source tools for 4D spatial data</h2>

Open4D is an open, research-driven platform for the representation, compression, processing, evaluation, and streaming of time-varying 4D geometry.

I initiated Open4D with my advisor, Professor [Mallesham Dasari](https://mallesham.com/), building on my first paper [*TVMC*](https://dl.acm.org/doi/abs/10.1145/3712676.3714440). The project has since grown into a broader open-source initiative, supported by: <a class="open4d-funding"><strong>$300K NSF funding</strong></a>


<div class="open4d-actions">
<a class="open4d-badge" href="https://github.com/open4dfoundation/Open4D">
<img src="https://img.shields.io/github/stars/open4dfoundation/Open4D?style=social&amp;label=Code%20Stars" alt="GitHub stars" height="20">
</a>
<a class="open4d-badge" href="https://open4dfoundation.github.io/">
<img src="https://img.shields.io/badge/Project%20Webpage-white?style=flat" alt="Project website" height="20">
</a>
</div>

</div>
</div>

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM SIGGRAPH 2026</div><img src='images/TSMC_SIGGRAPH_2026.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span style="font-size: 16px; font-weight: bold;">
            TSMC: Time-varying 4D Scene Mesh Compression
    </span>


**Guodong Chen**, Libor Váša, Amrita Mazumdar, and Mallesham Dasari. 

The Special Interest Group on Computer Graphics and Interactive Techniques Conference Conference Papers (SIGGRAPH). 2026.

[![Code Stars](https://img.shields.io/github/stars/SINRG-Lab/TSMC?style=social&label=Code Stars)](https://github.com/SINRG-Lab/TSMC) [![Static Badge](https://img.shields.io/badge/Project%20Webpage-white?style=flat&link=https%3A%2F%2Ffrozzzen3.github.io%2FTSMC%2F)](https://frozzzen3.github.io/TSMC/)

![Presenter](https://img.shields.io/badge/Presenter-✅-while)


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MMSys 2025</div><img src='images/TVMC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span style="font-size: 16px; font-weight: bold;">
            TVMC: Time-Varying Mesh Compression Using Volume-Tracked Reference Meshes
    </span>


**Guodong Chen**, Filip Hácha, Libor Váša, and Mallesham Dasari. 

The 16th ACM Multimedia Systems Conference (MMSys)

[![Code Stars](https://img.shields.io/github/stars/open4dfoundation/Open4D?style=social&label=Code Stars)](https://github.com/open4dfoundation/Open4D) <span class='show_paper_citations' data=''></span>

![Static Badge](https://img.shields.io/badge/Best%20Reproducible%20Paper%20Award-blue) ![Presenter](https://img.shields.io/badge/Presenter-✅-while)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/N4MC_arXiv_2026.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span style="font-size: 16px; font-weight: bold;">
            N4MC: Neural 4D Mesh Compression
    </span>



**Guodong Chen**, Huanshuo Dong, Mallesham Dasari. 

arXiv 2026


</div>
</div>

## Conference
- ![SenSys 2027](https://img.shields.io/badge/SenSys-2027-blue)
 *CapGaze: Capactive Sensing-based Eye Tracking on Smart Glasses*. Majd Khalaf, **Guodong Chen**, Aidan Hanson, and Mallesham Dasari. In *Proceedings of the 2027 ACM/IEEE International Conference on Embedded Artificial Intelligence and Sensing Systems*. 2027.


- ![MMSys 2026](https://img.shields.io/badge/MMSys-2026-blue)
 [*LMG: Efficient Streaming of Layered Mesh–Gaussian 3D Scenes.*](https://dl.acm.org/doi/10.1145/3793853.3795764) Yuan-Chun Sun, **Guodong Chen**, Sam Ziaie Kondori, Mallesham Dasari, and Cheng-Hsin Hsu. In *Proceedings of the 17th ACM Multimedia Systems Conference (MMSys)*. 2026.

## Workshop & Demo
- ![HotMobile 2025](https://img.shields.io/badge/HotMobile-2025-blue) [*Spatial Video Streaming on XR Headsets.*](https://dl.acm.org/doi/abs/10.1145/3708468.3711878) **Guodong Chen\***, Sizhe Wang\*, Jacob Chakareski, Dimitrios Koutsonikolas, and Mallesham Dasari. In *Proceedings of the 26th International Workshop on Mobile Computing Systems and Applications*, pp. 115-120. 2025. ![Presenter](https://img.shields.io/badge/Presenter-✅-while  )

- ![HotMobile 2025](https://img.shields.io/badge/HotMobile-2025-blue) [*Remote Human-Robot Collaboration in XR.*](https://sinrg.org/papers/RoboTwin_Demo_HotMobile_24.pdf) Yang Zhewen\*, **Guodong Chen\***, Mayank Chadha, Barath Balamurugan, and Mallesham Dasari. In *Proceedings of the 26th International Workshop on Mobile Computing Systems and Applications*, pp. 131-131. 2025. ![Static Badge](https://img.shields.io/badge/Best%20Demo%20Award-blue)&nbsp;[![Static Badge](https://img.shields.io/badge/Demo%20Video%20Link-8A2BE2)](https://youtu.be/7PKZyjSJMXk)&nbsp;![Presenter](https://img.shields.io/badge/Presenter-✅-while  )

## Dataset

- ![ACM MM 2025](https://img.shields.io/badge/ACM_MM-2025-blue) [*SVD: Spatial Video Dataset.*](https://dl.acm.org/doi/abs/10.1145/3746027.3758246) Izadimehr, MohammadHossein, Milad Ghanbari, **Guodong Chen**, Wei Zhou, Xiaoshuai Hao, Mallesham Dasari, Christian Timmerer, and Hadi Amirpour. *In Proceedings of the 33rd ACM International Conference on Multimedia*, pp. 12988-12994. 2025.

# 🎠 Honors & Awards

- *2025*, Best Reproducible Paper Award, ACM Multimedia Systems Conference (MMSys)
- *2025*, Best Demo Award, ACM HotMobile
- *2025*, ACM Travel Grant, ACM Multimedia Systems Conference (MMSys)
- *2025*, ACM Travel Grant, ACM HotMobile

# 📖 Education

- *2024.09 - now*, PhD student, Northeastern University, US
- *2020.09 - 2024.06*, Undergraduate, Nanjing Normal University, China
- *2017.09 - 2020.06*, High-School Student, Wenzhou High School, China

# 🎮 Miscellaneous

I did Mathematical Olympiad in high school.

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=300&t=n&d=97bHT3iHb1RyhPmFRzsHz-UbADoRGZFiIviWP0M94Fw'></script>



<p style="text-align:right;font-size:small;" >Last updated: September 18, 2026</p>
