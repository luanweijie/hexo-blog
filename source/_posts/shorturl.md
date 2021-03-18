---
layout:     post
title:      "短连接生成"
subtitle:   " \"quickly create a short link\""
date:       2019-04-16 12:00:00
author:     "weijie"
tags:
    - 工具
---

# t.cn/xxx

越来越多的短链接受到欢迎，今天分享一下t.cn

## Getting Started

t.cn属于新浪微博的一个短链接平台，同类的还有很多，比如百度dwz.cn等等，相对来说新浪的还是比较稳定。

### 新旧版api

https://api.weibo.com/2/short_url/shorten.json <br/>
http://api.t.sina.com.cn/short_url/shorten.json

```
Give examples
xml:http://api.t.sina.com.cn/short_url/shorten.xml
json:http://api.t.sina.com.cn/short_url/shorten.json
```

### 准备

apkey：3271760578（需要自己申请）


```
Give the example
http://api.t.sina.com.cn/short_url/shorten.json?source=3271760578&url_long=http://blog.cellmean.com
```

更多请参考：https://open.weibo.com/wiki/Short_url/shorten


