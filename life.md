---
layout: page
title: 生活随笔
permalink: /life/
---

# 生活随笔

{% for post in site.life %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
