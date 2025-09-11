---
---

# Lab Website Template

    宏观农业研究院（MARI）是华中农业大学与国际食物政策研究所（IFPRI）共同建立的一所国际化跨学科研究机构，立志建设成为水平一流、具有国际影响力的高端学术平台以及特色鲜明、视野宽广的新型农业智库。MARI由华中农业大学经济管理学院、植物科学技术学院、资源与环境学院、信息学院、公共管理学院、动物科学技术学院、动物医学院共同建设。
    MARI立足国际学术前沿，以融合多维度多层次的农业大数据为突破口，整合不同学科的研究范式和研究方法，探索超越单一学科的复杂性科学问题，为全面认识农业系统以及人与自然的关系提供新的视角和分析框架，同时为决策者提供智力支持，以促进农业可持续发展以及人与自然的和谐共处。


{%
  include button.html
  type="docs"
  link="https://greene-lab.gitbook.io/lab-website-template-docs"
%}
{%
  include button.html
  type="github"
  text="On GitHub"
  link="greenelab/lab-website-template"
%}

{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
