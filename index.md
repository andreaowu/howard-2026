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
This course is run by [Codepath](codepath.org), a non-profit that partners with colleges on industry-informed CS courses. You're currently enrolled in [Codepath in Residence](https://docs.google.com/presentation/d/1B92S4eL-lRrdG6HRFncXXyoyu2ikelQtBmGx9FQeTC4/edit?slide=id.g3f6db6b437c_0_38#slide=id.g3f6db6b437c_0_38), a program where students attend a Codepath course at their own college, for credit.

## Course Materials
{% for module in site.modules %}
{{ module }}
{% endfor %}
