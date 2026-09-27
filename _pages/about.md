---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a senior undergraduate student in the [Department of Computer Science and Technology](https://www.cs.tsinghua.edu.cn/) at Tsinghua University, advised by [Prof. Jun Zhu](https://ml.cs.tsinghua.edu.cn/~jun/) and [Prof. Hang Su](https://www.cs.tsinghua.edu.cn/csen/info/1313/4403.htm) in the [TSAIL group](https://ml.cs.tsinghua.edu.cn/). In summer 2026, I was a visiting research student in [Prof. Jeannette Bohg](https://web.stanford.edu/~bohg/)'s [Interactive Perception and Robot Learning Lab (IPRL)](https://iprl.stanford.edu/) at Stanford through the Undergraduate Visiting Research (UGVR) Program.

My research is in embodied AI, with a focus on **world action models**, which learn from large-scale video how the world evolves and how a robot should act, so that robots can pick up general-purpose skills.

Outside of research, I enjoy playing basketball, and I have also learned Wing Chun and ballroom dance.

News
======

- **2026.06** &nbsp; Visited Stanford IPRL for summer research through the UGVR 2026 program.

Selected Publications
======

<!-- Cards are generated from _publications/*.md: set `selected: true` and `selected_order` there to show a paper here.
     Layout lives in _includes/pub-card.html, styles in _includes/pub-card-style.html (shared with the Publications page). -->
{% include pub-card-style.html %}
{% assign selected_pubs = site.publications | where: "selected", true | sort: "selected_order" %}
{% for pub in selected_pubs %}{% include pub-card.html pub=pub %}{% endfor %}

<div class="pub-note">* Joint first authors / equal contribution &nbsp;·&nbsp; † Project lead &nbsp;·&nbsp; All papers on the <a href="/publications/">Publications</a> page and <a href="https://scholar.google.com/citations?user=SxSu_KsAAAAJ">Google Scholar</a></div>
