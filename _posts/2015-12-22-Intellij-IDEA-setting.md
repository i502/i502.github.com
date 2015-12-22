---
layout: post
category: "Intellij IDEA"
title: "Intellij IDEA的配置修改到其它分区的办法"
tags: ["Intellij IDEA"]
---

###
不管你将 IntelliJ 装在什么地方，它都会在 C 盘的用户目录下创建 .IntelliJIdeaXX 目录，而且这个目录会随着时间增长到几个 G 那么大。这对于 C 盘小得可怜的人来说确实是个问题。不用怕，这里介绍一个将 .IntelliJIdeaXX 目录移到其他分区的办法。

我的 IntelliJ 装在 D:\Program Files\JetBrains\IntelliJ IDEA 8.1 目录下。我是这么做的：

1、首先在 D:\Program Files\JetBrains\ 下创建一个文件夹：IdeaConfig，用来存放所有的 IntelliJ 配置。

2、然后打开 D:\Program Files\JetBrains\IntelliJ IDEA 8.1\bin\idea.properties。

3、将所有的 ${user.home} 替换为 D:/Program Files/JetBrains/IdeaConfig （注意斜杠的方向）

4、保存 idea.properties

5、打开 C:\Documents and Settings\XXX 目录，把 .IntelliJIdea8x 和 .IntelliJIdea80 两个目录移动到 IdeaConfig 目录下。

这样你就可以启动 IntelliJ，而且以后也不会再占用 C 盘空间了。

