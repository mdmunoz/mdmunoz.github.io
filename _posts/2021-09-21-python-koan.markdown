---
layout: post
title:  "Python Koan"
date:   2021-09-21 00:00:00 -0700
---

```
def outerleave(pages, n):
    return zip(*zip(*([iter(pages)]*n)))
```