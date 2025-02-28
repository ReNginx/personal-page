---
permalink: /
title: "Hanxiang Ren's Homepage."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I'm Hanxiang Ren (CN.任瀚祥), a 4th-year Ph.D. candidate at the State Key Lab of CAD&CG, Zhejiang University, supervised by Prof. Youyi Zheng. I also work very closely with Prof. Yanchao Yang at The University of Hong Kong. Previously, I obtained my B.Eng. Degree from the Honor School of Harbin Institute of Technology in 2021. 


**Research Interests**: Unsupervised Learning, 3D Reconstruction, Robotics

My CV is available **[here](/files/Resume_HanxiangRen_ZhejiangUniversity.pdf)**

## Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
