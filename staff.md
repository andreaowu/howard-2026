---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Staff

For a quicker response on homework or project help, please ask on [EdStem](https://edstem.org/us/courses/41289) rather than emailing staff members individually. On EdStem, all staff members (and students!) can see your question and answer it.

## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign howard_teaching_assistants = site.staffers | where: 'role', 'Tech Fellow' %}
{% assign num_howard_teaching_assistants = howard_teaching_assistants | size %}
{% if num_howard_teaching_assistants != 0 %}
## Howard Tech Fellows
Think of these as TA’s (teacher’s assistants). They are employed by Codepath, and these are students that went through your position. You’ll see them in lectures and labs to help answer questions, office hours if Andrea's office hours aren’t enough, and they'll be helping a lot behind the scenes.

{% for staffer in howard_teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

{% assign google_teaching_assistants = site.staffers | where: 'role', 'Google Teaching Assistant' %}
{% assign num_google_teaching_assistants = google_teaching_assistants | size %}
{% if num_google_teaching_assistants != 0 %}
## Google Teaching Assistants

{% for staffer in google_teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
