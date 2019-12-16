---
title: script标签
date: 2019-12-16 11:28:31
tags:
- js
- javascript高级程序设计笔记
---

# script标签

## 介绍

> 向HTML页面中插入Javascript的主要方法，就是使用`<script>`元素

HTML 4.01为`<script>`标签定义了6个属性

- async
- charset
- defer
- language
- src
- type

#### async

> 可选

表示因该立刻下载脚本，但是不应妨碍页面得其他操作，不如下载其他资源或等待加载其他脚本，只对外部脚本文件使用。

#### charset

> 可选

表示通过src属性指定的代码的字符集，由于大多数浏览器会忽略它的值，因此这个属性很少有人用。

#### defer

> 可选

便是脚本可以延迟到人当完全被解析和显示之后再执行。只对外部脚本有效。IE7及更早版本对嵌入脚本也支持这个属性

#### language

> 已废弃

原来用于表示编写代码使用的脚本语言（如JavaScript、JavaScript1.2或VBScript）。大多数浏览器会忽略这个属性

#### src

> 可选

表示包含要执行代码的外部文件

#### type

> 可选

可以看出是language的代替属性，表示编写代码使用的脚本语言的内容类型（也就是称为MIME类型）。如果没有这个属性默认为`text/javascript`
