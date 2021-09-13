---
layout: hack
title: Example Hack Project
---

This page is meant as a template for adding your own hacks. Put the description at the top. The formatting is in [Markdown](https://www.markdownguide.org/cheat-sheet/)

### Goal of Hack

What do you want your hack to achieve?

### Who's Leading this Hack

_Your Name Here_ - _slack username_

### Important Steps

- Lists
- Look
- List this

### Some Code

Syntax highlighting works like this...

```python
from random import randint, random
from math import floor

def fisher_yates_shuffle(the_list):
    list_range = range(0, len(the_list))
    for i in list_range:
        j = randint(list_range[0], list_range[-1])
        the_list[i], the_list[j] = the_list[j], the_list[i]
    return the_list
```

Try to make your project sound appealing so it will attacts others

