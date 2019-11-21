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
<img src="https://doltegg.github.io/coding/assets/img/2019/cssposition.jpg" style="width:700px"/>

### 結論
- Static 代表只能用自動排列的位置，不能調整偏移。
- Absolute 只能針對可以定位的上層元素做調整：它只能載 relative、absolute、fixe 三種屬性的元素做獨特的定位。
- Fixed 最常拿來當導覽列，它會固定在視窗的同一個位置。
