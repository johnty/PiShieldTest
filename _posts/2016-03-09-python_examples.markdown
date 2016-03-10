---
layout: post
title:  "Python Examples"
date:   2016-03-09 09:00:13
categories: tutorials python
permalink: /archive/python_examples
---

### Python Examples for PiShield
``` python
adcValues = [0 for i in range(8)]

while 1:
try:
time.sleep(0.1) #10 hz output
for ch in range(0,7):
adcValues[ch] = readADC(ch)
```

