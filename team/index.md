---
title: 团队
nav:
  order: 3
  tooltip: 关于本团队
---

# {% include icon.html icon="fa-solid fa-users" %}Team

华中农业大学

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}