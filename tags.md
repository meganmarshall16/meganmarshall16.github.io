---
layout: page
title: Tags
---

## Tags

{% if post.tags %}
	{% for tag in post.tags %}
  	<a href="/tag#{{ tag }}" title="">{{ tag }}</a>
	{% endfor %}
{% endif %}


{% if page.tags %}
	{% for tag in page.tags %}
	  <a href="/tag#{{ tag }}" title="">{{ tag }}</a>
	{% endfor %}
{% endif %}
