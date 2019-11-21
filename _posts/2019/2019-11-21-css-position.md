---
layout: post
title: CSS 定位方式
subtitle:
date: 2019-11-21 15:14:00 +0800
author: egg
cover: ''
description:
categories: CSS
tags: [HTML, CSS] 
---

### HTML

```HTML
<h3>CSS定位方式</h3>
<div class="static">Static 會自動排列下來</div>
<div class="relative">Relative 會自動排列下來而且可以調整偏移 (左邊離30px)</div>
<div class="absolute">Absolute 可以絕對定位</div>
<div class="fixed">Fixed 會固定在視窗中特定的位置</div>
```


### CSS

```CSS
body{
  height: 4000px;
}
div{
  border: solid 2px;
  width: 200px;
  height: 100px;  
}
.static{
  position: static;
  left: 30px;
}
.relative{
  position: relative;
  left: 30px;
  top: 30px;
}
.absolute{
  position: absolute;
  right: 50px;
  top: 50px;
}
.fixed{
  position: fixed;
  right: 50px;
  top: 200px;
}
````

### 結果
<img src="https://doltegg.github.io/coding/assets/img/2019/cssposition.jpg" style="width:800px"/>
