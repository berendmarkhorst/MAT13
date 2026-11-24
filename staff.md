---
layout: page
title: Staff
description: Teacher and contact information for MAT13.
---

# Staff

MAT13 is taught by Berend Markhorst.

## Teacher

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
