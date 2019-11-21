---
layout: post
title: CSS 內距及外距
subtitle:
date: 2019-11-21 16:00:00 +0800
author: egg
cover: ''
description:
categories: CSS
tags: [HTML, CSS] 
---



### HTML

```HTML
<ul class="outer">
  <li class="inner">
    項目清單
  </li>
  <li class="inner">
    項目清單
  </li>
  <li class="inner">
    項目清單
  </li>
  <li class="inner">
    項目清單
  </li> 
</ul>
```


### CSS

```CSS
.outer{
  display: inline-block;
  border: solid 2px black;
  width: 480px;
  height: 300px;
 }
.inner{
  display: block;
  border: solid 2px black;
  padding: 10px;
  padding-left: 30px;
  padding-right: 30px;
  
  margin-left: 20px;
  margin-top: 20px;
  
  margin-right: 80px;
  }
````

### 結果
<img src="https://doltegg.github.io/coding/assets/img/2019/csspadding.jpg" style="width:700px"/>

### 結論
Position 的排列並不影響其他物件的排列，而內距外距的方式採網頁的自動排列，所以會影響到其他物件的排列，一整各建構整個網頁。
- padding 用來調整內部
- margin 用來調整外部
