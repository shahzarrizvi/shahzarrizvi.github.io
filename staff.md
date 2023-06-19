---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Staff

Staff information is stored in the `_staffers` directory and rendered according to the layout file, `_layouts/staffer.html`.

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign staff = site.staffers | where: 'team', 'Staff' %}
{% assign num_staff = staff | size %}
{% if num_staff != 0 %}
## Course Staff

{% for staffer in staff %}
{{ staffer }}
{% endfor %}
{% endif %}
