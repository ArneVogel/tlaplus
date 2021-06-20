---
title: "Working with Numbers"
date: 2021-06-20T19:10:24+02:00
draft: true
---

To work with numbers the module must extend `Naturals`.

```
EXTENDS Naturals
```

Common errors when you didn't extend `Naturals` but still try to work with numbers in your spec:
```
Couldn't resolve infix operator symbol `<'.
Couldn't resolve infix operator symbol `+'.
Unknown operator: `Nat'.
```
