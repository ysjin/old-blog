---
layout: page
title: About
comments: True
---

내가 알고 즐기는 것들을 정리하면서 내 생각을 정리하고 또 혹시나 찾아오는 사람들에게 소개하고 나누려고 합니다.
현재는 지금까지 읽은 책들을 다시 읽어보면서 독후감같은 글을 쓰려는 중입니다.
얼마나 시간을 내서 할 수 있을지 모르지만, 이걸로 책을 한권이라도 더 읽고 더 깊게 이해하려는 동기가 되었으면 좋겠습니다.

### me
Engineer. 

Ph.D in Computer Science and Electrical Engineering

Born and raised in South Korea, and living in San Diego, CA

### site
This site is built using [Jekyll](http://jekyllrb.com/) with [Lanyon theme](https://github.com/poole/lanyon).

All the source code for this site is availble in [my github](https://github.com/ysjin/ysjin.github.io). 


### books I've read 읽은 책들
{% for post in site.posts %}
  {% if {{post.category}} == "book" %} [ {{ post.book-title }} ]({{ post.url }}) {% endif %}
{% endfor %}

