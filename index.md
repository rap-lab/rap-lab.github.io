---
title: RAP Lab
subtitle: Robotics Autonomy and Planning Lab
layout: page
show_sidebar: true
hide_footer: false
title_color_bg: black
hero_height: is-medium
hero_image: todo.png
hero_link: /research/
hero_link_text: Our Research
hero_link2: /publications
hero_link_text2: Our Publication
---

# About Us

We are part of the [UM-SJTU Joint Institute](https://www.ji.sjtu.edu.cn/) at [Shanghai Jiao Tong University (SJTU)](https://www.sjtu.edu.cn/).

We research **Robotics, Autonomy and Planning**, with the focus on fundamental **motion planning** and **path planning** problems for **single and multiple robots**.
We leverage and advance the frontier of motion planning, multi-agent path planning, combinatorial search and optimal control.
These problems are often NP-hard, and our research exploits the underlying structure of these problems to develop algorithms that balance between **runtime efficiency** and **solution quality** with **rigorous guarantees**, while being **deployable to physical robots**.
These problems arise in **warehouse logistics, manufacturing and search-and-rescue**.

# Highlights

{% assign posts = site.posts | where:"categories","highlights" %}
<div class="columns is-multiline">
    {% for post in posts %}
    <div class="column is-3-desktop is-6-tablet">
        {% include post-card.html %}
    </div>
    {% endfor %}
</div>
