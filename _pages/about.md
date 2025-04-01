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

Hi there! I am Haoyu, a current master student at [National University of Singapore](https://www.nus.edu.sg/), major in [robotics](https://cde.nus.edu.sg/me/graduate/msc-robotics/). Prior to that, I obtained my bachelor's degree in robotics engineering at [Beihang University](https://ev.buaa.edu.cn/). My research interest lies in robot learning, especially in general purpose robot manipulation. More specifically, I am focusing on representation learning, large pre-trained models, and continual learning. Currently I am under [Prof. Lin Shao](https://linsats.github.io/)'s supervision. Please feel free to ask me any questions regarding my research projects.

# 🔥 News
- *2024.06*: &nbsp;🎉🎉 One paper “ManiFoundation Model for General-Purpose Robotic Manipulation of Contact Synthesis with Arbitrary Objects and Robots” was accepted to IROS 2024 as <span style="color: red;">oral presentation<span>.  
- *2024.03*: One paper “Generalizable Long-Horizon Manipulations with Large Language Models” was on Arxiv.
- *2023.07*: &nbsp;🎉🎉 One paper “ClothesNet: An Information-Rich 3D Garment Model Repository with Simulated Clothes Environment” was accepted to ICCV 2023.  

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2024</div><img src='images/ManiFoundation.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<span style="color: red;">(Oral)</span> ManiFoundation Model for General-Purpose Robotic Manipulation of Contact Synthesis with Arbitrary Objects and Robots

<span style="font-size: 15px;">[Zhixuan Xu](https://ariszxxu.github.io/)\*, [Chongkai Gao](https://chongkaigao.com/)\*, [Zixuan Liu](https://panda-shawn.github.io/)\*, [Gang Yang](https://openreview.net/profile?id=~Gang_Yang8)\*, [Chenrui Tie](https://crtie.github.io/),[Haozhuo Zheng](http://zzdirty.cn/), **Haoyu Zhou**, [Weikun Peng](https://www.linkedin.com/in/weikun-peng-7731281b4/?originalSubdomain=sg), [Debang Wang](https://www.linkedin.com/in/debang-wang-5690b5158/?originalSubdomain=sg), [Tianrun Hu](https://h-tr.github.io/), Tianyi Chen, [Zhouliang Yu](https://scholar.google.com/citations?user=qUMjnPcAAAAJ&hl=en), [Lin Shao](https://linsats.github.io/)</span>

[Website](https://manifoundationmodel.github.io/) \| [Google Scholar Page](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=WFkhn04AAAAJ&citation_for_view=WFkhn04AAAAJ:9yKSN-GCB0IC)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv Preprint</div><img src='images/GenMani.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Generalizable Long-Horizon Manipulations with Large Language Models

<span style="font-size: 15px;">**Haoyu Zhou**, [Mingyu Ding](https://dingmyu.github.io/), [Weikun Peng](https://www.linkedin.com/in/weikun-peng-7731281b4/?originalSubdomain=sg), [Masayoshi Tomizuka](https://me.berkeley.edu/people/masayoshi-tomizuka/), [Lin Shao](https://linsats.github.io/), [Chuang Gan](https://people.csail.mit.edu/ganchuang/)</span>

[Website](https://object814.github.io/Task-Condition-With-LLM/) \| [Google Scholar Page](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=WFkhn04AAAAJ&citation_for_view=WFkhn04AAAAJ:u5HHmVD_uO8C)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/ClothesNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

ClothesNet: An Information-Rich 3D Garment Model Repository with Simulated Clothes Environment

<span style="font-size: 15px;">[Bingyang Zhou](https://github.com/BingyangZHOU), **Haoyu Zhou**, [Tianhai Liang](https://tinhal.github.io/), [Qiaojun Yu](https://scholar.google.com/citations?user=hOxT8QUAAAAJ&hl=zh-CN), [Siheng Zhao](https://sihengz02.github.io/), [Yuwei Zeng](https://friolero.github.io/), [Jun Lv](https://lyuj1998.github.io/), [Siyuan Luo](https://www.siyuanluo.com/), [Qiancai Wang](https://dblp.org/pid/355/1112.html), Xinyuan Yu, Haonan Chen, [Cewu Lu](https://www.mvig.org/), and [Lin Shao](https://linsats.github.io/)</span>

[Website](https://sites.google.com/view/clothesnet/) \| [Google Scholar Page](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=WFkhn04AAAAJ&citation_for_view=WFkhn04AAAAJ:u-x6o8ySG0sC)

</div>
</div>

# 🔧 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/ME5400B.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Prompt-Learning in Vision-Language-Action Model for robot manipulation –– A step forward to continual learning 

NUS ME5400B course project

<span style="font-size: 15px;">*2024.09-2024.12*</span>

<span style="font-size: 15px;">Supervisor: [Lin Shao](https://linsats.github.io/), Advisors: [Chongkai Gao](https://chongkaigao.com/), [Zixuan Liu](https://panda-shawn.github.io/)</span>

[Report](https://drive.google.com/file/d/10B5aHKWvnoIdX6kv1YqkAp62ejDWGtf9/view?usp=sharing)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/ME5400A.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Vision-based Exoskeleton Pose Estimation with Simple RGB Cameras

NUS ME5400A course project @ [Biorobotics Lab](https://cde.nus.edu.sg/bme/bioroboticslab/#)

<span style="font-size: 15px;">*2024.03-2024.06*</span>

<span style="font-size: 15px;">Supervisor: [Haoyong Yu](https://cde.nus.edu.sg/bme/bioroboticslab/author/haoyong-yu/), Advisors: [Ashwin Narayan](https://cde.nus.edu.sg/bme/bioroboticslab/author/ashwin-narayan/), [Cindy Sia Ching Li](https://cde.nus.edu.sg/bme/bioroboticslab/author/cindy-sia-ching-li/), [Seyram Ofori
](https://cde.nus.edu.sg/bme/bioroboticslab/author/seyram-ofori/), [Shounak Bhattacharya](https://cde.nus.edu.sg/bme/bioroboticslab/author/shounak-bhattacharya/)</span>

[Report](https://drive.google.com/file/d/1gNs3HpIpQ59PC-283UBBNn4cAPPd2INB/view?usp=sharing)

</div>
</div>


# 🎖 Honors and Awards
- *2025.01* National University of Singapore Graduate Honours (Highest Distinction).
- *2023.06* Beihang Outstanding Graduates.
- *2022.10* [Aubo robotics](https://www.aubo-cobot.com/public/) second class scholarship.
- *2022.07* National ROBOCON Competition 2022, National First Prize.
- *2021.11* ABU Asia-Pacific Robot Contest 2021, Mabuchi Special Prize.
- *2021.04* Mathematical Contest in Modeling 2021, Meritorious Winner.

# 📖 Educations
- *2023.08 - 2025.01*, Master of Science Robotics, National University of Singapore.
- *2019.09 - 2023.06*, Bachelor of Engineer in Robotics Engineering, Beihang University.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

<div style="width: 30%; margin: 20px auto;">
    <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=QdI4Scbeh_wTSQJ38tEfbCGJgPxn5_Iw8JYWb7K8Evc&cl=ffffff&w=a"></script>
</div>

<span style="font-size: 15px;">If you like the template of this homepage, welcome to star and fork Yi Ren’s open-sourced [template](https://github.com/RayeRen/acad-homepage.github.io). Modifications were down inspired by Zixuan's [homepage](https://panda-shawn.github.io/)</span>
