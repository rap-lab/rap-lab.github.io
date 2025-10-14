---
title: RAP Lab
subtitle: Robotics Autonomy and Planning Lab (机器人自主规划实验室)
layout: page
show_sidebar: false
hide_footer: false
title_color_bg: black
hero_height: is-medium
hero_image: todo.png
---

<script async src="https://www.googletagmanager.com/gtag/js?id=G-D9QZD7Y8D0"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-D9QZD7Y8D0');
</script>

**We are looking for self-motivated staffs and postdocs in Robotics. Please send an email to [Prof. Ren](https://rap-lab.github.io/team/zren/) if you are interested in joining us.**

**欢迎热爱机器人的同学和博士后加入我们，有兴趣请发送邮件给[任教授](https://rap-lab.github.io/team/zren/)。（对于希望保研的同学，因为申请邮件太多，如果没有收到回复，请默认婉拒。）**

# About Us (简介)

We are part of the [Global College](https://www.ji.sjtu.edu.cn/) at [Shanghai Jiao Tong University (SJTU)](https://www.sjtu.edu.cn/).

We research **Robotics, Autonomy and Planning**, with the focus on fundamental **motion planning** and **path planning** problems for **single and multiple robots** in dynamic, interactive and unknown environments.
We leverage and advance the frontier of combinatorial search, optimal control and mixed integer programming approaches.
The problems we addressed are often NP-hard, and our research exploits the underlying structure of these problems to develop algorithms that balance between **runtime efficiency** and **solution quality** with **rigorous guarantees**, while being **deployable to physical robots**.
These problems arise in **warehouse logistics, manufacturing and search-and-rescue**.

我们隶属于[上海交通大学](https://www.sjtu.edu.cn/)[密西根学院](https://www.ji.sjtu.edu.cn/)。

我们研究**机器人学，自主系统，智能规划**，尤其关注**单机器人和多机器人**中的**运动规划和路径规划**问题。
我们的研究利用组合搜索，最优控制，混合整数规划等方法，同时推动这些方法的发展。
我们研究的问题在计算复杂度上往往是NP-hard问题。我们的研究利用这些问题中的结构来设计算法，平衡计算速度和求解质量，提供严格的理论保证，并最终部署在实体机器人上。
我们研究的问题广泛存在于仓储物流，智慧生产，搜索救援等应用中。


# News

* \[2025.10\] A [paper](https://rap-lab.github.io/documents/publications/2025_MRS_TCMAPF_Focal_ZhenlongFang.pdf) is accepted to MRS-2025.
* \[2025.7\] Three papers [paper1](https://rap-lab.github.io/documents/publications/2025_IROS_MCPFTT_XuemianWu.pdf) [paper2](https://rap-lab.github.io/documents/publications/2025_IROS_ESPC_YongceLiu.pdf) [paper3](https://rap-lab.github.io/documents/publications/2025_IROS_MAMP_MICP_ShizheZhao.pdf) are accepted to IROS-2025.
* \[2025.6\] A [paper](https://rap-lab.github.io/documents/publications/2025_TRO_Cstar_Allen.pdf) on Moving Target Traveling Salesman Problem is accepted to T-RO.
* \[2025.6\] A [paper](https://rap-lab.github.io/documents/publications/2025_IJRR_IL_ChenWang.pdf) on Neuro-Symbolic Approach is accepted to IJRR.
* \[2025.5\] A [paper](https://rap-lab.github.io/documents/publications/2025_ICRA_MTTSP3D_Anoop.pdf) on Moving Target Traveling Salesman Problem enters the Best Paper Finalist at ICRA-2025.
* \[2025.5\] Two papers [paper1](https://rap-lab.github.io/documents/publications/2025_SOCS_BOTSPTW_ShizheZhao.pdf) [paper2](https://rap-lab.github.io/documents/publications/2025_SOCS_LSPRstar_ShuaiZhou.pdf) accepted to SOCS-2025.
* \[2025.4\] A [paper](https://rap-lab.github.io/documents/publications/2025_RSS_IMEC_YongceLiu_cam.pdf) on Multi-Robot Connectivity and Ergodic Optimization is accepted to RSS-2025.
* \[2025.3\] A [paper](https://rap-lab.github.io/documents/publications/2025_ICRA_MTTSP3D_Anoop.pdf) on Moving Target Traveling Salesman Problem is accepted to ICRA-2025.
* \[2025.3\] A [paper](https://rap-lab.github.io/documents/publications/2025_ICRA_PDOMP_YuChen.pdf) on Inverse Kinematics is accepted to ICRA-2025.
* \[2025.3\] A [paper](https://rap-lab.github.io/documents/publications/2025_ICRA_PAMO.pdf) on Path Planning among Movable Obstacles is accepted to ICRA-2025.
* \[2025.2\] A [paper](https://rap-lab.github.io/documents/publications/2025_RAL_Refuel_ShizheZhao.pdf) on path planning with refueling is accepted to RAL.
* \[2024.12\] A [paper](https://rap-lab.github.io/documents/publications/2025_AAAI_LSRP_ShuaiZhou.pdf) on Multi-Agent Path Finding is accepted to AAAI-2025.
* \[2024.12\] A [paper](https://rap-lab.github.io/documents/publications/2024_AIJ_EMOA.pdf) on Multi-Objective Shortest Path is accepted to [AIJ](https://doi.org/10.1016/j.artint.2024.104260).
* \[2024.10\] A [paper](https://rap-lab.github.io/documents/publications/2024_TASE_AKstar_CBSSAPX.pdf) on Multi-Agent Combinatorial Path Finding is accepted to [T-ASE](https://doi.org/10.1109/TASE.2024.3466183).
* \[2024.09\] A [paper](https://rap-lab.github.io/documents/publications/2024_WAFR_PDO_YuChen_cam.pdf) on Inverse Kinematics is accepted to WAFR-2024.
* \[2024.09\] A [paper](https://rap-lab.github.io/documents/publications/2024_WAFR_MT-TSP-O_Anoop_cam.pdf) on Moving-Target Traveling Salesman Problem is accepted to WAFR-2024.

# Highlights

{% assign posts = site.posts | where:"categories","highlights" %}
<div class="columns is-multiline">
    {% for post in posts %}
    <div class="column is-3-desktop is-6-tablet">
        {% include post-card.html %}
    </div>
    {% endfor %}
</div>
