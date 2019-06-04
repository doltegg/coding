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

<script src="prism.js"></script>
<link rel="stylesheet" type="text/css" href="prism.css">

```
<pre><code class='language-python line-numbers'>
def tri_recursion(k):
  if(k>0):
    result = k+tri_recursion(k-1)
    print(result)
  else:
    result = 0
  return result

print("\n\nRecursion Example Results")
tri_recursion(6)
</code></pre>
```
