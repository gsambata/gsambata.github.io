---
layout: single
title: "Project Supervision"
permalink: /supervision/
collection: supervision
author_profile: true
---

{% for item in site.supervision %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}

