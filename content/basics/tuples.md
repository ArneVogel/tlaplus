---
title: "Tuples"
date: 2021-06-20T19:54:51+02:00
draft: true
katex: true
markup: "mmark"
---

## Check if a variable is an element of a tuple
You can not just use $$\in$$ to check if something is inside of a tuple. So writing `variable \in Tuple` would not work.

What you can use to check if a variable is element of a tuple is:

$$ \exists i \in 1..Len(\text{Tuple}): \text{Tuple}[i] = \text{variable} $$
```
\E i \in 1..Len(Tuple): Tuple[i] = variable
```

If you want to check if a variable is **not** part of a tuple you can instead use:

$$ \forall i \in 1..Len(\text{Tuple}): \text{Tuple}[i] \neq \text{variable} $$
```
\A i \in 1..Len(Tuple): Tuple[i] # variable
```


