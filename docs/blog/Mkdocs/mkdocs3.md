---
title: 解决 mkdocs部署 Github Pages 自定义域名失效的问题
---

在/docs目录下创建一个 CNAME 的 无后缀 文件，然后在里面填入你的域名  
![](../blogimgs/mkdocs3.png)
  

因为每次在 Custom domain 添加后都会给我们生成一个 CNAME 的文件，但是因为项目我们没有 pull 到本地，所以造成了，每次 push 之后 CNAME 信息被 clear 了

