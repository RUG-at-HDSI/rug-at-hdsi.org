---
layout: single
title: ""
---

# Upcoming Events

{% for event in site.upcoming_events %}
<h5>
<a href="{{ event.url }}.html">{{ event.event_date | date_to_long_string }}, 
{{ event.time }} — {{ event.title }}</a>
</h5>

<center>
<a href="{{ event.url }}.html">
<img src="{{ event.poster_png }}" width='50%'
style="margin-top: 18px; margin-bottom: 18px;">
</a>
</center>

<p> {{ event.blurb }} </p>
{% endfor %}
<hr>

# Past Events

{% assign sorted = site.past_events | sort: 'date' | reverse %}
{% for event in sorted %}


<h5> 
<a href="{{ event.url }}.html">
{{ event.event_date | date_to_long_string }} — {{ event.title }} </a>
</h5>
<center>
<a href="{{ event.url }}.html">
<img src="{{ event.poster_png }}" width='25%'
style="margin-top: 18px; margin-bottom: 18px;">
</a>
</center>
<p> {{ event.blurb }} </p>
{% endfor %}

