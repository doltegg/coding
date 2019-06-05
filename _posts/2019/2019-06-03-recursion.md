---
layout: post
title: 遞歸 (recursion)
subtitle:
date: 2019-06-03 21:00:00 +0800
author: egg
cover: ''
description:
categories: Python
tags: [function, recursion] 
---

Python 也接受函數遞歸，這意味著定義的函數可以調用自身。

遞歸是一種常見的數學和編程概念。 這意味著函數調用自身。 這樣做的好處是可以循環訪問數據以達到結果。

開發人員應該非常小心遞歸，因為它可以很容易地編寫一個永不終止的函數，或者使用過量內存或處理器能力的函數。 但是，正確編寫時，遞歸可能是一種非常有效且數學上優雅的編程方法。

在這個例子中，tri_recursion（）是我們定義為調用自身的函數（“recurse”）。 我們使用 k 變量作為數據，每次遞歸時遞減（-1）。 當條件不大於 0 時（即，當它為 0 時），遞歸結束。


```python
def tri_recursion(k):
  if(k>0):
    result = k+tri_recursion(k-1)
    print(result)
  else:
    result = 0
  return result

print("\n\nRecursion Example Results")
tri_recursion(6)
```

w3schools.com 的答案是：
```python
Recursion Example Results
1
3
6
10
15
21
```

但我的答案卻是：
```python
Recursion Example Results
1
3
6
10
15
21
21
```
我總是多一個最後一項。
