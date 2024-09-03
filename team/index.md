---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-people-group" %}Team

{% include section.html %}

{% include list.html  data="members"  component="portrait"  filters="role: pi" %}
{% include list.html  data="members"  component="portrait"  filters="role: current-manager" %}
{% include list.html  data="members"  component="portrait"  filters="role: current-technician" %}
{% include list.html  data="members"  component="portrait"  filters="role: current-postdoc" %}
{% include list.html  data="members"  component="portrait"  filters="role: current-phd" %}
{% include list.html  data="members"  component="portrait"  filters="role: current-rotation" %}
{% include list.html  data="members"  component="portrait"  filters="role: current-undergrad" %}
{% include list.html  data="members"  component="portrait"  filters="role: current-hs" %}


