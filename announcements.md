---
layout: default
title: Announcements
---

# Announcements

<ul>
{% for post in site.announcements %}
<li><a href="{{ post.url }}" class="btn">{{ post.title }}</a></li>
{% endfor %}
</ul>
