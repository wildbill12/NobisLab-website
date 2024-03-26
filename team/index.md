---
title: Team
nav:
  order: 3
  tooltip: About our team
---


# {% include icon.html icon="fa-solid fa-people-group" %}People

{% include section.html %}

## Current Members

{% include list.html  data="members"  component="portrait"  filters="role: pi" %}
{% include list.html  data="members"  component="portrait"  filters="role: current-ra" %}
{% include list.html  data="members"  component="portrait"  filters="role: postdoc" %}
{% include list.html  data="members"  component="portrait"  filters="role: phd" %}
{% include list.html  data="members"  component="portrait"  filters="role: undergrad" %}
{% include list.html  data="members"  component="portrait"  filters="role: summer" %}


{% include section.html %}

## Alumni

{% include list.html  data="members"  component="portrait"  filters="role: alum" %}
