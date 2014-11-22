---
layout: post
title: 我的第一篇测试博客
category: blog
description: 看样子要送学习Markdown开始了。
---

what's fuck about the h1 title,two line?
===

why is bold here?one line
---


---
#one
##two
### where is threeeeeeee ###
---
>wh,null blank
>
> hn
>123
>
>ha

>     123,five blank
>     123 hn,咦，貌似有着色效果
>     for i in range(10):
>     	print(i)
>     how to change the colors

>ok
>>two
>
>twotwo

---

+ red
+ green
+ black
- one
- two
- three
* starone
* startwo
* starthree


>     +,-,* the effect is same



1. what effect
2. h

***
123

*145*
**098**
_167_
__120__

---
>` is before number 1

like this `printf()` function

``
123
heihei
code here
``




    people said do like this is code


---

拿来了别人的模板，慢慢看慢慢改慢慢学习咯~
感谢[beiyuu][]！

当然，还是要记得这些东西要做

##了解
*[zeroMQ][]，各个消息队列

1.blog 搞起，github上

2.V4的xbus

3.sb3

4.UNIX环境高级编程，C++ Python书籍

5.android java基础

6.ctypes源码

7.Qt4.8.5的 qcreate源码

搭建这个博客，用的是jekyll

然后自己创建的这些配置文件，也不知道是不是有模板。
后来才从[beiyuu][]那里，按照他的模板开始了第一次搭建。
啥时候再去搞个域名吧~

开始搭建时，一些菜菜的问题：

{{ page.url}}  ({{ page.title }}) 这个是干吗用的,打出来就知道了哦

左上角的加关注在哪里修改？ok，在_layouts的default.html里找到了

文章显示界面，右上角的在哪里？  在_config.yml里设置title，要重开jekyll serve

显示主页是任务栏里的描述在哪里修改？   _layout的post.html
#为毛markdown换个行，要两个回车？加#号，中间又多了个空白行
# master跟gh-pages怎么搞，我看别人的都只有一个master分支，莫非合并了？
# 咦？好吧，原来两个行首都有#的话，就不会有空白行出现了~真是摸爬滚打啊

主页左边的图片怎么弄？找到index.md里有一个div class=aside 的东西
但是图片怎么加载进去的？ 在css中的default.css，第74行找到了aside
怎么加评论栏？
#试试换行学习
哈哈




![Panda](/images/panda.jpeg)

[zeroMQ]:    http://zeromq.org/ "zeroMQ"
[beiyuu]:    https://github.com/beiyuu/Github-Pages-Example "beiyuu"

[1]:    {{ page.url}}  ({{ page.title }})
