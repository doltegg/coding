---
layout: post
title: IRR 函數
subtitle:
date: 2019-06-20 14:59:00 +0800
author: egg
cover: ''
description:
categories: Python
tags: [function] 
---

自己寫一個 IRR 函數。

但這個函數要跑好久好久。


```python
def irr(guess, *xx):
    i=guess/12
    total=0
    a=xx
    while True:
        for x in range(len(xx)):
            total += a[x]/((1+i)**x)
        if (abs(total)<0.0001):
            break
        elif (total>0):
            i += i/4
        else:
            i -= i/4
    return i*12
```

實際跑一遍，借款 106.839 元，每月還款 9 元。先猜 IRR 約 1.9%，開始讓它算。


```python
ti=irr(0.019, -106.839,9,9,9,9,9,9,9,9,9,9,9,9)
print('%.4f%%' % (ti*100))
```

不知道要跑多久才能完成？跑那麼久，不會是沒收斂吧！
