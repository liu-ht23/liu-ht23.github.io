---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Tsinghua University** — B.Eng. in Computer Science and Technology, *Aug 2023 – Present*

Research Experience
======
* **TSAIL Group, Tsinghua University** — Undergraduate Researcher, *Sep 2025 – Present*<br>
  Advisors: Prof. Jun Zhu and Prof. Hang Su
* **Interactive Perception and Robot Learning Lab (IPRL), Stanford University** — Visiting Research Student, Stanford Undergraduate Visiting Research (UGVR) Program, *Jun – Aug 2026*<br>
  Host: Prof. Jeannette Bohg

Industry Experience
======
* **Shengshu Technology (GensPI)** — Research Intern, *Jan 2026 – Present*

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

{% comment %}
  Sections below are the template's examples, kept for reference. Move a section out of this
  comment block once you have content for it (Talks/Teaching list the _talks/_teaching folders).

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1

Service and leadership
======
* Reviewer / organizer / TA roles go here
{% endcomment %}
