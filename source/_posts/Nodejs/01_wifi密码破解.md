---
title: wifi密码
date: 2023-04-02 00:58:47
tags:
- wifi
- 密码
categories:
- wifi
- 密码
---

## 代码如下
```
npm install wifi-password

const wifiPassword = require('wifi-password');

//当前wifi密码
wifiPassword().then(password => {
	console.log(password);
});

//其他wifi密码
wifiPassword("wifiname").then(password => {
	console.log(password);
});
```
