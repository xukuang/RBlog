---
title: 读写数据函数默认值
author: Kuang, Xu
date: '2020-02-20'
slug: file-rename
categories: [技术篇]
tags: [R]
---

作为以后自己使用R读写数据参数默认值的手头资料。


R中读入数据时，函数默认值设置：
data = read.csv("文件名", as.is = T)

R中写出数据时，函数默认值设置：
write.csv(data,"文件名", na = "", row.names = F)