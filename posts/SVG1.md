---
title: 会转动的谷歌浏览器图标可见过？
layout: page
excerpt_separator: "<!--more-->"
categories: 
     - SVG笔记
tags: 
     - SVG笔记
---


#### 修改的第一个简易版谷歌浏览器 logo
<!--more-->
以下是我在 Font Awesome 找到的一个简易版的谷歌浏览器logo
我为其改变了图案颜色，用font-size放大图标，制作动态图标fa-pulse类使图标以 8 步为周期进行旋转
***
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdn.staticfile.org/font-awesome/4.7.0/css/font-awesome.css">
</head>
<body>
<i class="fa fa-chrome"></i>
<i class="fa fa-chrome fa-spin" style="font-size:48px;color:red"></i>
</body>
