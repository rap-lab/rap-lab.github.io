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

# About Us (简介)

We are part of the [UM-SJTU Joint Institute](https://www.ji.sjtu.edu.cn/) at [Shanghai Jiao Tong University (SJTU)](https://www.sjtu.edu.cn/).

We research **Robotics, Autonomy and Planning**, with the focus on fundamental **motion planning** and **path planning** problems for **single and multiple robots**.
We leverage and advance the frontier of motion planning, multi-agent path planning, combinatorial search and optimal control.
These problems are often NP-hard, and our research exploits the underlying structure of these problems to develop algorithms that balance between **runtime efficiency** and **solution quality** with **rigorous guarantees**, while being **deployable to physical robots**.
These problems arise in **warehouse logistics, manufacturing and search-and-rescue**.

我们隶属于[上海交通大学](https://www.sjtu.edu.cn/)[密西根学院](https://www.ji.sjtu.edu.cn/)。

我们研究**机器人学，自主系统，智能规划**，尤其关注**单机器人和多机器人**中的**运动规划和路径规划**问题。
我们的研究利用运动规划，多机器人路径规划，组合搜索，最优控制等领域的相关技术，同时推动这些领域的发展。
我们研究的问题在计算复杂度上往往是NP-hard问题。我们的研究利用这些问题中的结构来设计算法，平衡计算速度和求解质量，提供严格的理论保证，并最终部署在实体机器人上。
我们研究的问题广泛存在于仓储物流，智慧生产，搜索救援等应用中。


# News

* \[2024.08\] One [paper](https://rap-lab.github.io/documents/publications/2024_IROS_TCCBSt.pdf) on Multi-Agent Teamwise Cooperative Path Finding is accepted to IROS-2024.
* \[2024.07\] One [paper](https://rap-lab.github.io/documents/publications/2024_RAL_DMS.pdf) on Multi-Agent Combinatorial Path Finding is accepted to RAL-2024.
* \[2024.04\] One [paper](https://rap-lab.github.io/documents/publications/2024_SOCS_RMA.pdf) on the Orienteering Problem with Time Varying Reward is accepted to SOCS-2024.


# Highlights

{% assign posts = site.posts | where:"categories","highlights" %}
<div class="columns is-multiline">
    {% for post in posts %}
    <div class="column is-3-desktop is-6-tablet">
        {% include post-card.html %}
    </div>
    {% endfor %}
</div>
