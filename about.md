---
layout: page
title: About
comments: True
---

내가 알고 즐기는 것들을 친구들에게 소개하고 나누려고 합니다.

### About me


### Books I've read 읽은 책들
{% for post in site.posts %}
  {% if {{post.tags}} == "book" %} [ {{ post.title }} ]({{ post.url }}) {% endif %}
{% endfor %}

