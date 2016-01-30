---
layout: post
title: Jekyll on Cygwin in Windows
tags: howto
published: true
comments: true
---

## What is Jekyll
[Jekyll](https://jekyllrb.com/) is a simple, blog-aware, static site generator.
ELI5: It converts simple markdown texts into HTML web pages, and it supports blog-aware features such as Permalinks, categories, pages, posts, tags and so on. By using these features, users can easyly customize their blog layout. Obviously it is harder than ready-to-use blog sites like bloggers and egloos.

[지킬](https://jekyllrb.com/)은 간단하면서 블로그를 지원하는 정적 사이트 생성기다. 
더 쉽게 이야기하자면, 지킬은 간단한 markdown된 글을 HTML 웹페이지로 변환하고, Permalinks, categories, pages, posts, tags 등과 같은 블로그 지원 기능을 지원한다. 이런 기능을 사용하면 사용자는 블로그 레이아웃을 쉽게 입맛대로 바꿀 수 있는다. 그래도 bloggers나 egloos같은 미리 만들어진 블로그 사이트보다는 어렵다.

## Would you also like to install Jekyll on Cygwin?
Windows is not supported officially, but it is possible to run Jekyll on Windows. (And so far I've seen no issue)
You can find instructions in [here](http://jekyll-windows.juthilo.com/).
I prefer to use Cygwin, so I did it successfully and like to share the steps how to install Jekyll on Cygwin in Windows.
Before you read further, please make sure that you also prefer Cygwin. If you don't know what it is, then just follow the link above.

윈도우즈는 공식적으로 지원이 안되는데, 그래도 지킬을 돌리는 건 가능하다. (그리고 지금까지 별문제 없더라.)
[여기서](http://jekyll-windows.juthilo.com/) 어떻게 하는지 찾아보면 된다.
난 Cygwin 사용하는게 좋아서, 그렇게 해서 성공했고, 어떻게 설치하는지에 대한 방법을 공유하려고 한다.
더 읽어보시기 전에 Cygwin을 더 선호하시는지 확실히 해두는게 좋다. 혹시 그게 뭔지도 모른다면 그냥 위에 링크된 방법을 따라하는게 좋다. 

## Steps to install Jekyll on Cygwin
1. Install [Cygwin](http://cygwin.org/) 
    Install minimum and default set of packages.

2. Install Ruby, Make, g++, libraries on Cygwin

    Please, check whether you already have Ruby in your Windows and if you do, then don't install it on Cygwin.
    Instead, link the Ruby commands to Windows Ruby's.
    Install a few more packages which listed [here](http://ryayon.github.io/cygwin/Install-Jekyll-on-Windows/).

3. Install Jekyll and test

    ```
    $ gem install jekyll
    $ jekyll 
    ```
    Read what the message say, it might give error message which leads to a log file. Read the log file and install more packages if there are missing packages for Jekyll.

4. Now Jekyll is ready to use. 

  All the next steps are same as in Linux or MacOS.
  That's why I prefer Cygwin. And again, I've had no issues.
  The last step is to visit [Jekyll documentation site](https://jekyllrb.com/docs/home/). 

