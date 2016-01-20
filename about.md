---
layout: page
title: About
comments: True
---

## Under Construction 

### About me
개인정보를 너무 많이 담지 않은 내 소개가 뭘까?

### Books I've read 읽은 책들
{% for post in site.posts %}
  {% if post.tags == "book" %} [ {{ post.title }} ]({{ post.url }}) {% endif %}
{% endfor %}

