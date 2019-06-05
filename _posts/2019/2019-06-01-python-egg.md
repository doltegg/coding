---
layout: post
title: Python 彩蛋
subtitle:
date: 2019-06-01 21:00:00 +0800
author: egg
cover: ''
description: 據說 Python 有 5 個有趣的彩蛋。
categories: Python
tags: [] 
---

據說 Python 有 5 個有趣的彩蛋為該語言添加一些有趣和特別話題以及隐藏的特性。

### Hello World

傳統來說，當一位程式員接觸一門新的程式語言的時候，「Hello, World」就會成為首個接觸的內容。

```python
>>> import __hello__
Hello World...
```

### April Fool

下面的 April fool 玩笑是由 Barry Warsaw 提出的，與他的退休有關。他是一位著名的 Python 開發者，在他宣布正式退休的时候，就誕生了下面這個彩蛋：

```python
>>> from __future__ import barry_as_FLUFL
>>> 1 <> 2
True
```

### 由 C++ 轉換到 Python
'braces' 庫也是一個具有濃厚程序員風格的玩笑，它在其文檔中提到，當在編寫 Python 代碼時使用這個庫可提供使用 C++ 花括號的功能。但當你嘗試使用它的时候，你將會看到：

```python
>>> from __future__ import braces
SyntaxError: not a chance
```

哈哈哈，以為導入 braces 就可以使用花括號來结束代碼塊？Python 的答案是：「沒門兒！」

### 經典的 Python 之禪

運行 "import this" 此命令將顯示由 Tim Peters 編寫的 "Zen Of Python（Python 之禅）"。
據傳這是 Python 中的『八榮八恥』，每個有追求的 Python 程序員都應該謹記於心。

```python
>>> import this
The Zen of Python, by Tim Peters

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
```

### “反重力”对话

```python
import antigravity
```

输入这行代码，会直接跳转到漫画网页 xkcd。漫画很有意思，一个人漂浮在天空中，他的一位朋友好奇的问他是怎么飞起来的。



对话内容大致翻译：

上图：

“你在飞！怎么做到的？”

“Python!”

下左：

“我昨晚学习了 Python，一切都是那么简单”

“运行 HELLO WORLD 只需要 print "Hello World!"”

下中：

“我还是不明白……动态类型，还是空格？”

“来加入我们吧，编程又再次变得有趣起来了，Python 是一个全新的世界”

“但你是怎么飞起来的？”

下右：

“我只是输入了 import antigravity”

“就这样？”

“我还对药品柜中的所有东西进行了采样比较”（暗指他对比过多种编程语言，但还是觉得 Python 最简单）

“但我想这就是 Python.”
