---
title: "Gallery Test"
author: ["birdgg"]
date: 2022-07-23T23:24:00+08:00
lastmod: 2022-07-23T23:36:47+08:00
draft: false
summary: "相册功能测试"
cover: "iku.png"
series: ["start"]
categories: ["other"]
---

Gallery 测试

下面是使用了 shortcode gallery 包裹的效果

```markdown
{{ </*gallery*/> }}
![](iku.png)
![](lilan.jpeg)
![](https://tva2.sinaimg.cn/large/6833939bly1giciub8ja1j20zk0m81ky.jpg)
{{ </*/gallery*/> }}
```

{{< gallery >}}

![](iku.png)
![](lilan.jpeg)
![](https://tva2.sinaimg.cn/large/6833939bly1giciub8ja1j20zk0m81ky.jpg)

{{< /gallery >}}

下面是单张图片测试
![](iku.png)
![](lilan.jpeg)
![](https://tva2.sinaimg.cn/large/6833939bly1giciub8ja1j20zk0m81ky.jpg)
