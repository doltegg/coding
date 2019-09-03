---
layout: post
title: Pandas 基本 funcion 介紹 (Series, DataFrame, Selectionn, Grouping)
subtitle:
date: 2019-09-03 10:18:00 +0800
author: egg
cover: ''
description:
categories: Python
tags: [sklearn, pandas] 
---


```python
import numpy as np
import pandas as pd
from sklearn import datasets

iris=datasets.load_iris()
x=pd.DataFrame(iris['data'], columns=iris['feature_names'])
print("target_name: "+str(iris['target_names']))
y=pd.DataFrame(iris['target'], columns=['target_names'])
data=pd.concat([x,y], axis=1)
data.head(3)
```

執行結果：

<img src="https://doltegg.github.io/coding/assets/img/2019/matplotlibout1.jpg" style="width:400px"/>

-->
