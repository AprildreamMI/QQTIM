---
typora-copy-images-to: img
---

# TIM主页	

### 项目描述

#### 原理

​	TIM主页运用了 背景页固定的原理，

```
background-attachment: fixed;
```

​	从而达到视差滚动的效果，显得清新艺术

#### 基于

​	本项目基于 “jquery.stellar.js” 插件，快速高效的完成视差滚动效果

> ​    插件初始化代码如下

```javascript
$(function () {
    /*1.引入*/
    /*2.结构   data-stellar-background-ratio="0.3"  样式 bg 需要 background-attachment: fixed;*/
    /*3.初始化插件*/
    $.stellar({
        horizontalScrolling: false,
        responsive: true
    });
});
```

### 项目预览

![tim](https://github.com/AprildreamMI/QQTIM/blob/master/img/tim.png)

![Tim2](https://github.com/AprildreamMI/QQTIM/blob/master/img/Tim2.png)
