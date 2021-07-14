---
layout: single
title: ""
---

# Upcoming Events

{% for upcoming_event in site.upcoming_events %}
<h5>
<a href="{{ upcoming_event.url }}.html">{{ upcoming_event.date | date_to_long_string }}, 
{{ upcoming_event.time }} — {{ upcoming_event.title }}</a>
</h5>

<center>
<a href="{{ upcoming_event.url }}.html">
<img src="{{ upcoming_event.poster_png }}" width='50%'
style="margin-top: 18px; margin-bottom: 18px;">
</a>
</center>

<p> {{ upcoming_event.blurb }} </p>
{% endfor %}
<hr>

# Past Events

{% assign sorted = site.past_events | sort: 'date' | reverse %}
{% for past_event in sorted %}
<h5> 
<a href="{{ past_event.url }}.html">
{{ past_event.date | date_to_long_string }} — {{ past_event.title }} </a>
</h5>
<p> {{ past_event.blurb }} </p>
{% endfor %}

