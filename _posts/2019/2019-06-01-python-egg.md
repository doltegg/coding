---
layout: post
title: Python 彩蛋
subtitle: '據說 Python 有 5 個有趣的彩蛋。'
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
"braces" 庫也是一個具有濃厚程序員風格的玩笑，它在其文檔中提到，當在編寫 Python 代碼時使用這個庫可提供使用 C++ 花括號的功能。但當你嘗試使用它的时候，你將會看到：

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

參考翻譯：

優美勝於醜陋，<br />
顯示勝於隱式，<br />
簡單勝於複雜，<br />
複雜勝於難懂，<br />
扁平勝於嵌套，<br />
分散勝於密集，<br />
可讀性應當被重視，<br />
儘管時用性會打敗純粹性，特例也不能凌駕於規則之上，<br />
除非明確地使用其沉默，錯誤永遠不應該默默地溜走，<br />
面對不明確的定義，拒絕猜測的誘惑，<br />
用一種方法，最好只有一種方法來做一件事，<br />
雖然一開始這種方法並不是顯而易見的，但誰叫你不是 Python 之父呢，<br />
做比不做好，但立刻去做有時還不如不做，<br />
如果實現很難說明，那它是個壞想法，<br />
如果實現容易解釋，那它有可能是個好想法，<br />
命名空間是個絕妙的想法，讓我們多多地使用它們吧！



### 「反重力」對話

```python
import antigravity
```

輸入這行代碼，瀏覽器會直接跳轉到漫畫網頁。漫畫很有意思，一個人飄浮在天空中，他的一位朋友好奇的問他是怎麼飛起來的。

<img src="/coding/assets/img/2019/python.png" style="display:block;margin:auto;width:460px" />

參考翻譯：

上圖：

「你在飛！怎麼做到的？」

“Python!”

下左：

「我昨晚學習了 Python，一切都是那麼簡單。」

「運行 HELLO WORLD 只需要 print "Hello World!"」

下中：

「我還是不明白... 動態類型，還是空格？」

「來加入我們吧，編程又再次變得趣味起來了，Python 是一個全新的世界。」

「但你是怎麼飛起來的？」

下右：

「我只是輸入了 import antigravity」

「就這樣？」

「我還對藥品櫃中的所有東西進行了採樣比對。」(按指他對比過多種語言，但還是覺得 Python 最簡單)

「但我想這就是 Python。」
