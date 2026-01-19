---
title: Project
nav:
  order: 2
  tooltip: 数据集和更多
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

农业系统是一个人类-自然耦合的复杂系统，本团队整合计算机仿真模型、一般均衡模型、作物生长模型等方法，对农业系统中经济社会子系统和生态环境子系统各自内部及其相互之间各层次之间的关联与互动进行建模，并将计量经济学模型的估计结果和遥感技术获取的数据用于校准（calibrate）和检验（validate）模型。这项工作将有助于提升对农业系统的系统性、整体性的认识，帮助人们理解农业生产经营行为对生态环境的影响，从而为制定兼顾经济效应和环境效应的政策提供支持。

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
