---
layout: page
title: 科技文章
permalink: /tech/
---

# 科技文章

{% for post in site.tech %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
