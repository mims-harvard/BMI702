---
layout: page
title: Schedule
nav_order: 13
description: BMI 702 - Biomedical AI weekly course schedule
---

# Weekly Schedule

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
