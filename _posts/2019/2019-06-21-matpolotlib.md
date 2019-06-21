---
layout: post
title: matplotlib 繪折線圖
subtitle:
date: 2019-06-21 10:28:00 +0800
author: egg
cover: ''
description:
categories: Python
tags: [plt] 
---

用 matplotlib 繪圖庫模組畫折線圖。


```python
Benz=[3367, 4120,5530]
BMW=[4000, 3590,4423]
Lexus=[5299,4930, 5350]

seq=[2018, 2019, 2020]
plt.xticks(seq)
plt.plot(seq,Benz,'-*', label="Benz")
plt.plot(seq,BMW,'-o', label="BMW")
plt.plot(seq,Lexus,'-^', label='Lexus')
plt.legend(loc='best')
plt.title("Sales Report", fontsize=24)
plt.xlabel("Year", fontsize=14)
plt.ylabel("Number of Sales", fontsize=14)
plt.tick_params(axis='both', labelsize=12, color='red')
plt.savefig('out.jpg', bbox_inches='tight')
plt.show()
```


<img src="https://doltegg.github.io/coding/others/egg/story1.jpg" style="width:250px"/>
