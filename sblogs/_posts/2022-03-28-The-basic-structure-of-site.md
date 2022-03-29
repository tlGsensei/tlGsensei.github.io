---
layout: post
title: "The basic structure of site"
date: 2022-3-28
---

#### 项目目录结构

**_layouts/**
default.html: 页面默认布局，被index.html引用，Every time you commit a file that specifies layout: default at the top, Jekyll will magically generate the full HTML

**_diaries/**
存储diary，markdown文件，命名为“YYYY-MM-DD-Title.md”

**_blogs/**
存储blog，markdown文件，命名为“YYYY-MM-DD-Title.md”

**_videos/**
存储video，markdown文件，命名为“YYYY-MM-DD-Title.md”

以上三个项目中均存在_posts子文件夹，Jekyll只能对 _posts中的markdown文件进行构建

**_site/**
**about/** 
index.html: about页布局

**assert/**
存放内嵌图片等非文本对象

**blog/**
index.html: blog页布局

**diary/**
index.html: diary页布局

**vedio/**
index.html: vedio页布局

**css/**
main.css: 页面参数设置

**.gitigore** 
不参与Jekyll构建的文件目录

**_config.yml** 
页面布局文件

**index.html** 
首页布局