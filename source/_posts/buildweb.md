---
title: 如何通过服务器源码构建网站
date: 2025-02-12 16:17:36
tags:
sticky: 995
---
## 准备
你需要[NodeJS](https://nodejs.org)（＞15）和git

## 教程
首先，将源代码下载到自己的服务器
``` powershell
git clone https://github.com/HRMTR/hrmtrbeta.git
```
然后进入`hrmtrbeta`文件夹，运行
``` powershell
npm install
npm install hexo-cli
```
最后运行
``` powershell
hexo server
```
即可启动网站，打开`localhost:4000`来打开网站。