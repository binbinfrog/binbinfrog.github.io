---
layout: post
title: 网页实现一个无限向下滚动的消息框
tags: [javascript, css]
author-id: OYX
excerpt_separator: <!--more-->
---

工作中又遇到这么一个需求：

- 需要配合播放器播放进度滚动展示操作日志
- 操作日志量可能很大
- 要好看，有动画
- 播放器可以拖动进度条同步，所以时间同步之后会产生前向后的大范围跳转

思考了几天，尽可能地少用js动画实现了一个，这里做个记录。

具体的代码在这里可以看到[message-flow](https://github.com/OYangXiao/message-flow)




