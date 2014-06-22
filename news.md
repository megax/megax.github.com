---
layout: default
title: News
---

<h2>News</h2>

{% for post in site.posts %}
<h3><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date_to_string }}</h3>
{% endfor %}
