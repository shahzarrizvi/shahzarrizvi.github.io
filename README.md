---
layout: home
title: Data 88S
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: Data 88S
---

Welcome to Data 88S!

Lecture: 10:30 AM - 12:00 PM in McCone 141 on Mondays, Tuesdays, Wednesdays, and Thursdays. 
Discussions: 2:00 PM - 4:00 PM in Evans 340 on Tuesdays and Thursdays.

# Calendar

{% for module in site.modules %}
{{ module }}
{% endfor %}