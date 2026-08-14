---
layout: home
title: Home
nav_exclude: true
seo:
  type: Course
  name: CSCI135 Howard
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

<!-- {% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %} -->

## About the Class

CSCI 135 is an introductory class designed for students with no formal exposure to computer science or programming. The goal is to provide a gentle but thorough introduction to computer science that will prepare students to either take further computer science courses, or use computer science in their field of study.

See the [Syllabus page](syllabus.md) for more details on course policies and the [Calendar page](calendar.md) page for office hours, due dates, and class times. 
## Course Materials
{% for module in site.modules %}
{{ module }}
{% endfor %}
