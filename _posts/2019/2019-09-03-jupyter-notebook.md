---
layout: post
title: Jupyter notebook 快捷鍵
subtitle:
date: 2019-09-03 10:28:00 +0800
author: egg
cover: ''
description:
categories: Python
tags: [] 
---

1. Shift $+$ Enter： 執行這個 cell。
2. Esc $+$ A： 在現有的 cell 上方新增一個 cell (A 是 above 的意思)。
3. ESC $+$ B： 在現有的 cell 下方新增一個 cell (B 是 below 的意思)。
4. Esc $+$ H： help 的意思，能列出所有快捷鍵。
5. Shift $+$ Tab： 函式的說明，不需要再去 google 相關的文件。




<!--
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
plt.savefig('matplotlibout1.jpg', bbox_inches='tight')
plt.show()
```

執行結果：

<img src="https://doltegg.github.io/coding/assets/img/2019/matplotlibout1.jpg" style="width:400px"/>

-->
