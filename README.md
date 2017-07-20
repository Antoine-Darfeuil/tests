# tests
only for test purposes

> **Mardown Extra**
> *Extends **Markdown** syntax with some nice extra features.*
> *You can find more information about **Markdown Extra** extension [here][1]*

### Tables

Item | Value
---- | ---
item1 | $1000
item2 | $200
item3 | $100

| Item | Value | Qty |
| :--- | ----: | :--: |
| Computer | $2500 | 1 |
| Phone | $700 | 1 |
| Music | $20 | 243 |

> **Python2.7**
> *Some python 2.7 code (maybe)*

```python
import numpy as np
import cv2
import time, os, sys

cap = cv2.CaptureVideo(0)

while True:
  frame = cv2.read(cap)
```

### Footnotes
You can create footnotes like this[^footnote].

[^footnote]: Here is the *text* of the **footnote**.


### Tables Again

|                  | ASCII                        | HTML              |
 ----------------- | ---------------------------- | ------------------
| Single backticks | `'Isn't this fun?'`            | 'Isn't this fun?' |
| Quotes           | `"Isn't this fun?"`            | "Isn't this fun?" |
| Dashes           | `-- is en-dash, --- is em-dash` | -- is en-dash, --- is em-dash |



`[TOC]`

```flow
st=>start: Start
e=>end
op=>operation: My Operation
cond=>condition: Yes or No?

st->op->cond
cond(yes)->e
cond(no)->op
```





[1]:https://github.com/jmcmanus/pagedown-extra "Pagedown Extra Link"
