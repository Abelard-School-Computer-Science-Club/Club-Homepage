---
layout: default
title: Updates
---

# Updates

There are no updates yet...

<ul>
{% for post in site.updates %}
	<li><a href="{{ post.url }}" class="btn">{{ post.title }}</a></li>
{% endfor %}
</ul>
