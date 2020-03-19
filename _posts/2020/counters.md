---
layout: post
title: counters()
subtitle:
date: 2020-03-19 04:33:00 +0800
author: egg
cover: ''
description:
categories: CSS
tags: [HTML, CSS] 
---

<style>
	.reset { 
  		padding-left: 20px; 
  		counter-reset: wangxiaoer;
	}
	.counter:before { 
  		content: counters(wangxiaoer, '-') '. '; 
  		counter-increment: wangxiaoer;
	}
</style>


### HTML

```HTML
<div class="reset">
    <div class="counter">我是王小二
        <div class="reset">
            <div class="counter">我是王小二的大兒子</div>
            <div class="counter">我是王小二的二兒子
                <div class="reset">
                    <div class="counter">我是王小二的二兒子的大孫子</div>
                    <div class="counter">我是王小二的二兒子的二孫子</div>
                    <div class="counter">我是王小二的二兒子的小孫子</div>
                </div>
            </div>
            <div class="counter">我是王小二的三兒子</div>
        </div>
    </div>
    <div class="counter">我是王小三</div>
    <div class="counter">我是王小四
        <div class="reset">
            <div class="counter">我是王小四的大兒子</div>
        </div>
    </div>
</div>
```


### CSS

```CSS
.reset { 
  padding-left: 20px; 
  counter-reset: wangxiaoer;
}
.counter:before { 
  content: counters(wangxiaoer, '-') '. '; 
  counter-increment: wangxiaoer;
}
````


### 結果

<div class="reset">
    <div class="counter">我是王小二
        <div class="reset">
            <div class="counter">我是王小二的大兒子</div>
            <div class="counter">我是王小二的二兒子
                <div class="reset">
                    <div class="counter">我是王小二的二兒子的大孫子</div>
                    <div class="counter">我是王小二的二兒子的二孫子</div>
                    <div class="counter">我是王小二的二兒子的小孫子</div>
                </div>
            </div>
            <div class="counter">我是王小二的三兒子</div>
        </div>
    </div>
    <div class="counter">我是王小三</div>
    <div class="counter">我是王小四
        <div class="reset">
            <div class="counter">我是王小四的大兒子</div>
        </div>
    </div>
</div>
