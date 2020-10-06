---
title: remove_duplicates
tags: list,beginner
---

Removes duplicated elements in a list.

- Cast the input list to a `set`, which is a collection of *distinct* objects.
- Pass the set back to `list()`.

```py
def remove_duplicates(lst):
  return list(set(lst))
```

```py
remove_duplicates([1, 1, 2, 3, 5, 8, 13, 8, 5]) # [1, 2, 3, 5, 8, 13]
```
