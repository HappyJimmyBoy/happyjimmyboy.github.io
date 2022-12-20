---
title: hexo引入思维导图
date: 2022-12-20 10:33:08
tags:
- 思维导图
- 成长路线
categories:
- 思维导图
---

## 1.安装依赖
> npm install hexo-simple-mindmap

## 2.使用方法
```
{% pullquote mindmap mindmap-md %}
- 在 Hexo 中使用思维导图
  - 前言
  - 操作指南
    - 准备需要的文件
    - 为主题添加 CSS/JS 文件
  - 使用方法
{% endpullquote %}
```
> {% pullquote mindmap mindmap-md %}
- 工程师成长路线
  - 前端
    - html
    - css
      - flex
      - grid
      - ...
    - javascript
      - vue
      - react
      - threejs
      - ...
    - nodejs
  - 移动端
    - 微信小程序（donut 多端框架）
    - uniapp
  - 后端 
    - 编程语言
      - java
        - spring全家桶
      - python
      - go
      - nodejs
      - rust
      - ...
    - 数据库
      - mysql
      - mongodb
      - redis
      - elasticsearch
      - ...
    - 微服务
      - spring cloud alibaba
      - ...
    - 其他
      - docker
      - k8s
      - ...
  
{% endpullquote %}

<style>
	.mindmap-md{
		height:1000px !important;
	}
</style>



