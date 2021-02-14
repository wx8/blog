---
title: 博客搬家大作战
date: 2019-04-13 08:00:00 +08:00
layout: post
subtitle: https://🈳.cc/al
author: 熊的猫
cover: https://quiet.a.blog.hi.cn/large/00337920ly1gl79bn9ga8j20sx0jjdh2.jpg
---

上个月`bitcron`变得异常的不稳定，先后出现过两次5xx不能正常访问的情况，这很让人上火。再加上`bitcron`迟迟没有sitemap实时更新的功能，就有了给博客搬家的想法。

因为`bitcron`采用的是md文档来渲染，最平稳的过渡应该是导入到静态博客中去。但是在使用`bitcron`之前，我用的就是静态博客，每次重新渲染生成一遍博客，其实还是挺麻烦的。所以又把目光重新对焦到动态博客框架。

根据技术支持的完整程度，我最终选出了3套程序作为备选，分别是：Wordpress、Typecho和Ghost。

WP不用说了，是迄今为止最成熟、最有影响力的CMS之一了，但是不支持Markdown；Ghost无论是前端还是后台的样式，都是我最爱的，但是Node.js的虚拟主机在市面上几乎没有，又不想折腾VPS。因此，最后还是采用了Typecho。

至于原来依托在`bitcron`上的文章，只能一篇一篇纯手动解决了。此处可以省略好多字……

有了程序，就要有虚拟主机跟着搭配才好。花了不下200元，试了一圈大大小小的空间服务商，最后总算是找到一家个人相对比较满意的服务商，整个构架都是基于全球的云处理技术。顺带还把博客的图床迁移到了七牛云，数据库也直接上云，搬到了景安那边（就他家的数据库便宜）。

既然使用了自己的空间，可定制的东西就更多了，所以特意把博客的域名提交到了`HSTS preload`，不知道何年何月可以正式加入到`HSTS preload`的大家庭中。